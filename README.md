# HDU-Beamer-Theme

杭州电子科技大学（HDU）Beamer 主题模板，适用于课程汇报、学术报告和答辩展示等场景。模板主体为 `HDU.sty`，示例入口为 `slide.tex`，校徽与图片素材放在 `pic/` 目录下。

## 使用方式

本模板建议使用 XeLaTeX 编译，适合中文内容：

```bash
xelatex slide.tex
xelatex slide.tex
```

编译后会生成 `slide.pdf`。如果 PDF 正在被预览器占用，先关闭预览窗口再重新编译。

## 文件说明

- `HDU.sty`：HDU Beamer 主题样式，包括页眉页脚、主题色、目录页和 block 样式。
- `slide.tex`：演示文稿主文件，可在此修改标题、作者、章节和正文内容。
- `pic/`：校徽、透明水印和其他图片素材。
- `ref.bib`：BibTeX 参考文献文件。

## 辅助工具

- 表格生成：https://www.tablesgenerator.com/
- 公式识别：https://mathpix.com/
- 文献整理：https://dblp.uni-trier.de/
- LaTeX 图表说明：https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions#Tip

## 致谢

本模板参考了开源 Beamer 主题的结构，并结合 HDU 汇报场景进行了样式调整。
