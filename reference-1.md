
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

#### 遍历目录下所有文件夹和子文件

```php
function read_directory($dir)
{
    if ($handle = opendir($dir)) {
        while (($file = readdir($handle))!== false) {
            if ($file != '..' && $file != '.') {
                if (is_dir($dir . '/' . $file)) {
                    $files[$file] = read_directory($dir . '/' . $file);
                } else {
                    $files[] = $file;
                }
            }
        }
        closedir($handle);
        return $files;
    }
}

print_r(read_directory('./'));
```
