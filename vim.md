﻿1. 模式切换
- esc nomal
- i insert
- v visual
- r 替换
2. 上下左右kjhl
3. 转移光标位置（这些可以多次用转到别的词）
 - w 下个词头
 - b 词头
 - e 词尾
4. 操作前加数字表示次数
5. 数字i内容  多次插入内容
6. f字母 光标移至字母
7. % 跳到括号的另一端
8. 0 跳到行头；$ 跳到行尾
9. \* 找到下一个该词; # 找到上一个该词
10. gg 文件头；G 文件尾 ；第2行 2G
11. /balabala 搜索balabala；n 下一个；N 上一个
12. o或O 新一行
13. x或X 删除
14. e esc中替换
15. d 剪切到词的结尾，用p粘贴；dw删一个词，d2e删两个词，w带空格，e不带
16. . 重复上一个命令
17. visual模式 e选择，标出范围，d删除
18. :w保存,:q退出,:q!退出不保存
19. u undo,ctrl+R redo
20. :help
建议设置 inoremap jj <Esc>