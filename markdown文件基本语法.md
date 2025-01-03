1. **标题**
   - **一级标题**：使用`#`号来表示一级标题，`#`后面跟一个空格，再写标题内容。例如`# 这是一级标题`。
   - **二级标题**：使用`##`来表示二级标题，同样`##`后有一个空格，如`## 这是二级标题`。依此类推，最多可以使用`######`来表示六级标题。标题级别越高，`#`的数量越多。

2. **段落**
   - 段落之间通过空行来分隔。在同一行中连续输入的文本会被视为一个段落。例如：
   ```markdown
   这是第一段内容。

   这是第二段内容。
   ```

3. **字体格式**
   - **加粗**：使用`**`或`__`将需要加粗的内容包裹起来。例如`**这部分文字是加粗的**`或者`__这部分文字也是加粗的__`。
   - **斜体**：用`*`或`_`包裹内容来表示斜体。如`*这是斜体文字*`或者`_这是斜体文字_`。
   - **加粗斜体**：将加粗和斜体的符号组合使用，即`***`或`___`包裹内容，例如`***这是加粗斜体文字***`。

4. **列表**
   - **无序列表**：使用`-`、`+`或者`*`作为列表项的开头，后面跟一个空格。例如：
   ```markdown
   - 第一项
   - 第二项
   - 第三项
   ```
   - **有序列表**：使用数字加上`.`来表示有序列表项，数字后面跟一个空格。例如：
   ```markdown
   1. 第一个步骤
   2. 第二个步骤
   3. 第三个步骤
   ```

5. **引用**
   - 使用`>`符号来表示引用内容。例如：
   ```markdown
   > 这是一段引用的文字。
   ```
   - 可以进行多层引用，每一层引用都添加一个`>`。例如：
   ```markdown
   > 第一层引用。
   >> 第二层引用。
   ```

6. **代码块**
   - **行内代码**：使用反引号（`）将代码内容包裹起来。例如`这是一段`printf("Hello, World!");`代码。`
   - **代码块**：使用三个反引号（```）来包裹代码块。可以在三个反引号后面指定代码的语言类型，这样在一些支持语法高亮的编辑器中可以对代码进行正确的高亮显示。例如：
   ```python
   def hello():
       print("Hello, World!")
   ```

7. **链接**
   - **普通链接**：使用`[链接文字](链接地址)`的格式来插入链接。例如`[百度](https://www.baidu.com)`。
   - **引用式链接**：先定义链接的标识，格式为`[链接标识]:链接地址`，然后在需要使用链接的地方使用`[链接文字][链接标识]`。例如：
   ```markdown
   [我的博客][blog]

   [blog]:https://example.com
   ```

8. **图片**
   - 图片的插入格式与链接类似，为`![图片说明](图片地址)`。例如`![美丽的风景](https://example.com/picture.jpg)`。

9. **表格**
   - 使用`|`来分隔列，使用`-`来分隔表头和表格内容。例如：
   ```markdown
   |表头1|表头2|
   |----|----|
   |内容1|内容2|
   ```
   - 可以通过在`-`两侧添加`:`来设置表格列的对齐方式，`:`在左边表示左对齐，在右边表示右对齐，两边都有表示居中对齐。例如：
   ```markdown
   |表头1|表头2|
   |:----|:----:|
   |内容1|内容2|
   ```
