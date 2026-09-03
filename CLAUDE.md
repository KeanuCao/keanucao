# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库是什么

这是 GitHub 个人主页仓库（`KeanuCao/keanucao`，remote: `git@github.com:KeanuCao/keanucao.git`）。`README.md` 是唯一内容，会直接渲染为 GitHub 个人主页（曹檀的个人简介/作品集），全文使用简体中文。

- 本仓库没有代码，因此没有构建、测试、lint 命令，也没有依赖或配置文件。
- README 中的「个人项目」表格目前为空，是预留位，未来用于填充个人项目（原则：**有说明、能运行、可复用**）。
- 编辑 README 时保持简体中文和现有章节/表格结构。

## Git 状态（重要）

仓库尚无任何 commit，且 HEAD 指向不存在的引用 `.invalid`（`git log` / `git status` 会报错）。首次提交前需先修复分支：

```sh
git checkout -b main
```

之后即可正常 add/commit。主分支约定为 `main`。
