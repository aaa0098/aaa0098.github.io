# 硬件工程师个人网站

这是一个不依赖构建工具的静态网站。双击 `index.html` 即可预览；发布时将整个 `portfolio-site` 目录部署到静态托管服务。

投递前请替换以下占位内容：

- `index.html` 中的邮箱 `your.email@example.com`
- `index.html` 中的 GitHub/Gitee 链接
- 如有个人姓名，可将首页标题下或页脚的 `HARDWARE PORTFOLIO` 改为姓名

PDF 同时位于 `../output/pdf/hardware-engineer-portfolio.pdf` 和网站根目录 `hardware-engineer-portfolio.pdf`，因此部署网站后下载链接仍然可用。重新生成 PDF 时，在当前素材根目录运行：

```powershell
& 'C:\Users\LH745211\.cache\codex-runtimes\codex-primary-runtime\dependencies\python\python.exe' tools\build_portfolio_pdf.py
```
