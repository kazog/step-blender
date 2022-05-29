# Markdowm 语法

- 标题: # 名称 注意#后面是一个空格
- 换行:   结尾两个空格或者<br>
- 粗体: **bold text** 或者 __bold text__
- 斜体: *cat's meow* 或者 _cat's meow_
- 粗体加斜体: ***bold  meow*** ___bold  meow___ **_bold meow_** __*bold  meow*__ 
- 引用: >> 饮用使用>后跟一个空格
> 引用内容
>> 嵌套引用内容
> - 引用加章节
- 多段引用: 段落之间的空白行添加一个 > 符号
- 嵌套引用: 在要嵌套段落前添加一个 >> 符号
- 删除线: 两个波浪号 ~~删除的文本~~
- 列表: 键入一个冒号:，后跟一个空格 : 
- 有序章节: 1. 数字加. 后面跟一个空格
- 无序章节: -、*、+ 后面跟一个空格
1. One item
    - Indented item
- 代码: 要将单词或短语表示为代码，请将其包裹在反引号 `如`
- 转义: 使用两层``a``  (``)
- 代码块: 反引号（(```）或三个波浪号（~~~）
- 语法高亮: ```json 或 ~~~json
- 分割线: 在单独一行上使用三个(***)、(---)或(___)并且不能包含其他内容。
- 链接: [超链接显示名](超链接地址 "超链接title")
- 可点击文本: 使用尖括号 <https://meng.com>
- 强调 链接: 链接语法前后增加星号 **[Meng](https://meng.com)**
- 或者+ https://github.com/
- 图片: ![图片alt](图片链接 "图片title")
[![沙漠中的岩石图片](assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)
- 转义字符: 在字符前面添加反斜杠字符 \
- 内嵌Html: 区块元素──比如 \<div>\<table>\<pre>\<p> 等标签，必须在前后加上空行  
行级內联标签如 \<span>\<cite>\<del> 不受限制
- 表格: 使用三个---）创建每列的标题，并用管道（|）分隔每列  

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

- 对齐: 可以在标题行中的连字符的左侧，右侧或两侧添加冒号（:），将列中的文本对齐到左侧，右侧或中心。

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

- 任务列表: 破折号-和方括号[ ]，并在[ ]前面加上空格。要选择一个复选框，请在方括号[x]之间添加 x
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

- Emoji: 以冒号开头和结尾，并包含表情符号的名称。
去露营了！ :tent: 很快回来。
真好笑！ :joy:

[1]: http://weibo.com
[2]: https://git.oschina.net