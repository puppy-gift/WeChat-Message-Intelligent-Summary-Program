# 微信聊天记录 AI 智能总结工具

一个基于 Flask 的本地化微信聊天记录 AI 总结工具，支持自动抓取、文件上传、手动粘贴三种模式，集成 DeepSeek、OpenAI、Grok、Gemini 等多种 AI 提供商。

## 功能特性

-  **AI 智能总结**：自动提取聊天记录中的关键信息、与你相关的讨论、约定事项
-  **三合一模式**：自动抓取（wx-cli）、文件上传（支持 TXT/DOCX/PDF 等多种格式）、手动粘贴
-  **自定义风格**：可选择让 AI 自动选择总结风格，或手动指定（幽默吐槽、正式汇报等）
-  **关键词追踪**：可设置关注关键词，重点总结相关内容并查看提及原话
-  **本地处理**：所有数据在本地处理，不经过任何第三方服务器
-  **API Key 加密记忆**：多 AI 提供商的 API Key 加密存储在本地，一次配置永久使用

## 快速开始

### 环境要求

- Windows 10/11 64位
- Python 3.10+
- 微信 PC 官网版（自动抓取模式需要）

### 安装

```bash
pip install -r requirements.txt


### 重要提醒
本项目仅供个人学习、研究和技术探索使用，严禁用于任何非法或商业用途。

违反协议风险：本工具通过第三方技术读取微信本地数据，该行为可能违反《腾讯微信软件许可及服务协议》。

封号风险：微信官方严禁任何形式的"破解数据库"及"违规获取用户数据"行为。使用本工具可能导致您的微信账号被限制功能、短期封禁，甚至永久封号。

隐私风险：任何不当使用都可能泄露您及他人的聊天记录，构成对他人隐私的侵犯。

法律责任豁免：使用本工具即表示您已阅读并同意，所有责任和风险由您自行承担。本项目的开发者及贡献者不对您使用本工具所造成的任何后果承担任何形式的法律责任。

请务必在充分了解上述风险后，再决定是否使用本项目


This project is intended for personal learning, research, and technical exploration only. Any illegal or commercial use is strictly prohibited.

Terms of Service Violation: This tool reads WeChat local data through third-party technology, which may violate the Tencent WeChat Software License and Service Agreement.

Account Ban Risk: WeChat officially prohibits any form of "database cracking" and "unauthorized user data access". Using this tool may result in your WeChat account being restricted, temporarily banned, or even permanently banned.

Privacy Risk: Improper use may expose your and others' chat records, constituting a violation of others' privacy.

Liability Disclaimer: By using this tool, you acknowledge and agree that all responsibilities and risks are borne solely by you. The developers and contributors of this project shall not be held liable for any consequences resulting from your use of this tool.

Please fully understand the above risks before deciding to use this project
