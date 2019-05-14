
#### file

- file($filename, $flags, $content)
    - $content, 使用 stream_context_create() 函数创建的上下文资源
    - $content 一般是 filename 为 url 才进行设置

- 把整个文件读入一个数组中
- 返回的数组的每个元素都对应于文件中的一行，失败时返回 false

```php

file('./faobar.php')

// FILE_IGNORE_NEW_LINES 在数组每个元素的末尾不要添加换行符
// FILE_SKIP_EMPTY_LINES 跳过空行
file('http://free-andy.cn', FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES)

```
