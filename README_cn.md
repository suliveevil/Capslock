# ultimate macOS

forked from [Vonng/Capslock](https://github.com/Vonng/Capslock/)

*让 <kbd>CapsLock</kbd> 更 NB！* <span align="left"> [**English**](https://github.com/suliveevil/Capslock/blob/master/README_cn.md)</span>

需要改进的地方：

- [ ] **删除模块** 需要重新设计
- [ ]  **鼠标移动** 需要重新设计
- [ ]  
- [ ]  
- [ ]  
- [ ]  
- [ ] 







![](images/trump.jpg)



## Why CapsLock

### 让 Capslock 成为一个 *Hyper* 键, 极大提高效率!

* 功能强大: 把 <kbd>Capslock</kbd> 变成一个新的修饰键: **<kbd>Hyper(✱)</kbd>**.。
* 精心设计: 在键盘热区高频率使用的按键. 带来很多有用的功能。
* 兼容性: 和其他修饰键、应用、设备一起为你提高效率。
* 轻量级:  仅一个小脚本, 随处使用 !
* [设计文档](design.md)




## 平台

<details>
<summary>details</summary>

- [CapsLock(macOS)](mac/) 使用   [Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - macOS High Sierra (10.13)
  - macOS Sierra (10.12)
  - macOS EI Capitan (10.11)


  - 旧版 [XML]() 文件 (before OS X 10.11)，*不再维护* 。
- [CapsLock(Windows)](win/) 使用 AutoHotKey，*不再维护*。
  - Windows XP, Vista, 7, 8, 10

</details>



## 安装 (macOS)

1. 下载 [Karabiner-Elements](https://pqrs.org/osx/karabiner/) 并安装

2. 拷贝下面的链接到浏览器来导入设置脚本。

```bash
# 本仓库 (在 Safari 中打开)
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Vonng/Capslock/master/mac/capslock.json
```

```bash
# Karabiner-Elements 官方脚本库
karabiner://karabiner/assets/complex_modifications/import?url=https%3A%2F%2Fpqrs.org%2Fosx%2Fkarabiner%2Fcomplex_modifications%2Fjson%2Fcaps_lock_enhancement.json
```

3. 打开 Karabiner, 找到 "ComplexModification", 点击 "Add Item", 开始自定义配置。
4. 默认配置文件的路径是  `$HOME/.config/karabiner/assets/complex_modifications`。你可以自行修改。
5. 开启 **CapsLock** 功能: `[App] karabiner-elements -> [Tab] Complex Modification -> Add Item`

## 符号说明

### 修饰键:  macOS

<details>
<summary>macOS 符号说明</summary>

| Sym  | Key     |
| ---- | ------- |
| <kbd>✱</kbd>    | Hyper   |
| <kbd>⌃</kbd>    | Control |
| <kbd>⌥</kbd>    | Option  |
| <kbd>⇧</kbd>    | Shift   |
| <kbd>⌘</kbd>    | Command |

</details>


### 修饰键: ⊞ Windows

<details>
<summary>Windows 符号说明</summary>

| Sym  | Key     |
| ---- | ------- |
| <kbd>✱</kbd>    | Hyper   |
| <kbd>⌃</kbd>    | Control |
| <kbd>⊞</kbd>    | Windows |
| <kbd>⇧</kbd>    | Shift   |
| <kbd>⎇</kbd>    | Alter   |

</details>


### 常用键

<details>
<summary>details</summary>

| GLYPH   | NAME                                   |
| ------- | -------------------------------------- |
| <kbd></kbd>       | Apple                                  |
| <kbd>⌘</kbd>       | Command, Cmd, Clover, (formerly) Apple |
| <kbd>⌃</kbd>       | Control, Ctl, Ctrl                     |
| <kbd>⌥</kbd>       | Option, Opt, (Windows) Alt             |
| <kbd>⎇</kbd>       | Alt                                   |
| <kbd>⇧</kbd>       | Shift                                  |
| <kbd>⇪</kbd>       | 大写锁定键(Caps Lock)                    |
| <kbd>⏏</kbd>       | Eject                                  |
| <kbd>↩</kbd>, <kbd>↵</kbd>, <kbd>⏎</kbd> | 返回键, 回车键(Return, Carriage Return) |
| <kbd>⌤</kbd>       | Enter                                  |
| <kbd>⌫</kbd>       | Delete, Backspace                      |
| <kbd>⌦</kbd>       | Forward Delete                         |
| <kbd>⎋</kbd>       | 退出(Escape, Esc)                       |
| <kbd>→</kbd>       | 右箭头                                  |
| <kbd>←</kbd>       | Left arrow                             |
| <kbd>↑</kbd>       | Up arrow                               |
| <kbd>↓</kbd>       | Down arrow                             |
| <kbd>⇞</kbd>       | Page Up, PgUp                          |
| <kbd>⇟</kbd>       | Page Down, PgDn                        |
| <kbd>↖</kbd>       | Home                                   |
| <kbd>↘</kbd>       | End                                    |
| <kbd>⌧</kbd>       | Clear                                  |
| <kbd>⇥</kbd>       | Tab, Tab Right, Horizontal Tab         |
| <kbd>⇤</kbd>       | Shift Tab, Tab Left, Back-tab          |
| <kbd>␢</kbd>       | 空格键(Space, Blank)                    |
| <kbd>␣</kbd>       | 空格键(Space, Blank)                    |
| <kbd>❘⃝</kbd>      | 电源键                                  |
| <kbd>⇭</kbd>       | Num lock                               |
| <kbd>?⃝</kbd>      | Help                                   |
| <kbd></kbd>      | Context menu                           |

</details>






## 用法 (mac)

![](images/keyboard.png)

### 基础用法

<kbd>✱</kbd> Hyper 键实际上映射为 <kbd>⌃</kbd> <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> (右边所有的修饰键) , 它和左边的修饰键能够一起工作，并且兼容大多数应用程序。 

按住(Hold) <kbd>CapsLock</kbd> 并按下(Press)其他键来触发 <kbd>Hyper</kbd> 功能，而单独按下 <kbd>CapsLock</kbd> 作为 <kbd>Escape</kbd> 键。

| 键盘上的键 | Maps to    | 备注                       |
| ---------- | ---------- | -------------------------- |
| <kbd>⇪</kbd> 按下  | <kbd>⎋</kbd> Escape | 单独按下，成为 <kbd>escape</kbd>  |
| <kbd>⇪</kbd> 按住   | <kbd>✱</kbd>  Hyper | 开启 Hyper 功能 |

### 浏览

- 按住  <kbd>✱</kbd> Hyper 开始浏览
- 再按住一个<kbd>⌘</kbd> 来 **选择** . ( 就像按住 <kbd>⇧</kbd> 来进行大写字母输入那样)
- 再按住一个<kbd>⌥</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **鼠标移动**
- 再按住一个<kbd>⇧</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **标签页/app切换**
- 再按住一个<kbd>⌃</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **桌面管理** . (就像按下 <kbd>⌃</kbd> 和 <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> 一样)

| Origin | Maps to        | Comment                  |
| ------ | -------------- | ------------------------ |
| <kbd>H</kbd>    | <kbd>←</kbd> 左箭头  | 光标左移         |
| <kbd>J</kbd>    | <kbd>↓</kbd> 下箭头  | 光标下移          |
| <kbd>K</kbd>    | <kbd>↑</kbd> 上箭头    | 光标上移        |
| <kbd>L</kbd>    | <kbd>→</kbd> 右箭头 | 光标右移           |
| <kbd>U</kbd>    | <kbd>⇞</kbd> PageUp     | 光标向上翻页   |
| <kbd>I</kbd>    | <kbd>↖</kbd> Home       | 光标移动到行首 |
| <kbd>O</kbd>    | <kbd>↘</kbd>  End       | 光标移动到行末 |
| <kbd>P</kbd>    | <kbd>⇟</kbd> PageDn     | 光标向下翻页   |
|  <kbd>⌃</kbd> <kbd>H</kbd>    | <kbd>⌃</kbd> <kbd>←</kbd> 左箭头  | expose all      |
|  <kbd>⌃</kbd> <kbd>J</kbd>    | <kbd>⌃</kbd> <kbd>↓</kbd> 下箭头  | 应用程序窗口 ~~show desktops~~  |
|  <kbd>⌃</kbd> <kbd>K</kbd>    | <kbd>⌃</kbd> <kbd>↑</kbd> 上箭头    | 转到上一桌面    |
|  <kbd>⌃</kbd> <kbd>L</kbd>    | <kbd>⌃</kbd> <kbd>→</kbd> 右箭头 | 转到下一桌面   |
| <kbd>⌘</kbd> <kbd>H</kbd>    | <kbd>⇧</kbd><kbd>←</kbd> 左箭头  | 光标左移并选择         |
| <kbd>⌘</kbd> <kbd>J</kbd>    | <kbd>⇧</kbd> <kbd>↓</kbd> 下箭头  | 光标下移并选择          |
| <kbd>⌘</kbd> <kbd>K</kbd>    | <kbd>⇧</kbd> <kbd>↑</kbd> 上箭头    | 光标上移并选择        |
| <kbd>⌘</kbd> <kbd>L</kbd>    | <kbd>⇧</kbd> <kbd>→</kbd> 右箭头 | 光标右移并选择          |
|  <kbd>⌥</kbd> <kbd>H</kbd>    | <kbd>←</kbd> 左箭头  | 光标左移     |
|  <kbd>⌥</kbd> <kbd>J</kbd>    | <kbd>↓</kbd> 下箭头  | 光标下移      |
|  <kbd>⌥</kbd> <kbd>K</kbd>    | <kbd>↑</kbd> 上箭头    | 光标上移    |
|  <kbd>⌥</kbd> <kbd>L</kbd>    | <kbd>→</kbd> 右箭头 | 光标右移   |


### 鼠标键

* 用键盘模拟鼠标
* Also can be achieved by <kbd>⌥</kbd>  with <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 

| Origin | Maps to        | Comment                  |
| ------ | -------------- | ------------------------ |
| <kbd>←</kbd>   | 鼠标左移  | 鼠标光标向左移动              |
| <kbd>↓</kbd>    | 鼠标下移  | 鼠标光标向右移动              |
| <kbd>↑</kbd>    | 鼠标上移    | 鼠标光标向上移动            |
| <kbd>→</kbd>    | 鼠标右移 | 鼠标光标向右移动               |
| <kbd>↩</kbd>    | 鼠标左键     | 鼠标左键点击              |
| <kbd>⌘</kbd> <kbd>↩</kbd>    | 鼠标右键    | 鼠标右键点击 |

### 删除 

这个模块与 vim 的 delete 不同，需要改进

| Origin    | Maps to                            | Comment             |
| --------- | ---------------------------------- | ------------------- |
| <kbd>N</kbd>       | <kbd>⌥</kbd> <kbd>⌫</kbd>  Option + ForwardDelete       | 删除光标前面的一个单词 |
| <kbd>M</kbd>       | <kbd>⌫</kbd>  ForwardDelete       | 删除光标前面的一个字符 |
| <kbd>,</kbd>       | <kbd>⌦</kbd>  Delete      | 删除光标后面的一个字符 |
| <kbd>.</kbd>       | <kbd>⌥</kbd> <kbd>⌦</kbd>  Option + Delete       | 删除光标后面的一个单词 |
| <kbd>⌘</kbd> <kbd>M</kbd> + <kbd>⌘</kbd> <kbd>N</kbd> | <kbd>⌘</kbd> <kbd>⌥</kbd> <kbd>⌫</kbd> Command+Option+ForwardDelete | 删除到行首 |

### 窗口管理

| Origin           | Maps to                 | Comment                                  |
| ---------------- | ----------------------- | ---------------------------------------- |
| <kbd>⇥</kbd> Tab          | <kbd>⌘</kbd> <kbd>⇥</kbd> Command+Tab | 切换窗口                        |
| <kbd>⌘</kbd><kbd>⇥</kbd> Command+Tab | <kbd>⌘</kbd><kbd>⇧</kbd><kbd>⇥</kbd> Command+Shift+Tab | 反向切换窗口              |
| <kbd>Q</kbd>              | <kbd>⌘</kbd> <kbd>Q</kbd>                   | 关闭窗口                             |
| <kbd>W</kbd>              | <kbd>⌘</kbd> <kbd>W</kbd>                   | Close Tab                                |
| <kbd>A</kbd>              | <kbd>⌃</kbd> <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>A</kbd>               | [Moom*](https://manytricks.com/moom/) 专用。※ 一个窗口管理 app |
| <kbd>⌘</kbd><kbd>A</kbd>             | <kbd>⌃</kbd> <kbd>↑</kbd>  Ctrl+UpArrow      | 应用 Expose                        |
| <kbd>S</kbd>             | <kbd>⌃</kbd> <kbd>⇥</kbd>  Ctrl+Tab          | 切换标签页                               |
| <kbd>⌘</kbd><kbd>S</kbd>             | <kbd>⌃</kbd> <kbd>⇧</kbd> <kbd>⇥</kbd> Ctrl+Shift+Tab    | 反向切换标签页                    |
| <kbd>⌘</kbd><kbd>D</kbd>             | <kbd>F11</kbd>                   | Show Desktop                             |

### Bash

- 常用 bash 工具: EOF, SIGINT, SIGTSTP, VIM/Tmux Prefix

| Origin | Maps to     | Comment                                      |
| ------ | ----------- | -------------------------------------------- |
| <kbd>Z</kbd>   | <kbd>⌃</kbd> <kbd>Z</kbd> | 暂停进程 SIGTSTP                                 |
| <kbd>X</kbd>   | <kbd>⌃</kbd> <kbd>R</kbd> | 运行 IDE                                   |
| <kbd>C</kbd>   | <kbd>⌃</kbd> <kbd>C</kbd> | 终止进程 SIGINT                                  |
| <kbd>V</kbd>   | <kbd>⌃</kbd> <kbd>V</kbd> | Vim Prefix                                   |
| <kbd>B</kbd>   | <kbd>⌃</kbd> <kbd>B</kbd> | [Tmux](http://tmux.github.io) Default Prefix |
| <kbd>D</kbd>   | <kbd>⌃</kbd> <kbd>D</kbd> | 文件结束 EOF                                     |

#### 应用

- 以下设置可以被重写为你喜欢的 app。

| Origin | Maps to      | Comment                       |
| ------ | ------------ | ----------------------------- |
| <kbd>E</kbd>          | 打开 Safari  | 打开网页浏览器    |
| <kbd>⌘</kbd> <kbd>E</kbd> | 打开访达 | 打开文件浏览器    |
| <kbd>R</kbd>    | 打开 iTerm2  | macOS 上一个很棒的终端 app (`Run`) |
| <kbd>⌘</kbd> <kbd>R</kbd>   | 打开预览    | 转到打开的文件 |
| <kbd>T</kbd>    | 打开 Visual Studio Code | 文本编辑器: Visual Studio Code                 |
| <kbd>⌘</kbd> <kbd>T</kbd>  | 打开 Typora  | 文本编辑器: Typora , 一个所见即所得的 markdown 编辑器 |
| <kbd>⌘</kbd> <kbd>D</kbd> | 打开词典 | 查询单词 |
| <kbd>⌘</kbd> <kbd>F</kbd>   | 打开 Dash      | 查询 API 文档      |
| <kbd>F</kbd> | 打开 Alfred | Leaves to <kbd>⌃</kbd><kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>F</kbd>|
| <kbd>G</kbd>    | 打开 Intellij IDEA      | 打开 IDE                                        |
| <kbd>⌘</kbd><kbd>G</kbd>   | 打开 Chrome             | Google Chrome                                   |

### 功能键

- 使用 F1,…F12 作为标准功能键，当按下 hyper to turn them back.

- If you are using RMBP with Bar, consider changing your bar back to function keys with 

  `Karabiner -> Function Keys -> Use all F1, F2, etc. keys as standard function keys  `

| Origin            | Maps to              | Comment                          |
| ----------------- | -------------------- | -------------------------------- |
| <kbd>F1</kbd>              | <kbd>BrightnessDown</kbd>     |                                  |
| <kbd>F2</kbd>              | <kbd>BrightnessUp</kbd>       |                                  |
| <kbd>F3</kbd>              | <kbd>ExposeAll</kbd>          |                                  |
| <kbd>F4</kbd>              | <kbdLaunchPad></kbd>          |                                  |
| <kbd>F5</kbd>              | <kbd>KeyboardLightDown</kbd>  |                                  |
| <kbd>F6</kbd>              | <kbd>KeyboardLightUp</kbd>    |                                  |
| <kbd>F7</kbd>              | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>F8</kbd>              | <kbd>MusicPlay</kbd>          |                                  |
| <kbd>F9</kbd>              | <kbd>MusicNext</kbd>          |                                  |
| <kbd>F10</kbd>             | <kbd>Mute</kbd>               |                                  |
| <kbd>F11</kbd>             | <kbd>VolumeDown</kbd>         |                                  |
| <kbd>F12</kbd>             | <kbd>VolumeUp</kbd>           |                                  |
| <kbd>F13</kbd> <kbd>PrintScreen</kbd> | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>F14</kbd> <kbd>ScrollLock</kbd>  | <kbd>MusicNext</kbd>          |                                  |
| <kbd>F15</kbd> Pause       | <kbd>MusicPlay</kbd>          | Just as it shows                 |
| <kbd>Insert</kbd>          | <kbd>⌥</kbd><kbd>BrightnessUp</kbd>      | Fine grained brightness up       |
| <kbd>Delete</kbd>          | <kbd>⌥</kbd><kbd>BrightnessDown</kbd>    | Fine grained brightness down     |
| <kbd>Home</kbd>            | <kbd>⌥</kbd><kbd>KeyboardLightUp</kbd>   | Fine grained keyboard light up   |
| <kbd>End</kbd>             | <kbd>⌥</kbd><kbd>KeyboardLightDown</kbd> | Fine grained keyboard light down |
| <kbd>PgUp</kbd>            | <kbd>⌥</kbd><kbd>VolumeUp</kbd>          | Fine grained volume up           |
| <kbd>PgDn</kbd>            | <kbd>⌥</kbd><kbd>VolumeDown</kbd>        | Fine grained volume down         |

### Shifter

- 更方便的 <kbd>shift</kbd>
- 分号<kbd> ;</kbd> 引号  <kbd>'</kbd> 被特殊处理， 使得输入 <kbd>!=</kbd> 和 <kbd>:=</kbd>  更方便

| Origin             | Maps to | Comment                  |
| ------------------ | ------- | ------------------------ |
| <kbd>1</kbd>                | <kbd>!</kbd>     | 感叹号                           |
| <kbd>2</kbd>                | <kbd>@</kbd>     | At                       |
| <kbd>3</kbd>                | <kbd>#</kbd>     | Sharp                    |
| <kbd>4</kbd>                | <kbd>$</kbd>     | Dollar                   |
| <kbd>5</kbd>                | <kbd>%</kbd>     | 百分号                  |
| <kbd>6</kbd>                | <kbd>^</kbd>     | 脱字符 Caret                |
| <kbd>7</kbd>                | <kbd>&</kbd>     | Ampersand                |
| <kbd>8</kbd>                | <kbd>*</kbd>     | 星号                     |
| <kbd>9</kbd>                | <kbd>(</kbd>     | 左括号       |
| <kbd>0</kbd>                | <kbd>)</kbd>     | 右括号   |
| <kbd>-</kbd> Minus          | <kbd>_</kbd>     | Hyphen                   |
| <kbd>=</kbd> Equal          | <kbd>+</kbd>     | Plus                     |
| <kbd>[</kbd> Left Bracket   | <kbd>(</kbd>     | 左括号  <kbd>⇧</kbd><kbd>9</kbd> |
| <kbd>]</kbd>  Right Bracket | <kbd>)</kbd>     | 右括号 <kbd>⇧</kbd><kbd>0</kbd> |
| <kbd>;</kbd> Semicolon      | <kbd>!</kbd>     | Exclamation              |
| <kbd>'</kbd> Single Quote   | <kbd>=</kbd>     | EqualSign                |
| <kbd>⌘</kbd> <kbd>;</kbd> Semicolon     | <kbd>!</kbd>     | Colon                    |
| <kbd>⌘</kbd> <kbd>'</kbd> Single Quote  | <kbd>=</kbd>     | EqualSign                |

### Misc

| Origin                 | Maps to             | Comment                                        |
| ---------------------- | ------------------- | ---------------------------------------------- |
| <kbd>⎋</kbd> Escape             | <kbd>⇪</kbd>  CapsLock       | Bug: Difficult to turn capslock off after emit |
| <kbd>~</kbd> BackQuote          | <kbd>⌃</kbd><kbd>⇧</kbd><kbd>⌘4</kbd><kbd>4</kbd>             | macOS 区域截图并保存到剪切板 |
| <kbd>⌘</kbd><kbd>~</kbd> Command+BackQuote | <kbd>⌃</kbd><kbd>⇧</kbd><kbd>4</kbd>                | macOS 区域截图并保存到桌面    |
| <kbd>⌫</kbd> Backspace          | <kbd>⌘</kbd><kbd>⌫</kbd>                | macOS 删除文件                              |
| <kbd>/</kbd> Slash              | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | IDE 注释               |
| <kbd>`\`</kbd> Backslash        | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | IDE 注释            |
| <kbd>␢</kbd> Spacebar           | <kbd>⌃</kbd><kbd>␢</kbd>  Ctrl+Spacebar | 切换输入法                     |







## 问答

- Q： 为什么使用 <kbd>✱</kbd> 作为 hyper 键的符号？

  A：因为星号的 ascii 码是 42, 是生命、宇宙、一切的答案!  并且它也可以被理解为一颗星星。 :star: <kbd>✱</kbd> (加粗的星号) 比 <kbd> * </kbd> (星号) 更好看. 如果 Github 能够正确显示的话，其实我更愿意使用 <kbd>☯</kbd>。

- Q：为什么没有 Linux 版本？

  A：因为我用 Mac, 在终端使用 Linux。

- Q:  为什么 macOS 版 和 Windows 版有些键盘绑定不一样?

  A:   我现在已经不用 Windows 了,  Windows 版已不再维护，欢迎你来完善它。

- Q:  为什么这儿还有一个旧的 Mac 版本?

  A:  Apple 真的是很反复无常。 macOS Sierra 改变了内核架构, 所以老版本的 Karabiner 不兼容 10.12 以后的 macOS。 但现在有了新版本的 karabiner 并被取名为 Karabiner-Elements。 Karabiner-Elements 使用 JSON 格式配置文件而不是原来的 XML 格式。 请使用新版本。

  



## About

作者：suliveevil（suliveevil@outlook.com）

License：WTFPL

![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/WTFPL_logo.svg/140px-WTFPL_logo.svg.png)

```
Do What The Fuck you want to Public License

Version 1.0
Copyright (C) 2018 Feng Ruohang (Vonng).
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

Ok, the purpose of this license is simple
and you just

DO WHAT THE FUCK YOU WANT TO.
```





