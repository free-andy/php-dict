### [数组](#数组-1)
### [字符串](#字符串-1)
### [多字节字符串](#多字节字符串-1)
### [变量处理](#变量处理-1)
### [文件系统](#文件系统-1)
### [目录处理](#目录处理-1)
### [数学](#数学-1)
### [类和对象](#类和对象-1)
### [字符类型检测](#字符类型检测-1)
### [日期和时间](#日期和时间-1)
### [CURL](#CURL-1)
### [过滤器](#过滤器-1)
### [函数处理](#函数处理-1)
### [正则处理](#正则处理-1)
### [网络](#网络-1)
### [程序执行](#程序执行-1)
### [PHP选项和信息](#PHP选项和信息-1)
### [错误处理](#错误处理-1)
### [输出缓冲控制](#输出缓冲控制-1)
### [密码散列算法](#密码散列算法-1)
### [杂项](#杂项-1)

<h3 id='数组'>数组</h3>

- [array_change_key_case](https://www.php.net/manual/zh/function.array-change-key-case.php) — 将数组中的所有键名修改为全大写或小写
- [array_chunk](https://www.php.net/manual/zh/function.array-chunk.php) — 将一个数组分割成多个
- [array_column](https://www.php.net/manual/zh/function.array-column.php) — 返回数组中指定的一列
- [array_combine](https://www.php.net/manual/zh/function.array-combine.php) — 创建一个数组，用一个数组的值作为其键名，另一个数组的值作为其值
- [array_count_values](https://www.php.net/manual/zh/function.array-count-values.php) — 统计数组中所有的值
- [array_diff_assoc](https://www.php.net/manual/zh/function.array-diff-assoc.php) — 带索引检查计算数组的差集
- [array_diff_key](https://www.php.net/manual/zh/function.array-diff-key.php) — 使用键名比较计算数组的差集
- [array_diff_uassoc](https://www.php.net/manual/zh/function.array-diff-uassoc.php) — 用用户提供的回调函数做索引检查来计算数组的差集
- [array_diff_ukey](https://www.php.net/manual/zh/function.array-diff-ukey.php) — 用回调函数对键名比较计算数组的差集
- [array_diff](https://www.php.net/manual/zh/function.array-diff.php) — 计算数组的差集
- [array_fill_keys](https://www.php.net/manual/zh/function.array-fill-keys.php) — 使用指定的键和值填充数组
- [array_fill](https://www.php.net/manual/zh/function.array-fill.php) — 用给定的值填充数组
- [array_filter](https://www.php.net/manual/zh/function.array-filter.php) — 用回调函数过滤数组中的单元
- [array_flip](https://www.php.net/manual/zh/function.array-flip.php) — 交换数组中的键和值
- [array_intersect_assoc](https://www.php.net/manual/zh/function.array-intersect-assoc.php) — 带索引检查计算数组的交集
- [array_intersect_key](https://www.php.net/manual/zh/function.array-intersect-key.php) — 使用键名比较计算数组的交集
- [array_intersect_uassoc](https://www.php.net/manual/zh/function.array-intersect-uassoc.php) — 带索引检查计算数组的交集，用回调函数比较索引
- [array_intersect_ukey](https://www.php.net/manual/zh/function.array-intersect-ukey.php) — 用回调函数比较键名来计算数组的交集
- [array_intersect](https://www.php.net/manual/zh/function.array-intersect.php) — 计算数组的交集
- [array_key_exists](https://www.php.net/manual/zh/function.array-key-exists.php) — 检查数组里是否有指定的键名或索引
- [array_key_first](https://www.php.net/manual/zh/function.array-key-first.php) — Gets the first key of an array
- [array_key_last](https://www.php.net/manual/zh/function.array-key-last.php) — Gets the last key of an array
- [array_keys](https://www.php.net/manual/zh/function.array-keys.php) — 返回数组中部分的或所有的键名
- [array_map](https://www.php.net/manual/zh/function.array-map.php) — 为数组的每个元素应用回调函数
- [array_merge_recursive](https://www.php.net/manual/zh/function.array-merge-recursive.php) — 递归地合并一个或多个数组
- [array_merge](https://www.php.net/manual/zh/function.array-merge.php) — 合并一个或多个数组
- [array_multisort](https://www.php.net/manual/zh/function.array-multisort.php) — 对多个数组或多维数组进行排序
- [array_pad](https://www.php.net/manual/zh/function.array-pad.php) — 以指定长度将一个值填充进数组
- [array_pop](https://www.php.net/manual/zh/function.array-pop.php) — 弹出数组最后一个单元（出栈）
- [array_product](https://www.php.net/manual/zh/function.array-product.php) — 计算数组中所有值的乘积
- [array_push](https://www.php.net/manual/zh/function.array-push.php) — 将一个或多个单元压入数组的末尾（入栈）
- [array_rand](https://www.php.net/manual/zh/function.array-rand.php) — 从数组中随机取出一个或多个单元
- [array_reduce](https://www.php.net/manual/zh/function.array-reduce.php) — 用回调函数迭代地将数组简化为单一的值
- [array_replace_recursive](https://www.php.net/manual/zh/function.array-replace-recursive.php) — 使用传递的数组递归替换第一个数组的元素
- [array_replace](https://www.php.net/manual/zh/function.array-replace.php) — 使用传递的数组替换第一个数组的元素
- [array_reverse](https://www.php.net/manual/zh/function.array-reverse.php) — 返回单元顺序相反的数组
- [array_search](https://www.php.net/manual/zh/function.array-search.php) — 在数组中搜索给定的值，如果成功则返回首个相应的键名
- [array_shift](https://www.php.net/manual/zh/function.array-shift.php) — 将数组开头的单元移出数组
- [array_slice](https://www.php.net/manual/zh/function.array-slice.php) — 从数组中取出一段
- [array_splice](https://www.php.net/manual/zh/function.array-splice.php) — 去掉数组中的某一部分并用其它值取代
- [array_sum](https://www.php.net/manual/zh/function.array-sum.php) — 对数组中所有值求和
- [array_udiff_assoc](https://www.php.net/manual/zh/function.array-udiff-assoc.php) — 带索引检查计算数组的差集，用回调函数比较数据
- [array_udiff_uassoc](https://www.php.net/manual/zh/function.array-udiff-uassoc.php) — 带索引检查计算数组的差集，用回调函数比较数据和索引
- [array_udiff](https://www.php.net/manual/zh/function.array-udiff.php) — 用回调函数比较数据来计算数组的差集
- [array_uintersect_assoc](https://www.php.net/manual/zh/function.array-uintersect-assoc.php) — 带索引检查计算数组的交集，用回调函数比较数据
- [array_uintersect_uassoc](https://www.php.net/manual/zh/function.array-uintersect-uassoc.php) — 带索引检查计算数组的交集，用单独的回调函数比较数据和索引
- [array_uintersect](https://www.php.net/manual/zh/function.array-uintersect.php) — 计算数组的交集，用回调函数比较数据
- [array_unique](https://www.php.net/manual/zh/function.array-unique.php) — 移除数组中重复的值
- [array_unshift](https://www.php.net/manual/zh/function.array-unshift.php) — 在数组开头插入一个或多个单元
- [array_values](https://www.php.net/manual/zh/function.array-values.php) — 返回数组中所有的值
- [array_walk_recursive](https://www.php.net/manual/zh/function.array-walk-recursive.php) — 对数组中的每个成员递归地应用用户函数
- [array_walk](https://www.php.net/manual/zh/function.array-walk.php) — 使用用户自定义函数对数组中的每个元素做回调处理
- [array](https://www.php.net/manual/zh/function.array.php) — 新建一个数组
- [arsort](https://www.php.net/manual/zh/function.arsort.php) — 对数组进行逆向排序并保持索引关系
- [asort](https://www.php.net/manual/zh/function.asort.php) — 对数组进行排序并保持索引关系
- [compact](https://www.php.net/manual/zh/function.compact.php) — 建立一个数组，包括变量名和它们的值
- [count](https://www.php.net/manual/zh/function.count.php) — 计算数组中的单元数目，或对象中的属性个数
- [current](https://www.php.net/manual/zh/function.current.php) — 返回数组中的当前单元
- [each](https://www.php.net/manual/zh/function.each.php) — 返回数组中当前的键／值对并将数组指针向前移动一步
- [end](https://www.php.net/manual/zh/function.end.php) — 将数组的内部指针指向最后一个单元
- [extract](https://www.php.net/manual/zh/function.extract.php) — 从数组中将变量导入到当前的符号表
- [in_array](https://www.php.net/manual/zh/function.in-array.php) — 检查数组中是否存在某个值
- [key_exists](https://www.php.net/manual/zh/function.key-exists.php) — 别名 array_key_exists
- [key](https://www.php.net/manual/zh/function.key.php) — 从关联数组中取得键名
- [krsort](https://www.php.net/manual/zh/function.krsort.php) — 对数组按照键名逆向排序
- [ksort](https://www.php.net/manual/zh/function.ksort.php) — 对数组按照键名排序
- [list](https://www.php.net/manual/zh/function.list.php) — 把数组中的值赋给一组变量
- [natcasesort](https://www.php.net/manual/zh/function.natcasesort.php) — 用&ldquo;自然排序&rdquo;算法对数组进行不区分大小写字母的排序
- [natsort](https://www.php.net/manual/zh/function.natsort.php) — 用&ldquo;自然排序&rdquo;算法对数组排序
- [next](https://www.php.net/manual/zh/function.next.php) — 将数组中的内部指针向前移动一位
- [pos](https://www.php.net/manual/zh/function.pos.php) — current 的别名
- [prev](https://www.php.net/manual/zh/function.prev.php) — 将数组的内部指针倒回一位
- [range](https://www.php.net/manual/zh/function.range.php) — 根据范围创建数组，包含指定的元素
- [reset](https://www.php.net/manual/zh/function.reset.php) — 将数组的内部指针指向第一个单元
- [rsort](https://www.php.net/manual/zh/function.rsort.php) — 对数组逆向排序
- [shuffle](https://www.php.net/manual/zh/function.shuffle.php) — 打乱数组
- [sizeof](https://www.php.net/manual/zh/function.sizeof.php) — count 的别名
- [sort](https://www.php.net/manual/zh/function.sort.php) — 对数组排序
- [uasort](https://www.php.net/manual/zh/function.uasort.php) — 使用用户自定义的比较函数对数组中的值进行排序并保持索引关联
- [uksort](https://www.php.net/manual/zh/function.uksort.php) — 使用用户自定义的比较函数对数组中的键名进行排序
- [usort](https://www.php.net/manual/zh/function.usort.php) — 使用用户自定义的比较函数对数组中的值进行排序

<h3 id='字符串'>字符串</h3>

- [addcslashes](https://www.php.net/manual/zh/function.addcslashes.php) — 以 C 语言风格使用反斜线转义字符串中的字符
- [addslashes](https://www.php.net/manual/zh/function.addslashes.php) — 使用反斜线引用字符串
- [bin2hex](https://www.php.net/manual/zh/function.bin2hex.php) — 函数把包含数据的二进制字符串转换为十六进制值
- [chop](https://www.php.net/manual/zh/function.chop.php) — rtrim 的别名
- [chr](https://www.php.net/manual/zh/function.chr.php) — 返回指定的字符
- [chunk_split](https://www.php.net/manual/zh/function.chunk-split.php) — 将字符串分割成小块
- [convert_cyr_string](https://www.php.net/manual/zh/function.convert-cyr-string.php) — 将字符由一种 Cyrillic 字符转换成另一种
- [convert_uudecode](https://www.php.net/manual/zh/function.convert-uudecode.php) — 解码一个 uuencode 编码的字符串
- [convert_uuencode](https://www.php.net/manual/zh/function.convert-uuencode.php) — 使用 uuencode 编码一个字符串
- [count_chars](https://www.php.net/manual/zh/function.count-chars.php) — 返回字符串所用字符的信息
- [crc32](https://www.php.net/manual/zh/function.crc32.php) — 计算一个字符串的 crc32 多项式
- [crypt](https://www.php.net/manual/zh/function.crypt.php) — 单向字符串散列
- [echo](https://www.php.net/manual/zh/function.echo.php) — 输出一个或多个字符串
- [explode](https://www.php.net/manual/zh/function.explode.php) — 使用一个字符串分割另一个字符串
- [fprintf](https://www.php.net/manual/zh/function.fprintf.php) — 将格式化后的字符串写入到流
- [get_html_translation_table](https://www.php.net/manual/zh/function.get-html-translation-table.php) — 返回使用 htmlspecialchars 和 htmlentities 后的转换表
- [hebrev](https://www.php.net/manual/zh/function.hebrev.php) — 将逻辑顺序希伯来文（logical-Hebrew）转换为视觉顺序希伯来文（visual-Hebrew）
- [hebrevc](https://www.php.net/manual/zh/function.hebrevc.php) — 将逻辑顺序希伯来文（logical-Hebrew）转换为视觉顺序希伯来文（visual-Hebrew），并且转换换行符
- [hex2bin](https://www.php.net/manual/zh/function.hex2bin.php) — 转换十六进制字符串为二进制字符串
- [html_entity_decode](https://www.php.net/manual/zh/function.html-entity-decode.php) — Convert HTML entities to their corresponding characters
- [htmlentities](https://www.php.net/manual/zh/function.htmlentities.php) — 将字符转换为 HTML 转义字符
- [htmlspecialchars_decode](https://www.php.net/manual/zh/function.htmlspecialchars-decode.php) — 将特殊的 HTML 实体转换回普通字符
- [htmlspecialchars](https://www.php.net/manual/zh/function.htmlspecialchars.php) — 将特殊字符转换为 HTML 实体
- [implode](https://www.php.net/manual/zh/function.implode.php) — 将一个一维数组的值转化为字符串
- [join](https://www.php.net/manual/zh/function.join.php) — 别名 implode
- [lcfirst](https://www.php.net/manual/zh/function.lcfirst.php) — 使一个字符串的第一个字符小写
- [levenshtein](https://www.php.net/manual/zh/function.levenshtein.php) — 计算两个字符串之间的编辑距离
- [localeconv](https://www.php.net/manual/zh/function.localeconv.php) — Get numeric formatting information
- [ltrim](https://www.php.net/manual/zh/function.ltrim.php) — 删除字符串开头的空白字符（或其他字符）
- [md5_file](https://www.php.net/manual/zh/function.md5-file.php) — 计算指定文件的 MD5 散列值
- [md5](https://www.php.net/manual/zh/function.md5.php) — 计算字符串的 MD5 散列值
- [metaphone](https://www.php.net/manual/zh/function.metaphone.php) — Calculate the metaphone key of a string
- [money_format](https://www.php.net/manual/zh/function.money-format.php) — 将数字格式化成货币字符串
- [nl_langinfo](https://www.php.net/manual/zh/function.nl-langinfo.php) — Query language and locale information
- [nl2br](https://www.php.net/manual/zh/function.nl2br.php) — 在字符串所有新行之前插入 HTML 换行标记
- [number_format](https://www.php.net/manual/zh/function.number-format.php) — 以千位分隔符方式格式化一个数字
- [ord](https://www.php.net/manual/zh/function.ord.php) — 转换字符串第一个字节为 0-255 之间的值
- [parse_str](https://www.php.net/manual/zh/function.parse-str.php) — 将字符串解析成多个变量
- [print](https://www.php.net/manual/zh/function.print.php) — 输出字符串
- [printf](https://www.php.net/manual/zh/function.printf.php) — 输出格式化字符串
- [quoted_printable_decode](https://www.php.net/manual/zh/function.quoted-printable-decode.php) — 将 quoted-printable 字符串转换为 8-bit 字符串
- [quoted_printable_encode](https://www.php.net/manual/zh/function.quoted-printable-encode.php) — 将 8-bit 字符串转换成 quoted-printable 字符串
- [quotemeta](https://www.php.net/manual/zh/function.quotemeta.php) — 转义元字符集
- [rtrim](https://www.php.net/manual/zh/function.rtrim.php) — 删除字符串末端的空白字符（或者其他字符）
- [setlocale](https://www.php.net/manual/zh/function.setlocale.php) — 设置地区信息
- [sha1_file](https://www.php.net/manual/zh/function.sha1-file.php) — 计算文件的 sha1 散列值
- [sha1](https://www.php.net/manual/zh/function.sha1.php) — 计算字符串的 sha1 散列值
- [similar_text](https://www.php.net/manual/zh/function.similar-text.php) — 计算两个字符串的相似度
- [soundex](https://www.php.net/manual/zh/function.soundex.php) — Calculate the soundex key of a string
- [sprintf](https://www.php.net/manual/zh/function.sprintf.php) — Return a formatted string
- [sscanf](https://www.php.net/manual/zh/function.sscanf.php) — 根据指定格式解析输入的字符
- [str_getcsv](https://www.php.net/manual/zh/function.str-getcsv.php) — 解析 CSV 字符串为一个数组
- [str_ireplace](https://www.php.net/manual/zh/function.str-ireplace.php) — str_replace 的忽略大小写版本
- [str_pad](https://www.php.net/manual/zh/function.str-pad.php) — 使用另一个字符串填充字符串为指定长度
- [str_repeat](https://www.php.net/manual/zh/function.str-repeat.php) — 重复一个字符串
- [str_replace](https://www.php.net/manual/zh/function.str-replace.php) — 子字符串替换
- [str_rot13](https://www.php.net/manual/zh/function.str-rot13.php) — 对字符串执行 ROT13 转换
- [str_shuffle](https://www.php.net/manual/zh/function.str-shuffle.php) — 随机打乱一个字符串
- [str_split](https://www.php.net/manual/zh/function.str-split.php) — 将字符串转换为数组
- [str_word_count](https://www.php.net/manual/zh/function.str-word-count.php) — 返回字符串中单词的使用情况
- [strcasecmp](https://www.php.net/manual/zh/function.strcasecmp.php) — 二进制安全比较字符串（不区分大小写）
- [strchr](https://www.php.net/manual/zh/function.strchr.php) — 别名 strstr
- [strcmp](https://www.php.net/manual/zh/function.strcmp.php) — 二进制安全字符串比较
- [strcoll](https://www.php.net/manual/zh/function.strcoll.php) — 基于区域设置的字符串比较
- [strcspn](https://www.php.net/manual/zh/function.strcspn.php) — 获取不匹配遮罩的起始子字符串的长度
- [strip_tags](https://www.php.net/manual/zh/function.strip-tags.php) — 从字符串中去除 HTML 和 PHP 标记
- [stripcslashes](https://www.php.net/manual/zh/function.stripcslashes.php) — 反引用一个使用 addcslashes 转义的字符串
- [stripos](https://www.php.net/manual/zh/function.stripos.php) — 查找字符串首次出现的位置（不区分大小写）
- [stripslashes](https://www.php.net/manual/zh/function.stripslashes.php) — 反引用一个引用字符串
- [stristr](https://www.php.net/manual/zh/function.stristr.php) — strstr 函数的忽略大小写版本
- [strlen](https://www.php.net/manual/zh/function.strlen.php) — 获取字符串长度
- [strnatcasecmp](https://www.php.net/manual/zh/function.strnatcasecmp.php) — 使用&ldquo;自然顺序&rdquo;算法比较字符串（不区分大小写）
- [strnatcmp](https://www.php.net/manual/zh/function.strnatcmp.php) — 使用自然排序算法比较字符串
- [strncasecmp](https://www.php.net/manual/zh/function.strncasecmp.php) — 二进制安全比较字符串开头的若干个字符（不区分大小写）
- [strncmp](https://www.php.net/manual/zh/function.strncmp.php) — 二进制安全比较字符串开头的若干个字符
- [strpbrk](https://www.php.net/manual/zh/function.strpbrk.php) — 在字符串中查找一组字符的任何一个字符
- [strpos](https://www.php.net/manual/zh/function.strpos.php) — 查找字符串首次出现的位置
- [strrchr](https://www.php.net/manual/zh/function.strrchr.php) — 查找指定字符在字符串中的最后一次出现
- [strrev](https://www.php.net/manual/zh/function.strrev.php) — 反转字符串
- [strripos](https://www.php.net/manual/zh/function.strripos.php) — 计算指定字符串在目标字符串中最后一次出现的位置（不区分大小写）
- [strrpos](https://www.php.net/manual/zh/function.strrpos.php) — 计算指定字符串在目标字符串中最后一次出现的位置
- [strspn](https://www.php.net/manual/zh/function.strspn.php) — 计算字符串中全部字符都存在于指定字符集合中的第一段子串的长度。
- [strstr](https://www.php.net/manual/zh/function.strstr.php) — 查找字符串的首次出现
- [strtok](https://www.php.net/manual/zh/function.strtok.php) — 标记分割字符串
- [strtolower](https://www.php.net/manual/zh/function.strtolower.php) — 将字符串转化为小写
- [strtoupper](https://www.php.net/manual/zh/function.strtoupper.php) — 将字符串转化为大写
- [strtr](https://www.php.net/manual/zh/function.strtr.php) — 转换指定字符
- [substr_compare](https://www.php.net/manual/zh/function.substr-compare.php) — 二进制安全比较字符串（从偏移位置比较指定长度）
- [substr_count](https://www.php.net/manual/zh/function.substr-count.php) — 计算字串出现的次数
- [substr_replace](https://www.php.net/manual/zh/function.substr-replace.php) — 替换字符串的子串
- [substr](https://www.php.net/manual/zh/function.substr.php) — 返回字符串的子串
- [trim](https://www.php.net/manual/zh/function.trim.php) — 去除字符串首尾处的空白字符（或者其他字符）
- [ucfirst](https://www.php.net/manual/zh/function.ucfirst.php) — 将字符串的首字母转换为大写
- [ucwords](https://www.php.net/manual/zh/function.ucwords.php) — 将字符串中每个单词的首字母转换为大写
- [vfprintf](https://www.php.net/manual/zh/function.vfprintf.php) — 将格式化字符串写入流
- [vprintf](https://www.php.net/manual/zh/function.vprintf.php) — 输出格式化字符串
- [vsprintf](https://www.php.net/manual/zh/function.vsprintf.php) — 返回格式化字符串
- [wordwrap](https://www.php.net/manual/zh/function.wordwrap.php) — 打断字符串为指定数量的字串

<h3 id='多字节字符串'>多字节字符串</h3>

- [mb_check_encoding](https://www.php.net/manual/zh/function.mb-check-encoding.php) — 检查字符串在指定的编码里是否有效
- [mb_chr](https://www.php.net/manual/zh/function.mb-chr.php) — Get a specific character
- [mb_convert_case](https://www.php.net/manual/zh/function.mb-convert-case.php) — 对字符串进行大小写转换
- [mb_convert_encoding](https://www.php.net/manual/zh/function.mb-convert-encoding.php) — 转换字符的编码
- [mb_convert_kana](https://www.php.net/manual/zh/function.mb-convert-kana.php) — Convert &quot;kana&quot; one from another (&quot;zen-kaku&quot;, &quot;han-kaku&quot; and more)
- [mb_convert_variables](https://www.php.net/manual/zh/function.mb-convert-variables.php) — 转换一个或多个变量的字符编码
- [mb_decode_mimeheader](https://www.php.net/manual/zh/function.mb-decode-mimeheader.php) — 解码 MIME 头字段中的字符串
- [mb_decode_numericentity](https://www.php.net/manual/zh/function.mb-decode-numericentity.php) — 根据 HTML 数字字符串解码成字符
- [mb_detect_encoding](https://www.php.net/manual/zh/function.mb-detect-encoding.php) — 检测字符的编码
- [mb_detect_order](https://www.php.net/manual/zh/function.mb-detect-order.php) — 设置/获取 字符编码的检测顺序
- [mb_encode_mimeheader](https://www.php.net/manual/zh/function.mb-encode-mimeheader.php) — 为 MIME 头编码字符串
- [mb_encode_numericentity](https://www.php.net/manual/zh/function.mb-encode-numericentity.php) — Encode character to HTML numeric string reference
- [mb_encoding_aliases](https://www.php.net/manual/zh/function.mb-encoding-aliases.php) — Get aliases of a known encoding type
- [mb_ereg_match](https://www.php.net/manual/zh/function.mb-ereg-match.php) — Regular expression match for multibyte string
- [mb_ereg_replace_callback](https://www.php.net/manual/zh/function.mb-ereg-replace-callback.php) — Perform a regular expression search and replace with multibyte support using a callback
- [mb_ereg_replace](https://www.php.net/manual/zh/function.mb-ereg-replace.php) — Replace regular expression with multibyte support
- [mb_ereg_search_getpos](https://www.php.net/manual/zh/function.mb-ereg-search-getpos.php) — Returns start point for next regular expression match
- [mb_ereg_search_getregs](https://www.php.net/manual/zh/function.mb-ereg-search-getregs.php) — Retrieve the result from the last multibyte regular expression match
- [mb_ereg_search_init](https://www.php.net/manual/zh/function.mb-ereg-search-init.php) — Setup string and regular expression for a multibyte regular expression match
- [mb_ereg_search_pos](https://www.php.net/manual/zh/function.mb-ereg-search-pos.php) — Returns position and length of a matched part of the multibyte regular expression for a predefined multibyte string
- [mb_ereg_search_regs](https://www.php.net/manual/zh/function.mb-ereg-search-regs.php) — Returns the matched part of a multibyte regular expression
- [mb_ereg_search_setpos](https://www.php.net/manual/zh/function.mb-ereg-search-setpos.php) — Set start point of next regular expression match
- [mb_ereg_search](https://www.php.net/manual/zh/function.mb-ereg-search.php) — Multibyte regular expression match for predefined multibyte string
- [mb_ereg](https://www.php.net/manual/zh/function.mb-ereg.php) — Regular expression match with multibyte support
- [mb_eregi_replace](https://www.php.net/manual/zh/function.mb-eregi-replace.php) — Replace regular expression with multibyte support ignoring case
- [mb_eregi](https://www.php.net/manual/zh/function.mb-eregi.php) — Regular expression match ignoring case with multibyte support
- [mb_get_info](https://www.php.net/manual/zh/function.mb-get-info.php) — 获取 mbstring 的内部设置
- [mb_http_input](https://www.php.net/manual/zh/function.mb-http-input.php) — 检测 HTTP 输入字符编码
- [mb_http_output](https://www.php.net/manual/zh/function.mb-http-output.php) — 设置/获取 HTTP 输出字符编码
- [mb_internal_encoding](https://www.php.net/manual/zh/function.mb-internal-encoding.php) — 设置/获取内部字符编码
- [mb_language](https://www.php.net/manual/zh/function.mb-language.php) — 设置/获取当前的语言
- [mb_list_encodings](https://www.php.net/manual/zh/function.mb-list-encodings.php) — 返回所有支持编码的数组
- [mb_ord](https://www.php.net/manual/zh/function.mb-ord.php) — Get code point of character
- [mb_output_handler](https://www.php.net/manual/zh/function.mb-output-handler.php) — 在输出缓冲中转换字符编码的回调函数
- [mb_parse_str](https://www.php.net/manual/zh/function.mb-parse-str.php) — 解析 GET/POST/COOKIE 数据并设置全局变量
- [mb_preferred_mime_name](https://www.php.net/manual/zh/function.mb-preferred-mime-name.php) — 获取 MIME 字符串
- [mb_regex_encoding](https://www.php.net/manual/zh/function.mb-regex-encoding.php) — Set/Get character encoding for multibyte regex
- [mb_regex_set_options](https://www.php.net/manual/zh/function.mb-regex-set-options.php) — Set/Get the default options for mbregex functions
- [mb_scrub](https://www.php.net/manual/zh/function.mb-scrub.php) — Description
- [mb_send_mail](https://www.php.net/manual/zh/function.mb-send-mail.php) — 发送编码过的邮件
- [mb_split](https://www.php.net/manual/zh/function.mb-split.php) — 使用正则表达式分割多字节字符串
- [mb_strcut](https://www.php.net/manual/zh/function.mb-strcut.php) — 获取字符的一部分
- [mb_strimwidth](https://www.php.net/manual/zh/function.mb-strimwidth.php) — 获取按指定宽度截断的字符串
- [mb_stripos](https://www.php.net/manual/zh/function.mb-stripos.php) — 大小写不敏感地查找字符串在另一个字符串中首次出现的位置
- [mb_stristr](https://www.php.net/manual/zh/function.mb-stristr.php) — 大小写不敏感地查找字符串在另一个字符串里的首次出现
- [mb_strlen](https://www.php.net/manual/zh/function.mb-strlen.php) — 获取字符串的长度
- [mb_strpos](https://www.php.net/manual/zh/function.mb-strpos.php) — 查找字符串在另一个字符串中首次出现的位置
- [mb_strrchr](https://www.php.net/manual/zh/function.mb-strrchr.php) — 查找指定字符在另一个字符串中最后一次的出现
- [mb_strrichr](https://www.php.net/manual/zh/function.mb-strrichr.php) — 大小写不敏感地查找指定字符在另一个字符串中最后一次的出现
- [mb_strripos](https://www.php.net/manual/zh/function.mb-strripos.php) — 大小写不敏感地在字符串中查找一个字符串最后出现的位置
- [mb_strrpos](https://www.php.net/manual/zh/function.mb-strrpos.php) — 查找字符串在一个字符串中最后出现的位置
- [mb_strstr](https://www.php.net/manual/zh/function.mb-strstr.php) — 查找字符串在另一个字符串里的首次出现
- [mb_strtolower](https://www.php.net/manual/zh/function.mb-strtolower.php) — 使字符串小写
- [mb_strtoupper](https://www.php.net/manual/zh/function.mb-strtoupper.php) — 使字符串大写
- [mb_strwidth](https://www.php.net/manual/zh/function.mb-strwidth.php) — 返回字符串的宽度
- [mb_substitute_character](https://www.php.net/manual/zh/function.mb-substitute-character.php) — 设置/获取替代字符
- [mb_substr_count](https://www.php.net/manual/zh/function.mb-substr-count.php) — 统计字符串出现的次数
- [mb_substr](https://www.php.net/manual/zh/function.mb-substr.php) — 获取部分字符串

<h3 id='变量处理'>变量处理</h3>

- [boolval](https://www.php.net/manual/zh/function.boolval.php) — 获取变量的布尔值
- [debug_zval_dump](https://www.php.net/manual/zh/function.debug-zval-dump.php) — Dumps a string representation of an internal zend value to output
- [doubleval](https://www.php.net/manual/zh/function.doubleval.php) — floatval 的别名
- [empty](https://www.php.net/manual/zh/function.empty.php) — 检查一个变量是否为空
- [floatval](https://www.php.net/manual/zh/function.floatval.php) — 获取变量的浮点值
- [get_defined_vars](https://www.php.net/manual/zh/function.get-defined-vars.php) — 返回由所有已定义变量所组成的数组
- [get_resource_type](https://www.php.net/manual/zh/function.get-resource-type.php) — 返回资源（resource）类型
- [gettype](https://www.php.net/manual/zh/function.gettype.php) — 获取变量的类型
- [import_request_variables](https://www.php.net/manual/zh/function.import-request-variables.php) — 将 GET／POST／Cookie 变量导入到全局作用域中
- [intval](https://www.php.net/manual/zh/function.intval.php) — 获取变量的整数值
- [is_array](https://www.php.net/manual/zh/function.is-array.php) — 检测变量是否是数组
- [is_bool](https://www.php.net/manual/zh/function.is-bool.php) — 检测变量是否是布尔型
- [is_callable](https://www.php.net/manual/zh/function.is-callable.php) — 检测参数是否为合法的可调用结构
- [is_countable](https://www.php.net/manual/zh/function.is-countable.php) — Verify that the contents of a variable is a countable value
- [is_double](https://www.php.net/manual/zh/function.is-double.php) — is_float 的别名
- [is_float](https://www.php.net/manual/zh/function.is-float.php) — 检测变量是否是浮点型
- [is_int](https://www.php.net/manual/zh/function.is-int.php) — 检测变量是否是整数
- [is_integer](https://www.php.net/manual/zh/function.is-integer.php) — is_int 的别名
- [is_iterable](https://www.php.net/manual/zh/function.is-iterable.php) — Verify that the contents of a variable is an iterable value
- [is_long](https://www.php.net/manual/zh/function.is-long.php) — is_int 的别名
- [is_null](https://www.php.net/manual/zh/function.is-null.php) — 检测变量是否为 NULL
- [is_numeric](https://www.php.net/manual/zh/function.is-numeric.php) — 检测变量是否为数字或数字字符串
- [is_object](https://www.php.net/manual/zh/function.is-object.php) — 检测变量是否是一个对象
- [is_real](https://www.php.net/manual/zh/function.is-real.php) — is_float 的别名
- [is_resource](https://www.php.net/manual/zh/function.is-resource.php) — 检测变量是否为资源类型
- [is_scalar](https://www.php.net/manual/zh/function.is-scalar.php) — 检测变量是否是一个标量
- [is_string](https://www.php.net/manual/zh/function.is-string.php) — 检测变量是否是字符串
- [isset](https://www.php.net/manual/zh/function.isset.php) — 检测变量是否已设置并且非 NULL
- [print_r](https://www.php.net/manual/zh/function.print-r.php) — 以易于理解的格式打印变量。
- [serialize](https://www.php.net/manual/zh/function.serialize.php) — 产生一个可存储的值的表示
- [settype](https://www.php.net/manual/zh/function.settype.php) — 设置变量的类型
- [strval](https://www.php.net/manual/zh/function.strval.php) — 获取变量的字符串值
- [unserialize](https://www.php.net/manual/zh/function.unserialize.php) — 从已存储的表示中创建 PHP 的值
- [unset](https://www.php.net/manual/zh/function.unset.php) — 释放给定的变量
- [var_dump](https://www.php.net/manual/zh/function.var-dump.php) — 打印变量的相关信息
- [var_export](https://www.php.net/manual/zh/function.var-export.php) — 输出或返回一个变量的字符串表示

<h3 id='文件系统'>文件系统</h3>

- [basename](https://www.php.net/manual/zh/function.basename.php) — 返回路径中的文件名部分
- [chgrp](https://www.php.net/manual/zh/function.chgrp.php) — 改变文件所属的组
- [chmod](https://www.php.net/manual/zh/function.chmod.php) — 改变文件模式
- [chown](https://www.php.net/manual/zh/function.chown.php) — 改变文件的所有者
- [clearstatcache](https://www.php.net/manual/zh/function.clearstatcache.php) — 清除文件状态缓存
- [copy](https://www.php.net/manual/zh/function.copy.php) — 拷贝文件
- [delete](https://www.php.net/manual/zh/function.delete.php) — 参见 unlink 或 unset
- [dirname](https://www.php.net/manual/zh/function.dirname.php) — 返回路径中的目录部分
- [disk_free_space](https://www.php.net/manual/zh/function.disk-free-space.php) — 返回目录中的可用空间
- [disk_total_space](https://www.php.net/manual/zh/function.disk-total-space.php) — 返回一个目录的磁盘总大小
- [diskfreespace](https://www.php.net/manual/zh/function.diskfreespace.php) — disk_free_space 的别名
- [fclose](https://www.php.net/manual/zh/function.fclose.php) — 关闭一个已打开的文件指针
- [feof](https://www.php.net/manual/zh/function.feof.php) — 测试文件指针是否到了文件结束的位置
- [fflush](https://www.php.net/manual/zh/function.fflush.php) — 将缓冲内容输出到文件
- [fgetc](https://www.php.net/manual/zh/function.fgetc.php) — 从文件指针中读取字符
- [fgetcsv](https://www.php.net/manual/zh/function.fgetcsv.php) — 从文件指针中读入一行并解析 CSV 字段
- [fgets](https://www.php.net/manual/zh/function.fgets.php) — 从文件指针中读取一行
- [fgetss](https://www.php.net/manual/zh/function.fgetss.php) — 从文件指针中读取一行并过滤掉 HTML 标记
- [file_exists](https://www.php.net/manual/zh/function.file-exists.php) — 检查文件或目录是否存在
- [file_get_contents](https://www.php.net/manual/zh/function.file-get-contents.php) — 将整个文件读入一个字符串
- [file_put_contents](https://www.php.net/manual/zh/function.file-put-contents.php) — 将一个字符串写入文件
- [file](https://www.php.net/manual/zh/function.file.php) — 把整个文件读入一个数组中
- [fileatime](https://www.php.net/manual/zh/function.fileatime.php) — 取得文件的上次访问时间
- [filectime](https://www.php.net/manual/zh/function.filectime.php) — 取得文件的 inode 修改时间
- [filegroup](https://www.php.net/manual/zh/function.filegroup.php) — 取得文件的组
- [fileinode](https://www.php.net/manual/zh/function.fileinode.php) — 取得文件的 inode
- [filemtime](https://www.php.net/manual/zh/function.filemtime.php) — 取得文件修改时间
- [fileowner](https://www.php.net/manual/zh/function.fileowner.php) — 取得文件的所有者
- [fileperms](https://www.php.net/manual/zh/function.fileperms.php) — 取得文件的权限
- [filesize](https://www.php.net/manual/zh/function.filesize.php) — 取得文件大小
- [filetype](https://www.php.net/manual/zh/function.filetype.php) — 取得文件类型
- [flock](https://www.php.net/manual/zh/function.flock.php) — 轻便的咨询文件锁定
- [fnmatch](https://www.php.net/manual/zh/function.fnmatch.php) — 用模式匹配文件名
- [fopen](https://www.php.net/manual/zh/function.fopen.php) — 打开文件或者 URL
- [fpassthru](https://www.php.net/manual/zh/function.fpassthru.php) — 输出文件指针处的所有剩余数据
- [fputcsv](https://www.php.net/manual/zh/function.fputcsv.php) — 将行格式化为 CSV 并写入文件指针
- [fputs](https://www.php.net/manual/zh/function.fputs.php) — fwrite 的别名
- [fread](https://www.php.net/manual/zh/function.fread.php) — 读取文件（可安全用于二进制文件）
- [fscanf](https://www.php.net/manual/zh/function.fscanf.php) — 从文件中格式化输入
- [fseek](https://www.php.net/manual/zh/function.fseek.php) — 在文件指针中定位
- [fstat](https://www.php.net/manual/zh/function.fstat.php) — 通过已打开的文件指针取得文件信息
- [ftell](https://www.php.net/manual/zh/function.ftell.php) — 返回文件指针读/写的位置
- [ftruncate](https://www.php.net/manual/zh/function.ftruncate.php) — 将文件截断到给定的长度
- [fwrite](https://www.php.net/manual/zh/function.fwrite.php) — 写入文件（可安全用于二进制文件）
- [glob](https://www.php.net/manual/zh/function.glob.php) — 寻找与模式匹配的文件路径
- [is_dir](https://www.php.net/manual/zh/function.is-dir.php) — 判断给定文件名是否是一个目录
- [is_executable](https://www.php.net/manual/zh/function.is-executable.php) — 判断给定文件名是否可执行
- [is_file](https://www.php.net/manual/zh/function.is-file.php) — 判断给定文件名是否为一个正常的文件
- [is_link](https://www.php.net/manual/zh/function.is-link.php) — 判断给定文件名是否为一个符号连接
- [is_readable](https://www.php.net/manual/zh/function.is-readable.php) — 判断给定文件名是否可读
- [is_uploaded_file](https://www.php.net/manual/zh/function.is-uploaded-file.php) — 判断文件是否是通过 HTTP POST 上传的
- [is_writable](https://www.php.net/manual/zh/function.is-writable.php) — 判断给定的文件名是否可写
- [is_writeable](https://www.php.net/manual/zh/function.is-writeable.php) — is_writable 的别名
- [lchgrp](https://www.php.net/manual/zh/function.lchgrp.php) — 修改符号链接的所有组
- [lchown](https://www.php.net/manual/zh/function.lchown.php) — 修改符号链接的所有者
- [link](https://www.php.net/manual/zh/function.link.php) — 建立一个硬连接
- [linkinfo](https://www.php.net/manual/zh/function.linkinfo.php) — 获取一个连接的信息
- [lstat](https://www.php.net/manual/zh/function.lstat.php) — 给出一个文件或符号连接的信息
- [mkdir](https://www.php.net/manual/zh/function.mkdir.php) — 新建目录
- [move_uploaded_file](https://www.php.net/manual/zh/function.move-uploaded-file.php) — 将上传的文件移动到新位置
- [parse_ini_file](https://www.php.net/manual/zh/function.parse-ini-file.php) — 解析一个配置文件
- [parse_ini_string](https://www.php.net/manual/zh/function.parse-ini-string.php) — 解析配置字符串
- [pathinfo](https://www.php.net/manual/zh/function.pathinfo.php) — 返回文件路径的信息
- [pclose](https://www.php.net/manual/zh/function.pclose.php) — 关闭进程文件指针
- [popen](https://www.php.net/manual/zh/function.popen.php) — 打开进程文件指针
- [readfile](https://www.php.net/manual/zh/function.readfile.php) — 输出文件
- [readlink](https://www.php.net/manual/zh/function.readlink.php) — 返回符号连接指向的目标
- [realpath_cache_get](https://www.php.net/manual/zh/function.realpath-cache-get.php) — 获取真实目录缓存的详情
- [realpath_cache_size](https://www.php.net/manual/zh/function.realpath-cache-size.php) — 获取真实路径缓冲区的大小
- [realpath](https://www.php.net/manual/zh/function.realpath.php) — 返回规范化的绝对路径名
- [rename](https://www.php.net/manual/zh/function.rename.php) — 重命名一个文件或目录
- [rewind](https://www.php.net/manual/zh/function.rewind.php) — 倒回文件指针的位置
- [rmdir](https://www.php.net/manual/zh/function.rmdir.php) — 删除目录
- [set_file_buffer](https://www.php.net/manual/zh/function.set-file-buffer.php) — stream_set_write_buffer 的别名
- [stat](https://www.php.net/manual/zh/function.stat.php) — 给出文件的信息
- [symlink](https://www.php.net/manual/zh/function.symlink.php) — 建立符号连接
- [tempnam](https://www.php.net/manual/zh/function.tempnam.php) — 建立一个具有唯一文件名的文件
- [tmpfile](https://www.php.net/manual/zh/function.tmpfile.php) — 建立一个临时文件
- [touch](https://www.php.net/manual/zh/function.touch.php) — 设定文件的访问和修改时间
- [umask](https://www.php.net/manual/zh/function.umask.php) — 改变当前的 umask
- [unlink](https://www.php.net/manual/zh/function.unlink.php) — 删除文件

<h3 id='目录处理'>目录处理</h3>

- [chdir](https://www.php.net/manual/zh/function.chdir.php) — 改变目录
- [chroot](https://www.php.net/manual/zh/function.chroot.php) — 改变根目录
- [closedir](https://www.php.net/manual/zh/function.closedir.php) — 关闭目录句柄
- [dir](https://www.php.net/manual/zh/function.dir.php) — 返回一个 Directory 类实例
- [getcwd](https://www.php.net/manual/zh/function.getcwd.php) — 取得当前工作目录
- [opendir](https://www.php.net/manual/zh/function.opendir.php) — 打开目录句柄
- [readdir](https://www.php.net/manual/zh/function.readdir.php) — 从目录句柄中读取条目
- [rewinddir](https://www.php.net/manual/zh/function.rewinddir.php) — 倒回目录句柄
- [scandir](https://www.php.net/manual/zh/function.scandir.php) — 列出指定路径中的文件和目录

<h3 id='数学'>数学</h3>

- [abs](https://www.php.net/manual/zh/function.abs.php) — 绝对值
- [acos](https://www.php.net/manual/zh/function.acos.php) — 反余弦
- [acosh](https://www.php.net/manual/zh/function.acosh.php) — 反双曲余弦
- [asin](https://www.php.net/manual/zh/function.asin.php) — 反正弦
- [asinh](https://www.php.net/manual/zh/function.asinh.php) — 反双曲正弦
- [atan2](https://www.php.net/manual/zh/function.atan2.php) — 两个参数的反正切
- [atan](https://www.php.net/manual/zh/function.atan.php) — 反正切
- [atanh](https://www.php.net/manual/zh/function.atanh.php) — 反双曲正切
- [base_convert](https://www.php.net/manual/zh/function.base-convert.php) — 在任意进制之间转换数字
- [bindec](https://www.php.net/manual/zh/function.bindec.php) — 二进制转换为十进制
- [ceil](https://www.php.net/manual/zh/function.ceil.php) — 进一法取整
- [cos](https://www.php.net/manual/zh/function.cos.php) — 余弦
- [cosh](https://www.php.net/manual/zh/function.cosh.php) — 双曲余弦
- [decbin](https://www.php.net/manual/zh/function.decbin.php) — 十进制转换为二进制
- [dechex](https://www.php.net/manual/zh/function.dechex.php) — 十进制转换为十六进制
- [decoct](https://www.php.net/manual/zh/function.decoct.php) — 十进制转换为八进制
- [deg2rad](https://www.php.net/manual/zh/function.deg2rad.php) — 将角度转换为弧度
- [exp](https://www.php.net/manual/zh/function.exp.php) — 计算 e 的指数
- [expm1](https://www.php.net/manual/zh/function.expm1.php) — 返回 exp(number) - 1，甚至当 number 的值接近零也能计算出准确结果
- [floor](https://www.php.net/manual/zh/function.floor.php) — 舍去法取整
- [fmod](https://www.php.net/manual/zh/function.fmod.php) — 返回除法的浮点数余数
- [getrandmax](https://www.php.net/manual/zh/function.getrandmax.php) — 显示随机数最大的可能值
- [hexdec](https://www.php.net/manual/zh/function.hexdec.php) — 十六进制转换为十进制
- [hypot](https://www.php.net/manual/zh/function.hypot.php) — 计算一直角三角形的斜边长度
- [intdiv](https://www.php.net/manual/zh/function.intdiv.php) — 对除法结果取整
- [is_finite](https://www.php.net/manual/zh/function.is-finite.php) — 判断是否为有限值
- [is_infinite](https://www.php.net/manual/zh/function.is-infinite.php) — 判断是否为无限值
- [is_nan](https://www.php.net/manual/zh/function.is-nan.php) — 判断是否为合法数值
- [lcg_value](https://www.php.net/manual/zh/function.lcg-value.php) — 组合线性同余发生器
- [log10](https://www.php.net/manual/zh/function.log10.php) — 以 10 为底的对数
- [log1p](https://www.php.net/manual/zh/function.log1p.php) — 返回 log(1 + number)，甚至当 number 的值接近零也能计算出准确结果
- [log](https://www.php.net/manual/zh/function.log.php) — 自然对数
- [max](https://www.php.net/manual/zh/function.max.php) — 找出最大值
- [min](https://www.php.net/manual/zh/function.min.php) — 找出最小值
- [mt_getrandmax](https://www.php.net/manual/zh/function.mt-getrandmax.php) — 显示随机数的最大可能值
- [mt_rand](https://www.php.net/manual/zh/function.mt-rand.php) — 生成更好的随机数
- [mt_srand](https://www.php.net/manual/zh/function.mt-srand.php) — 播下一个更好的随机数发生器种子
- [octdec](https://www.php.net/manual/zh/function.octdec.php) — 八进制转换为十进制
- [pi](https://www.php.net/manual/zh/function.pi.php) — 得到圆周率值
- [pow](https://www.php.net/manual/zh/function.pow.php) — 指数表达式
- [rad2deg](https://www.php.net/manual/zh/function.rad2deg.php) — 将弧度数转换为相应的角度数
- [rand](https://www.php.net/manual/zh/function.rand.php) — 产生一个随机整数
- [round](https://www.php.net/manual/zh/function.round.php) — 对浮点数进行四舍五入
- [sin](https://www.php.net/manual/zh/function.sin.php) — 正弦
- [sinh](https://www.php.net/manual/zh/function.sinh.php) — 双曲正弦
- [sqrt](https://www.php.net/manual/zh/function.sqrt.php) — 平方根
- [srand](https://www.php.net/manual/zh/function.srand.php) — 播下随机数发生器种子
- [tan](https://www.php.net/manual/zh/function.tan.php) — 正切
- [tanh](https://www.php.net/manual/zh/function.tanh.php) — 双曲正切

<h3 id='类和对象'>类和对象</h3>

- [__autoload](https://www.php.net/manual/zh/function.autoload.php) — 尝试加载未定义的类
- [call_user_method_array](https://www.php.net/manual/zh/function.call-user-method-array.php) — 以参数列表的数组，调用用户方法
- [call_user_method](https://www.php.net/manual/zh/function.call-user-method.php) — 对特定对象调用用户方法
- [class_alias](https://www.php.net/manual/zh/function.class-alias.php) — 为一个类创建别名
- [class_exists](https://www.php.net/manual/zh/function.class-exists.php) — 检查类是否已定义
- [get_called_class](https://www.php.net/manual/zh/function.get-called-class.php) — 后期静态绑定（&quot;Late Static Binding&quot;）类的名称
- [get_class_methods](https://www.php.net/manual/zh/function.get-class-methods.php) — 返回由类的方法名组成的数组
- [get_class_vars](https://www.php.net/manual/zh/function.get-class-vars.php) — 返回由类的默认属性组成的数组
- [get_class](https://www.php.net/manual/zh/function.get-class.php) — 返回对象的类名
- [get_declared_classes](https://www.php.net/manual/zh/function.get-declared-classes.php) — 返回由已定义类的名字所组成的数组
- [get_declared_interfaces](https://www.php.net/manual/zh/function.get-declared-interfaces.php) — 返回一个数组包含所有已声明的接口
- [get_declared_traits](https://www.php.net/manual/zh/function.get-declared-traits.php) — 返回所有已定义的 traits 的数组
- [get_object_vars](https://www.php.net/manual/zh/function.get-object-vars.php) — 返回由对象属性组成的关联数组
- [get_parent_class](https://www.php.net/manual/zh/function.get-parent-class.php) — 返回对象或类的父类名
- [interface_exists](https://www.php.net/manual/zh/function.interface-exists.php) — 检查接口是否已被定义
- [is_a](https://www.php.net/manual/zh/function.is-a.php) — 如果对象属于该类或该类是此对象的父类则返回 TRUE
- [is_subclass_of](https://www.php.net/manual/zh/function.is-subclass-of.php) — 如果此对象是该类的子类，则返回 TRUE
- [method_exists](https://www.php.net/manual/zh/function.method-exists.php) — 检查类的方法是否存在
- [property_exists](https://www.php.net/manual/zh/function.property-exists.php) — 检查对象或类是否具有该属性
- [trait_exists](https://www.php.net/manual/zh/function.trait-exists.php) — 检查指定的 trait 是否存在

<h3 id='字符类型检测'>字符类型检测</h3>

- [ctype_alnum](https://www.php.net/manual/zh/function.ctype-alnum.php) — 做字母和数字字符检测
- [ctype_alpha](https://www.php.net/manual/zh/function.ctype-alpha.php) — 做纯字符检测
- [ctype_cntrl](https://www.php.net/manual/zh/function.ctype-cntrl.php) — 做控制字符检测
- [ctype_digit](https://www.php.net/manual/zh/function.ctype-digit.php) — 做纯数字检测
- [ctype_graph](https://www.php.net/manual/zh/function.ctype-graph.php) — 做可打印字符串检测，空格除外
- [ctype_lower](https://www.php.net/manual/zh/function.ctype-lower.php) — 做小写字符检测
- [ctype_print](https://www.php.net/manual/zh/function.ctype-print.php) — 做可打印字符检测
- [ctype_punct](https://www.php.net/manual/zh/function.ctype-punct.php) — 检测可打印的字符是不是不包含空白、数字和字母
- [ctype_space](https://www.php.net/manual/zh/function.ctype-space.php) — 做空白字符检测
- [ctype_upper](https://www.php.net/manual/zh/function.ctype-upper.php) — 做大写字母检测
- [ctype_xdigit](https://www.php.net/manual/zh/function.ctype-xdigit.php) — 检测字符串是否只包含十六进制字符

<h3 id='日期和时间'>日期和时间</h3>

- [checkdate](https://www.php.net/manual/zh/function.checkdate.php) — 验证一个格里高里日期
- [date_add](https://www.php.net/manual/zh/function.date-add.php) — 别名 DateTime::add
- [date_create_from_format](https://www.php.net/manual/zh/function.date-create-from-format.php) — 别名 DateTime::createFromFormat
- [date_create_immutable_from_format](https://www.php.net/manual/zh/function.date-create-immutable-from-format.php) — 别名 DateTimeImmutable::createFromFormat
- [date_create_immutable](https://www.php.net/manual/zh/function.date-create-immutable.php) — 别名 DateTimeImmutable::__construct
- [date_create](https://www.php.net/manual/zh/function.date-create.php) — 别名 DateTime::__construct
- [date_date_set](https://www.php.net/manual/zh/function.date-date-set.php) — 别名 DateTime::setDate
- [date_default_timezone_get](https://www.php.net/manual/zh/function.date-default-timezone-get.php) — 取得一个脚本中所有日期时间函数所使用的默认时区
- [date_default_timezone_set](https://www.php.net/manual/zh/function.date-default-timezone-set.php) — 设定用于一个脚本中所有日期时间函数的默认时区
- [date_diff](https://www.php.net/manual/zh/function.date-diff.php) — 别名 DateTime::diff
- [date_format](https://www.php.net/manual/zh/function.date-format.php) — 别名 DateTime::format
- [date_get_last_errors](https://www.php.net/manual/zh/function.date-get-last-errors.php) — 别名 DateTime::getLastErrors
- [date_interval_create_from_date_string](https://www.php.net/manual/zh/function.date-interval-create-from-date-string.php) — 别名 DateInterval::createFromDateString
- [date_interval_format](https://www.php.net/manual/zh/function.date-interval-format.php) — 别名 DateInterval::format
- [date_isodate_set](https://www.php.net/manual/zh/function.date-isodate-set.php) — 别名 DateTime::setISODate
- [date_modify](https://www.php.net/manual/zh/function.date-modify.php) — 别名 DateTime::modify
- [date_offset_get](https://www.php.net/manual/zh/function.date-offset-get.php) — 别名 DateTime::getOffset
- [date_parse_from_format](https://www.php.net/manual/zh/function.date-parse-from-format.php) — Get info about given date formatted according to the specified format
- [date_parse](https://www.php.net/manual/zh/function.date-parse.php) — Returns associative array with detailed info about given date
- [date_sub](https://www.php.net/manual/zh/function.date-sub.php) — 别名 DateTime::sub
- [date_sun_info](https://www.php.net/manual/zh/function.date-sun-info.php) — Returns an array with information about sunset/sunrise and twilight begin/end
- [date_sunrise](https://www.php.net/manual/zh/function.date-sunrise.php) — 返回给定的日期与地点的日出时间
- [date_sunset](https://www.php.net/manual/zh/function.date-sunset.php) — 返回给定的日期与地点的日落时间
- [date_time_set](https://www.php.net/manual/zh/function.date-time-set.php) — 别名 DateTime::setTime
- [date_timestamp_get](https://www.php.net/manual/zh/function.date-timestamp-get.php) — 别名 DateTime::getTimestamp
- [date_timestamp_set](https://www.php.net/manual/zh/function.date-timestamp-set.php) — 别名 DateTime::setTimestamp
- [date_timezone_get](https://www.php.net/manual/zh/function.date-timezone-get.php) — 别名 DateTime::getTimezone
- [date_timezone_set](https://www.php.net/manual/zh/function.date-timezone-set.php) — 别名 DateTime::setTimezone
- [date](https://www.php.net/manual/zh/function.date.php) — 格式化一个本地时间／日期
- [getdate](https://www.php.net/manual/zh/function.getdate.php) — 取得日期／时间信息
- [gettimeofday](https://www.php.net/manual/zh/function.gettimeofday.php) — 取得当前时间
- [gmdate](https://www.php.net/manual/zh/function.gmdate.php) — 格式化一个 GMT/UTC 日期／时间
- [gmmktime](https://www.php.net/manual/zh/function.gmmktime.php) — 取得 GMT 日期的 UNIX 时间戳
- [gmstrftime](https://www.php.net/manual/zh/function.gmstrftime.php) — 根据区域设置格式化 GMT/UTC 时间／日期
- [idate](https://www.php.net/manual/zh/function.idate.php) — 将本地时间日期格式化为整数
- [localtime](https://www.php.net/manual/zh/function.localtime.php) — 取得本地时间
- [microtime](https://www.php.net/manual/zh/function.microtime.php) — 返回当前 Unix 时间戳和微秒数
- [mktime](https://www.php.net/manual/zh/function.mktime.php) — 取得一个日期的 Unix 时间戳
- [strftime](https://www.php.net/manual/zh/function.strftime.php) — 根据区域设置格式化本地时间／日期
- [strptime](https://www.php.net/manual/zh/function.strptime.php) — 解析由 strftime 生成的日期／时间
- [strtotime](https://www.php.net/manual/zh/function.strtotime.php) — 将任何字符串的日期时间描述解析为 Unix 时间戳
- [time](https://www.php.net/manual/zh/function.time.php) — 返回当前的 Unix 时间戳
- [timezone_abbreviations_list](https://www.php.net/manual/zh/function.timezone-abbreviations-list.php) — 别名 DateTimeZone::listAbbreviations
- [timezone_identifiers_list](https://www.php.net/manual/zh/function.timezone-identifiers-list.php) — 别名 DateTimeZone::listIdentifiers
- [timezone_location_get](https://www.php.net/manual/zh/function.timezone-location-get.php) — 别名 DateTimeZone::getLocation
- [timezone_name_from_abbr](https://www.php.net/manual/zh/function.timezone-name-from-abbr.php) — Returns the timezone name from abbreviation
- [timezone_name_get](https://www.php.net/manual/zh/function.timezone-name-get.php) — 别名 DateTimeZone::getName
- [timezone_offset_get](https://www.php.net/manual/zh/function.timezone-offset-get.php) — 别名 DateTimeZone::getOffset
- [timezone_open](https://www.php.net/manual/zh/function.timezone-open.php) — 别名 DateTimeZone::__construct
- [timezone_transitions_get](https://www.php.net/manual/zh/function.timezone-transitions-get.php) — 别名 DateTimeZone::getTransitions
- [timezone_version_get](https://www.php.net/manual/zh/function.timezone-version-get.php) — Gets the version of the timezonedb

<h3 id='CURL'>CURL</h3>

- [curl_close](https://www.php.net/manual/zh/function.curl-close.php) — 关闭 cURL 会话
- [curl_copy_handle](https://www.php.net/manual/zh/function.curl-copy-handle.php) — 复制一个cURL句柄和它的所有选项
- [curl_errno](https://www.php.net/manual/zh/function.curl-errno.php) — 返回最后一次的错误代码
- [curl_error](https://www.php.net/manual/zh/function.curl-error.php) — 返回当前会话最后一次错误的字符串
- [curl_escape](https://www.php.net/manual/zh/function.curl-escape.php) — 使用 URL 编码给定的字符串
- [curl_exec](https://www.php.net/manual/zh/function.curl-exec.php) — 执行 cURL 会话
- [curl_file_create](https://www.php.net/manual/zh/function.curl-file-create.php) — 创建一个 CURLFile 对象
- [curl_getinfo](https://www.php.net/manual/zh/function.curl-getinfo.php) — 获取一个cURL连接资源句柄的信息
- [curl_init](https://www.php.net/manual/zh/function.curl-init.php) — 初始化 cURL 会话
- [curl_multi_add_handle](https://www.php.net/manual/zh/function.curl-multi-add-handle.php) — 向curl批处理会话中添加单独的curl句柄
- [curl_multi_close](https://www.php.net/manual/zh/function.curl-multi-close.php) — 关闭一组cURL句柄
- [curl_multi_errno](https://www.php.net/manual/zh/function.curl-multi-errno.php) — 返回上一次 curl 批处理的错误码
- [curl_multi_exec](https://www.php.net/manual/zh/function.curl-multi-exec.php) — 运行当前 cURL 句柄的子连接
- [curl_multi_getcontent](https://www.php.net/manual/zh/function.curl-multi-getcontent.php) — 如果设置了CURLOPT_RETURNTRANSFER，则返回获取的输出的文本流
- [curl_multi_info_read](https://www.php.net/manual/zh/function.curl-multi-info-read.php) — 获取当前解析的cURL的相关传输信息
- [curl_multi_init](https://www.php.net/manual/zh/function.curl-multi-init.php) — 返回一个新cURL批处理句柄
- [curl_multi_remove_handle](https://www.php.net/manual/zh/function.curl-multi-remove-handle.php) — 移除cURL批处理句柄资源中的某个句柄资源
- [curl_multi_select](https://www.php.net/manual/zh/function.curl-multi-select.php) — 等待所有cURL批处理中的活动连接
- [curl_multi_setopt](https://www.php.net/manual/zh/function.curl-multi-setopt.php) — 为 cURL 并行处理设置一个选项
- [curl_multi_strerror](https://www.php.net/manual/zh/function.curl-multi-strerror.php) — 返回字符串描述的错误代码
- [curl_pause](https://www.php.net/manual/zh/function.curl-pause.php) — 暂停和取消暂停一个连接。
- [curl_reset](https://www.php.net/manual/zh/function.curl-reset.php) — 重置一个 libcurl 会话句柄的所有的选项
- [curl_setopt_array](https://www.php.net/manual/zh/function.curl-setopt-array.php) — 为 cURL 传输会话批量设置选项
- [curl_setopt](https://www.php.net/manual/zh/function.curl-setopt.php) — 设置 cURL 传输选项
- [curl_share_close](https://www.php.net/manual/zh/function.curl-share-close.php) — 关闭 cURL 共享句柄
- [curl_share_errno](https://www.php.net/manual/zh/function.curl-share-errno.php) — 返回共享 curl 句柄的最后一次错误号
- [curl_share_init](https://www.php.net/manual/zh/function.curl-share-init.php) — 初始化一个 cURL 共享句柄。
- [curl_share_setopt](https://www.php.net/manual/zh/function.curl-share-setopt.php) — 为 cURL 共享句柄设置选项。
- [curl_share_strerror](https://www.php.net/manual/zh/function.curl-share-strerror.php) — 返回错误号对应的错误消息
- [curl_strerror](https://www.php.net/manual/zh/function.curl-strerror.php) — 返回错误代码的字符串描述
- [curl_unescape](https://www.php.net/manual/zh/function.curl-unescape.php) — 解码给定的 URL 编码的字符串
- [curl_version](https://www.php.net/manual/zh/function.curl-version.php) — 获取 cURL 版本信息

<h3 id='过滤器'>过滤器</h3>

- [filter_has_var](https://www.php.net/manual/zh/function.filter-has-var.php) — 检测是否存在指定类型的变量
- [filter_id](https://www.php.net/manual/zh/function.filter-id.php) — 返回与某个特定名称的过滤器相关联的id
- [filter_input_array](https://www.php.net/manual/zh/function.filter-input-array.php) — 获取一系列外部变量，并且可以通过过滤器处理它们
- [filter_input](https://www.php.net/manual/zh/function.filter-input.php) — 通过名称获取特定的外部变量，并且可以通过过滤器处理它
- [filter_list](https://www.php.net/manual/zh/function.filter-list.php) — 返回所支持的过滤器列表
- [filter_var_array](https://www.php.net/manual/zh/function.filter-var-array.php) — 获取多个变量并且过滤它们
- [filter_var](https://www.php.net/manual/zh/function.filter-var.php) — 使用特定的过滤器过滤一个变量

<h3 id='函数处理'>函数处理</h3>

- [call_user_func_array](https://www.php.net/manual/zh/function.call-user-func-array.php) — 调用回调函数，并把一个数组参数作为回调函数的参数
- [call_user_func](https://www.php.net/manual/zh/function.call-user-func.php) — 把第一个参数作为回调函数调用
- [create_function](https://www.php.net/manual/zh/function.create-function.php) — Create an anonymous (lambda-style) function
- [forward_static_call_array](https://www.php.net/manual/zh/function.forward-static-call-array.php) — Call a static method and pass the arguments as array
- [forward_static_call](https://www.php.net/manual/zh/function.forward-static-call.php) — Call a static method
- [func_get_arg](https://www.php.net/manual/zh/function.func-get-arg.php) — 返回参数列表的某一项
- [func_get_args](https://www.php.net/manual/zh/function.func-get-args.php) — 返回一个包含函数参数列表的数组
- [func_num_args](https://www.php.net/manual/zh/function.func-num-args.php) — Returns the number of arguments passed to the function
- [function_exists](https://www.php.net/manual/zh/function.function-exists.php) — 如果给定的函数已经被定义就返回 TRUE
- [get_defined_functions](https://www.php.net/manual/zh/function.get-defined-functions.php) — 返回所有已定义函数的数组
- [register_shutdown_function](https://www.php.net/manual/zh/function.register-shutdown-function.php) — 注册一个会在php中止时执行的函数
- [register_tick_function](https://www.php.net/manual/zh/function.register-tick-function.php) — Register a function for execution on each tick
- [unregister_tick_function](https://www.php.net/manual/zh/function.unregister-tick-function.php) — De-register a function for execution on each tick

<h3 id='正则处理'>正则处理</h3>

- [preg_filter](https://www.php.net/manual/zh/function.preg-filter.php) — 执行一个正则表达式搜索和替换
- [preg_grep](https://www.php.net/manual/zh/function.preg-grep.php) — 返回匹配模式的数组条目
- [preg_last_error](https://www.php.net/manual/zh/function.preg-last-error.php) — 返回最后一个PCRE正则执行产生的错误代码
- [preg_match_all](https://www.php.net/manual/zh/function.preg-match-all.php) — 执行一个全局正则表达式匹配
- [preg_match](https://www.php.net/manual/zh/function.preg-match.php) — 执行匹配正则表达式
- [preg_quote](https://www.php.net/manual/zh/function.preg-quote.php) — 转义正则表达式字符
- [preg_replace_callback_array](https://www.php.net/manual/zh/function.preg-replace-callback-array.php) — Perform a regular expression search and replace using callbacks
- [preg_replace_callback](https://www.php.net/manual/zh/function.preg-replace-callback.php) — 执行一个正则表达式搜索并且使用一个回调进行替换
- [preg_replace](https://www.php.net/manual/zh/function.preg-replace.php) — 执行一个正则表达式的搜索和替换
- [preg_split](https://www.php.net/manual/zh/function.preg-split.php) — 通过一个正则表达式分隔字符串

<h3 id='网络'>网络</h3>

- [checkdnsrr](https://www.php.net/manual/zh/function.checkdnsrr.php) — 给指定的主机（域名）或者IP地址做DNS通信检查
- [closelog](https://www.php.net/manual/zh/function.closelog.php) — 关闭系统日志链接
- [define_syslog_variables](https://www.php.net/manual/zh/function.define-syslog-variables.php) — Initializes all syslog related variables
- [dns_check_record](https://www.php.net/manual/zh/function.dns-check-record.php) — 别名 checkdnsrr
- [dns_get_mx](https://www.php.net/manual/zh/function.dns-get-mx.php) — 别名 getmxrr
- [dns_get_record](https://www.php.net/manual/zh/function.dns-get-record.php) — 获取指定主机的DNS记录
- [fsockopen](https://www.php.net/manual/zh/function.fsockopen.php) — 打开一个网络连接或者一个Unix套接字连接
- [gethostbyaddr](https://www.php.net/manual/zh/function.gethostbyaddr.php) — 获取指定的IP地址对应的主机名
- [gethostbyname](https://www.php.net/manual/zh/function.gethostbyname.php) — 返回主机名对应的 IPv4地址。
- [gethostbynamel](https://www.php.net/manual/zh/function.gethostbynamel.php) — 获取互联网主机名对应的 IPv4 地址列表
- [gethostname](https://www.php.net/manual/zh/function.gethostname.php) — 获取主机名
- [getmxrr](https://www.php.net/manual/zh/function.getmxrr.php) — 获取互联网主机名对应的 MX 记录
- [getprotobyname](https://www.php.net/manual/zh/function.getprotobyname.php) — Get protocol number associated with protocol name
- [getprotobynumber](https://www.php.net/manual/zh/function.getprotobynumber.php) — Get protocol name associated with protocol number
- [getservbyname](https://www.php.net/manual/zh/function.getservbyname.php) — 获取互联网服务协议对应的端口
- [getservbyport](https://www.php.net/manual/zh/function.getservbyport.php) — Get Internet service which corresponds to port and protocol
- [header_register_callback](https://www.php.net/manual/zh/function.header-register-callback.php) — 调用一个 header 函数
- [header_remove](https://www.php.net/manual/zh/function.header-remove.php) — 删除之前设置的 HTTP 头
- [header](https://www.php.net/manual/zh/function.header.php) — 发送原生 HTTP 头
- [headers_list](https://www.php.net/manual/zh/function.headers-list.php) — 返回已发送的 HTTP 响应头（或准备发送的）
- [headers_sent](https://www.php.net/manual/zh/function.headers-sent.php) — 检测 HTTP 头是否已经发送
- [http_response_code](https://www.php.net/manual/zh/function.http-response-code.php) — 获取/设置响应的 HTTP 状态码
- [inet_ntop](https://www.php.net/manual/zh/function.inet-ntop.php) — Converts a packed internet address to a human readable representation
- [inet_pton](https://www.php.net/manual/zh/function.inet-pton.php) — Converts a human readable IP address to its packed in_addr representation
- [ip2long](https://www.php.net/manual/zh/function.ip2long.php) — 将 IPV4 的字符串互联网协议转换成长整型数字
- [long2ip](https://www.php.net/manual/zh/function.long2ip.php) — 将长整型转化为字符串形式带点的互联网标准格式地址（IPV4）
- [openlog](https://www.php.net/manual/zh/function.openlog.php) — Open connection to system logger
- [pfsockopen](https://www.php.net/manual/zh/function.pfsockopen.php) — 打开一个持久的网络连接或者Unix套接字连接。
- [setcookie](https://www.php.net/manual/zh/function.setcookie.php) — 发送 Cookie
- [setrawcookie](https://www.php.net/manual/zh/function.setrawcookie.php) — 发送未经 URL 编码的 cookie
- [socket_get_status](https://www.php.net/manual/zh/function.socket-get-status.php) — 别名 stream_get_meta_data
- [socket_set_blocking](https://www.php.net/manual/zh/function.socket-set-blocking.php) — 别名 stream_set_blocking
- [socket_set_timeout](https://www.php.net/manual/zh/function.socket-set-timeout.php) — 别名 stream_set_timeout
- [syslog](https://www.php.net/manual/zh/function.syslog.php) — Generate a system log message

<h3 id='程序执行'>程序执行</h3>

- [escapeshellarg](https://www.php.net/manual/zh/function.escapeshellarg.php) — 把字符串转码为可以在 shell 命令里使用的参数
- [escapeshellcmd](https://www.php.net/manual/zh/function.escapeshellcmd.php) — shell 元字符转义
- [exec](https://www.php.net/manual/zh/function.exec.php) — 执行一个外部程序
- [passthru](https://www.php.net/manual/zh/function.passthru.php) — 执行外部程序并且显示原始输出
- [proc_close](https://www.php.net/manual/zh/function.proc-close.php) — 关闭由 proc_open 打开的进程并且返回进程退出码
- [proc_get_status](https://www.php.net/manual/zh/function.proc-get-status.php) — 获取由 proc_open 函数打开的进程的信息
- [proc_nice](https://www.php.net/manual/zh/function.proc-nice.php) — 修改当前进程的优先级
- [proc_open](https://www.php.net/manual/zh/function.proc-open.php) — 执行一个命令，并且打开用来输入/输出的文件指针。
- [proc_terminate](https://www.php.net/manual/zh/function.proc-terminate.php) — 杀除由 proc_open 打开的进程
- [shell_exec](https://www.php.net/manual/zh/function.shell-exec.php) — 通过 shell 环境执行命令，并且将完整的输出以字符串的方式返回。
- [system](https://www.php.net/manual/zh/function.system.php) — 执行外部程序，并且显示输出

<h3 id='PHP选项和信息'>PHP选项和信息</h3>

- [assert_options](https://www.php.net/manual/zh/function.assert-options.php) — 设置/获取断言的各种标志
- [assert](https://www.php.net/manual/zh/function.assert.php) — 检查一个断言是否为 FALSE
- [cli_get_process_title](https://www.php.net/manual/zh/function.cli-get-process-title.php) — Returns the current process title
- [cli_set_process_title](https://www.php.net/manual/zh/function.cli-set-process-title.php) — Sets the process title
- [dl](https://www.php.net/manual/zh/function.dl.php) — 运行时载入一个 PHP 扩展
- [extension_loaded](https://www.php.net/manual/zh/function.extension-loaded.php) — 检查一个扩展是否已经加载
- [gc_collect_cycles](https://www.php.net/manual/zh/function.gc-collect-cycles.php) — 强制收集所有现存的垃圾循环周期
- [gc_disable](https://www.php.net/manual/zh/function.gc-disable.php) — 停用循环引用收集器
- [gc_enable](https://www.php.net/manual/zh/function.gc-enable.php) — 激活循环引用收集器
- [gc_enabled](https://www.php.net/manual/zh/function.gc-enabled.php) — 返回循环引用计数器的状态
- [gc_mem_caches](https://www.php.net/manual/zh/function.gc-mem-caches.php) — Reclaims memory used by the Zend Engine memory manager
- [gc_status](https://www.php.net/manual/zh/function.gc-status.php) — Gets information about the garbage collector
- [get_cfg_var](https://www.php.net/manual/zh/function.get-cfg-var.php) — 获取 PHP 配置选项的值
- [get_current_user](https://www.php.net/manual/zh/function.get-current-user.php) — 获取当前 PHP 脚本所有者名称
- [get_defined_constants](https://www.php.net/manual/zh/function.get-defined-constants.php) — 返回所有常量的关联数组，键是常量名，值是常量值
- [get_extension_funcs](https://www.php.net/manual/zh/function.get-extension-funcs.php) — 返回模块函数名称的数组
- [get_include_path](https://www.php.net/manual/zh/function.get-include-path.php) — 获取当前的 include_path 配置选项
- [get_included_files](https://www.php.net/manual/zh/function.get-included-files.php) — 返回被 include 和 require 文件名的 array
- [get_loaded_extensions](https://www.php.net/manual/zh/function.get-loaded-extensions.php) — 返回所有编译并加载模块名的 array
- [get_magic_quotes_gpc](https://www.php.net/manual/zh/function.get-magic-quotes-gpc.php) — 获取当前 magic_quotes_gpc 的配置选项设置
- [get_magic_quotes_runtime](https://www.php.net/manual/zh/function.get-magic-quotes-runtime.php) — 获取当前 magic_quotes_runtime 配置选项的激活状态
- [get_required_files](https://www.php.net/manual/zh/function.get-required-files.php) — 别名 get_included_files
- [get_resources](https://www.php.net/manual/zh/function.get-resources.php) — Returns active resources
- [getenv](https://www.php.net/manual/zh/function.getenv.php) — 获取一个环境变量的值
- [getlastmod](https://www.php.net/manual/zh/function.getlastmod.php) — 获取页面最后修改的时间
- [getmygid](https://www.php.net/manual/zh/function.getmygid.php) — 获取当前 PHP 脚本拥有者的 GID
- [getmyinode](https://www.php.net/manual/zh/function.getmyinode.php) — 获取当前脚本的索引节点（inode）
- [getmypid](https://www.php.net/manual/zh/function.getmypid.php) — 获取 PHP 进程的 ID
- [getmyuid](https://www.php.net/manual/zh/function.getmyuid.php) — 获取 PHP 脚本所有者的 UID
- [getopt](https://www.php.net/manual/zh/function.getopt.php) — 从命令行参数列表中获取选项
- [getrusage](https://www.php.net/manual/zh/function.getrusage.php) — 获取当前资源使用状况
- [ini_alter](https://www.php.net/manual/zh/function.ini-alter.php) — 别名 ini_set
- [ini_get_all](https://www.php.net/manual/zh/function.ini-get-all.php) — 获取所有配置选项
- [ini_get](https://www.php.net/manual/zh/function.ini-get.php) — 获取一个配置选项的值
- [ini_restore](https://www.php.net/manual/zh/function.ini-restore.php) — 恢复配置选项的值
- [ini_set](https://www.php.net/manual/zh/function.ini-set.php) — 为一个配置选项设置值
- [magic_quotes_runtime](https://www.php.net/manual/zh/function.magic-quotes-runtime.php) — 别名 set_magic_quotes_runtime
- [main](https://www.php.net/manual/zh/function.main.php) — 虚拟的main
- [memory_get_peak_usage](https://www.php.net/manual/zh/function.memory-get-peak-usage.php) — 返回分配给 PHP 内存的峰值
- [memory_get_usage](https://www.php.net/manual/zh/function.memory-get-usage.php) — 返回分配给 PHP 的内存量
- [php_ini_loaded_file](https://www.php.net/manual/zh/function.php-ini-loaded-file.php) — 取得已加载的 php.ini 文件的路径
- [php_ini_scanned_files](https://www.php.net/manual/zh/function.php-ini-scanned-files.php) — 返回从额外 ini 目录里解析的 .ini 文件列表
- [php_logo_guid](https://www.php.net/manual/zh/function.php-logo-guid.php) — 获取 logo 的 guid
- [php_sapi_name](https://www.php.net/manual/zh/function.php-sapi-name.php) — 返回 web 服务器和 PHP 之间的接口类型
- [php_uname](https://www.php.net/manual/zh/function.php-uname.php) — 返回运行 PHP 的系统的有关信息
- [phpcredits](https://www.php.net/manual/zh/function.phpcredits.php) — 打印 PHP 贡献者名单
- [phpinfo](https://www.php.net/manual/zh/function.phpinfo.php) — 输出关于 PHP 配置的信息
- [phpversion](https://www.php.net/manual/zh/function.phpversion.php) — 获取当前的PHP版本
- [putenv](https://www.php.net/manual/zh/function.putenv.php) — 设置环境变量的值
- [restore_include_path](https://www.php.net/manual/zh/function.restore-include-path.php) — 还原 include_path 配置选项的值
- [set_include_path](https://www.php.net/manual/zh/function.set-include-path.php) — 设置 include_path 配置选项
- [set_magic_quotes_runtime](https://www.php.net/manual/zh/function.set-magic-quotes-runtime.php) — 设置当前 magic_quotes_runtime 配置选项的激活状态
- [set_time_limit](https://www.php.net/manual/zh/function.set-time-limit.php) — 设置脚本最大执行时间
- [sys_get_temp_dir](https://www.php.net/manual/zh/function.sys-get-temp-dir.php) — 返回用于临时文件的目录
- [version_compare](https://www.php.net/manual/zh/function.version-compare.php) — 对比两个「PHP 规范化」的版本数字字符串
- [zend_logo_guid](https://www.php.net/manual/zh/function.zend-logo-guid.php) — 获取 Zend guid
- [zend_thread_id](https://www.php.net/manual/zh/function.zend-thread-id.php) — 返回当前线程的唯一识别符
- [zend_version](https://www.php.net/manual/zh/function.zend-version.php) — 获取当前 Zend 引擎的版本

<h3 id='错误处理'>错误处理</h3>

- [debug_backtrace](https://www.php.net/manual/zh/function.debug-backtrace.php) — 产生一条回溯跟踪(backtrace)
- [debug_print_backtrace](https://www.php.net/manual/zh/function.debug-print-backtrace.php) — 打印一条回溯。
- [error_clear_last](https://www.php.net/manual/zh/function.error-clear-last.php) — 清除最近一次错误
- [error_get_last](https://www.php.net/manual/zh/function.error-get-last.php) — 获取最后发生的错误
- [error_log](https://www.php.net/manual/zh/function.error-log.php) — 发送错误信息到某个地方
- [error_reporting](https://www.php.net/manual/zh/function.error-reporting.php) — 设置应该报告何种 PHP 错误
- [restore_error_handler](https://www.php.net/manual/zh/function.restore-error-handler.php) — 还原之前的错误处理函数
- [restore_exception_handler](https://www.php.net/manual/zh/function.restore-exception-handler.php) — 恢复之前定义过的异常处理函数。
- [set_error_handler](https://www.php.net/manual/zh/function.set-error-handler.php) — 设置用户自定义的错误处理函数
- [set_exception_handler](https://www.php.net/manual/zh/function.set-exception-handler.php) — 设置用户自定义的异常处理函数
- [trigger_error](https://www.php.net/manual/zh/function.trigger-error.php) — 产生一个用户级别的 error/warning/notice 信息
- [user_error](https://www.php.net/manual/zh/function.user-error.php) — trigger_error 的别名

<h3 id='输出缓冲控制'>输出缓冲控制</h3>

- [flush](https://www.php.net/manual/zh/function.flush.php) — 刷新输出缓冲
- [ob_clean](https://www.php.net/manual/zh/function.ob-clean.php) — 清空（擦掉）输出缓冲区
- [ob_end_clean](https://www.php.net/manual/zh/function.ob-end-clean.php) — 清空（擦除）缓冲区并关闭输出缓冲
- [ob_end_flush](https://www.php.net/manual/zh/function.ob-end-flush.php) — 冲刷出（送出）输出缓冲区内容并关闭缓冲
- [ob_flush](https://www.php.net/manual/zh/function.ob-flush.php) — 冲刷出（送出）输出缓冲区中的内容
- [ob_get_clean](https://www.php.net/manual/zh/function.ob-get-clean.php) — 得到当前缓冲区的内容并删除当前输出缓。
- [ob_get_contents](https://www.php.net/manual/zh/function.ob-get-contents.php) — 返回输出缓冲区的内容
- [ob_get_flush](https://www.php.net/manual/zh/function.ob-get-flush.php) — 刷出（送出）缓冲区内容，以字符串形式返回内容，并关闭输出缓冲区。
- [ob_get_length](https://www.php.net/manual/zh/function.ob-get-length.php) — 返回输出缓冲区内容的长度
- [ob_get_level](https://www.php.net/manual/zh/function.ob-get-level.php) — 返回输出缓冲机制的嵌套级别
- [ob_get_status](https://www.php.net/manual/zh/function.ob-get-status.php) — 得到所有输出缓冲区的状态
- [ob_gzhandler](https://www.php.net/manual/zh/function.ob-gzhandler.php) — 在ob_start中使用的用来压缩输出缓冲区中内容的回调函数。ob_start callback function to gzip output buffer
- [ob_implicit_flush](https://www.php.net/manual/zh/function.ob-implicit-flush.php) — 打开/关闭绝对刷送
- [ob_list_handlers](https://www.php.net/manual/zh/function.ob-list-handlers.php) — 列出所有使用中的输出处理程序。
- [ob_start](https://www.php.net/manual/zh/function.ob-start.php) — 打开输出控制缓冲
- [output_add_rewrite_var](https://www.php.net/manual/zh/function.output-add-rewrite-var.php) — 添加URL重写器的值（Add URL rewriter values）
- [output_reset_rewrite_vars](https://www.php.net/manual/zh/function.output-reset-rewrite-vars.php) — 重设URL重写器的值（Reset URL rewriter values）

<h3 id='密码散列算法'>密码散列算法</h3>

- [password_get_info](https://www.php.net/manual/zh/function.password-get-info.php) — 返回指定散列（hash）的相关信息
- [password_hash](https://www.php.net/manual/zh/function.password-hash.php) — 创建密码的散列（hash）
- [password_needs_rehash](https://www.php.net/manual/zh/function.password-needs-rehash.php) — 检测散列值是否匹配指定的选项
- [password_verify](https://www.php.net/manual/zh/function.password-verify.php) — 验证密码是否和散列值匹配

<h3 id='杂项'>杂项</h3>

- [connection_aborted](https://www.php.net/manual/zh/function.connection-aborted.php) — 检查客户端是否已经断开
- [connection_status](https://www.php.net/manual/zh/function.connection-status.php) — 返回连接的状态位
- [constant](https://www.php.net/manual/zh/function.constant.php) — 返回一个常量的值
- [define](https://www.php.net/manual/zh/function.define.php) — 定义一个常量
- [defined](https://www.php.net/manual/zh/function.defined.php) — 检查某个名称的常量是否存在
- [die](https://www.php.net/manual/zh/function.die.php) — 等同于 exit
- [eval](https://www.php.net/manual/zh/function.eval.php) — 把字符串作为PHP代码执行
- [exit](https://www.php.net/manual/zh/function.exit.php) — 输出一个消息并且退出当前脚本
- [get_browser](https://www.php.net/manual/zh/function.get-browser.php) — 获取浏览器具有的功能
- [__halt_compiler](https://www.php.net/manual/zh/function.halt-compiler.php) — 中断编译器的执行
- [highlight_file](https://www.php.net/manual/zh/function.highlight-file.php) — 语法高亮一个文件
- [highlight_string](https://www.php.net/manual/zh/function.highlight-string.php) — 字符串的语法高亮
- [hrtime](https://www.php.net/manual/zh/function.hrtime.php) — Get the system's high resolution time
- [ignore_user_abort](https://www.php.net/manual/zh/function.ignore-user-abort.php) — 设置客户端断开连接时是否中断脚本的执行
- [pack](https://www.php.net/manual/zh/function.pack.php) — 将数据打包成二进制字符串
- [php_check_syntax](https://www.php.net/manual/zh/function.php-check-syntax.php) — 检查PHP的语法（并执行）指定的文件
- [php_strip_whitespace](https://www.php.net/manual/zh/function.php-strip-whitespace.php) — 返回删除注释和空格后的PHP源码
- [sapi_windows_cp_conv](https://www.php.net/manual/zh/function.sapi-windows-cp-conv.php) — Convert string from one codepage to another
- [sapi_windows_cp_get](https://www.php.net/manual/zh/function.sapi-windows-cp-get.php) — Get process codepage
- [sapi_windows_cp_is_utf8](https://www.php.net/manual/zh/function.sapi-windows-cp-is-utf8.php) — Indicates whether the codepage is UTF-8 compatible
- [sapi_windows_cp_set](https://www.php.net/manual/zh/function.sapi-windows-cp-set.php) — Set process codepage
- [sapi_windows_vt100_support](https://www.php.net/manual/zh/function.sapi-windows-vt100-support.php) — Get or set VT100 support for the specified stream associated to an output buffer of a Windows console.
- [show_source](https://www.php.net/manual/zh/function.show-source.php) — 别名 highlight_file
- [sleep](https://www.php.net/manual/zh/function.sleep.php) — 延缓执行
- [sys_getloadavg](https://www.php.net/manual/zh/function.sys-getloadavg.php) — 获取系统的负载（load average）
- [time_nanosleep](https://www.php.net/manual/zh/function.time-nanosleep.php) — 延缓执行若干秒和纳秒
- [time_sleep_until](https://www.php.net/manual/zh/function.time-sleep-until.php) — 使脚本睡眠到指定的时间为止。
- [uniqid](https://www.php.net/manual/zh/function.uniqid.php) — 生成一个唯一ID
- [unpack](https://www.php.net/manual/zh/function.unpack.php) — Unpack data from binary string
- [usleep](https://www.php.net/manual/zh/function.usleep.php) — 以指定的微秒数延迟执行
