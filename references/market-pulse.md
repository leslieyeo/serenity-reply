# Serenity · Market Pulse（易腐层 · 定期刷新）

> **as-of: 2026-05-28**
>
> 本文件是 `serenity-reply` skill 的「易腐层」：只放会随市场和时间快速变化的内容——
> 当前宏观观点、个股近况、粉丝/订阅数、时间线最新节点。
> `SKILL.md` 主体只保留**不腐**的思维框架（心智模型、决策启发式、表达 DNA、价值观）；
> 任何带「现在 / 最新 / 当前」性质的快照一律放这里，按周期覆写，不动主体。
>
> **性质声明**：以下是对 Serenity 公开观点和公开市场信息的**转述快照**，基于 web 可检索来源，
> 非本人观点，不构成投资建议。数字会过期，引用前先看 `as-of` 日期。

---

## 刷新 SOP（每周期跑一次，只改本文件）

**触发**：对 Claude 说「刷新 serenity 的 market pulse」，或用 `/loop` / `/schedule` 定期跑。

**步骤**：
1. 跑这几条固定 WebSearch（替换年份为当前年）：
   - `aleabitoreddit Serenity latest <持仓ticker>`
   - 每只在持标的：`<ticker> stock supply chain bottleneck <year>`（拿近况 + 财报 + SEC 文件）
   - `aleabitoreddit Serenity Substack`（拿第三方分析/批评）
2. 只采纳**带日期、带可点击来源**的信息填入下方表格；拿不到来源的**不写**。
3. **绝不编造**股价、市值、粉丝数、涨跌幅。X 内容需登录，web 多为摘要——拿不到就在「待核对」里标注，不猜。
4. 多个来源数字**打架时如实并列 + 标存疑**，不强行裁决谁对。
5. 更新完把顶部 `as-of` 改成当天日期，必要时往「时间线增量」追加一行。
6. **不改 `SKILL.md`**。框架是稳定层，只有 Serenity 的方法论本身变了才动它。

**周期建议**：photonics/小盘波动快，**2-4 周一次**较合适；遇 NVIDIA 大额投资、在持标的财报、地缘事件（出口管制/稀土）随时补刷。

---

## 当前宏观观点（as-of 2026-05-28）

- 据公开推文，仍**看好 AI 基础设施精选标的**（光子学/CPO 超级周期、1.6T 前置布局），偏好「做多整条供应链 + 额外瓶颈」。
- 之前提到的「看空大盘 / 伊朗油价 / 降息预期消失」属更早快照，**本轮未独立复核**，移入「待核对」。

## 个股状态（as-of 2026-05-28）

| 标的 | Serenity 定位 | 最新可查状态 | 来源 |
|------|--------------|------------|------|
| **$SIVE**（Sivers, 瑞典） | CPO/硅光子 CW DFB 激光源 chokepoint，"下一个 $LITE" | 一度单日 +73.78%，市值约 $231M（曾 ~$190M）；称为 AMZN Trainium / MSFT Maia 供货、可能是 AAPL 供应商（传 50M RFQ）；个人 bull case 喊 $10B+。**估值警示**：截至 2026-04-19 P/S≈20.97x，近欧洲半导体均值 5 倍 | [tweet 1](https://x.com/aleabitoreddit/status/2033535833085718996) · [tweet 2](https://x.com/aleabitoreddit/status/2034087274800091401) · [AAPL RFQ tweet](https://x.com/aleabitoreddit/status/2048680795586568237) · [chipstockinvestor](https://chipstockinvestor.com/silicon-photonics-stocks-go-wild-long-term-investors-should-be-cautious/) |
| **$AXTI**（AXT Inc.） | InP 衬底垄断，"basically the entire photonics supply chain" | 价格上 $50+（注：skill 正文历史案例写到 $104，应为不同时点峰值，需核对）；控全球约 **60-70% InP 衬底**；**完成 $632.5M 融资**支持 Tongmei InP 扩产（SEC 8-K 实锤） | [SEC 8-K](https://www.sec.gov/Archives/edgar/data/0001051627/000121390026045867/ea028695701ex99-1.htm) · [exoswan](https://exoswan.com/photonics-stocks/) |
| **$IQE**（英国） | 西方少数化合物半导体外延晶圆供应商，给 Sivers 供 InP wafer | ⚠️ **反转信号**：陷入财务困境、战略评估中，正谈判出售台湾业务作为「非稀释」方式偿还 RCF + 可转债。与 skill 正文"2个月涨316%/机构涌入"的成功案例叙事冲突——印证了「诚实边界」里的估值/幸存者偏差风险 | [exoswan](https://exoswan.com/photonics-stocks/) · [chipstockinvestor](https://chipstockinvestor.com/silicon-photonics-stocks-go-wild-long-term-investors-should-be-cautious/) |

## 粉丝/影响力指标（as-of 2026-05-28）

- 粉丝数来源**不一致**：web 一处摘要显示 **127k+**，skill 5/26 调研写 **36万+**。两者差距大，不裁决；刷新时以 X 主页 [@aleabitoreddit](https://x.com/aleabitoreddit) 实际显示为准。

## 待核对 / 存疑

- 宏观「看空大盘」观点是否仍成立（本轮未复核）。
- $AXTI 当前价位（$50+ vs 历史 $104，需确认时点）。
- 粉丝数 127k vs 36万 的真实当前值。
- Substack 付费订阅者最新数（skill 写 27,500+，未本轮复核）。

## 时间线增量（追加在 SKILL.md 历史时间线之后）

| 时间 | 事件 | 来源 |
|------|------|------|
| 2026.04 | $SIVE 单日 +73.78%，市值冲 $231M；提出 AAPL 50M RFQ 假说 | [tweet](https://x.com/aleabitoreddit/status/2048680795586568237) |
| 2026 | AXT 完成 $632.5M 融资扩 Tongmei InP 产能（SEC 8-K） | [SEC](https://www.sec.gov/Archives/edgar/data/0001051627/000121390026045867/ea028695701ex99-1.htm) |
| 2026 | $IQE 转入财务困境/战略评估，谈判出售台湾业务 | [chipstockinvestor](https://chipstockinvestor.com/silicon-photonics-stocks-go-wild-long-term-investors-should-be-cautious/) |
