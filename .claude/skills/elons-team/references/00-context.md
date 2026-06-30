# 00 — Venture Context & Locked-in Strategy

> The board MUST ground every opinion in this. Generic startup advice is banned.
> Update the 裁决记录 at the bottom after each real decision.

## Founder

- 28 y/o. Ex-TikTok PM, multiple 0→1 successes.
- **Edge:** growth, organic/social distribution, consumer virality, 0→1, China出海 context.
- **Gaps (flagged repeatedly):** SMB/B2B domain depth; ML/data-engineering capability
  to build the learning loop; tendency to over-expand (too many fronts) and to
  over-analyze the ceiling while under-executing the last mile.
- **Guardrail (Zhang Yiming's one line): 经验是负债 — don't reuse the TikTok consumer
  playbook on SMB B2B.**

## What the company does

An **SMB customer-acquisition engine**. Absorb the full complexity of acquisition
into the system; the SMB only: inputs its product/service info, sets strategy, makes
key decisions, and receives qualified leads. The company keeps the marketing- and
sales-conversion data to continuously optimize. **Deliverable = SMB 获客 (outcomes),
not tools.**

### Customer priority
1. US domestic SMB (primary)
2. China出海 ecommerce (secondary)

### Capability priority (the funnel the system absorbs)
1. **Social-platform ORGANIC acquisition** (自然流量) — the lead wedge
2. Their paid-ad acquisition
3. Google acquisition
4. SDR active lead-mining + outreach + auto AI customer service

### Channels
TikTok + Meta + YouTube + Google. Future SDR mining: Reddit, community forums,
public LinkedIn profiles, social comments/profiles.

### Vertical sequence (NOTE: order is under active debate — see 裁决记录)
Stated: 美妆+金融 → 新车+房产 → 医美+法律 → 教育+旅游 → 餐饮+招聘.
Board's standing correction: **金融/医美/法律 are regulated, lead-gen, structurally
different moats — do NOT pair them early.** Start in the ecommerce-creative-organic
cluster (美妆 → fashion/home/fitness/supplements) where the organic engine shines,
data is clean, and learnings TRANSFER across adjacent verticals.

## The operating model (the user's own, board-refined)

- **Conquer vertical-by-vertical.** Each vertical early is its own unit/dept (even
  company). Horizontal infra is NOT designed up front — but a thin set of shared
  contracts (esp. **data schema + attribution口径**) is mandated from day 1, or the
  later merge becomes an expensive rewrite AND you forfeit cross-vertical learning
  (which is the whole point of being multi-vertical).
- **Within each vertical:** start with 头部 SMB high-touch SERVICE → accumulate
  reputation + extract the success recipe → productize into a SaaS-grade platform for
  the 腰尾部 (one-stop管理, data collection, best-in-class outcomes delivered).
- **Validate per vertical, THEN merge** into a unified platform. Long-term a THIN
  shared middle-platform serves all (best UX + ops ROI). Keep 中台 thin — heavy 中台
  becomes the bottleneck.

## Moat & competitive thesis (board-refined)

- **Three moats:** (1) horizontal infra — weak/copyable; (2) per-vertical outcome-data
  flywheel — strong, slow; (3) operational "absorb-complexity + own-the-data +
  own-the-relationship" — sticky, horizontal. #3 keeps customers; #2 wins them.
- **You don't beat vertical incumbents by "doing it better on day 1"** (you can't —
  no data yet) **or by a cross-subsidized 消耗战** (attrition favors the lower-cost
  focused player; if you need to outspend, you've admitted you have no cost edge).
- **You beat them with a structural cost advantage (AI automation) that PROFITABLY
  serves the long tail their human-labor cost can't** — i.e., the 腰尾 SaaS play — and
  with a **Day-1 entry wedge that is NOT "better results"**: organic-first (incumbents
  are paid-media shops), the underserved tail, or creative volume/speed at a price
  their cost structure can't match.
- **Cross-vertical profit funds ENTERING the next vertical, not subsidizing a losing
  battle in the current one.**

## Threat radar (who to actually watch)

- **Low / not competitors:** Madgicx (~$6.8M ARR, Meta-only paid optimization),
  Smartlead (cold-email, different motion), Persado (enterprise language/copy, no SMB —
  a validation benchmark and possible acquirer, not a rival), Ordo AI/星曜野望 (weak
  2025 newcomer, inflated claims, C-end founder mismatched to B-end).
- **Watch (medium):** Hyper AI / HyperFX (early but well-incubated autonomous
  multi-channel agent with "100+ skills"); other horizontal SMB-growth-OS players;
  vertical-focused players who could spin YOUR first vertical's flywheel first.
- **Platforms (Meta/Google/TikTok/Shopify):** not competitors (their core is the
  platform; they'll cooperate if you drive spend/GMV). But they are your **landlord**
  (API/policy/organic-reach/data risk) and they **commoditize layers from below**
  (TikTok Symphony, Meta Advantage+). So **build the moat on the data + relationship +
  outcome layer they won't give away — never on creative generation, which they will.**

## Where things stand (live)

- 2 weeks self-operating TikTok+IG; ~4 videos/day; **no revenue, no closed loop yet.**
- Real opening: **钛动 (Tec-Do, makers of Navos) US head wants a pilot** (clients:
  Dr. Scholl's, Peter Thomas Roth). 钛动 is the real出海营销 leader (10万+ advertisers,
  自研多模态大模型). Pilot must-gets: per-asset performance data, case-study/naming
  rights, a seat in the optimization loop. **Protect the method/IP (black-box delivery)
  — 钛动/Navos can absorb the capability.**
- Validation wedge available without B2B contracts: TikTok Shop Affiliate (open
  collaboration) for free conversion signal + small self-funded paid test as a clean
  "lab."

---

## 裁决记录 (decision log — append dated entries)

- **2026-06-30 — 第一性原理是删除刀，不是 TCO 账本。**
  - **问题**：用第一性原理评估 SMB 获客引擎；纠结是否要把全链三方（模型算力、Agency 人力、SDR 人力、SMB 生产物理极限）都算进成本；担心第一性原理会否定 venture 或不适用于多三方场景。
  - **裁决**：第一性原理**完全适用且不否定 venture**——它否定的是"全链 TCO 核算"这个框架本身（那正是它要删的 anti-pattern）。Elon 在 Tesla/SpaceX 没有枚举供应商的供应商；他只画"物理地板价 vs 市场价"，攻击信息租金。垂直整合只在三方"既收暴利租金、又卡关键路径"时才做（电池单元 yes，铝/硅 no——他不挖矿）。
  - **三方分类**：模型算力 = 商品，买，从护城河删；Agency/SDR = 高租金中间商，仅作冷启动临时分发，逐步工程化掉；SMB 生产极限 = 客户约束，是资质过滤器不是你的成本。
  - **对标"内存+能源"的两大约束**：① "能源" = 每垂类闭环 outcome 归因数据（生成归零后，稀缺的是"选择"信号）；② "内存" = 自有归因基底 + 交付关系（system of record，不能被三方拿走）；前置使能约束 = **ML/数据联合创始人**（deal-breaker 级花钱对象）。
  - **谁主张/谁反对**：Elon（删+先拿信号/节奏胜出）、Collison（能力约束=ML 合伙人是花钱主战场）、Bezos（Day-1 薄归因 schema 是不能省的单向门）；王兴反对急着把 Agency 当临时品（服务现金流有价值）——零闭环阶段 Elon 胜。
  - **下一个动作**：钛动 pilot 条款里把 per-asset 转化归因数据所有权写成 must-get。
  - **推翻信号**：第一个环显示 last-mile 归因物理上拿不到 → 约束变为"数据访问权"，thesis 重估。

- **2026-06-30(b) — 自营美妆做实验室先闭环；钛动留作第二步真金验证。**
  - **问题**：第一个环走哪条——(A) 自己从零做美妆账号；(B) 接钛动一个愿配合但非美妆（如珠宝）的客户、给他做一套垂类创作工具？如何分精力？
  - **判据（用户自己点出的唯一门控变量）**：哪条路 per-asset 转化归因最干净、最归你、且配方能沉进美妆楔子并可迁移。不按"哪个客户更像真生意"选。
  - **裁决**：**~70% 自营美妆**=机制实验室（零三方依赖、归因不漏、日级迭代、证出"为何火→怎么做→哪步 human-in-the-loop"的配方，证的是引擎成立）。**~30% 钛动**=商业验证（证 SMB 真金 WTP，自营证不了）。**有序非并行**：3 周内自营闭一个完全理解的环 → 闭上后精力翻转给钛动，带"已证配方"去接客户。
  - **当场删**："给珠宝商从零做垂类创作工具"三杀必删——过早产品化（零配方）+ 错垂类（不复利）+ 服务陷阱（debug 别人漏斗）。
  - **接钛动客户的唯一两条门槛**：(1) per-asset 转化归因写进 must-get；(2) 优先美妆/电商创意邻近垂类，珠宝只能当迁移性测试第二点、不能当第一环。
  - **谁主张/谁反对**：Elon（删到一个、先证机制）；王兴反对浪费钛动真金现金流——零闭环阶段先证机制胜出。
  - **推翻信号**：自营 affiliate 信号太弱、撑不起创意选择 → 提前把钛动美妆/邻近客户拉成第一环。

- **2026-06-30(c) — 验证价值层即可；删掉自研 Higgsfield + 两个平台。**
  - **用户 thesis（内核成立、最锋利一版）**：UI 层薄=commodity（≈Higgsfield）；真价值=prompt+数据+策略，且这是少数随垂类变的层；"接数据才服务"是自助平台抄不了的反向定位。**这些全对，保留。**
  - **三刀**：
    1. **删自研 Higgsfield**（自相矛盾——既然生成层是 commodity 就该买）→ 改"买来的模型 + 一层薄编排"，编排只干两件事：注入垂类 prompt/数据/策略 + 捕获 per-asset metadata 并绑转化。只建价值层。
    2. **删"现在建对外+对内两个平台"**——平台是验证的产出不是输入；零闭环阶段对内=你+脚本、对外=多余。"跨垂类不变"是"以后建一次复用"的理由、不是"现在建"的理由；现在建=盲建会重写（壳的需求由第一个跑通的配方吐出）。**唯一 Day-1 不变量=数据契约**（per-asset 字段+归因口径）。
    3. **"接数据才服务"降级**：是终局护城河、不是 Day-1 闸门。冷启动没人为未证明的提升交数据；头 2–3 家用钛动/免费换数据/付费撬入，先把"提升"做成一个数字，闸门才咬得动。
  - **假设磨成可证伪**：同商家同 KPI 做 A/B（你的数据驱动素材 vs 其现素材/通用 Higgsfield 输出）；溢价要说清"贵 X% 因效果好 Y%"。
  - **下一个动作**：选 1 个能给闭环投放数据的商家，"买来的模型+手搓策略"做一组 A/B，目标=一个干净的效果提升数字；同时写出数据契约字段表（唯一现在该写的"平台"）。
  - **谁主张/反对**：Collison（买生成层建价值层）+Elon（删两平台）+黄峥（数据闸门=终局非开局）；王兴反对（早搭对内平台顺运营）——零配方阶段壳必重写，先证配方胜出。
  - **推翻信号**：薄编排做 A/B 时发现不深控生成管线就拿不到关键 per-asset metadata → 那时才值得向下自建一层，而非现在重建整个 Higgsfield。

- **2026-06-30(d) — 事实纠正 + A/B 路线分叉（前端之争的真问题）。**
  - **事实纠正（board 自查）**：上一轮把 Arcads 当 concierge 背书是**错的**。核实：Arcads 2024/1 即 **self-serve PLG 软件**起家，warm-network 验证（首周 $5K MRR），founder 自带隐性知识（前 agency+app studio），$6M ARR / 5–7 人 / bootstrapped；那个"打电话 2 天交付"只是次要 managed add-on，非验证方式非核心模式。[getlatka, admiral, prnewswire]
  - **关键洞察**：Arcads 不反驳"先 concierge"——因为它**故意绕开了高隐性知识**，做模板化通用 UGC（AI 演员口播），且**无数据护城河**（正是 context 警告的 commodity 创意生成层）。它印证 Perkins：手作学习早在他们自己 agency 做完了，再压成模板建 UI。
  - **逼出的真分叉（现在卡用户的真问题）**：
    - **路 A（Arcads 式）**：刻意选品牌创意里可模板化/低隐性知识的一刀 → self-serve UI 先行成立 → 但护城河弱、commodity。
    - **路 B（用户一直描述的）**：高隐性知识+品牌定制+数据闭环 → 非 self-serve-UI-first → concierge-first 适用 → 护城河强但慢重人。
    - 用户"必须建前端"的冲动指向 A；用户整个 thesis（数据闭环=护城河）指向 B。**A 与 B 对 UI 要求相反——这是内部矛盾，必须先选一条。**
  - **下一个动作**：一句话写死赌 A 还是 B。B → 前端延后先 concierge 抽知识；A → 差异化不再是数据闭环，thesis 重写。
  - **谁主张/反对**：Perkins（Arcads 印证先手作再产品化）+ Collison（别学它赢在 commodity 层）。
  - **推翻信号**：若品牌创意里"可模板化那一刀"本身够大 + 能拿到熟人网络 → 路 A 成立、concierge 不必要，但须承认护城河变弱。
