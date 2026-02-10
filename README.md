Prompt Refiner Ultimate Pro



一个现代化的 AI 提示词优化工具，支持多种 AI 服务商和专业模式，可将粗略想法转化为专家级 Prompt。

✨ 核心特性

🎯 智能优化

· 普通模式: 基础 Prompt 优化，适用于通用场景
· 前端模式: 专注 UI/UX 设计，包含视觉规范、交互细节
· 专业模式: 全栈项目管理，输出完整技术方案和验收标准

🔌 多服务商支持

· DeepSeek: 默认服务商，性价比高
· GLM-4: 智谱 AI 大模型
· OpenAI: GPT 系列模型，支持自定义 API 地址

📱 现代化界面

· 响应式设计，完美适配移动端和桌面端
· 三种主题配色（普通/前端/专业）
· 实时 Markdown 渲染
· 流畅的动画和交互反馈

⚡ 增强功能

· 智能流式输出: 实时显示生成过程
· 一键复制: 双重保险复制机制（Clipboard API + execCommand）
· 多种下载格式: 支持 TXT 和 Markdown 格式
· 本地存储: 配置自动保存到浏览器

🚀 快速开始

在线使用

1. 直接打开 index.html 即可使用
2. 无需安装，纯 HTML + JavaScript 实现

本地部署

```bash
git clone https://github.com/yourusername/prompt-refiner.git
cd prompt-refiner
# 直接使用任意 HTTP 服务器，如：
python3 -m http.server 8000
# 或
npx serve .
```

⚙️ 配置说明

API 密钥设置

1. 点击右上角设置按钮 ⚙️
2. 选择服务商（DeepSeek/GLM-4/OpenAI）
3. 输入对应的 API Key
4. OpenAI 用户可自定义 API URL

模式选择

· 普通模式: 紫色主题，基础优化
· 前端模式: 粉色主题，UI/UX 设计优化
· 专业模式: 绿色主题，项目级文档输出

📖 使用指南

基础使用

1. 选择需要的模式
2. 在输入框中描述你的需求
3. 点击发送按钮或按 Enter
4. 等待 AI 生成优化后的 Prompt

输出示例

```
---ANALYSIS_START---
【原始需求分析】
- 核心意图：创建一个登录表单
- 缺失要素：验证规则、错误提示、响应式设计
- 潜在歧义：表单样式未明确
---ANALYSIS_END---

---OPTIMIZED_START---
请设计一个现代化的登录表单，要求：

1. 视觉设计
   - 使用渐变色背景 (#667eea → #764ba2)
   - 圆角设计：12px
   - 阴影：0 10px 25px rgba(0,0,0,0.1)

2. 包含字段
   - 邮箱输入框（带邮箱图标）
   - 密码输入框（带眼睛图标显示/隐藏密码）
   - 记住我复选框
   - 提交按钮

3. 交互要求
   - 表单验证（实时反馈）
   - 加载状态（提交时按钮显示加载动画）
   - 错误提示（红色边框 + 下方文字提示）

4. 响应式设计
   - 移动端：垂直排列，适当间距
   - 桌面端：固定宽度 400px

请使用纯 HTML/CSS/JavaScript 实现，不依赖框架。
---OPTIMIZED_END---
```

🔧 技术特性

复制功能

· 优先使用 Clipboard API（HTTPS 环境）
· 降级使用 execCommand（HTTP/本地环境）
· iOS Safari 特殊处理
· 完善的错误处理和用户反馈

下载功能

· 支持 Blob URL 方案（现代浏览器）
· 降级 Data URL 方案（兼容性）
· 自动文件名生成
· 移动端兼容性测试

流式输出

· 实时显示生成过程
· 打字机效果光标
· 错误状态友好提示
· 网络中断自动恢复

🎨 设计理念

用户体验

· 即时反馈: 按钮点击、复制成功都有视觉反馈
· 无障碍: 键盘导航支持，适当的对比度
· 移动优先: 完美适配小屏幕设备
· 离线使用: 配置本地存储，无需重复输入 API Key

代码质量

· 纯前端实现，无后端依赖
· 模块化 JavaScript 代码
· Tailwind CSS 实现响应式布局
· 完整的错误边界处理

📁 项目结构

```
prompt-refiner/
├── index.html          # 主界面
├── README.md           # 说明文档
```

🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 项目
2. 创建功能分支 (git checkout -b feature/AmazingFeature)
3. 提交更改 (git commit -m 'Add some AmazingFeature')
4. 推送到分支 (git push origin feature/AmazingFeature)
5. 开启 Pull Request

📄 许可证

MIT License - 详见 LICENSE 文件

🙏 致谢

· DeepSeek - 默认 AI 服务
· Tailwind CSS - 样式框架
· Marked - Markdown 解析器
· Google Fonts - 字体服务

📞 支持

如有问题或建议，请：

1. 查看 Issues
2. 提交新的 Issue
3. 或通过邮件联系

---

温馨提示: 请妥善保管你的 API Key，不要公开分享。本项目完全运行在客户端，不会收集任何用户数据。

最新更新: 2026年2月 - 增加专业模式，优化复制/下载功能
