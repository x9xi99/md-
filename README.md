GitHub Markdown 教程
1. 基础语法
标题
Markdown 使用 # 符号定义标题，最多支持六级标题：

markdown
复制代码
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
段落与换行
直接输入文字会显示为一个段落。若需要换行，可以在行末加上两个空格或插入一个空行。

强调（加粗、斜体）
加粗：在文字两侧加 ** 或 __。
斜体：在文字两侧加 * 或 _。
加粗+斜体：在文字两侧加 *** 或 ___。
markdown
复制代码
**加粗**
*斜体*
***加粗+斜体***
列表
有序列表使用数字和 . 号。
无序列表使用 -、* 或 +。
markdown
复制代码
1. 有序项 1
2. 有序项 2

- 无序项 1
- 无序项 2
链接与图片
链接：[链接文本](链接地址)。
图片：![图片描述](图片URL)。
markdown
复制代码
[GitHub](https://github.com)
![示例图片](https://example.com/image.png)
引用
使用 > 表示引用块。

markdown
复制代码
> 这是一个引用块。
代码块
单行代码用反引号（`）包裹，多行代码使用三个反引号（```）开始和结束，语言可选：

markdown
复制代码
`单行代码`

```python
# Python 代码示例
print("Hello, GitHub!")
perl
复制代码

### 表格
使用 `|` 分隔列，`---` 分隔表头和内容：
```markdown
| 列1 | 列2 |
| --- | --- |
| 数据1 | 数据2 |
2. GitHub Markdown 扩展语法
GitHub Markdown 支持一些特有功能：

任务列表
可以创建带复选框的任务列表：

markdown
复制代码
- [x] 已完成任务
- [ ] 未完成任务
表情符号
可以使用 :emoji_name: 添加表情。常见的有 :smile:、:rocket: 等。

markdown
复制代码
Hello :smile:
链接文件
GitHub 上可以直接链接到仓库内的文件：

markdown
复制代码
[README](README.md)
@提及与 #issue
可以使用 @username 提及用户，或使用 #issue_number 链接问题。

markdown
复制代码
@octocat
#42
代码块中显示行号
在代码块语言名后加 :linenumbers 显示行号：

markdown
复制代码
```python:linenumbers
print("Hello, GitHub!")
3. 预览与提交
预览：在 GitHub 中编辑 Markdown 文件时，可以点击“Preview”查看效果。
提交：编辑完成后，填写 Commit 信息，点击“Commit changes”提交。
