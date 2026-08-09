# 🏛️ 公考AI全流程备考仪表盘

一个**纯前端、零依赖**的公考备考一站式仪表盘。打开即用，数据本地存储，无需注册。

## ✨ 功能

| 模块 | 说明 |
|------|------|
| 📅 考试倒计时 | 国考 + 各省省考倒计时、公告发布提醒 |
| 🗺️ 省份选择 | 各省考情对比（题型差异、竞争比、分数线） |
| ✅ 每日打卡 | 学习时长、刷题量、模块分布、连续打卡统计 |
| 📊 行测自测 | 分模块正确率追踪（言语/数量/判断/资料/常识） |
| ✏️ 申论追踪 | 小题 + 大作文分数记录 |
| 🧠 AI讲师复盘 | 接入 DeepSeek API，名师风格苏格拉底式追问 |
| 📸 OCR识别 | 上传错题截图自动识别（Tesseract.js） |
| 📖 每日积累 | 成语辨析 + 时政热点 |

## 🚀 使用方式

### 方式一：在线使用
直接访问：**[https://pyyy.top/gongkao/](https://pyyy.top/gongkao/)**

### 方式二：下载使用
1. 从 [Releases](https://github.com/tortoise014/gongkao-ai-dashboard/releases) 下载最新版本
2. 解压后用浏览器打开 `公考AI全流程备考仪表盘.html`
3. 所有数据存储在浏览器 localStorage

### AI讲师配置
点击顶栏 ⚙ → 输入 [DeepSeek API Key](https://platform.deepseek.com)（新用户免费送 500 万 tokens）

## 🛠 技术栈

- 纯 HTML/CSS/JS，无需构建工具
- [Tesseract.js](https://tesseract.projectnaptha.com/) 离线 OCR
- [DeepSeek API](https://platform.deepseek.com) 驱动 AI 对话

## 📦 版本

- **v1.0** — 首次发布，完整功能

## 📄 License

MIT
