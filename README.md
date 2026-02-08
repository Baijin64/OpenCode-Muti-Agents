# OpenCode Multi-Agents

OpenCode Multi-Agents 是一个多代理AI编程助手系统，支持多种编程语言和开发模式。

## 编程CLI官网

访问OpenCode官网获取更多信息：[https://opencode.ai/](https://opencode.ai/)

## 安装

### 方法一：使用安装脚本

```bash
curl -fsSL https://opencode.ai/install | bash
```

### 方法二：使用npm

```bash
npm i -g opencode-ai
```

## 配置Agent

1. 将Agent文件放置在用户目录下的 `.config/opencode` 目录中。
2. 将文件夹重命名为 `agents`，完整路径为：`~/.config/opencode/agents`（在Windows上为 `%USERPROFILE%\.config\opencode\agents`）。

## 使用方法

### 切换模式

- 使用 `Tab` 键切换不同的代理模式。
- 支持的模式包括：
  - SOLO Mode
  - GUIDED Mode
  - REFACTOR Mode
  - SPEC Mode
  - 包含各种编程语言工程师模式（如Python Engineer、Java Engineer等）

### 配置模型提供商

在使用前，需要在每个Agent的 `.md` 文件中切换第8行的模型提供商设置。根据您的需求选择合适的AI模型提供商，模板默认使用Google Antigravity，Gihub Copilot和自带的OpenCode Zen Free。使用Antigravity模型: [https://github.com/NoeFabris/opencode-antigravity-auth](https://github.com/NoeFabris/opencode-antigravity-auth)

**订阅说明：**

- ChatGPT Plus：可以直接使用Plus和Pro账号订阅
- GitHub Copilot：也可以直接使用Pro和Pro＋订阅
- Claude：订阅只允许使用Max版

### IDE集成

安装命令行工具后，您可以在以下IDE中集成OpenCode：

#### VSCode

1. 在扩展市场搜索 "opencode"
2. 点击安装扩展

#### JetBrains IDE

1. 打开JetBrains AI Assistant
2. 选择添加ACP协议命令行编程服务后端
3. 选择opencode并下载
4. 等待刷新完成

#### Visual Studio

1. 打开PowerShell
2. 输入 `opencode` 命令

## 支持的Agent类型

- 1-Product Manager.md
- 2-Architecture Designer.md
- 3-Project Manager.md
- 4-Environment.md
- 5-各种编程语言工程师（C, C#, C++, Golang, GPU, HDL, Java&Kotlin, Matlab, Protocol, Python, Rust, Shader, Shell, SQL, Wasm, Web）
- 6-Code Reviewer.md
- 7-QA Tester.md
- 8-Style Formatter.md
- 9-Doc Writer.md
- 10-Dev Mentor.md

## 注意事项

- 确保Agent文件正确放置在指定目录中。
- 根据您的开发需求选择合适的Agent模式。
- 定期检查官网以获取最新更新和功能。

## 反馈与支持

如果您遇到任何问题或有建议，请访问我们的官网或联系支持团队。
