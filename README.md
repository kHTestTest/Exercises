# 提交和各分支说明

最好的版本是v4分支，最初的提交是main分支

main分支是最早的提交，现学的go的结构体和解析yaml的方法，master做的不好，用很多if去匹配用户的输入，其实可以用map来找对应的映射，但此时用go的map的时候，有一些语法错误尚未处理好， main分支也没有处理环境变量的需求


v2分支，用map结构来找用户的命令行参数和结果之间的映射关系，避免了大量的if

v3分支，处理了环境变量，并在输出上处理了之前的一点错误：与题意原始要求略有差异（题意只要求输出eat/move/speak的对应结果的字符串，之前把name + eat + 对应结果字符串全部输出了）

v4分支，去除了不用的注释，并进一步精简了代码：合并了输出结果的语句
