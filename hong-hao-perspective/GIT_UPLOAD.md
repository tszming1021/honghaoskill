# 上传到 GitHub

本项目已经准备好提交。项目目录中的 `.gitignore` 会自动排除 macOS 元数据、编辑器缓存，以及包含本机路径的本地 PDF 索引文件。

在项目目录执行：

```bash
git init
git add .
git status
git commit -m "初始提交：洪灏视角宏观策略 Skill"
git branch -M main
git remote add origin git@github.com:tszming1021/honghaoskill.git
git push -u origin main
```

如果已经配置过 `origin`，将远程地址改为：

```bash
git remote set-url origin git@github.com:tszming1021/honghaoskill.git
```

上传前建议确认 `git status` 中没有出现不希望公开的文件。当前项目保留的是方法论摘要，不包含已删除的原始抽取文本、图书 OCR、PDF 和网络下载材料。

