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
- **Why this moat exists at all (the incumbent-data insight):** TikTok/Meituan have
  massive data but structurally underuse it — not by mistake but because (1) the data
  serves the platform's objective (watch-time/GMV/ad-rev), not the customer's growth;
  (2) walled gardens are never channel-neutral; (3) the org can't convert tacit
  knowledge into learnable skills; (4) the data is deep-but-narrow and locked. These
  are structural — they WON'T fix them because fixing conflicts with their P&L. So your
  moat is NOT data volume (you'll always have less). It's **data ALIGNMENT**: build on
  the customer-aligned, channel-neutral, first-party OUTCOME data the platforms are
  structurally forbidden to give — and the skill-learning layer on top. Never build on
  data volume, nor on the layer platforms give away free (creative generation).
- **First data layer to build (board verdict 2026-06-29):** a **first-party, clean-
  labeled "creative→conversion" causal dataset**, in ONE vertical (beauty), harvested
  in a **PAID-traffic lab** (NOT organic). Rationale: organic is the product wedge but
  gives the dirtiest signal (algo lottery); paid isolates creative quality from algo
  luck → clean labels → learnable skills, then transfer to organic at scale. Narrow +
  clean + structurally-protected beats broad + dirty.

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

- **2026-06-29 — 第一层数据/护城河该建哪个**
  - 召唤:黄峥 × Collison(主),Bezos(飞轮),Elon(删减)。
  - 裁决:第一层 = 自有的、干净打标的「创意→转化」因果数据集;垂类=美妆;**采集场=
    付费流量实验室(不是自然流量)**;站位=客户对齐、不依赖平台数据。
  - 删:跨渠道数据平台 / SDR·线索数据 / 多垂类采集——全部推后(广而脏=零价值)。
  - 下一步:定义"转化结果"的标签 schema,挂在 affiliate + 小预算付费测试上,让每条视频
    产出一行你拥有的干净带标签结果。
  - 反对/翻盘:黄峥想更早把站位铺宽到跨渠道;若能在纯自然流量上做到干净归因(目前做不到),
    第一实验室可由付费切回自然流量。
