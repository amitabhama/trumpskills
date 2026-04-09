# Trump Psychology Analyzer (特朗普心理分析器)

[![Version](https://img.shields.io/badge/version-v2.0-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()

> 通过分析特朗普的公开言论，解读其**意图**和**心理特征**，中英双语输出。

## 🎯 核心功能

1. **意图分析** - 分析言论背后的**目的**和**核心思路** ⭐
2. **心理分析** - 识别性格特质、行为模式
3. **预测反应** - 预测对特定事件的回应

## 📦 安装

###方式一：ClawHub 安装
```bash
clawhub install trump-psychology-analyzer
```

###方式二：手动安装
```bash
# 克隆到本地 Skills 目录
git clone https://github.com/你的username/trump-psychology-analyzer.git ~/.workbuddy/skills/trump-psychology-analyzer
```

## 🔧 依赖环境

- **WorkBuddy** 或 **OpenClaw** 平台
- 无额外依赖，纯 Prompt 驱动的分析 Skill

## 📁 文件结构

```
trump-psychology-analyzer/
├── SKILL.md                      # 核心 Skill 文件
├── trump_psychology_prompt.md    # 分析引擎（含意图分析框架）
├── metadata.json                  # Skill 元数据
├── corpus/
│   └── trump_quotes.md           # 特朗普语录语料库
└── examples/
    ├── analysis_examples.md       # 分析案例
    └── media_response_analysis.md # 媒体回应分析示例
```

## 🚀 使用方法

### 基本用法

输入任何特朗普的**推文、演讲、采访内容**，AI 会自动分析：

```
用户输入: "China is paying us billions in tariffs! Make America Great Again!"

输出: 完整的心理分析 + 意图分析报告
```

### 输入示例

| 输入类型 | 示例 |
|----------|------|
| 推文 | "Sleepy Joe is too weak to handle China!" |
| 演讲 | 竞选集会演讲片段 |
| 采访 | 新闻采访回答 |
| 新闻 | "特朗普对XX事件的回应" |

### 输出格式

```markdown
## 🧠 特朗普心理分析报告 v2.0

### 📊 基础评估
| 维度 | 得分 | 说明 |

### 🎯 ⭐ 意图分析
#### 核心目的: [1句话概括]
#### 意图类型: ATK ★★★★☆ / DEF ★★☆☆ etc
#### 核心思路: [思维模式 + 逻辑链条]
#### 受众定位: 基本盘★★★★★ / 温和派★★★☆☆

### 🔍 深度分析
[中文分析150字+]
[English analysis 150 words+]

### 📈 预测与应对
[预测反应] / [建议]
```

## 🎓 意图分析框架

### 意图类型

| 代码 | 类型 | 说明 |
|------|------|------|
| ATK | 攻击意图 | 贬低对手、制造负面标签 |
| DEF | 防御意图 | 否认指控、扮演受害者 |
| CON | 巩固意图 | 强化支持者、激发情绪 |
| SHP | 塑形意图 | 定义叙事、抢占话语权 |
| IMP | 即时反应 | 情绪发泄、报复性发推 |

### 思维模式

| 模式 | 特征 | 典型表达 |
|------|------|----------|
| 交易思维 | 谁占便宜谁吃亏 | "这笔交易好/坏" |
| 零和博弈 | 非赢即输 | "有人赢就有人输" |
| 强人叙事 | 强者vs弱者 | "强有力领导" |
| 受害心理 | 被迫害感 | "他们在害我" |
| 直觉至上 | 我感觉 | "我的直觉告诉我" |
| 即时满足 | 现在就要 | "立刻见效" |

## 📚 分析案例

### 案例1：关税推文

**输入:**
> "TARIFFS ARE BEAUTIFUL! China is paying us billions of dollars. Make America Great Again!"

**意图分析:**
| 分析项 | 结果 |
|--------|------|
| 核心目的 | 吹嘘关税政策成效，塑造"贸易战赢家"形象 |
| 意图类型 | ATK ★★★★☆ (攻击中国) / CON ★★★☆☆ (巩固基本盘) |
| 思维模式 | 交易思维 + 强人叙事 |
| 逻辑链条 | 加征关税 → 中国"在付钱" → 美国赢 → 我赢了 |

---

### 案例2：受害叙事

**输入:**
> "This is a WITCH HUNT! The Democrats and the Fake News Media are trying to destroy me!"

**意图分析:**
| 分析项 | 结果 |
|--------|------|
| 核心目的 | 否认指控，把自己塑造成受害者 |
| 意图类型 | DEF ★★★★★ (核心防御) |
| 思维模式 | 受害心理 + 阴谋论 |
| 逻辑链条 | 被起诉 → 敌人联手陷害 → 我是无辜受害者 |

---

### 案例3：攻击对手

**输入:**
> "Sleepy Joe Biden is too weak to handle China. I made China pay billions!"

**意图分析:**
| 分析项 | 结果 |
|--------|------|
| 核心目的 | 贬低拜登，对比凸显自己"强大" |
| 意图类型 | ATK ★★★★★ + SHP ★★☆☆☆ |
| 思维模式 | 强人叙事 + 零和博弈 |
| 逻辑链条 | 拜登软弱 → 中国占便宜 / 我强硬 → 中国付钱 |

---

## 📖 语录语料

### 自我炫耀类
- "I'm a very stable genius."
- "Nobody knows more than me."
- "The biggest crowd ever."
- "Most successful President."

### 攻击绰号
- Crooked Hillary
- Sleepy Joe
- Crazy Nancy
- Liddle Bob Corker
- Lyin' Ted

### 受害叙事
- Witch Hunt!
- Hoax!
- Fake News!
- They're trying to stop me.

## ⚠️ 使用限制

- 仅分析公开言论，不做医学诊断
- 保持客观中立，承认分析局限性
- 仅供参考娱乐

## 📝 更新日志

### v2.0 (2026-04-09)
- ⭐ 新增意图分析模块
- 新增核心思路识别
- 新增受众定位分析
- 中英双语输出

### v1.0 (2026-04-09)
- 基础心理分析框架
- 语录语料库

## 🤝 贡献

欢迎提交 Issue 和 PR！

## 📄 License

MIT License

---

**作者:** 基于公开资料整理
**版本:** v2.0
**更新:** 2026-04-09