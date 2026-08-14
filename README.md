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
| 🎓 名师对话 | 多风格 AI 名师（苏格拉底式追问），独立成页内嵌主仪表盘 |
| 🧠 AI讲师复盘 | 支持 DeepSeek / 通义千问 / 智谱GLM 多平台切换 |
| 📸 OCR识别 | 上传错题截图自动识别（通义/GLM 识图） |
| 📖 每日积累 | 成语辨析 + 时政热点 |
| 🎯 AI选岗助手 | 结合考情智能选岗建议 |

## 🚀 使用方式

### 方式一：在线使用
直接访问：**[https://pyyy.top/gongkao/](https://pyyy.top/gongkao/)**

### 方式二：下载使用
1. 从 [Releases](https://github.com/tortoise014/gongkao-ai-dashboard/releases) 下载最新版本
2. 解压后浏览器打开 `公考AI全流程备考仪表盘.html`
3. 所有数据存储在浏览器 localStorage

### AI 配置
点击顶栏 ⚙ → 选择平台（DeepSeek / 通义千问 / 智谱GLM）→ 输入对应 API Key
- [DeepSeek](https://platform.deepseek.com)：新用户免费 500 万 tokens
- [通义千问](https://dashscope.aliyuncs.com)：免费额度
- [智谱GLM](https://open.bigmodel.cn)：免费额度

## 🛠 技术栈

- 纯 HTML/CSS/JS，无需构建工具
- [DeepSeek / 通义千问 / 智谱GLM API](https://platform.deepseek.com) 驱动 AI 对话与识图
- 数据本地存储（localStorage）

## 📦 版本

- **v1.0** — 首次发布，完整功能
- **v1.1** — 功能优化
- **v1.2** — 功能优化
- **v1.3** — 名师对话独立成页、多 AI 平台支持（DeepSeek/通义/智谱）、AI选岗助手

## 📄 License

MIT
