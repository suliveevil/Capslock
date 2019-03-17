# Capslock

*让 <kbd>CapsLock</kbd> 更NB！*  

![](images/trump.jpg)



## Why CapsLock

### 让 Capslock 成为一个 *Hyper* 键, 极大提高效率!

* 功能强大: 把 <kbd>Capslock</kbd> 变成一个新的修饰键: **Hyper(✱)**.。
* 精心设计: 在键盘热区高频率使用的按键. 带来很多有用的功能。
* 兼容性: 和其他修饰键、应用、设备一起为你提高效率。
* 轻量级:  仅一个小脚本, 随处使用 !
* [设计文档](design.md)




## 平台

- [CapsLock(Mac)](mac/)  via  [Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - macOS High Sierra (10.13)
  - macOS Sierra (10.12)
  - macOS EI Capitan (10.11)


  - 旧版 [XML]() 文件 (before OS X 10.11, *不再维护*) 
- [CapsLock(Windows)](win/) via AutoHotKey  *(不再维护)*
  - Windows XP, Vista, 7, 8, 10


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
4. 默认配置文件的路径是  `$HOME/.config/karabiner/assets/complex_modifications`. Modify it if you like.
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
| <kbd>⎇</kbd>       | Alt                                    |
| <kbd>⇧</kbd>       | Shift                                  |
| <kbd>⇪</kbd>       | Caps lock                              |
| <kbd>⏏</kbd>       | Eject                                  |
| <kbd>↩</kbd>, <kbd>↵</kbd>, <kbd>⏎</kbd> | Return, Carriage Return                |
| <kbd>⌤</kbd>       | Enter                                  |
| <kbd>⌫</kbd>       | Delete, Backspace                      |
| <kbd>⌦</kbd>       | Forward Delete                         |
| <kbd>⎋</kbd>       | Escape, Esc                            |
| <kbd>→</kbd>       | Right arrow                            |
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
| <kbd>␢</kbd>       | Space, Blank                           |
| <kbd>␣</kbd>       | Space, Blank                           |
| <kbd>❘⃝</kbd>      | Power                                  |
| <kbd>⇭</kbd>       | Num lock                               |
| <kbd>?⃝</kbd>      | Help                                   |
| <kbd></kbd>       | Context menu                           |

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
| `H`    | `←` LeftArrow  | cursor left              |
| `J`    | `↓` DownArrow  | cursor down              |
| `K`    | `↑` UpArrow    | cursor up                |
| `L`    | `→` RightArrow | cursor right             |
| `U`    | `⇞` PageUp     | cursor page up           |
| `I`    | `↖` Home       | cursor to line(doc) head |
| `O`    | `↘`  End       | cursor to line(doc) end  |
| `P`    | `⇟` PageDn     | cursor page down         |
| `⌘H`    | `⇧←` LeftArrow  | cursor left and selection         |
| `⌘J`    | `⇧↓` DownArrow  | cursor down and selection         |
| `⌘K`    | `⇧↑` UpArrow    | cursor up and selection         |
| `⌘L`    | `⇧→` RightArrow | cursor right and selection         |
| `⌥H`    | `←` LeftArrow  | mouse left              |
| `⌥J`    | `↓` DownArrow  | mouse down              |
| `⌥K`    | `↑` UpArrow    | mouse up                |
| `⌥L`    | `→` RightArrow | mouse right             |
| `⌃H`    | `←` LeftArrow  | expose all              |
| `⌃J`    | `↓` DownArrow  | show desktops              |
| `⌃K`    | `↑` UpArrow    | switch prev desktop               |
| `⌃L`    | `→` RightArrow | switch next desktop        |



### 鼠标键

* 用键盘模拟鼠标
* Also can be archived by `⌥`  with `HJKL`

| Origin | Maps to        | Comment                  |
| ------ | -------------- | ------------------------ |
| `←`    | MouseLeft  | mouse cursor left              |
| `↓`    | MouseDown  | mouse cursor down              |
| `↑`    | MouseUp    | mouse cursor up                |
| `→`    | MouseRight | mouse cursor right             |
| `↩`    | MouseLeft     | mouse left button click           |
| `⌘↩`    | MouseRight      | mouse right button click |

### 删除

| Origin    | Maps to                            | Comment             |
| --------- | ---------------------------------- | ------------------- |
| `N`       | `⌥⌫`  Option + ForwardDelete       | Delete a word ahead |
| `M`       | `⌫` ForwardDelete                  | Delete a char ahead |
| `,`       | `⌦` Delete                         | Delete a char after |
| `.`       | `⌥⌦` Option + Delete               | Delete a word after |
| `⌘M`,`⌘N` | `⌘⌥⌫` Command+Option+ForwardDelete | Delete to line head |

### 窗口管理

| Origin           | Maps to                 | Comment                                  |
| ---------------- | ----------------------- | ---------------------------------------- |
| `⇥` Tab          | `⌘⇥` Command+Tab        | Switch Window                            |
| `⌘⇥` Command+Tab | `⌘⇧⇥` Command+Shift+Tab | Switch Window Reversely                  |
| `Q`              | `⌘Q`                    | Close Window                             |
| `W`              | `⌘W`                    | Close Tab                                |
| `A`              | `⌃⌥⇧⌘A`                 | Leaves to [Moom](https://manytricks.com/moom/), ※a window resize app |
| `⌘A`             | `⌃↑`  Ctrl+UpArrow      | OSX Expose All                           |
| `S`              | `⌃⇥`  Ctrl+Tab          | Switch Tab                               |
| `⌘S`             | `⌃⇧⇥` Ctrl+Shift+Tab    | Swtich Tab Reversely                     |
| `⌘D`             | `F11`                   | Show Desktop                             |

### Bash

- Common bash utils: EOF, SIGINT, SIGTSTP, VIM/Tmux Prefix

| Origin | Maps to     | Comment                                      |
| ------ | ----------- | -------------------------------------------- |
| `Z`    | `⌃Z` Ctrl+Z | SIGTSTP                                      |
| `X`    | `⌃R` Ctrl+R | IDE Run                                      |
| `C`    | `⌃C`Ctrl+C  | SIGINT                                       |
| `V`    | `⌃V`Ctrl+V  | Vim Prefix                                   |
| `B`    | `⌃B`Ctrl+B  | [Tmux](http://tmux.github.io) Default Prefix |
| `D`    | `⌃D` Ctrl+D | EOF                                          |

#### 应用

- Maybe you'd like overwrite these with your own favorite apps.

| Origin | Maps to      | Comment                       |
| ------ | ------------ | ----------------------------- |
| <kbd>E</kbd>          | 打开 Safari  | 打开网页浏览器    |
| <kbd>⌘</kbd> <kbd>E</kbd> | 打开访达 | 打开文件浏览器    |
| <kbd>R</kbd>    | 打开 iTerm2  | Great terminal for osx (`Run`)   |
| <kbd>⌘</kbd> <kbd>R</kbd>   | 打开预览    | 转到打开的文件 |
| <kbd>T</kbd>    | 打开 Visual Studio Code | 文本编辑器: Visual Studio Code                 |
| <kbd>⌘</kbd> <kbd>T</kbd>  | 打开 Typora  | 文本编辑器: Typora , 一个所见即所得的 markdown 编辑器 |
| <kbd>⌘</kbd> <kbd>D</kbd> | 打开词典 | 查询单词 |
| <kbd>⌘</kbd> <kbd>F</kbd>   | 打开 Dash      | 查询 API 文档      |
| <kbd>F</kbd> | 打开 Alfred | Leaves to <kbd>⌃</kbd><kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>F</kbd>|
| `G`    | 打开 Intellij IDEA      | 打开 IDE                                        |
| `⌘G`   | 打开 Chrome             | Google Chrome                                   |

### Functional

- Use F1,…F12 as standard functional keys, while hold hyper to turn them back.

- If you are using RMBP with Bar, consider changing your bar back to function keys with 

  `Karabiner -> Function Keys -> Use all F1, F2, etc. keys as standard function keys  `

| Origin            | Maps to              | Comment                          |
| ----------------- | -------------------- | -------------------------------- |
| `F1`              | `BrightnessDown`     |                                  |
| `F2`              | `BrightnessUp`       |                                  |
| `F3`              | `ExposeAll`          |                                  |
| `F4`              | `LaunchPad`          |                                  |
| `F5`              | `KeyboardLightDown`  |                                  |
| `F6`              | `KeyboardLightUp`    |                                  |
| `F7`              | `MusicPrev`          |                                  |
| `F8`              | `MusicPlay`          |                                  |
| `F9`              | `MusicNext`          |                                  |
| `F10`             | `Mute`               |                                  |
| `F11`             | `VolumeDown`         |                                  |
| `F12`             | `VolumeUp`           |                                  |
| `F13` PrintScreen | `MusicPrev`          |                                  |
| `F14` ScrollLock  | `MusicNext`          |                                  |
| `F15` Pause       | `MusicPlay`          | Just as it shows                 |
| `Insert`          | `⌥BrightnessUp`      | Fine grained brightness up       |
| `Delete`          | `⌥BrightnessDown`    | Fine grained brightness down     |
| `Home`            | `⌥KeyboardLightUp`   | Fine grained keyboard light up   |
| `End`             | `⌥KeyboardLightDown` | Fine grained keyboard light down |
| `PgUp`            | `⌥VolumeUp`          | Fine grained volume up           |
| `PgDn`            | `⌥VolumeDown`        | Fine grained volume down         |

### Shifter

- A more convient shift for most case
- Semicolon`;` and Quote  `'` have some special treatment, makes input `!=` and `:=`  easier

| Origin             | Maps to | Comment                  |
| ------------------ | ------- | ------------------------ |
| `1`                | `!`     | Exclamation              |
| `2`                | `@`     | At                       |
| `3`                | `#`     | Sharp                    |
| `4`                | `$`     | Dollar                   |
| `5`                | `%`     | Percent                  |
| `6`                | `^`     | Caret                    |
| `7`                | `&`     | Ampersand                |
| `8`                | `*`     | Star                     |
| `9`                | `(`     | Left Round Bracket       |
| `0`                | `)`     | Right Round Bracket      |
| `-` Minus          | `_`     | Hyphen                   |
| `=` Equal          | `+`     | Plus                     |
| `[` Left Bracket   | `(`     | Left Round Bracket `⇧9`  |
| `]`  Right Bracket | `)`     | Right Round Bracket `⇧0` |
| `;` Semicolon      | `!`     | Exclamation              |
| `'` Single Quote   | `=`     | EqualSign                |
| `⌘;` Semicolon     | `!`     | Colon                    |
| `⌘'` Single Quote  | `=`     | EqualSign                |

### Misc

| Origin                 | Maps to             | Comment                                        |
| ---------------------- | ------------------- | ---------------------------------------------- |
| `⎋` Escape             | `⇪`  CapsLock       | Bug: Difficult to turn capslock off after emit |
| `~` BackQuote          | `⌃⇧⌘4`              | macOS Area Screenshot to Clipboard             |
| `⌘~` Command+BackQuote | `⌃⇧4`               | macOS Area Screenshot to Desktop File          |
| `⌫` Backspace          | `⌘⌫`                | macOS Delete File                              |
| `/` Slash              | `⌘/` Command+Slash  | Comment/Uncomment in many IDE                  |
| `\` Backslash          | `⌘/` Command+Slash  | Comment/Uncomment in many IDE                  |
| `␢` Spacebar           | `⌃␢`  Ctrl+Spacebar | Switch Input Source                            |







## FAQ

- Q： Why using ✱ as symbol of hyper key？

  A：Cause asterisk have the ascii code 42, which is the answer to life, the universe, and everything!  while itself has meaning 'star'. ✱ (Heavy-Asterisk) is a pretty version of `*` (Asterisk). Actually I would choose ☯  if Github could render it properly...

- Q：Why Linux support is missing？

  A：because I choose Mac, and use Linux through terminal.

- Q:  Why there is some different key bindings between Mac version and Win version?

  A:   I don't use windows anymore,  Win version is no longer maintained. Welcome if you can fix that.

- Q:  Why there's an old Mac version?

  A:  Apple is really capricious. macOS Sierra changes it's kernel architecture, so the old version karabiner is incompatible with macOS after 10.12. But now there's a new version of karabiner named karabiner-elements. While karabiner-elements use a new JSON-format conf instead of old XML-format. Please using the new version.

  



## About

Author：Vonng (fengruohang@outlook.com)

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





