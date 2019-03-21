![ADM-3A终端机键盘电路板](images/ADM-3A终端机键盘电路板.jpg) 

# Vim 笔记

[TOC]

<details>
<summary>Beginner Text Navigation</summary>

| 操作 | 目的                 | why                                                          |
| ---- | -------------------- | ------------------------------------------------------------ |
| <kbd>h</kbd>    | <kbd>←</kbd>向左移动**一个字符** | 当 Bill Joy 创建 Vi 文本编辑器时，他使用的机器机器是 ADM-3A 终端机。|
| <kbd>j</kbd>    | <kbd>↓</kbd>向下移动**一行** | ADM-3A 把 HJKL 键作为方向键。<kbd>←</kbd> <kbd>↓</kbd> <kbd>↑</kbd> <kbd>→</kbd> |
| <kbd>k</kbd>    | <kbd>↑</kbd> 向上移动**一行**       | 当时的 <kbd>Esc</kbd> 在 <kbd>Q</kbd> 的左边，Home 键 <kbd>～</kbd> 在键盘右上角 |
| <kbd>l</kbd>    | <kbd>→</kbd> 向右移动**一个字符**     |                                                              |
| <kbd>e</kbd> | 移动到单词**末尾** | Move to **end** of word |
| <kbd>b</kbd> | 移动到单词**开始**** | Move to **beginning** of word |
| <kbd>$</kbd> | 移动到行尾 | Move to **end** of line |
| <kbd>0</kbd> | 移动到行首 | Move to **beginning** of line |
| <kbd>⇧</kbd> <kbd>H</kbd> | 移动到屏幕显示的首行 | Move to first line(**head**) of screen |
| <kbd>⇧</kbd> <kbd>M</kbd> | 移动到屏幕显示的中间行 |Move to **middle** line of screen|
| <kbd>⇧</kbd> <kbd>L</kbd> | 移动到屏幕显示的末行 |Move to **last** line of screen|
| <kbd>w</kbd> | 移动到下一个单词 |Move to next **word**|
| <kbd>b</kbd> | 移动到上一个单词 |可能只是因为和 <kbd>w</kbd> 对称吧，Move to previous word |

</details>



<details>
<summary>Beginner Text Editing</summary>

| 操作 | 目的                 | why                                                          |
| ---- | -------------------- | ------------------------------------------------------------ |
| <kbd>r</kbd> | 替换字符 |Change char and return to cmd mode|
| <kbd>⇧</kbd> <kbd>R</kbd> | 替换模式（批量替换） | Enter **Replace** Mode |
| <kbd>ESC</kbd> | 退出插入模式 |**Exit** Insert Mode to Normal Mode|

</details>


<details>
<summary>Intermediate Text Navigation 1</summary>

| 操作 | 目的                 | why                                                          |
| ---- | -------------------- | ------------------------------------------------------------ |
| <kbd>f</kbd> <kbd>w</kbd> | 移到本行下一个(➡️)单词 |Move to next(**forward**) **word**(<kbd>w</kbd>) on line|
| <kbd>⇧</kbd> <kbd>F</kbd> + <kbd>w</kbd> | 移到本行下一个(➡️)单词 |Move to previous(<kbd>⇧</kbd> 取反义) **word**(<kbd>w</kbd>) on line|
| <kbd>t</kbd> <kbd>w</kbd> | 移到本行下一个(➡️)单词之前 |Move before next **word**(<kbd>w</kbd>) on line|
| <kbd>⇧</kbd> <kbd>T</kbd> + <kbd>w</kbd> | 移到本行下一个(➡️)单词 |Move before previous(<kbd>⇧</kbd> 取反义) **word**(<kbd>w</kbd>) on line|
| <kbd>;</kbd> | |Repeat last <kbd>f</kbd> <kbd>F</kbd> <kbd>t</kbd> <kbd>T</kbd>|
| <kbd>,</kbd> | | Repeat last <kbd>f</kbd> <kbd>F</kbd> <kbd>t</kbd> <kbd>T</kbd> reversed |
| <kbd>5</kbd> <kbd>j</kbd> | | Move down(<kbd>j</kbd>) 5 lines |
| <kbd>5</kbd> <kbd>k</kbd> | | Move up(<kbd>k</kbd>) 5 lines |

</details>


<details>
<summary>Intermediate Text Navigation 2</summary>

| 操作 | 目的                 | why                                                          |
| ---- | -------------------- | ------------------------------------------------------------ |
| <kbd>5</kbd> <kbd>w</kbd> | | Move 5 words forward |
| <kbd>5</kbd> <kbd>b</kbd> | | Move 5 words backward |
| <kbd>⌃</kbd> <kbd>e</kbd> | | Scroll down |
| <kbd>⌃</kbd> <kbd>y</kbd> | | Scroll up |
| <kbd>y</kbd> <kbd>e</kbd> | | Yank(copy) to end of word |
| <kbd>d</kbd> <kbd>d</kbd> | 删除(剪切)当前行 | **Delete(cut)** current line |
| <kbd>5</kbd><kbd>d</kbd> <kbd>d</kbd> | 删除(剪切)5行 | **Delete(cut)** 5 lines |
| <kbd>d</kbd> <kbd>2</kbd> <kbd>w</kbd>| | **Delete** next two words |
| <kbd>⇧</kbd> <kbd>D</kbd> | | **Delete** to end of line（one char） |
| <kbd>p</kbd> | 粘贴 | **paste** |

</details>

<details>
<summary>Intermediate Text Editing 2</summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| <kbd>⇧</kbd><kbd>p</kbd> | 粘贴到光标之前 | **Paste** before cursor |
| <kbd>u</kbd> | 撤销操作 |**Undo** |
| <kbd>⇧</kbd><kbd>U</kbd> | 撤销对当前行的所有操作 |**Undo** all changes to current line |
| <kbd>⌃</kbd> <kbd>r</kbd> | | Redo |
| <kbd>.</kbd> | | Repeat last change |
| <kbd>5</kbd> <kbd>.</kbd> | | Repeat last change 5 times |
| <kbd>d</kbd> <kbd>e</kbd> | | Delete(cut) to end of word|
| <kbd>d</kbd> <kbd>$</kbd> | | Delete(cut) to end of line|

</details>


<details>
<summary>Advanced Text Navigation</summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| <kbd>⌃</kbd> | | Move to first non whitespace char |
| <kbd>2</kbd> <kbd>0</kbd> <kbd>l</kbd> | | Go to column 20 |
| <kbd>%</kbd> | | Go to matching parenthesis or brackets |
| <kbd>⌃ </kbd> <kbd>o</kbd> | | Move to **older** position |
| <kbd>⌃ </kbd> <kbd>i</kbd> | | Move to **newer** position |
| <kbd>z</kbd> <kbd>t</kbd> | | Scroll current line to **top** of window |

</details>


<details>
<summary>Visual Mode</summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `:w FileName` <kbd>↵</kbd> | | Write selection to 'FileName' |
| <kbd>v</kbd> | |**Visual** mode select characters |
| <kbd>⇧</kbd><kbd>V</kbd> | |**Visual** mode highlight lines |
| <kbd>~</kbd> | | Swap case |
| <kbd>></kbd> | | Shift **right** |
| <kbd><</kbd> | | Shift **left** |
| <kbd>c</kbd> | | **Change** highlighted text|
| <kbd>y</kbd> | | Yank(copy) highlighted text|
| <kbd>d</kbd> | | Cut highlighted text|
| <kbd>=</kbd> | | Re-indent selection |

</details>


<details>
<summary>Window Management</summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `:e FileName` <kbd>↵</kbd> | | Set current buffer to 'FileName' |
| `:sp`  <kbd>↵</kbd>| | New window above |
| `:vs`  <kbd>↵</kbd>| | New window to left |
| `:q`  <kbd>↵</kbd>| | Close current window |
| `:qa`  <kbd>↵</kbd>| | Close(**Quit**) **all** window |

</details>

<details>
<summary>File Management</summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `:q!` <kbd>↵</kbd> | | Quit without saving |
| `:wq` <kbd>↵</kbd> | | Save(**Write**) and exit |
| `:w !sudo tee %`| 追加 sudo 权限 | [How does the vim “write with sudo trick work?”](https://stackoverflow.com/questions/2600783/how-does-the-vim-write-with-sudo-trick-work) |
| `:x` <kbd>↵</kbd> | | Save(**Write**) and exit if modified |
| `:r FileName` <kbd>↵</kbd> | | Read and insert 'FileName' |
| `:r !cmd` <kbd>↵</kbd> | | Execute and insert results of 'cmd' |
| `:!rm FileName` <kbd>↵</kbd> | | Delete 'FileName' |
| `:e` <kbd>↵</kbd> | | Open new file |
| <kbd>⌃</kbd> <kbd>g</kbd> | | Show file info |
| <kbd>g</kbd> <kbd>a</kbd> | | Show character info |
| `:w` <kbd>↵</kbd> | | Save changes |
| `:q` <kbd>↵</kbd> | | quit |

</details>

<details>
<summary> Bookmarks </summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `marks` <kbd>↵</kbd> | | |
| <kbd>m</kbd> <kbd>a</kbd> | | |
| \`a | | |
| \`\` | | Go to previous position |

</details>

<details>
<summary> Replace </summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `:s/foo/bar` <kbd>↵</kbd> | | |
| `:s/foo/bar/g` <kbd>↵</kbd> | | |
| `:%s/foo/bar/g` <kbd>↵</kbd> | | |
| `:%s/foo/bar` <kbd>↵</kbd> | | |
| `:s/foo/bar/gc` <kbd>↵</kbd> | | |
| `:s/foo/bar/i` <kbd>↵</kbd> | | |
| <kbd>r</kbd> <kbd>x</kbd> | | |
| `:%s/foo/bar/gc` <kbd>↵</kbd> | | |
| `:2,9s/foo/bar/g` <kbd>↵</kbd> | | |

</details>

<details>
<summary> Search </summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `/foo` <kbd>↵</kbd>  | | |
| `?foo`<kbd>↵</kbd> | | |
| <kbd>n</kbd> | | |
| <kbd>⇧</kbd> <kbd>N</kbd> | | |
| `*` | | |
| `:set nois` <kbd>↵</kbd> | | |
| `:set ic` <kbd>↵</kbd> | | |
| `:set is` <kbd>↵</kbd> | | |
| `:set hls` <kbd>↵</kbd> | | |

</details>

<details>
<summary> Misc </summary>

| 操作 | 目的  | why     |
| ---- | ----- | ------ |
| `vim -t foo` <kbd>↵</kbd> | | |
| `:help cmd` <kbd>↵</kbd> | | |
|  `:make`  <kbd>↵</kbd>| | |
| `:!ls`  <kbd>↵</kbd> | | |
| <kbd>⌃</kbd> <kbd>p</kbd> | | |
| <kbd>⌃</kbd> <kbd>x</kbd> | | |
| <kbd>⌃</kbd> <kbd>o</kbd> | | |
| <kbd>⇧</kbd> <kbd>K</kbd> | | |
| <kbd>y</kbd> <kbd>w</kbd> | | |

</details>

# 参考资料

