# Serenity (@aleabitoreddit) · Perspective Skill

> *"Markets are generally positive sum if you're not touching options."*

**蒸馏 AI/半导体供应链分析师 Serenity 的思维框架。** 基于 6 维度深度调研（1,700+ 推文、Substack 长访谈、第三方分析、批评者观点），提炼他的认知操作系统——心智模型、决策启发式、表达 DNA。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)

---

## 他是谁

Serenity（X: [@aleabitoreddit](https://x.com/aleabitoreddit)），36 万+ 粉丝的 AI/半导体供应链分析师。前 AI 研究员，RISC-V Foundation 成员。从 Reddit WSB 起家（因 $AXTI 分析被封号），2025 年 7 月转 X。

**核心能力**：找到 AI 供应链中那些「机构忽略、散户看不懂」的小公司 chokepoint——如果它们断供，整个行业就停摆。

**著名 case**：$AXTI（$12→$104+）、$IQE（2 个月 +316%）、$RPI（帖发出去 LSE 两天涨 50%，Bloomberg/Reuters/FT 全报了）。

---

## 效果示例

```
用户      ❯ 如果 AXTI 现在 85x revenue，估值已经严重脱离基本面，你的 chokepoint 理论还成立吗？

Serenity  ❯ 85x revenue 确实离谱。但你不能用 expansion metrics 去 val 一个 chokepoint。
            AXTI 从 $500M MC 到 $2.6B，Point72 在高位往里买。
            机构不是在 val 它的 revenue，是在 val「如果它断供，整个 photonics 链会怎样」。
            
            我承认估值纪律是我的弱点。85x revenue 意味着你承受 -35% 到 -89% 的历史回撤。
            但如果瓶颈在，价格会自己找回来。
            
            还是那句：stocks don't move in a straight line up. DYOR.
```

```
用户      ❯ 量子计算成熟后，会对 AI 芯片供应链造成什么影响？

Serenity  ❯ 这不是我覆盖过的领域。我不会装懂然后给你一个看起来确定的答案。
            
            但如果我用我的框架推演一下……量子不是替代 GPU 的，它是解决特定问题类的工具。
            如果我要找量子供应链的 chokepoint，我会看：
            1. NVIDIA 在量子上押了什么？cuQuantum SDK、IonQ 合作
            2. 稀释制冷机的供应商是谁？这就像量子时代的 AXTI
            3. 量子纠错的硬件层需要什么材料？
            
            但我不确定的是时间线和交集有多大。这是我的框架推断，不是结论。
```

---

## 蒸馏了什么

| 层次 | 数量 | 说明 |
|------|------|------|
| **心智模型** | 5 个 | 供应链瓶颈理论、瓶颈博弈 vs 扩张估值、NVIDIA 信号读取、信息不对称套利、正和市场观 |
| **决策启发式** | 8 条 | chokepoint 测试、NVIDIA 跟随、欧洲小盘优先、反 meme stock 标签、机构跟随确认、反期权铁律、DYOR 底线、地缘政治折价 |
| **表达 DNA** | 完整 | 高频词汇、句式指纹、回复风格、幽默模式、风险披露习惯 |
| **内在矛盾** | 3 对 | gatekeeper 张力、正确性张力、credential 张力 |

---

## 安装

基于 [Agent Skills](https://agentskills.io) 协议，可在任何兼容的 AI agent runtime 中使用。

### 方式一：一行命令

```bash
npx skills add leslieyeo/aleabitoreddit-skill
```

或在你的 agent 对话里说：
```
帮我安装这个 skill: https://github.com/leslieyeo/aleabitoreddit-skill
```

### 方式二：手动安装

```bash
git clone https://github.com/leslieyeo/aleabitoreddit-skill.git
cp -r aleabitoreddit-skill/SKILL.md ~/.claude/skills/aleabitoreddit-perspective/
cp -r aleabitoreddit-skill/references ~/.claude/skills/aleabitoreddit-perspective/
```

### 方式三：直接粘贴

把 `SKILL.md` 的内容直接粘贴到 AI agent 对话中即可使用。

---

## 使用

装好后，在对话中触发：

```
> 用 Serenity 的视角帮我看看 $SMCI 现在能不能买
> aleabitoreddit 会怎么分析 NVIDIA 的新架构？
> 切换到 Serenity 模式
> Serenity perspective on this stock
```

也支持模糊触发：「帮我用他的角度想想」「如果他会怎么做」

---

## 仓库结构

```
aleabitoreddit-skill/
├── SKILL.md                          # 蒸馏产物（可直接使用）
├── README.md                         # 说明文档
├── references/
│   └── research/
│       ├── 01-writings.md            # 系统性长文/投资论文 (320 行)
│       ├── 02-conversations.md       # 对话模式/回应风格 (309 行)
│       ├── 03-expression-dna.md      # 表达风格/DNA (336 行)
│       ├── 04-external-views.md      # 他人评价/批评 (234 行)
│       ├── 05-decisions.md           # 投资决策/track record (294 行)
│       └── 06-timeline.md            # 完整人生时间线 (275 行)
├── tests/
│   └── sanity-check-axti-valuation.md # 质量验证报告
└── PHASE4-REPORT.md                  # 蒸馏流程质量报告
```

调研全透明。每个 research 文件都标注了来源 URL 和可信度，可以看到信息怎么被收集、筛选、变成心智模型。

---

## 诚实边界

此 Skill 基于公开信息提炼，存在以下局限：

- **Credential 未验证**：Nature 论文、RISC-V 成员身份、拒绝 NVIDIA 邀约均为 self-reported，未找到独立验证
- **无公开认错记录**：所有可检索内容中未发现公开承认分析错误的实例
- **幸存者偏差**：winner 高调宣传、loser 沉默的风险，Skill 可能高估了准确率
- **估值纪律缺失**：推广 85x revenue 小公司是真实弱点——Skill 会复现这个弱点
- **调研时间**：2026 年 5 月 26 日，之后的变化未覆盖

**一个不告诉你局限在哪的 Skill，不值得信任。**

---

## 质量验证

| 测试 | 结果 |
|------|------|
| Sanity Check（AXTI 估值问题） | ✅ 94% |
| Edge Case（量子计算影响） | ✅ 通过 |
| Style Check（表达辨识度） | ✅ 8/10 |
| 心智模型数量 (3-7) | ✅ 5 个 |
| 每个模型有局限性 | ✅ 全部 |
| 诚实边界 (≥3) | ✅ 6 条 |
| 内在张力 (≥2) | ✅ 3 对 |
| 一手来源占比 (>50%) | ✅ >70% |

详见 [PHASE4-REPORT.md](PHASE4-REPORT.md)

---

## 许可证

MIT — 随便用，随便改，随便造。
