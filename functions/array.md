
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

#### array_key_exists

- array_key_exists($key, $array)
- 检查数组里是否有指定的键名或索引
- 成功时返回 TRUE， 或者在失败时返回 FALSE

```php

$array = [
    'name' => null,
    'gender' => '男'
];

isset($array['name']) // false
array_key_exists('name', $array) // true

```

#### array_keys

- array_keys($array, $search_value, $strict)
    - strict 强制匹配 “===”

- 按值搜索数组的键
- 返回数组中部分的或所有的键名

```php

$data = [
    'name' => 'andy',
    'age' => 23
];

$result = array_keys($data, '23', true); // []

```

#### array_map

- arrray_map($callback, $array1, $arrry2 ...)
- 为数组的每个元素应用回调函数
- 返回数组，包含 callback 函数处理之后 array1 的所有元素。

```php

function demo($a, $b)
{
    return $a . '=>' . $b;
}

$a = ['name', 'age', 'gender'];
$b = ['andy', '23', 'man'];

// ['name' => 'andy', 'age' => '23', 'gender' => 'man']
$result = array_map('demo', $a, $b);

```

#### array_reduce

- array_reduce($array, $callback, $init)
- callback
    - carry 上次迭代里的值； 如果本次迭代是第一次，那么这个值是 init
    - item 携带了本次迭代的值
- 将回调函数 callback 迭代地作用到 array 数组中的每一个单元中，从而将数组简化为单一的值

```php

$arr = [1,2,3,4,5,6];

$result = array_reduce($arr, function ($carry, $item) {
    return $carry + $item;
}, 100);

echo $result; // 121

```
