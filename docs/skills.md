# StarParks客服系统技能说明

## 已安装技能列表

### 🎮 Discord管理核心

#### 1. discord-communities (v1.0.6)
**功能**: Discord服务器完整管理
- 管理服务器、频道、消息、成员、角色
- 应用指令管理
- 完整API集成（ClawLink驱动）

**使用场景**:
- 读取论坛帖子
- 发送自动回复
- 管理论坛频道
- 成员权限管理

---

#### 2. discord-context (v0.1.1) ⭐ 核心
**功能**: Discord论坛频道上下文管理
- 同步并缓存每线程上下文
- 轮询活跃线程
- 列出缓存上下文
- 专为Discord Forum频道设计

**使用场景**:
- **论坛帖子自动管理**（核心功能）
- 多轮对话上下文保持
- 帖子状态追踪
- 用户问题跟进

**为什么重要**:
这是Discord论坛客服的核心技能，能够：
- 自动识别新帖子
- 保持对话上下文
- 追踪问题解决进度
- 归档已解决帖子

---

#### 3. discord-project-manager (v2.1.6)
**功能**: Discord项目协作基础设施
- 论坛频道管理
- 帖子管理
- 三级权限体系
- 参与者权限管理
- 提及模式控制

**使用场景**:
- 客服团队协作
- 帖子分配管理
- 权限分级控制

---

### 🌏 东南亚多语言支持

#### 4. sea-doc-summarizer (v2.0.0) ⭐⭐⭐
**功能**: 东南亚多语言文档总结
- 支持：English + Chinese + **Bahasa Melayu** + **Bahasa Indonesia**
- 跨语言处理能力
- 专为东南亚语言优化
- 文档总结、内容提取

**使用场景**:
- 快速理解多语言用户问题
- 总结复杂游戏规则文档
- 跨语言信息提取
- 多语言FAQ生成

**优势**:
- **唯一专门为东南亚语言设计的技能**
- 支持马来语和印尼语（其他技能不支持）
- 跨语言处理能力强大

---

#### 5. cross-cultural-communication-engine (v1.0.0) ⭐⭐⭐⭐⭐
**功能**: 跨文化沟通助手
- 五大文化框架：Brazil + China + Europe + **Southeast Asia** + Middle East
- 自动适配语气、措辞、沟通风格
- "Soft wording"技巧减少用户抵触
- 文化合适的邮件/回复草稿生成
- **减少80%邮件往返**

**使用场景**:
- 处理用户投诉（文化适配）
- 编写道歉信（避免冒犯）
- 解释复杂政策（语气柔和）
- VIP客户沟通（文化尊重）

**东南亚沟通特点**:
1. 避免直接否定 → 使用间接表达
2. 注重礼貌 → 添加"请"、"谢谢"
3. 语气柔和 → 避免强硬措辞
4. 文化尊重 → 理解当地习俗
5. 耐心解释 → 详细而非简短

**示例**:
```
❌ 错误: "You cannot do this. It's against our policy."
✅ 正确: "I understand your concern. Let me explain our policy 
        and see if we can find a solution together."
```

---

#### 6. multilingual-game-translator (v1.0.0) ⭐⭐⭐⭐⭐
**功能**: 游戏行业专项翻译
- 支持10+语言（包括东南亚主要语言）
- 游戏本地化：UI提示、活动运营、剧情对话
- 商务沟通：邮件撰写、提案Pitch、合同术语
- 游戏专业术语翻译（研发、发行、运营）

**使用场景**:
- 游戏公告翻译（英语→东南亚语言）
- 活动规则翻译（文化适配）
- 客服回复翻译（保持游戏语境）
- 用户反馈翻译（理解玩家语言）

**支持语言**:
- ✅ English
- ✅ Chinese
- ✅ Japanese
- ✅ Korean
- ✅ Thai
- ✅ Vietnamese
- ✅ Indonesian
- ✅ Malay（部分支持）
- ✅ Russian
- ✅ French
- ✅ German
- ✅ Spanish
- ✅ Portuguese
- ✅ Arabic
- ✅ Hindi

---

### 🎯 单项语言专项

#### 7. indonesian (v1.0.0) ⭐⭐⭐⭐⭐
**功能**: 自然印尼语写作
- 避免AI生成感
- 避免过于正式
- 使用本地表达方式

**为什么重要**:
印尼是东南亚最大游戏市场（2.7亿人口），玩家对语言质量敏感。

---

#### 8. tutur-humanizer (v1.0.1) ⭐⭐⭐⭐
**功能**: 印尼语人性化处理
- 去除机器感
- 保持自然语气
- 上下文适配

**使用场景**:
二次优化AI生成的印尼语回复，使其更自然。

---

#### 9. thai (v1.0.0) ⭐⭐⭐⭐
**功能**: 自然泰语写作
- 泰语本地化表达
- 避免翻译腔
- 文化适配

---

#### 10. ecommerce-copy-humanizer-th (v1.0.0)
**功能**: 泰语文案人性化
- 电商文案优化
- 保持说服力
- 平台适配

---

#### 11. vietnamese (v1.0.0) ⭐⭐⭐⭐
**功能**: 自然越南语写作
- 越南语本地化
- 避免AI感
- 自然流畅

---

#### 12. ecommerce-copy-humanizer-vn (v1.0.0)
**功能**: 越南语文案人性化
- 文案优化
- 本地表达
- 平台适配

---

### 📊 客服质检

#### 13. multilingual-customer-service-qa (v1.3.0) ⭐⭐⭐⭐
**功能**: 多语言客服质检
- 支持：Chinese + English + Japanese + Korean
- 分析聊天记录、邮件、工单
- 识别合规风险
- 情绪分析
- 生成质检报告

**注意**: 
虽然不支持东南亚语言，但可用于英语客服质检（菲律宾、新加坡市场）。

---

## 技能组合策略

### 🎯 场景1: 印尼玩家咨询
```
工作流:
1. discord-context → 识别新帖子
2. indonesian → 生成印尼语回复
3. tutur-humanizer → 优化语气
4. cross-cultural-communication-engine → 文化适配
5. discord-communities → 发送回复
```

### 🎯 场景2: 泰国玩家投诉
```
工作流:
1. discord-context → 读取帖子内容
2. thai → 生成泰语回复
3. cross-cultural-communication-engine → Soft wording处理
4. discord-communities → 发送道歉信
```

### 🎯 场景3: 越南玩家询问规则
```
工作流:
1. sea-doc-summarizer → 总结游戏规则（英语）
2. multilingual-game-translator → 翻译成越南语
3. vietnamese → 优化表达
4. discord-communities → 发送回复
```

### 🎯 场景4: 多语言FAQ生成
```
工作流:
1. 编写英语FAQ
2. multilingual-game-translator → 翻译成印尼/泰/越
3. indonesian/thai/vietnamese → 优化本地表达
4. tutur-humanizer → 二次优化（印尼）
```

---

## 技能覆盖率

| 语言 | 翻译 | 优化 | 文化适配 | 综合评分 |
|------|------|------|---------|---------|
| Indonesian | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 95% |
| Thai | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 85% |
| Vietnamese | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 85% |
| Malay | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | 70% |
| English | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 100% |

---

## 安装命令汇总

```bash
# Discord核心
skillhub install discord-communities
skillhub install discord-context
skillhub install discord-project-manager

# SEA多语言
skillhub install sea-doc-summarizer
skillhub install cross-cultural-communication-engine
skillhub install multilingual-game-translator

# 单项语言
skillhub install indonesian
skillhub install tutur-humanizer
skillhub install thai
skillhub install ecommerce-copy-humanizer-th
skillhub install vietnamese
skillhub install ecommerce-copy-humanizer-vn

# 客服质检
skillhub install multilingual-customer-service-qa
```

---

## 维护建议

1. **每周检查**: 技能版本更新
2. **每月优化**: 根据质检报告调整技能配置
3. **季度复盘**: 分析客服数据，优化工作流
4. **年度评估**: 评估ROI，决定是否增减技能