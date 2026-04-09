# 特朗普推文意图分析示例

## 示例1: 关税推文

**原文:** "TARIFFS ARE BEAUTIFUL! China is paying us billions of dollars. Make America Great Again!"

### 🎯 意图分析

| 分析项 | 内容 |
|--------|------|
| **核心目的** | 吹嘘关税政策成效，塑造"贸易战赢家"形象 |
| **意图类型** | ATK ★★★★☆ (攻击中国) / CON ★★★☆☆ (巩固基本盘) |
| **思维模式** | 交易思维 + 强人叙事 |
| **逻辑链条** | 加征关税 → 中国"在付钱" → 美国赢 |

---

## 示例2: 受害叙事

**原文:** "This is a WITCH HUNT! The Democrats and the Fake News Media are trying to destroy me!"

### 🎯 意图分析

| 分析项 | 内容 |
|--------|------|
| **核心目的** | 否认指控，把自己塑造成受害者 |
| **意图类型** | DEF ★★★★★ (核心防御) / IMP ★★☆☆☆ (即时反应) |
| **思维模式** | 受害心理 + 阴谋论 |
| **逻辑链条** | 被起诉 → 敌人联手陷害 → 我是无辜受害者 |

---

## 示例3: 攻击对手

**原文:** "Sleepy Joe Biden is too weak to handle China. I made China pay billions!"

### 🎯 意图分析

| 分析项 | 内容 |
|--------|------|
| **核心目的** | 贬低拜登，对比凸显自己"强大" |
| **意图类型** | ATK ★★★★★ + SHP ★★☆☆☆ |
| **思维模式** | 强人叙事 + 零和博弈 |
| **逻辑链条** | 拜登软弱 → 中国占便宜 / 我强硬 → 中国付钱 |

---

## v2.0 Skill 文件结构

```
~/Downloads/trump-skills/
├── SKILL.md                    # 主技能说明
├── trump_psychology_prompt.md  # 核心分析引擎(含意图分析)
├── metadata.json               # 配置
├── corpus/
│   └── trump_quotes.md        # 语录语料
└── examples/
    └── analysis_examples.md   # 示例分析
```