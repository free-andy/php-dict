
#### array_chunk

- array_chunk($array, $size, $preserve_keys)
    - preserve_keys 是否保留数组中原来的键名，默认 false

- 将一个数组分割成多个
- 返回多维数组，每一维包含了 size 个元素

```php

$array = ['a', 'b', 'c', 'd'];

array_chunk($array, 2, false); // [['a', 'b'], ['c', 'd']]

```

#### array_combine

- array_combine($keys, $values)
- 创建一个数组，用一个数组的值作为其键名，另一个数组的值作为其值
- 返回合并的 array，如果两个数组的单元数不同则返回 FALSE

```php

$keys = [
    'name',
    'age',
    'gender'
];

$values = [
    'andy',
    '23',
    'man'
];

// ['name' => 'andy', 'age' => 23, 'gender' => 'man']
$result = array_combine($keys, $values);

```
