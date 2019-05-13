
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
