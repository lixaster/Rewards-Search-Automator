<div align="center">

# 🏆 Rewards Search Automator

<img src="https://raw.githubusercontent.com/lixaster/Rewards-Search-Automator/47d130ff07c6fe779984987cdcdbe747fd244ac9/img/icon128.png" alt="Rewards Search Automator Logo" width="128">

### 自动化你的 Bing 搜索，轻松获取 Microsoft Rewards 积分！

[![Version](https://img.shields.io/badge/version-2.2.0.1-green?style=for-the-badge)](https://github.com/lixaster/Rewards-Search-Automator/releases)
[![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lixaster/Rewards-Search-Automator?style=for-the-badge&logo=github)](https://github.com/lixaster/Rewards-Search-Automator/stargazers)

[🚀 功能](#-features) • [📦 安装](#-installation) • [🎯 使用方法](#-usage) • [⚙️ 配置](#️-configuration) • [🤝 支持](#-support)

---

</div>

## 📖 项目简介

**Rewards Search Automator** 是一款强大的 Chrome/Edge 扩展，旨在通过自动化 Bing 搜索帮助你最大化获取 **Microsoft Rewards** 积分。无论你是在桌面还是移动设备上，这个扩展都会处理繁琐的日常搜索任务，让你专注于兑换奖励！

✨ **完全免费** • 🚫 **无广告** • 🔒 **重视隐私** • 🎨 **现代界面**

<div align="center">
<img src="https://raw.githubusercontent.com/lixaster/Rewards-Search-Automator/fcf4a996ef7f3cfcbfaac59a53a27dd36abbb48b/img/preview-big.png" alt="Extension Preview" width="600">
</div>

---

## ✨ 功能亮点

### �️ 桌面与移动搜索自动化
- 在桌面与移动用户代理上执行自动搜索
- 智能设备模拟以实现更精确的移动搜索
- 支持单独或组合的搜索模式

### ⚡ 可自定义设置
- **可调搜索次数**：设置希望执行的搜索数量
- **随机延迟**：自定义每次搜索之间的最小/最大等待时间以更自然地模拟行为
- **实时进度跟踪**：可视化进度条显示自动化状态

### 🎨 现代化界面
- 漂亮的渐变设计与流畅动画
- 紧凑的弹出窗口，完美适配浏览器
- 直观的控制和清晰的视觉反馈
- 响应式布局

### 🔐 安全可靠
- 使用随机词典生成多样化搜索查询
- 随机化时序以模拟真人行为
- 不收集或跟踪用户数据
- 开源且透明

---

## 📦 安装

### 手动安装（开发者模式）
1. 下载或克隆本仓库：
   ```bash
   git clone https://github.com/lixaster/Rewards-Search-Automator.git
   ```
2. 在 Chrome/Edge 中打开 `chrome://extensions/`
3. 开启 **开发者模式**（右上角开关）
4. 点击 **“加载已解压的扩展程序”**
5. 选择扩展所在文件夹
6. 安装完成！

---

## 🎯 使用方法

### 快速开始
1. 点击浏览器工具栏中的扩展图标
2. （可选）配置偏好设置：
   - **桌面搜索**：桌面搜索次数（默认：20）
   - **移动搜索**：移动搜索次数（默认：20）
   - **最小/最大延迟**：搜索之间的等待时间（默认为 8-10 秒）
3. 选择自动化模式：
   - 🖥️ **桌面**：仅执行桌面搜索
   - 📱 **移动**：仅执行移动搜索
   - 📊 **同时**：先执行桌面再执行移动搜索
4. 观察进度条，等待自动化完成！

### 高级提示
- **每日运行**：建议每天运行一次以最大化积分
- **自然节奏**：将延迟设置为 8-15 秒更接近真实行为
- **组合模式**：使用“同时”模式一次性完成所有日常搜索
- **查看进度**：进度条显示实时完成状态

---

## ⚙️ 配置

### 默认设置
```javascript
Desktop Searches: 20
Mobile Searches: 20
Min Delay: 8 seconds
Max Delay: 10 seconds
```

### 自定义
所有设置可在弹出窗口中启动自动化前调整：
- 增加搜索次数以提高每日配额
- 调整延迟以在速度与自然性之间取得平衡
- 设置会在会话间持久保存

---

## 🛠️ 技术细节

- **Manifest 版本**：3（Chrome 扩展最新标准）
- **权限**：Debugger（用于移动设备模拟）
- **技术栈**：JavaScript (ES6+), jQuery, Bootstrap 5, Font Awesome
- **兼容浏览器**：Chrome、Edge、Brave 及其他 Chromium 内核浏览器

---

## 🤝 支持

### 🐛 发现 Bug？

请在仓库中 [打开 Issue](https://github.com/lixaster/Rewards-Search-Automator/issues) 并提供：
- 问题的详细描述
- 重现步骤
- 预期结果与实际结果
- 浏览器版本与操作系统信息

### 💡 功能建议

有想法想改善扩展？请 [创建功能请求](https://github.com/lixaster/Rewards-Search-Automator/issues/new)，我们一起讨论！

---

## 📄 许可证

本项目遵循 **MIT 许可证**，详见 [LICENSE](LICENSE) 文件。

---

## ⚠️ 免责声明

本扩展为独立项目，**与 Microsoft Corporation 或 Microsoft Rewards 项目无关且未受其认可或背书**。使用时请遵守 Microsoft Rewards 的服务条款，作者对因使用本工具导致的任何账户行为不承担责任。

---

<div align="center">

### 🌟 如果你喜欢此项目，请不要忘记点个 Star！🌟

[![GitHub followers](https://img.shields.io/github/followers/lixaster?style=social)](https://github.com/lixaster)
[![GitHub stars](https://img.shields.io/github/stars/lixaster/Rewards-Search-Automator?style=social)](https://github.com/lixaster/Rewards-Search-Automator/stargazers)

</div>

