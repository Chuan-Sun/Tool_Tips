[[Linux]]

[菜鸟教程](https://www.runoob.com/linux/linux-shell.html)
下文针对 bash

## 变量
`var="a"`，等号两边不能有空格，可以用双引号也可以用单引号
使用变量：`$var`、`${var}`
拼接字符串：`var2=$var$var`、`var2="1"$var"2"`

定义数组：`a=(v1 v2 v3)`
读取数组：`${a[0]}`
读取数组所有元素：`${a[@]}`
获取数组长度：`${#a[@]}`

注释：`#`，`{}`

## 运算
加减乘除等
```
`expr 1 + 1`
$[1+1]
```
注意空格

条件表达式要放在方括号中间
`[ $a == $b ]`

## 命令
`echo`：输出字符串

`printf`：输出字符串，比 `echo` 移植性好

`>`：输出结果存至文件
`>>`：输出结果追加至文件

`test`：检查某个条件是否成立，类似 `[]`

## 流程控制
```bash
if condition
then
	...
elif condition
then
	...
else
	...
fi


for var in item1 item2 ...
do
	...
done


while condition
do
	...
done
```
