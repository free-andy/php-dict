
#### filter_var

- filter_var($var, $filter, $options)
    - [filter](https://www.php.net/manual/zh/filter.filters.php)

- 使用特定的过滤器过滤一个变量
- 成功返回变量值，失败返回 false

```php

// return free-andy@foxmail.com
$var = 'free-andy@foxmail.com';
$result = filter_var($var, FILTER_VALIDATE_EMAIL); 

// FILTER_FLAG_EMAIL_UNICODE 这是一个过滤器选项(过滤器列表de options) \
// 允许邮箱名称部分出现 UNICODE 字符
// return free-andy哈哈@foxmail.com
$var = 'free-andy哈哈@foxmail.com';
$result = filter_var($var, FILTER_VALIDATE_EMAIL, FILTER_FLAG_EMAIL_UNICODE); 

// 携带默认值(更多配置，参考过滤器列表信息)
$result = filter_var($var, FILTER_VALIDATE_EMAIL, [
    'options' => [
        'default' => 'free-andy@foxmail.com'
    ],
    'flags' => FILTER_FLAG_EMAIL_UNICODE
]);

```

#### filter_input

- filter_input($type, $var, $filter, $options)
    - type 为 INPUT_GET, INPUT_POST, INPUT_COOKIE, INPUT_SERVER, INPUT_ENV 之一
    - [filter](https://www.php.net/manual/zh/filter.filters.php)

- 获取外部变量，并通过过滤器处理它
- [过滤器](https://www.php.net/manual/zh/filter.filters.php)
- 成功返回变量值，失败返回 false 或者 null

```php

// http://app.test?name=free-andy@foxmail.com;
// return free-andy@foxmail.com
$result = filter_input(INPUT_GET, 'name', FILTER_VALIDATE_EMAIL)

```
