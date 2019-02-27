
#### 不使用内置函数反转字符串

```php
$str = 'andy';
$i = 0;
$reverse = '';
while ($str[$i]) {
    $reverse = $str[$i] . $reverse;
    $i++;
}

echo $reverse; // ydna
```
