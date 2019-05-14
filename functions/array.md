
#### array_chunk

- array_chunk($array, $size, $preserve_keys)
    - preserve_keys 是否保留数组中原来的键名，默认 false

- 将一个数组分割成多个
- 返回多维数组，每一维包含了 size 个元素

```php

$array = ['a', 'b', 'c', 'd'];

array_chunk($array, 2, false); // [['a', 'b'], ['c', 'd']]

```
