
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

#### filter_var_array

- filter_var_array($type, $definition, $add_empty)
- 获取多个变量并且过滤它们
- 成功则返回一个包含所请求变量的数组，或者当失败时返回 FALSE

```php

$definition = [
    'foo' => [
        'fliter' => FILTER_VALIDATE_EMAIL,
        'flags' => FILTER_FLAG_EMAIL_UNICODE,
        'options' => [
            'default' => 'default'
        ]
    ],
    'bar' => [
        'fliter' => FILTER_VALIDATE_EMAIL,
        'flags' => FILTER_FLAG_EMAIL_UNICODE,
        'options' => [
            'default' => 'default'
        ]
    ]
];

$array = [
    'foo' => 'xx@qq.com',
];
// ['foo' => xx@qq.com, 'bar' => null]
$result = filter_var_array($array, $definition, true);

```

#### filter_input

- filter_input($type, $var, $filter, $options)
    - type 为 INPUT_GET, INPUT_POST, INPUT_COOKIE, INPUT_SERVER, INPUT_ENV 之一
    - [filter](https://www.php.net/manual/zh/filter.filters.php)

- 获取外部变量，并通过过滤器处理它
- 成功返回变量值，失败返回 false 或者 null

```php

// http://app.test?name=free-andy@foxmail.com;
// return free-andy@foxmail.com
$result = filter_input(INPUT_GET, 'name', FILTER_VALIDATE_EMAIL)

```

#### filter_input_array

- filter_input_array($type, $definition, $add_empty)
- 获取一系列外部变量，并且可以通过过滤器处理它们
- 成功返回一个所请求的变量的数组，失败返回 false

```php

$definition = [
    'foo' => [
        'fliter' => FILTER_VALIDATE_EMAIL,
        'flags' => FILTER_FLAG_EMAIL_UNICODE,
        'options' => [
            'default' => 'default'
        ]
    ],
    'bar' => [
        'fliter' => FILTER_VALIDATE_EMAIL,
        'flags' => FILTER_FLAG_EMAIL_UNICODE,
        'options' => [
            'default' => 'default'
        ]
    ]
];

// curl app.test?foo=xxx@qq.com
// ['foo' => xx@qq.com, 'bar' => null]
filter_input_array(INPUT_GET, $definition, true);

```