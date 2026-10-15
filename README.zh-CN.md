<h1 align="center">DSH For OortCloud Work</h1>

<p align="center"><strong>工作任务自动完成</strong></p>
<p align="center"><em>把工作任务交给智能体，存量 Web 系统无需改造。</em></p>

<p align="center">
  <a href="README.md">English</a> | 简体中文
</p>

![DSH For OortCloud Work](assets/aiagent_zh.jpg)

## 📖 项目概述

DSH For OortCloud Work 是基于 DeepSeek Harness Desktop（DSH）开发的 OortCloud Work 工作任务自动化桌面程序：用自然语言下达工作任务，智能体会理解页面、规划步骤、自动执行操作并回报结果。它以智能体自动化替代传统 RPA 场景，尤其注重对存量（利旧）Web 系统的自动化操作——不改造、不迁移、不要求原有系统开放接口。

它同时也是 OortCloud 企业级场景化群件（GroupWare）：一个桌面端承载 OortCloud 70+ 个服务场景，允许随时切换不同场景使用。这是 OortCloud 最核心、最关键、最激动人心的桌面端产品。

此外，OortCodex 产品系列均独创多环境登录技术：中国站与国际站共用一套程序，无需为两个站点分别发布两套程序。

> **工作任务，自动完成。**

## ✨ 核心亮点

- **自然语言即任务**：用平常的话描述要完成的工作，智能体自己规划步骤、动手执行、回报结果。
- **替代传统 RPA**：不录制脚本、不依赖选择器与固定坐标，界面变化也能自适应继续执行。
- **利旧 Web 系统**：不动存量系统一行代码，直接在现有 Web 系统上完成自动化，让既有投资继续产生价值。
- **企业级场景化群件**：一个桌面端承载 OortCloud 70+ 个服务场景，随时切换、按需使用。
- **多环境登录**：一套程序同时支持中国站与国际站，无需双份发布、双倍维护。

## 🤖 智能体自动化：替代传统 RPA

传统 RPA 依赖录制脚本、选择器与固定坐标：界面一变脚本就失效，需要专人持续维护。DSH For OortCloud Work 把任务交给智能体——它理解页面语义，自主规划并执行多步操作，最后把结果交回给你。

| 维度         | 传统 RPA                     | DSH For OortCloud Work         |
| ------------ | ---------------------------- | ------------------------------- |
| 任务定义     | 录制操作 / 编写脚本          | 自然语言描述工作任务            |
| 页面理解     | 依赖选择器与固定坐标         | 智能体理解页面语义              |
| 界面变化     | 脚本失效，需重新录制         | 自适应调整，继续执行            |
| 适用系统     | 通常要求系统配合改造         | 尤其擅长利旧存量 Web 系统       |
| 维护成本     | 需专人维护脚本               | 任务即描述，随改随用            |

### 利旧 Web 系统

企业里最有价值的业务逻辑，往往就在那些跑了很多年的存量 Web 系统里。DSH For OortCloud Work 不要求改造、迁移或重构这些系统，而是让智能体直接在现有页面上完成操作——存量系统的价值得以延续，自动化能力即时就位。

## 🏢 企业级场景化群件（GroupWare）

- 一个桌面端承载 OortCloud **70+ 个服务场景**，允许在不同场景之间随时切换使用。
- 它既是工作任务自动化工具，也是 OortCloud 场景化服务统一的桌面入口。
- 这是 OortCloud **最核心、最关键、最激动人心**的桌面端产品。

## 🌏 多环境登录技术

- OortCodex 产品系列均独创多环境登录技术。
- 中国站与国际站共用同一套程序，登录时选择环境即可。
- 彻底避免为两个站点分别开发、测试、发布两套程序所带来的双倍成本。

## 🚀 快速开始

### 下载安装

前往 [Releases](https://gitcode.com/OortCloudGroup/DSH-OortCloud-Work/releases) 下载安装包：

- **Windows**：`.exe` 安装程序

### 自动更新

客户端读取仓库根目录的 [latest.json](latest.json) 获取最新版本号、下载地址与 SHA-256 校验值，完成版本检测与自动更新。

### 首次使用

1. 启动 DSH For OortCloud Work。
2. 使用 OortCloud 账号登录，选择中国站或国际站环境。
3. 在 70+ 个服务场景中切换到当前需要的场景。
4. 用自然语言描述工作任务，智能体开始在 Web 系统上自动操作。

## 🛠 技术栈

基于 DeepSeek Harness Desktop（DSH）构建：Electron 桌面客户端 · 智能体运行时 · 内建浏览器操作能力，任务理解、步骤规划与页面执行在同一框架内闭环。

## 🤝 参与贡献

欢迎各种形式的贡献：

1. Fork 本仓库
2. 创建功能分支（`git checkout -b feature/AmazingFeature`）
3. 提交修改（`git commit -m 'feat: 新增某某功能'`）
4. 推送到远程分支（`git push origin feature/AmazingFeature`）
5. 创建 Pull Request

## 🐛 问题报告与反馈

遇到问题或有改进建议，请通过 GitHub / GitCode Issues 提交。

## 🔧 快速脚本更新 latest.json

在 PowerShell 中执行以下命令：

```powershell
# 使用指定版本更新 latest.json；默认 EXE 路径：G:\lanjian\nginx\html_88_56\OortCodex-Desktop.exe
.\scripts\update-latest.ps1 -Version "1.0.1"

# 使用自定义可执行文件路径
.\scripts\update-latest.ps1 -Version "1.0.2" -ExePath "G:\lanjian\nginx\html_88_56\OortCodex-Desktop.exe"
```

## 📄 许可证

本项目采用 MIT 许可证，完整内容请参阅 [LICENSE](LICENSE) 文件。

## 🙏 致谢

感谢所有为 DSH For OortCloud Work 做出贡献的开发者。

### 标语

**DSH For OortCloud Work —— 工作任务，自动完成。**
