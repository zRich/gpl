# 说明

本仓库用于存放GPL相关内容，包括GPL的翻译，GPL合规相关文章等内容。

# 工具

使用`pandoc`转换为pdf。

中文使用**思源黑体**，英文使用**Helvetica**字体
```
pandoc --pdf-engine=xelatex -V CJKmainfont="Source Han Sans SC" -V mainfont='Helvetica' gplv2/gplv2.md -o gplv2/gplv2.pdf
```
