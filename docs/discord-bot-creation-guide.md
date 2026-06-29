# Discord Bot创建详细指南

## 第一步：进入开发者门户

访问网址：https://discord.com/developers/applications

使用你的Discord账号登录。

---

## 第二步：创建新应用

### 2.1 点击右上角"New Application"按钮
（蓝色或紫色的按钮）

### 2.2 填写应用信息
```
应用名称: StarParks客服机器人
```
点击[Create]按钮

---

## 第三步：添加Bot ⭐ 关键步骤

### 3.1 找到左侧菜单栏

左侧菜单结构：
```
📋 菜单栏：
├── 📄 General Information（默认页面）
├── ⚙️ Settings
│   ├── 👀 Bot ← 【点这里！】
│   ├── 🔗 OAuth2
│   └── 🎨 Rich Presence
└── 📊 Resources
```

**重要**：
- 左侧菜单在"Settings"分组下
- 点击"Bot"（通常在第二个位置）

### 3.2 点击"Add Bot"

进入Bot页面后，你会看到：
```
Build-A-Bot
You haven't built a bot yet!

[Add Bot] ← 点击这个按钮
```

### 3.3 确认添加
弹出确认对话框，点击"Yes, do it!"

---

## 第四步：获取Bot Token

### 4.1 复制Token
成功添加后，你会看到：
```
Username: StarParks客服机器人
Token: [Copy] [Reset Token]
```

**点击[Copy]按钮，立即保存Token！**

⚠️ **重要**：
- Token只显示一次，务必立即保存
- 不要分享给任何人
- 不要推送到GitHub
- 保存到密码管理器或本地文件

---

## 第五步：配置Bot权限

### 5.1 启用Intents
在Bot页面向下滚动，找到"Privileged Gateway Intents"：
- ✅ SERVER MEMBERS INTENT
- ✅ MESSAGE CONTENT INTENT

点击[Save Changes]

---

## 第六步：邀请Bot到服务器

### 6.1 生成邀请链接
左侧菜单 → OAuth2 → URL Generator

### 6.2 选择权限
Scopes:
- ✅ bot

Bot Permissions:
- ✅ Manage Channels
- ✅ Read Messages
- ✅ Send Messages
- ✅ Manage Threads
- ✅ Read Message History

### 6.3 复制邀请链接
页面底部生成URL，复制并在浏览器打开

### 6.4 邀请Bot
- 选择你的服务器
- 点击[Authorize]
- 完成人机验证

---

## 第七步：获取服务器和频道ID

### 7.1 开启开发者模式
Discord桌面客户端：
设置（⚙️）→ 高级 → 开发者模式 → 开启

### 7.2 获取ID
**Guild ID（服务器ID）**：
- 右键点击服务器名称
- 选择"Copy Server ID"

**Forum Channel ID（论坛频道ID）**：
- 右键点击论坛频道
- 选择"Copy Channel ID"

---

## ✅ 完成清单

配置完成后，你应该有：
- [ ] Bot Token
- [ ] Application ID
- [ ] Guild ID（服务器ID）
- [ ] Forum Channel ID（论坛频道ID）

---

## 📝 配置文件填写

将获取的信息填写到：
```
starparks-customer-service/config/discord-bot.json
```

```json
{
  "bot_token": "YOUR_BOT_TOKEN",
  "guild_id": "YOUR_SERVER_ID",
  "forum_channel_id": "YOUR_FORUM_CHANNEL_ID"
}
```

---

## 🔍 常见问题

### 问题：找不到Bot选项
1. 确保在"General Information"页面
2. 左侧菜单应该有"Settings"分组
3. Bot在Settings下面
4. 刷新页面（F5）

### 问题：Token忘记了
1. 进入Bot页面
2. 点击[Reset Token]
3. 复制新Token（旧的会失效）

### 问题：Bot无法加入服务器
1. 检查邀请链接是否正确
2. 确保你在服务器有管理员权限
3. 确认Bot权限已正确配置

---

## 🆘 需要帮助？

如果仍有问题：
1. 截图你看到的页面
2. 告诉我你在第几步卡住了
3. 我会提供进一步指导

---

**更新时间**：2026-06-30