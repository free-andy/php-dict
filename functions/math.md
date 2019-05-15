
#### base_convert

- base_convert($number, $frombase, $tobase)
- 在任意进制之间转换数字
- 返回转换后的值

```php

// 10 进制，转 2 进制 
$number = 10;
base_convert($number, 10, 2); // 1010

```

#### mt_rand

- mt_rand($min, $max)
- 生成更好的随机数
- 返回 min 到 max 之间的随机整数

```php

// 返回，随机整数
$num = mt_rand(1, 100);

```
