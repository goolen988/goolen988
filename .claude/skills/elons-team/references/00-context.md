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

### 8-year endgame (two companies — user's own framing, board-endorsed)
1. **头部 AI-augmented Agency**: effect-driven, solves 自然流量+付费流量+SDR+私域经营
   as one integrated team. **Permanent, not a bootstrap crutch** (see 2026-07-02 log —
   corrects the earlier "工程化掉" framing). Its job: accumulate expert judgment +
   produce the COLD-START DATA the self-serve platform runs on. Markets never stop
   shifting, so someone must permanently scout the frontier (new platforms, new
   creative trends, new models) — that's this company's reason to exist forever, not
   just early on.
2. **SMB self-serve workbench**: SMB inputs its business info → gets ready-to-use
   acquisition creative/flows out of the box. Unsatisfied → pays API + service fee.
   Satisfied → shares data, binds to the platform for continuous optimization, revenue
   share.
   The mechanism connecting them: AI lets the Agency's "brain" flexibly call creative
   tools and deliver GUARANTEED/continuously-improving outcomes (not just delivery).
   As expert knowledge accumulates per vertical, a growing share of SMB demand gets
   served by the tooled self-serve side.

### Why incumbents fail (market diagnosis, board-endorsed)
- **Platforms** (Meta/TikTok/Google): traffic + ad seller. Structurally conflicted —
  won't seriously operate SMBs' business for them; limited incentive overlap.
- **Creative tools** (Adobe, CapCut, Higgsfield generation-tool 三代): deliver the
  DELIVERY PROCESS (lower the tech barrier + acquire more tool users), not the growth
  OUTCOME. They don't integrate tech into a final, directly-convertible asset.
- **Agencies**: human-labor service, low efficiency, too fragmented to capture
  industry-wide synergy.
- **The root failure is a two-language mismatch**: Agency people think in
  operations/business terms, don't understand AI, lack systems thinking (frontline
  first, THEN productize — the correct application of the Zhang Yiming guardrail).
  Tool people think in product/model terms, don't understand merchants — they lower
  the tech barrier and acquire tool users, which is NOT the same as internalizing all
  of a merchant's operating complexity into the system (the C-end/B-end mindset gap,
  restated for the AI era). **The fix is an abstraction-design problem (Collison's
  axis), not a hiring problem**: give Agency operators a thin interface that captures
  their tacit judgment as structured data by construction — don't ask them to become
  engineers.
- **Belief on strategy**: AI-era generalist tools burn too much money too fast (model
  iteration speed + collapsed coding cost = the "Mythical Man-Month" scale advantage
  is gone) — most land-grab-logic generalist players go bankrupt. Corollary: everyone
  must monetize fast → the old-era lesson applies — start from a few high-value
  region×vertical pairs, go deep, take a cut (rev-share), THEN expand. **Core metric:
  ARR + paid retention**, not user count or generation volume.

### Customer priority
1. US domestic SMB (primary)
2. China出海 ecommerce (secondary)

### Capability priority (the funnel the system absorbs)
Day-1 scope is ONLY #1. #2-#5 are the 8-year endgame's 5 acquisition domains,
explicitly NOT sequenced into current scope yet (Elon: naming the endgame is fine;
building 5 domains at once now is scope creep dressed as vision).
1. **Social-platform ORGANIC acquisition / 跨平台账号经营** (自然流量) — the lead
   wedge. Includes: platform positioning, per-platform rules, content strategy +
   production, data recovery/attribution.
2. **投广收割** (paid acquisition): creative strategy, creative production, spend
   optimization via data. [was: "paid-ad acquisition" + "Google acquisition"]
3. **转化链路** (conversion path) — NEWLY ADDED, unsequenced: landing pages, lead
   follow-up, SKU design.
4. **社群经营** (community) — NEWLY ADDED, unsequenced: fan community building,
   membership/benefit design, asset production, relationship deepening.
5. **SDR**: lead discovery, personalized outreach, active contact, AI customer
   service.

### Channels
TikTok + Meta + YouTube + Google. Future SDR mining: Reddit, community forums,
public LinkedIn profiles, social comments/profiles.

### Vertical sequence (refined 2026-07-02, consistent with prior board correction)
**Industry priority**: 电商 > 留资 > 餐饮.
- 电商 order: 美妆护肤 → 服装 → 保健品 → 3C → 家居 → 宠物.
- 留资 order: 情感咨询 → AI/线上营销 → 金融 → 教育 → 汽车 → 房产.
This matches the board's standing correction (start in the ecommerce-creative-organic
cluster, 美妆 first, regulated lead-gen verticals — 金融/教育/汽车/房产 — pushed later
in their cluster). Note: 情感咨询 as the FIRST lead-gen vertical needs one gut-check —
confirm it doesn't carry mental-health-adjacent regulatory exposure before treating it
as "unregulated" like the rest of 电商.

**Region priority**: US > China. Rationale (user, board-endorsed with a caveat):
historical pattern-match that ignoring China risks "being 偷家" (out-executed/cloned
by a faster, cheaper China-based team) — real risk pattern, but the correct response
at 0-closed-loops stage is to make the DATA MOAT compound fast enough to survive a
tool-layer clone, not to enter China now (mental-os anti-pattern: premature breadth).
Sequencing (US primary, China出海 ecommerce secondary) stays unchanged.

**Constraint-funnel method (board-endorsed, output pending)**: pick Day-1 segment by
intersecting (AI-amplifiable) ∩ (requires a strong/expensive model like Seedance
specifically — not just adequate for a cheap model) ∩ (current agencies underserve).
This is the correct first-principles filter for the actual wedge — output not yet
shared with the board as of 2026-07-02.

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

- **2026-06-30(e) — deep research 复核：结构判断成立，撤回两个虚高数字，修正 A 的楔子。**
  - **方法**：deep-research workflow（6 角度、26 源、121 claim、25 条对抗式三票验证），优先 2026 年 4-6 月源。
  - **✅ 扛住（独立数据加强）**：生成层商品化（IAB：gen-AI 参与制作/增强占比 22%→39%，非全 AI 生成；Symphony 免费、Higgsfield $130M/估值>$1.3B、Runway $315M/$5.3B、Adobe×Runway 2025/12）；Arcads 非 agency 工具/对实体产品弱；卡点已移到判断+控制+品牌保真；SMB 比大企业采用快。**最关键独立确认**：Symphony 只自动化创意执行，活下来的 agency 全部重定位到它不碰的两件事——上游"做什么"策略 + 下游效果优化 = **用户最初的数据闭环护城河被第三方坐实**。
  - **❌ 撤回（违反 mental-os 被对抗验证抓出）**："$9.1B/12% AI 视频广告支出"(0-3 毙,vivideo 厂商博客无原始引用)、"78% 团队季度用 AI 视频"(0-3 毙,同源)、"40% 广告是 gen-AI"(口径错,IAB 真实是"39% 参与制作或增强"≠全 AI)、Arcads"$6M ARR/4-6千客户"(getlatka 不可靠,争议;可靠的只有 2025/12 融 $16M seed)。
  - **战略修正（比数字更重要）**：上一轮把"真实产品保真"当 A 头号楔子 → **站不住**。产品保真在分裂：静态握持/展示正被商品化(EzUGC"Product in Hand"卖护肤品保真、Symphony 免费)= table-stakes；可信"使用/演示"仍是 gap 但属模型 roadmap、不可控。**真正防得住的楔子=Symphony/生成器都不碰的两层:上游判断 + 下游效果闭环=用户最初的数据护城河。结论:用户最初 thesis 比上一轮 A-spec 更对,是 AI 漂移了。**
  - **修正后 A 优先级**：① 产品保真=table-stakes 打勾项(买来的模型做到不输 EzUGC 即可),不是头号卖点;② Day-1 楔子=垂类原生 organic 创意品味(用户 TikTok edge,难抄);③ outcome 埋点从"隐形必做"升为**头号差异化**(数据攒起→卖点升级为"我做的视频我知道在你垂类会转"=B 升级闸门+不可抄楔子)。
  - **下一个动作**：自营美妆并行验 ① 产品保真不输 EzUGC（过线）② 垂类 organic 模板第一条出片达可发水准（真楔子）。
  - **谁主张/反对**：Collison（moat 在判断/效果层，Symphony 证伪法独立确认）+ 黄峥（别在被商品化的产品保真 all-in）。
  - **推翻信号**：自营测出你的垂类品味相对 Arcads/Symphony 免费输出无可感知优势 → A 无 day-1 楔子，回 concierge/B 直接打效果。

- **2026-07-02 — 8 年两家公司终局采纳；Agency 定位改判为永久前哨；两家公司接口是最大敞口。**
  - **背景**：用户下载了完整战略框架——8 年终局=两家公司（头部 AI Agency 负责冷启动数据源+永久一线侦察；SMB 自助工作台负责规模化交付，效果不满意付 API+服务费、满意则分成绑定）；市场三方失灵诊断（平台=流量贩子无动力做深；创作工具=交付过程不交付结果；Agency=人力服务效率低无法协同）；根因=两群人语言不通（Agency 懂生意不懂 AI，工具方懂产品不懂商家，这是 C 端/B 端思维差异的 AI 时代重演）；US>中国排序理由="不做中国怕被偷家"；约束漏斗方法论（AI 可放大 ∩ 非强模型不可 ∩ 当前 agency 服务不好的交集）。
  - **缺失信息（决定性但看不到）**：流量来源维度、经营环节维度、约束漏斗实际输出（TOP10 定位）均被飞书文档权限挡住；一份本地 HTML 文件路径不可达。**这些直接决定具体切口，本轮裁决止于方法论层面。**
  - **采纳**：8 年两家公司终局命名——是 context.md 已有"头部服务→提炼配方→腰尾 SaaS"模型的更锋利重述，非新增。两语言不通诊断（Collison：抽象层设计问题，不是招聘问题——解法是给 Agency 一线一个足够薄的接口，让判断"构造性"变成结构化数据，而非事后翻译）。"通用工具会因跑马圈地逻辑破产"的信念——反身性提醒：Runway/Higgsfield 自己正是这类玩家，他们的烧钱大战只会让生成层更便宜，加固而非削弱"买生成层"的判断。
  - **改判**：Agency 定位从 2026-06-30"逐步工程化掉的临时分发"→**永久前哨部门**，因市场永远在变、需要常驻一线的侦察职能持续喂给自助平台冷启动数据。王兴"无限游戏"轴此役胜出，此前判早了。
  - **新敞口（未解决，Bezos 点出）**：两家公司之间的接口契约设计——Agency 每单产出的不能只是"效果好"，必须是结构化的判断过程数据（哪步人介入、做了什么决定、为什么）。此前 concierge 方案里的"批注→数据契约"机制需要正式升级为这个永久接口，而不只是实验记录。
  - **范围裁决**：5 大获客领域（跨平台账号经营/投广收割/转化链路/社群经营/SDR）是 8 年终局范围，**不是 Day-1 范围**。转化链路、社群经营是本轮新增、尚未排入 capability priority 的领域，已计入终局清单但标注"非当前阶段"。Day-1 严格只做 #1（自然流量账号经营）。
  - **垂类顺序细化**：电商(美妆护肤→服装→保健品→3C→家居→宠物) > 留资(情感咨询→AI/线上营销→金融→教育→汽车→房产) > 餐饮，与此前板块纠偏一致；情感咨询作为首个留资垂类需一次监管风险 gut-check。
  - **谁主张/反对**：王兴（Agency 永久化改判胜出）+ Bezos（接口契约是最大敞口）+ Elon（5 领域是终局非 Day-1，范围蔓延警惕）。
  - **下一个动作**：用户补齐三段被挡住的内容（流量来源、经营环节、约束漏斗 TOP10 定位）；将批注→数据契约机制正式升级为 Agency↔自助平台接口契约。
  - **推翻信号**：约束漏斗实际输出如果指向一个强模型（Seedance 类）并不构成真实差异化的人群 → "非强模型不可"这条筛选条件需要重新论证。
