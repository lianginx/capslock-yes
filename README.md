# CAPSLOCK YES

> Windows 版本请查看 [CAPSLOCK YES（Auto Hotkey）](https://github.com/lianginx/capslock-yes-ahk)

通过 [Karabiner-Elements](https://karabiner-elements.pqrs.org/) 将按下 `CapsLock` 映射功能键，搭配字母键组合出一套全新的快捷键。

让你的双手在编辑代码时，不再需要离开字母区就能随心所欲地快速移动光标或选中文字。

右手使用鼠标时，也不再需要放开鼠标就能精准移动光标到想要的位置。


## 如何使用

```text
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/lianginx/capslock-yes/master/capslock-yes.json
```

1. 下载 [Karabiner-Elements](https://karabiner-elements.pqrs.org/) 并安装。
2. 复制上面的 URL 并使用浏览器打开以导入配置文件。
3. 点击 `Import` 导入的规则。
4. 找到 `CapsLock YES!` 规则集，点击 `Enable All` 启用全部规则。

## 映射规则

规则启用后按下 `CapsLock` 将映射为按下 `Ctrl + Option + Command + Shift`，如果与其他应用热键冲突请自行处理。

同时这也说明 `CapsLock` 将 **不能再切换大小写**，如果需要输入大写字符，按下 `Shift` 就可以输入大写字符了。

![key-bitmap](assets/key-bitmap.jpg)

### 移动光标

| 热键         | 功能                | 热键     | 功能             |
| ------------ | ------------------- | -------- | ---------------- |
| Caps + E     | 向上移动            | Caps + D | 向下移动         |
| Caps + S     | 向左移动            | Caps + F | 向右移动         |
| Caps + A     | 向左移动一个单词    | Caps + G | 向右移动一个单词 |
| Caps + W     | 移动到行首          | Caps + R | 移动到行尾       |
| Caps + T     | 移动到页面顶部      | Caps + B | 移动到页面底部   |
| Caps + Q     | 退格键（Backspace） | Caps +Z  | 删除键（Delete） |
| Caps + Space | 回车键（Enter）     |          |                  |

### 选中字符

| 热键     | 功能             | 热键     | 功能             |
| -------- | ---------------- | -------- | ---------------- |
| Caps + I | 向上移动         | Caps + K | 向下移动         |
| Caps + J | 向左移动         | Caps + L | 向右移动         |
| Caps + H | 向左移动一个单词 | Caps + ; | 向右移动一个单词 |
| Caps + U | 移动到行首       | Caps + O | 移动到行尾       |
| Caps + Y | 移动到页面顶部   | Caps + N | 移动到页面底部   |

> 细心的朋友应该发现了，这与移动光标的热键布局基本一致，很容易记忆。

### 数字区

| 热键                | 功能 | 热键            | 功能 | 热键            | 功能 |
| ------------------- | ---- | --------------- | ---- | --------------- | ---- |
| Cmd + Shift + U     | 7    | Cmd + Shift + I | 8    | Cmd + Shift + O | 9    |
| Cmd + Shift + J     | 4    | Cmd + Shift + K | 5    | Cmd + Shift + L | 6    |
| Cmd + Shift + M     | 1    | Cmd + Shift + , | 2    | Cmd + Shift + . | 3    |
| Cmd + Shift + Space | 0    |                 |      |                 |      |

> 这与数字小键盘的布局基本一致，非常符合手指的肌肉记忆。

### 其他

| 热键     | 功能     |
| -------- | -------- |
| Caps + ` | 打开访达 |
