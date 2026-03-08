# yuxiu — 个人简历

你好！欢迎来到 yuxiu 项目。

## 关于本项目

> **这是一个私人（个人）项目。**

本仓库由 [@anxionggithub](https://github.com/anxionggithub) 个人维护，用于托管个人 HTML 简历，不接受外部贡献（Pull Request / Issue）。仓库内容仅供个人求职使用，请勿直接复制用于商业用途。

## 使用方式

直接用浏览器打开 [resume.html](resume.html) 即可查看简历，支持打印为 PDF（Ctrl + P / ⌘ + P）。

## 在 VSCode 中打开

### 方法一：命令行打开整个项目

```bash
# 克隆仓库后，在项目根目录执行：
code .
```

### 方法二：命令行直接打开简历文件

```bash
code resume.html
```

### 方法三：使用 Live Server 实时预览

1. 在 VSCode 中打开项目（`code .`）
2. 安装推荐扩展：打开命令面板（`Ctrl+Shift+P` / `⌘+Shift+P`），输入
   `Extensions: Show Recommended Extensions`，安装 **Live Server**
3. 右键点击 `resume.html` → **Open with Live Server**，或点击状态栏右下角的 **Go Live** 按钮
4. 浏览器将自动打开并实时刷新页面；页面右下角会显示 **"在 VSCode 中打开"** 按钮，点击即可从浏览器跳回 VSCode 编辑该文件

> **提示**：首次克隆后，VSCode 会弹出「是否安装推荐扩展？」的提示，点击 **Install All** 即可一键完成安装。

## 文件说明

| 文件 | 说明 |
|------|------|
| `resume.html` | 个人简历主文件（单文件，无需构建） |
| `.vscode/extensions.json` | VSCode 推荐扩展列表 |
| `.vscode/settings.json` | VSCode 工作区配置（Live Server 等） |