
#### system

- system($command, $return_var)
    - 如果提供 return_var 参数， 则外部命令执行后的返回状态将会被设置到此变量中。

- 本函数执行 command 参数所指定的命令， 并且输出执行结果
- 成功则返回命令输出的最后一行， 失败则返回 false

```php

// 执行 ls -al，并返回输出的最后一行
$last_line = system('ls -al', $return_var);

```

#### escapeshellarg

- escapeshellarg($arg);
- 把字符串转码为可以在 shell 命令里使用的参数
    - 将给字符串增加一个单引号并且能引用或者转码任何已经存在的单引号
    - 这样以确保能够直接将一个字符串传入 shell 函数，并且还是确保安全的

- 返回转换之后字符串

```php

// 执行 ls -a
$arg = "-a";
system('ls '.escapeshellarg($arg));

```

#### shell_exec

- shell_exec($cmd)
- 通过 shell 环境执行命令，并且将完整的输出以字符串的方式返回
- 返回命令执行的输出。 如果执行过程中发生错误或者进程不产生输出，则返回 NULL

```php

// 返回 ls 输出
$result = shell_exec('ls')

```
