<!-- chenhz01/chenhz01 · Profile README v2.2 · 2026-10-29 增量（S1–S4 规格承诺兑现审计门禁 + spec-drift 入口 + 第 5 种合作形态） -->
<!-- v2.1 · 2026-10-15 增量版（v2.0 09-28 骨架保留 + 上游信任锚/行为层基准/中国区线注入） -->
<!-- 对标：awesome-github-profile-readme 行业公式（typing-SVG + shields + stats 三件套） -->

<div align="center">

<a href="https://github.com/chenhz01?tab=repositories">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1400&color=7C3AED&center=true&vCenter=true&random=false&width=920&lines=I+audit+self-evolving+AI+—+so+it+can+PROVE+it+didn't+drift.;I+turn+skill+collections+into+production+pipelines.;Pushing+audit-first+quality+standards+for+the+AI+Agent+industry.;Musician.+AI+is+my+creative+partner,+not+my+replacement." alt="Typing SVG" />
</a>

# chenhz01

**AI Agent 治理 × Skill 工程**
**做「把可审计质量推成 AI Agent 行业标准」的第一人。**

[![AI Agent Governance](https://img.shields.io/badge/focus-AI_Agent_Governance-7C3AED?style=flat-square&logo=openai&logoColor=white)](https://github.com/chenhz01)
[![Skill Engineering](https://img.shields.io/badge/field-Skill_Engineering-3B82F6?style=flat-square)](https://github.com/chenhz01)
[![Zero Dependency](https://img.shields.io/badge/tools-zero--dependency-success?style=flat-square)](https://github.com/chenhz01/skill-audit-kit)
[![arXiv-aligned](https://img.shields.io/badge/method-arXiv--aligned-8B5CF6?style=flat-square)](https://github.com/chenhz01/EEL)
[![Open to collaborate](https://img.shields.io/badge/status-open_to_collaborate-22C55E?style=flat-square)](#-正在寻找的合作)
[![Email](https://img.shields.io/badge/contact-shanlun2029@outlook.com-EA4335?style=flat-square&logo=minutemailer&logoColor=white)](mailto:shanlun2029@outlook.com)

</div>

---

> **恐惧失控是猜测；没有审计轨迹是事实。**
> 我不卖安全感。我造的是让自进化 AI「**可证明没跑偏**」的机械门禁——证据不可篡改，标准公开可采用。

## 📌 先从这七个入口开始

*Seven entry points — start anywhere, each one runs offline.*

| # | 角色 | 仓库 | 一句话 |
|---|---|---|---|
| 1 | 总入口 | **[zhengming-toolbox](https://github.com/chenhz01/zhengming-toolbox)** | 55 个零依赖工具的总索引，从任一垂类进入 |
| 2 | 对抗审计 | **[adversarial-research-audit](https://github.com/chenhz01/adversarial-research-audit)** | 抓「不撒谎但会骗人」的研究报告：覆盖算术、簇求和、引用完整性 |
| 3 | 记忆完整性 | **[agent-memory-doctor](https://github.com/chenhz01/agent-memory-doctor)** | 启动自检：约定静默丢失、注入稀释、回滚锚断裂 |
| 4 | 进化账本 | **[EEL](https://github.com/chenhz01/EEL)** | 为自进化 AI 造不可篡改的进化账本（求合作脱敏版） |
| 5 | 可重跑判决 | **[memory-gate-suite](https://github.com/chenhz01/memory-gate-suite)** | MGP-1.0 六道记忆质量门禁，第三方可复跑同一判决 |
| 6 | 领域研究 | **[neuromorphic-event-sensing](https://github.com/chenhz01/neuromorphic-event-sensing)** | 五套技术领域十讲：神经形态 / 老药新用 / 本地优先 / 后量子 / 软体机器人 |
| 7 | Agent 门禁 | **[agent-gates](https://github.com/chenhz01/agent-gates)** | 14 道门：把 Agent 的失败挡在合并之前（零依赖单文件，14 仓索引） |

## 🚦 agent-gates — 14 道门，把 Agent 的失败挡在合并之前

*14 gates · one `gate.py` each · stdlib only · exit `0`/`1` · every example fails on purpose*

Agent 上线之后的问题不是「能不能跑」，是「怎么知道它还在正轨上」。这一组每个仓都是一份零依赖单文件，对着你已有的文件或目录跑一次，给出一个能进 CI 的结论。总入口：**[agent-gates](https://github.com/chenhz01/agent-gates)**（决策树：「你卡在哪 → 装哪道门」+ `fetch.py` 一键取件）。

| 层 | 门 | 它给你的那个数 |
|---|---|---|
| 运行时 | [loop-gate](https://github.com/chenhz01/loop-gate) | 重复次数 + 停滞区间 |
| 运行时 | [permission-gate](https://github.com/chenhz01/permission-gate) | 过度授权分（0-100） |
| 运行时 | [price-gate](https://github.com/chenhz01/price-gate) | 价格表错行 |
| 输入 | [context-gate](https://github.com/chenhz01/context-gate) | 关键单元存活率 |
| 输入 | [instruction-gate](https://github.com/chenhz01/instruction-gate) | 冲突条款对 |
| 产出 | [output-gate](https://github.com/chenhz01/output-gate) | BLOCK / WARN 计数 |
| 产出 | [leak-gate](https://github.com/chenhz01/leak-gate) | 泄露命中 |
| 记忆 | [memory-expiry-gate](https://github.com/chenhz01/memory-expiry-gate) | 每条记忆的去向 |
| 检索 | [drift-gate](https://github.com/chenhz01/drift-gate) | 漂移分 + 最差维度 |
| 运维 | [backup-gate](https://github.com/chenhz01/backup-gate) | 不一致文件数 |
| 运维 | [trail-gate](https://github.com/chenhz01/trail-gate) | 链完整性 |
| 代码 | [complexity-ceiling](https://github.com/chenhz01/complexity-ceiling) | 超预算文件 |
| 代码 | [deadcode-gate](https://github.com/chenhz01/deadcode-gate) | 死代码占比 |
| 文档 | [docrot-gate](https://github.com/chenhz01/docrot-gate) | 失效引用数 |


## 🧰 Toolbox — 55 purpose-built AI-engineering tools

[![Toolbox](https://img.shields.io/badge/toolbox-55_tools-7C3AED?style=flat-square)](https://github.com/chenhz01/zhengming-toolbox)
[![Score-first](https://img.shields.io/badge/design-reverse_score--first-F0C674?style=flat-square)](https://github.com/chenhz01/zhengming-toolbox#methodology-reverse-score-first-design)
[![Zero dependency](https://img.shields.io/badge/deps-stdlib_only-success?style=flat-square)](https://github.com/chenhz01/zhengming-toolbox)

A toolbox of 55 purpose-built tools across neglected AI-engineering niches — prompt-engineering harnesses, agent governance, code-quality gates, security specs. Every tool: pure stdlib, CLI-first, 40+ self-test cases, CI-verified. Entry point: **[zhengming-toolbox](https://github.com/chenhz01/zhengming-toolbox)**.


## 📏 我正在推动的行业质量标准（公开 · 可采用）

别的个人主页列项目，这里列**标准**。以下门禁全部开源、零依赖、可直接接入你的 Agent 工程：

| # | 标准门禁 | 一句话 | 采用入口 |
|---|---|---|---|
| G1–G6 | **进化硬性拒绝护栏** | 自进化 AI 的六道审计关卡，跑偏即拒绝 | [EEL](https://github.com/chenhz01/EEL) |
| P1–P5 | **发布突破五流程** | 从设计到真实验证 100% 覆盖的发表纪律 | [ai-agent-skill-breakthrough](https://github.com/chenhz01/ai-agent-skill-breakthrough) |
| D1–D5 | **研究对抗审计** | 覆盖率算术、分簇加总、引用完整性——抓"没在撒谎却在撒谎" | [adversarial-research-audit](https://github.com/chenhz01/adversarial-research-audit) |
| M-Boot | **记忆开机体检** | 抓约定静默丢失与注入稀释 | [agent-memory-doctor](https://github.com/chenhz01/agent-memory-doctor) |
| S1–S4 | **规格承诺兑现审计** | 你写下的每条需求，代码里真兑现了吗——查未决澄清、状态虚报、需求失锚、跨 spec 静默取代 | [spec-drift](https://github.com/chenhz01/spec-drift) |

🎯 **把你的 Agent 项目接入以上任一门禁，开 Issue 标注 `adoption`**——你就是我推动行业质量的一部分。

## 🛡️ 治理与审计 — 旗舰项目

| 项目 | 一句话 |
|---|---|
| ⭐ [**EEL**](https://github.com/chenhz01/EEL) | 进化证据账本：为自进化 AI 造不可篡改的进化账本（6 篇 arXiv 论文 → G1–G6 硬性拒绝护栏）· `求合作` |
| [**agency**](https://github.com/chenhz01/agency) | AI 智能体的纪律操作系统：对抗审计、发布门禁、37 身份对攻锻造、防篡改演化账本 |
| [**adversarial-research-audit**](https://github.com/chenhz01/adversarial-research-audit) | 机械门禁审计研究报告：覆盖率算术、分簇加总、引用完整性 · 零依赖 |
| [**agent-memory-doctor**](https://github.com/chenhz01/agent-memory-doctor) | AI 记忆与约定文件的开机体检：抓沉默的约定丢失与注入稀释 · 零依赖 |

## 🧩 Skill 工程 — 让 skill 库从"收藏夹"变成"生产力"

| 项目 | 一句话 |
|---|---|
| [**skill-audit-kit**](https://github.com/chenhz01/skill-audit-kit) | skill 库健康检查：引用图谱、孤儿检测、冲突、语义近重复 · 零依赖 CLI · JSON+HTML 报告 |
| [**answer-contract**](https://github.com/chenhz01/answer-contract) | 四条规则止住 AI 注水：隐性需求补齐 / 结构化输出 / 三方案对比 / 假设熔断 · 单文件 |
| [**zhengming-openai-plugins**](https://github.com/chenhz01/zhengming-openai-plugins) | SKILL.md → OpenAI Codex 插件包转换器 · 纯标准库 · 强制官方 manifest 约束 |
| [**ai-agent-skill-breakthrough**](https://github.com/chenhz01/ai-agent-skill-breakthrough) | 学→超→破→用：把开源 agent skill 集合真正用起来的方法论 |

## 📐 方法论与工程实践

[ai-native-process-engine](https://github.com/chenhz01/ai-native-process-engine)（AI 原生流程引擎 · 七层架构 + L0-L3 自治分级）· [fork-to-mainrepo-playbook](https://github.com/chenhz01/fork-to-mainrepo-playbook)（衍生项目独立化方案）· [trending-scout](https://github.com/chenhz01/trending-scout)（Trending 对抗性审核）· [PartnerGene](https://github.com/chenhz01/PartnerGene)（基因中心型 AI 商务建联）

## 📚 同一套纪律，用在五个领域（研究笔记）

上面讲的是「怎么证明 AI 没跑偏」。这套纪律我也用在自己的技术判断上：**每条判断必须带边界数、来源等级、以及「什么证据能推翻它」**。五套写下来发现，判断方法其实是同一套，只是换了领域。

| 领域 | 十讲覆盖 | 入口 |
|---|---|---|
| 神经形态计算与事件驱动传感 | SNN 脉冲编码、事件相机 DVS、Loihi/Akida/SpiNNaker2 版图、能效优势的成立条件 | [notes](https://github.com/chenhz01/neuromorphic-event-sensing) |
| AI 老药新用与计算重定位 | 证据链四层、转录组指纹、扩散模型 DTI、1150 万人 EHR、10-30% 证伪边界 | [notes](https://github.com/chenhz01/ai-drug-repurposing) |
| 本地优先软件与 CRDT 同步 | 收敛数学、同步架构三型、TLA+ 验证、经济学反方视角、95% 定律 | [notes](https://github.com/chenhz01/local-first-crdt) |
| 后量子密码迁移 | HNDL 威胁模型、FIPS 203/204/205、混合密钥交换、CBOM 盘点、密码敏捷性 | [notes](https://github.com/chenhz01/post-quantum-migration) |
| 软体与折纸机器人 | 柔顺性第一性原理、折纸拓扑、气动驱动、控制难题、市场版图 | [notes](https://github.com/chenhz01/soft-origami-robotics) |

三条代表性判断，每句都能点进去验证：

> 「省 100 倍」不是芯片属性——三个条件各打九折还剩约七成，缺任何一条就塌回接近 1。（[能效真相](https://github.com/chenhz01/neuromorphic-event-sensing/blob/main/notes/06-efficiency-truth.md)）

> 95.3% 是回顾恢复率，10-30% 才是前瞻重复率，两者之间隔着一整个行业。（[证伪边界](https://github.com/chenhz01/ai-drug-repurposing/blob/main/notes/09-falsification-10-30-percent.md)）

> 95% 的冲突不需要 CRDT，谁最后改的听谁的，再加一本不可变流水账就够了。（[95% 定律](https://github.com/chenhz01/local-first-crdt/blob/main/notes/08-95-percent-law-lww.md)）

每篇过两道费曼关：**大众层**（12 岁能懂，回答「与我何干」，只能填 省钱/赚钱/避险/暂无）+ **专业层**（机制 / 边界数 / 反例 / 怎么复现，数字裸标 [一手] [二手] [推算]）。缺大众层是自嗨，缺专业层是空话。协议见 [FEYNMAN.md](https://github.com/chenhz01/local-first-crdt/blob/main/FEYNMAN.md)。

## 🧪 行为层 conformance — 已被上游验证的轨迹

[**agent-memory-benchmark**](https://github.com/chenhz01/agent-memory-benchmark)：行为层记忆质量基准——11 条机械可断言条款、零依赖 L1–L5 conformance checker、NMR 遗忘质量排行榜、AMTF 可移植 schema。

**一个 90 秒的发现**：对 mem0（v2.2.1）用 `deepseek-chat`（temperature=0）做行为探针——先说最爱 GPT-4o，再说已换成 DeepSeek-V3。记忆层正确存了带时间戳的更新，但查询"我最爱什么 LLM"返回**自相矛盾的两条**：被取代的旧记忆从未死去。该 FAIL 在 temperature=0 下确定性复现 N=2，证据逐字节一致。→ [完整报告 · 复现脚本 · 原始输出](https://gist.github.com/chenhz01/66c2474660298489a32716459a0b867f)

**上游信任锚**（每条可点击验证）：

- ✅ **[TeleAI-UAGI/Awesome-Agent-Memory #124](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory/pull/124)** — 维护者亲手合入 main，**co-author 署名**（[502656a](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory/commit/502656a)）
- 🔍 **[IAAR-Shanghai/Awesome-AI-Memory #177](https://github.com/IAAR-Shanghai/Awesome-AI-Memory/pull/177)** — 受邀贡献，review 中
- 📌 实证回信：[mem0ai/mem0 #7283](https://github.com/mem0ai/mem0/issues/7283)（write-gate）· [langchain-ai/langgraph #9006](https://github.com/langchain-ai/langgraph/issues/9006) · MangoDisk #66（file:line 双版本根因）

---

## 🤝 正在寻找的合作

- **谁**：做 agent 平台 / skill 生态 / AI 治理的团队与独立开发者
- **五种合作形态**：
  1. **集成**——审计引擎接入你的平台（EEL / adversarial-research-audit）
  2. **诊断**——skill 库健康体检 + 修复路线（skill-audit-kit）
  3. **定制**——SKILL.md→Codex 转换与 L3 配方层深度交付
  4. **中国区落地**——你在广州的 on-the-ground partner：本地开发者社区、中文模型栈 conformance 跑批（DeepSeek / Qwen / GLM / Kimi）、中国市场准入的步步落地——步子随你的节奏，今天无需任何承诺
  5. **规格承诺兑现审计**——你的 `specs/` 里那些写着却没人做的需求：我用 [spec-drift](https://github.com/chenhz01/spec-drift) 免费跑一遍（未决澄清 / 状态虚报 / 需求失锚 / 跨 spec 静默取代），**换一个可公开的案例**；不方便公开就匿名，你说了算。顺带说一句我在 57 个用 spec-kit 的公开项目上扫到的事实：**44% 的 spec 永远停在 Draft**，所以「这份 spec 还准不准」根本无从判断——因为它从来没被标成准过
- **怎么找**：邮件 [shanlun2029@outlook.com](mailto:shanlun2029@outlook.com)，或直接在对应仓库开 Issue（`adoption` / `collab`）



---

<div align="center">

*「进化是证据，证据不可篡改。」*

**如果你也在做 Agent 治理或 skill 生态——我们大概率该认识。**
[⭐ Star 一个项目](https://github.com/chenhz01?tab=repositories) · [📮 发封邮件](mailto:shanlun2029@outlook.com)

</div>

<details>
<summary><b>🌐 English</b></summary>

**AI Agent Governance × Skill Engineering.** The first person pushing *auditable quality* as the industry standard for AI Agents.

- I build mechanical gates that let self-evolving AI **prove** it didn't drift — G1–G6 evolution guardrails, adversarial research audits, boot-time memory integrity checks.
- I turn agent skill collections into production pipelines: health checks, contract rules, SKILL.md→Codex converters. All zero-dependency, all open source.
- **Behavior-layer conformance for agent memory** ([agent-memory-benchmark](https://github.com/chenhz01/agent-memory-benchmark)): 11 machine-assertable clauses, deterministic probes, raw outputs published. Sample finding: mem0 v2.2.1 keeps self-contradictory superseded facts alive at temperature 0 (deterministic, N=2) — [full report & repro](https://gist.github.com/chenhz01/66c2474660298489a32716459a0b867f).
- **Merged upstream:** my PR to [TeleAI-UAGI/Awesome-Agent-Memory](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory/pull/124) was merged to main by the maintainer with co-author credit.
- **Does your spec still describe your code?** [spec-drift](https://github.com/chenhz01/spec-drift) checks the four ways a spec-kit spec silently goes stale (unresolved clarifications, status that lies, requirements that lost their test anchor, cross-spec supersession). Zero deps, no LLM, CI-able. Building it, every naive version was wrong — the three filters that fixed it are in the README. I scanned 57 public spec-kit projects: **44% of specs never leave `Draft`**, which is why "is this spec still accurate?" is unanswerable — no spec was ever marked accurate. → **I'll run the audit on your `specs/` for free in exchange for a citable case** (anonymised if you prefer).
- **Adopt any gate in your project** — open an Issue tagged `adoption` and become part of the standard.
- **The same discipline, applied to my own technical judgments** — five sets of ten research notes (neuromorphic computing, AI drug repurposing, local-first CRDT, post-quantum migration, soft robotics). Every claim carries a boundary number, a source grade, and an explicit condition under which it is false: [notes index](https://github.com/chenhz01/neuromorphic-event-sensing).
- **Eyeing the China market?** I'm your on-the-ground partner in Guangzhou: local developer community, Chinese model-stack conformance (DeepSeek / Qwen / GLM / Kimi), and a China presence built step by step, at your pace.

Looking for: agent platform / skill ecosystem / AI governance teams. → shanlun2029@outlook.com

</details>
