# ✨ 互动特效合集

一个精心制作的网页互动特效集合，包含多种有趣的视觉体验和小游戏。

![Node.js](https://img.shields.io/badge/Node.js-v16+-green?logo=node.js)
![License](https://img.shields.io/badge/License-MIT-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

## 📋 项目列表

| 项目 | 描述 | 大小 |
|------|------|------|
| 🌸 飞花令 | 古典诗词互动体验 | 55.4 KB |
| 💫 粒子特效 | 梦幻粒子动画 | 27.7 KB |
| 🌟 粒子特效 Plus | 升级版粒子效果 | 27.9 KB |
| 🔫 枪击特效 | 射击视觉特效 | 56.7 KB |
| 💥 枪击特效 2.0 | 升级射击体验 | 49.3 KB |
| 🍉 切水果 | 经典水果忍者玩法 | 48.6 KB |
| 🎄 圣诞树 | 节日氛围特效 | 25.6 KB |
| 🎅 圣诞树 Plus | 豪华版圣诞树 | 37.8 KB |
| 💖 Love | 浪漫爱心特效 | 31.3 KB |

## ⚠️ 重要说明

由于部分项目需要使用 **摄像头权限**，浏览器出于安全考虑有以下限制：

1. **无法直接打开 HTML 文件** - 使用 `file://` 协议打开时，摄像头 API 会被禁用
2. **HTTPS 要求** - 部署到远程服务器时，必须使用 HTTPS 协议才能访问摄像头
3. **本地开发例外** - `localhost` 或 `127.0.0.1` 被视为安全来源，可使用 HTTP

因此，**必须通过本地服务器运行本项目**。

## 🚀 快速开始

### 方式一：使用 http-server（推荐）

```bash
# 安装 http-server（如果未安装）
npm install -g http-server

# 进入项目目录
cd your-project-folder

# 启动服务器
http-server

# 或指定端口
http-server -p 8080
```

访问：http://localhost:8080

### 方式二：使用 Python 服务器

Python 3.x：

```
# 进入项目目录
cd your-project-folder

# 启动服务器
python -m http.server 8080
```

Python 2.x：

```
python -m SimpleHTTPServer 8080
```

访问：http://localhost:8080

### 方式三：使用 VS Code Live Server

1. 安装 VS Code 扩展：Live Server
2. 右键点击 `index.html`
3. 选择 "Open with Live Server"

### 方式四：使用 PHP 内置服务器

```
# 进入项目目录
cd your-project-folder

# 启动服务器
php -S localhost:8080
```

### 方式五：使用 npx（无需全局安装）

```
# 使用 http-server
npx http-server -p 8080

# 或使用 serve
npx serve -p 8080
```

## 📁 项目结构

```
.
├── index.html              # 主导航页面
├── index_飞花令.html        # 飞花令
├── index_粒子特效.html      # 粒子特效
├── index_粒子特效2.html     # 粒子特效 Plus
├── index_枪击1.html         # 枪击特效
├── index_枪击2.html         # 枪击特效 2.0
├── index_切水果.html        # 切水果游戏
├── index_圣诞树.html        # 圣诞树
├── index_圣诞树plus.html    # 圣诞树 Plus
├── index_Love.html          # Love 特效
├── js/                      # JavaScript 资源
└── README.md               # 项目说明
```

## 🔧 环境要求

- 现代浏览器（Chrome、Firefox、Edge、Safari）
- Node.js v16+（如使用 http-server）
- Python 3.x（如使用 Python 服务器）

## 🌐 浏览器兼容性

| 浏览器  | 版本 | 支持情况   |
| ------- | ---- | ---------- |
| Chrome  | 80+  | ✅ 完全支持 |
| Firefox | 75+  | ✅ 完全支持 |
| Edge    | 80+  | ✅ 完全支持 |
| Safari  | 13+  | ✅ 完全支持 |
| IE      | 所有 | ❌ 不支持   |

## 🔐 关于摄像头权限

首次使用需要摄像头的功能时，浏览器会弹出权限请求：

1. 点击 "允许" 授予摄像头权限
2. 如果误点了 "拒绝"，需要在浏览器设置中重新开启：
   - Chrome：地址栏左侧 🔒 图标 → 网站设置 → 摄像头 → 允许
   - Firefox：地址栏左侧 🔒 图标 → 清除权限并重试

## ❓ 常见问题

**Q: 摄像头无法启动？**
 A: 请检查以下几点：

- 确保通过 `localhost` 或 `127.0.0.1` 访问，而非直接打开文件
- 确保浏览器已授予摄像头权限
- 确保没有其他程序正在使用摄像头
- 尝试刷新页面或重启浏览器

**Q: 页面样式显示异常？**
 A: 请确保使用现代浏览器，并启用 JavaScript。

**Q: 如何部署到服务器？**
 A: 如需部署到远程服务器，必须：

- 配置 HTTPS（可使用 Let's Encrypt 免费证书）
- 确保服务器正确设置 MIME 类型

## 📝 开源协议

本项目采用 MIT 协议开源。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！



​						Made with 💜 by Claude