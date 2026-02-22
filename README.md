# AI 写作助手 ✍️

一个基于 DeepSeek API 的智能文案生成工具，纯前端单文件实现。

## 功能

- **8 种文案类型**：小红书种草文、朋友圈文案、产品描述、商务邮件、自我介绍、工作周报、道歉信、感谢信
- **针对性表单**：每种类型有专属输入字段，引导填写关键信息
- **语气调节**：正式 / 轻松 / 幽默 / 专业，四种风格自由切换
- **多版本生成**：一次生成 1~5 个版本供选择
- **一键复制**：点击即复制到剪贴板
- **历史记录**：自动保存生成记录，支持回看和删除（localStorage 存储）
- **响应式设计**：手机、平板、桌面均可使用

## 使用方法

1. 直接用浏览器打开 `index.html`
2. 填入 [DeepSeek API Key](https://platform.deepseek.com/api_keys)，点击保存
3. 选择文案类型 → 填写信息 → 选择语气 → 点击生成
4. 从多个版本中选择满意的，一键复制使用

## 技术方案

- 纯前端：HTML + CSS + JavaScript，单个 `index.html` 文件
- API：DeepSeek Chat API (`deepseek-chat` 模型)
- 存储：localStorage（API Key + 历史记录）
- 无需构建工具，无需后端服务

## 获取 API Key

前往 [DeepSeek 开放平台](https://platform.deepseek.com/) 注册并创建 API Key。
