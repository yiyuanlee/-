# 今天吃什么 · WeChat Mini Program 🍱

一个为吃饭选择困难症用户打造的小程序，随机推荐美食选项，帮你轻松决定“今天吃什么”。

---

## 🚀 功能介绍

- 🎲 一键随机推荐食物
- 📸 支持用户选择头像 & 填写昵称
- 🧭 轻松跳转到推荐页面获取吃饭灵感
- ❤️ 美观简洁的界面设计，适合日常使用

---

## 🏗️ 项目结构

```
miniprogram/
├── pages/
│   ├── index/           # 首页：用户头像 + 昵称输入
│   │   ├── index.wxml
│   │   ├── index.wxss
│   │   ├── index.ts
│   │   └── index.json
│   ├── food/            # 推荐页面：随机食物推荐
│   │   ├── food.wxml
│   │   ├── food.wxss
│   │   ├── food.js
│   │   └── food.json
├── app.json             # 全局配置
├── project.config.json  # 小程序项目配置
```

---

## 📦 安装与使用

### 1. 克隆项目
```bash
git clone https://github.com/yourusername/today-eat-miniapp.git
```

### 2. 使用微信开发者工具打开
- 下载微信开发者工具（[官方链接](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)）
- 选择 “导入项目”，路径选中项目根目录

### 3. 编译运行
- 修改 `app.json` 中的 `appid`（使用你自己的）
- 点击 **编译** 即可预览

---

## 🧠 待办功能（可选扩展）

- [ ] 根据口味偏好推荐（辣/素/低卡等）
- [ ] 支持用户收藏喜欢的推荐
- [ ] 接入美团/大众点评 API 提供附近餐厅推荐
- [ ] 增加日历推荐，每天不同推荐菜品

---

## 👩‍💻 开发者

| 角色 | 昵称 |
|------|------|
| 💡 设计 & 开发 | Yiyuan Lee |
| 📦 技术栈 | 微信小程序原生框架 + TypeScript（首页） |

---
