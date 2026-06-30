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
