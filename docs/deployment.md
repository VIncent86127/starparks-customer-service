# StarParks客服系统部署指南

## 部署流程

### 第一步：技能安装

#### Discord管理核心
```bash
skillhub install discord-communities
skillhub install discord-context
skillhub install discord-project-manager
```

#### 东南亚多语言支持
```bash
skillhub install sea-doc-summarizer
skillhub install cross-cultural-communication-engine
skillhub install multilingual-game-translator
```

#### 单项语言专项
```bash
# 印尼语（最大市场）
skillhub install indonesian
skillhub install tutur-humanizer

# 泰语
skillhub install thai
skillhub install ecommerce-copy-humanizer-th

# 越南语
skillhub install vietnamese
skillhub install ecommerce-copy-humanizer-vn
```

#### 客服质检
```bash
skillhub install multilingual-customer-service-qa
```

### 第二步：Discord Bot配置

1. 创建Discord Bot（https://discord.com/developers/applications）
2. 获取Bot Token
3. 配置权限：
   - Manage Channels
   - Read Messages
   - Send Messages
   - Manage Threads
   - Read Message History

4. 邀请Bot到服务器
5. 配置config/discord-bot.json

### 第三步：语言识别配置

在config/languages.json中设置：
- 语言检测规则
- 自动回复映射
- FAQ知识库索引

### 第四步：知识库搭建

创建多语言FAQ知识库：
- 英语FAQ（基础版本）
- 印尼语FAQ（翻译版本）
- 泰语FAQ（翻译版本）
- 越南语FAQ（翻译版本）
- 马来语FAQ（翻译版本）

### 第五步：测试验证

- [ ] Discord连接测试
- [ ] 语言识别测试
- [ ] 自动回复测试
- [ ] 跨语言翻译测试
- [ ] 文化适配测试

---

## 配置文件模板

### config/discord-bot.json
```json
{
  "bot_token": "YOUR_BOT_TOKEN",
  "guild_id": "YOUR_SERVER_ID",
  "forum_channel_id": "YOUR_FORUM_CHANNEL_ID",
  "permissions": {
    "manage_channels": true,
    "read_messages": true,
    "send_messages": true,
    "manage_threads": true
  }
}
```

### config/languages.json
```json
{
  "primary_languages": ["en", "id", "th", "vi", "ms"],
  "default_language": "en",
  "auto_detect": true,
  "response_mapping": {
    "id": "indonesian",
    "th": "thai",
    "vi": "vietnamese",
    "ms": "sea-doc-summarizer",
    "en": "multilingual-game-translator"
  }
}
```

---

## 验证清单

部署完成后，验证以下功能：

### Discord功能
- [ ] Bot成功连接服务器
- [ ] 可以读取论坛帖子
- [ ] 可以发送回复
- [ ] 可以管理帖子标签
- [ ] 可以创建新帖子

### 语言功能
- [ ] 自动识别印尼语帖子
- [ ] 自动识别泰语帖子
- [ ] 自动识别越南语帖子
- [ ] 自动识别英语帖子
- [ ] 正确回复对应语言

### 客服功能
- [ ] FAQ自动回复正常
- [ ] 多语言FAQ切换正常
- [ ] 质检系统运行正常
- [ ] 跨文化沟通适配正常

---

## 维护指南

### 日常维护
1. 每周检查Discord连接状态
2. 每月更新FAQ知识库
3. 定期检查客服质检报告
4. 优化自动回复规则

### 问题排查
1. Bot连接失败 → 检查Token和权限
2. 语言识别错误 → 更新语言检测规则
3. 回复质量不佳 → 优化技能配置
4. 用户投诉增多 → 分析质检报告

---

## 联系支持

如遇到问题，请联系：
- 技术支持：OpenClaw AI Assistant
- 项目负责人：林然