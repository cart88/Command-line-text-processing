!! 执行上一条命令
!?string? 执行含有string字符串的最新命令

cd -
dirs
pushd
popd

CTRL+A              # 移动到行首，同 <Home>
ALT+B               # 向后（左边）移动一个单词
CTRL+B              # 向后移动，同 <Left>
CTRL+F              # 向前移动，同 <Right>
ALT+F               # 向前（右边）移动一个单词
CTRL+E              # 移动到行末，同 <End>

<!--CTRL+U              # 删除行首到光标位置的内容-->
CTRL+H              # 删除光标左边的字符，同 <Backspace>
<!--CTRL+W              # 删除光标左边的一个单词-->
ALT+D               # 删除光标后（右边）一个单词
<!--CTRL+K              # 删除光标位置到行末的内容-->
<!--CTRL+Y              # 粘贴前面 CTRL+u/k/w 删除过的内容-->
<!--CTRL+_              # 撤销（undo），有的终端将 CTRL+_ 映射为 CTRL+/ 或 CTRL+7-->

<!--CTRL+N              # 移动到命令历史的下一行，同 <Down>-->
<!--CTRL+P              # 移动到命令历史的上一行，同 <Up>-->

<!--CTRL+R              # 历史命令反向搜索，使用 CTRL+G 退出搜索-->
<!--使用方式: ctrl + r 输出关键词 若发现不是要找，ctrl + r继续往回找，直到找到-->
<!--CTRL+S              # 历史命令正向搜索，使用 CTRL+G 退出搜索-->

CTRL+L              # 清屏并重新显示 == clear
CTRL+C              # 结束当前命令

CTRL+D              # 删除光标前的字符，同 <Delete> ，或者没有内容时，退出会话
CTRL+G              # 退出当前编辑（比如正在 CTRL+R 搜索历史时）
CTRL+O              # 类似回车，但是会显示下一行历史
CTRL+V              # 输入字符字面量，先按 CTRL+V 再按任意键 如ctrl+v+tab 只输入tab不会有反应
?CTRL+X              # 列出可能的补全
CTRL+Z              # 暂停前台进程返回 bash，需要时可用 fg 将其切换回前台

ALT+t               # 交换字符
Esc+t 颠倒光标所在处及其相邻单词的位置

---------------------
ALT+BACKSPACE       # 删除光标前面一个单词，类似 CTRL+W，但不影响剪贴板

<!--CTRL+X CTRL+X       # 连续按两次 CTRL+X，光标在当前位置和行首来回跳转 -->
<!--CTRL+X CTRL+E       # 用你指定的编辑器，编辑当前命令-->

#securecrt用 set|grep TERM 的终端
#在session-terminal-emulation-emacs-use alt as meta key

SECURECRT 粘贴windows内容:使用shift+ctrl+c、shift+ctrl+v即可。。。

