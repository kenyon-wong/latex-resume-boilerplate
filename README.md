# Latex Resume Boilerplate

一个简洁优雅的 LaTeX 简历模板，支持中英文简历制作。

## ✨ 特性

- 🎨 简洁优雅的设计风格
- 🌏 完整的中英文支持
- 📦 开箱即用的模板结构
- 🔧 易于定制的样式设置

## 📝 快速开始

### 在线预览

- [预览示例简历 (PDF)](examples/resume-zh.pdf)

### 本地使用

1. 克隆仓库
```bash
git clone https://github.com/kenyon-wong/latex-resume-boilerplate.git
```

2. 编译简历
```powershell
xelatex path/to/template.tex
```

## 🔧 环境配置

### Windows 环境配置

#### 方式一：使用 Chocolatey（推荐）

> [!NOTE]
> - 示例命令基于 Windows 系统下的 TinyTeX 环境
> - 建议使用文件的绝对路径进行编译
> - 不建议使用 Scoop 安装 TinyTeX，可能存在证书信任、环境变量和中文支持等问题

```powershell
# 1. 安装 TinyTeX
choco install tinytex

# 2. 安装 chsrc（可选，用于配置镜像）
scoop install chsrc
chsrc set tlmgr

# 3. 更新并安装必要包
tlmgr update --self --all
tlmgr install enumitem titlesec fontawesome5 parskip ctex
```

#### 方式二：手动安装

1. 从 [TinyTeX 官网](https://yihui.org/tinytex/) 下载安装包
2. 按照官方指南完成安装
3. 使用 `tlmgr` 安装必要包

## 🎨 自定义

1. 打开 `template.tex`
2. 按照注释指引修改个人信息

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📚 相关资源

- [LaTeX 教程](https://www.latex-tutorial.com/)
- [TinyTeX 文档](https://yihui.org/tinytex/)
