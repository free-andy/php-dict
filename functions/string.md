
#### strip_tags

- strip_tags($str, $allowable_tags)
- 从字符串中去除 HTML 和 PHP 标记
- 返回处理后的字符串

```php

// return <a href="http://free-andy.cn">free-andy</a>
$string = '<div><p><a href="http://free-andy.cn">free-andy</a></p></div>';
$result = strip_tags($string, '<a>');

```

#### htmlentities

- htmlentities($str, $flags, $encoding, $double_encode = true)
- 将字符转换为 HTML 转义字符
- 返回编码后的字符，也可能是空字符串

```php

$str = "foo bar<a href='http://free-andy.cn'>free-andy</a>";
$result = htmlentities($str, ENT_COMPAT, 'UTF-8');

// foo bar&lt;a href='http://free-andy.cn'&gt;free-andy&lt;/a&gt;%
echo $result;

```

#### str_split

- str_split($string, $split_length)
- 将字符串切片为数组
- 返回每个元素均为 split_length 的数组，split_length 小于 1 返回 false

```php

$string = 'aaabbbccc';
str_split($string, 3); // ['aaa', 'bbb', 'ccc']
str_split($string, 100); // ['aaabbbccc']

```

#### str_shuffle

- str_shuffle($str)
- 随机打乱一个字符串
- 返回打乱后的字符串

```php

// 类似：aacbbcacb%
$str = 'aaabbbccc';
$result = str_shuffle($str);

```
