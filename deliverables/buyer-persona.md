# Buyer Persona: Who Buys a Company Brain

*Grounded in 73 vendors, 37 fully-profiled anchor customers, 64 enterprise context logos. Every claim below is traceable to a named company in the dossier.*

---

## 1. The pattern in one paragraph

The company brain is bought today by **small, technically-led, AI-native companies whose product is itself an agent** — not by enterprises with knowledge-management problems. Of the 37 anchor customers, 19 have 15 or fewer employees and 34 of 37 either ship an LLM agent as their core product or have retrofitted an agent layer onto an existing one. The buyer is almost always the founder or the senior-most engineer: of the 17 anchors with a named human attached to the citation, every single one is a founder, co-founder, CTO, engineering manager, product manager, or documentation lead — Adi Singh (Founder, AgentMail), Arjun Athreya (CTO, Hobbes), Jon Milles (Co-founder & CTO, Zaplar), Frank Li (Co-founder & CTO, Amorphic Labs), Casey Smith (Director of Documentation, Payabli), Clinton Blackburn (Engineering Manager, Vori), Dan Hanson (Product Manager, Middesk). There is not one CIO, head of ops, chief of staff, or procurement contact anywhere in the anchor set. They buy for one of two structurally different reasons, and the distinction matters more than anything else in this document: either **their own product's agent forgets its users** (OpenNote, Praktika, Flow, Scira, Hobbes, SlideSpeak, Luccid — memory as a shipped feature) or **their own team has outgrown its documentation** (Payabli, Vori, Thatch, Middesk, AgentMail, Composio — memory as internal infrastructure). Both populations are compressed into a 5–200 headcount band, disproportionately Y Combinator W24–S26, and roughly half were founded or funded within the last 24 months.

---

## 2. Firmographics

**Headcount (n=37, from the dossier's own figures):**

| Band | Count | Examples |
|---|---|---|
| 1–15 | 19 | Scira (1), Amorphic Labs (2), Superagent (2), OpenNote (3), Litmus (4), GodmodeHQ (5–6), Zaplar (8–9), Hobbes (9), SlideSpeak (9), AgentMail (10–11), Fleetline (11), Mission Inbox (13), Wordware (14) |
| 16–50 | 9 | Seapoint (20–30), Mastra (30–35), AllVoices (~33), Raycast (40), Cluely (20–70), AGI Inc (15–50), Composio, Eragon, Nous Research (all 11–50 bands) |
| 50–350 | 6 | Vori (50–100), Payabli (125+), Middesk (130–156), Upbound (51–200), Thatch (200+), Corgi (250–350) |
| Unknown | 3 | Praktika, Adapta, Chroma |

**Median anchor is under 15 people.** The largest is Corgi at ~250–350. Nothing in the anchor set is over 350; nothing is public.

**Funding stage (n=37):**
- **16 pre-seed / undisclosed / bootstrapped** — Zaplar, Amorphic, SlideSpeak, Luccid, Scira, Flow, Trag, Litmus, Superagent, Adapta, Vela, Fleetline, Agentplace, UnCircuit, Mission Inbox, OpenNote ($850K pre-YC)
- **8 seed** — AgentMail ($6M, General Catalyst), Hobbes ($6M, Foundation Capital), Wordware ($30M, Spark), Chroma ($18M), Eragon ($12M), Seapoint (€10M), GodmodeHQ ($2.6M), AllVoices ($3M)
- **5 Series A** — Composio ($29M), Mastra ($35M total), Praktika (~$38M), Cluely ($20.3M), AGI Inc
- **8 Series B+** — Corgi (~$268M), Thatch ($84.5M), Upbound ($69M), Payabli ($60M), Middesk ($57M), Vori ($50M), Raycast (~$45M+), Nous Research (~$70M)

The barbell is real: **43% have no disclosed round at all**, and the ones that do skew either freshly-seeded or Series B. Series A is the thinnest band.

**Accelerator:** 14 of 37 are Y Combinator companies, and **12 of those 14 are from W24 or later** (Superagent W24, Wordware S24, Corgi S24, Mastra W25, AgentMail S25, OpenNote S25, Fleetline S25, Vela W26, Zaplar S26, Amorphic S26, Litmus S26, UnCircuit S26). Only Middesk (W19) and Vori (W20) are older YC. Two more come from non-YC programs: Trag (Berkeley SkyDeck Europe B5) and Luccid (Xpreneurs/UnternehmerTUM, AI Campus Founders).

**Age:** the modal anchor is 0–24 months old. The mature tail founded 2018–2020 — Upbound (Series A May 2018), Middesk (W19), Vori (2019), Payabli (2020), AllVoices (seed Feb 2020), Raycast (seed Oct 2020) — is exactly the group that buys internal-docs brains rather than product memory.

**Geography — weak evidence, stated honestly.** Only a handful of anchors have a confirmed location: Payabli (Miami FL), Vori (San Francisco CA), Seapoint (UK/Ireland, "20 people building across Europe"), Luccid (Berlin/Munich), Trag (SkyDeck Europe), GodmodeHQ (Istanbul-linked via Troy Labs and Webrazzi coverage). Mastra and Upbound are explicitly fully remote; Payabli is fully remote. The YC concentration implies Bay Area presence for 14 of 37, but **the dossier does not support a quantitative geographic split** — see §10.

**Churn is measurable and high.** Three of 37 anchors (8%) are already dead or absorbed: OpenNote acquired May 2026 (into Reducto), Trag acquired by Aikido Security Aug 2025, GodmodeHQ wound down 30 April 2025 with capital returned.

---

## 3. Product archetypes

### A. Agent infrastructure and developer tools — 10 anchors
**AgentMail, Composio, Amorphic Labs, Mastra, Superagent, Chroma, Agentplace, Upbound, Nous Research, Trag.**

They sell the substrate other agents run on: inboxes agents own (AgentMail), the tool-calling and auth layer (Composio), a capability marketplace agents pay into at runtime (Amorphic's AgentMuxer), a TypeScript agent framework and runtime (Mastra), agent security scanning (Superagent), control planes where "Humans govern. Agents consume. Machines execute." (Upbound), an open agent harness (Nous Research's Hermes).

**Why memory matters:** two-person and ten-person teams shipping almost entirely via coding agents, with no headcount to absorb tribal knowledge. Amorphic is *two founders* building thousands of provider integrations. Superagent is two people. The buying moment is context recovery, and Composio's testimonial captures it exactly. This archetype is also the **highest false-positive risk** — Mastra ships working memory as a first-party primitive and Mem0 publishes a `/compare/mem0-vs-mastra` page; Chroma is the vector substrate memory products are *built on*, not a buyer.

### B. Consumer / prosumer AI apps — 9 anchors
**OpenNote, Scira AI, Flow, Praktika, Cluely, AGI Inc, Wordware, Raycast, SlideSpeak.**

Tutors, answer engines, note apps, meeting overlays, on-device assistants. Memory is not infrastructure here — **it is the product's core value proposition and its retention mechanism.** OpenNote's tutor restarted cold every session. Praktika's site claims tutors "maintain conversation context and learning history." AGI-0 "lives on the device. It learns your preferences and gets better over time." Flow's founder said memory "was the only important part for the product to go public." This archetype pays for memory as a feature and will switch vendors over quality — Scira migrated off Mem0 to Supermemory. Caveat: Raycast and Wordware already ship their own (Raycast Pro's Memory/Profile; Wordware's "AI assistant built for compounding context").

### C. Vertical agentic SaaS — 8 anchors
**Zaplar (hotels), Vori (grocery), Fleetline (trucking), Luccid (AEC/construction), AllVoices (HR/employee relations), Litmus (technical hiring), UnCircuit (candidate assessment), Vela (scheduling for exec search).**

Agents running a physical or regulated business process. Two memory needs: internal (Vori's engineering knowledge scattered across Notion, Slack, Linear, GitHub, Google Docs) and **per-tenant customer memory** (Luccid's building-code knowledge base "kept updated as regulations changed"; Vela's scheduling negotiation spanning days, email, SMS and WhatsApp for one meeting).

### D. AI-native fintech, insurtech and regulated infrastructure — 5 anchors
**Corgi (~250–350, Series B, full-stack AI carrier), Payabli (125+, embedded payments), Thatch (200+, ICHRA benefits + card), Middesk (~135, KYB), Seapoint (~25, startup finance ops).**

The largest, best-funded, most conventional buyers in the anchor set, and **the only ones with real organizational scale.** They are also where the *internal* company-brain job produces the strongest, most commercial evidence — four of the six Falconer citations sit here. Middesk runs "Agent in the Loop" research agents for OFAC false-positive resolution and beneficial-ownership tracing; Payabli shipped its Amigo agent suite in July 2026.

### E. AI SDR / GTM agents — 3 anchors
**Hobbes, GodmodeHQ (defunct), Mission Inbox.**

Small in the anchor set but the canonical category — 11x, the archetypal AI SDR, appears in the *context* set on Letta's wall. GodmodeHQ's agents only worked if they carried persistent ICP definitions, value props, brand rules and exclusion lists; the company shut down anyway. Hobbes needs its agent grounded in each customer's docs, help center and recorded calls, per tenant, kept current.

### F. Horizontal AI workspaces (buyers who are near-competitors) — 2 anchors
**Adapta, Eragon.**

Adapta was building its own memory systems in-house and stopped. Eragon sells a "company brain / AI OS" itself and its citation with Hyperspell is reciprocal. These two are the smallest cluster and the most strategically informative — see §6, trigger 3.

---

## 4. How they use agents — the jobs that create the memory need, in their own words

**Job 1 — One shared source of truth for humans and agents at once.**
> "The Hyperspell company brain has been incredibly helpful for our customer support. Having one shared source of truth across our whole team and agents has let us automate most of our internal operations." — Adi Singh, Founder, AgentMail

**Job 2 — Give the product's agent per-user continuity.**
> "Mem0 turned our AI tutors into true learning companions - tracking each student's struggles, strengths, and learning style across the entire platform and tools." — Abhi Arya, Co-Founder, OpenNote

> "SlideSpeak customers create slides from scratch over and over again. With cognee, we added memory, so users can create better slides from shared context and improve those slides over time." — Kevin Goedecke, Founder & CEO, SlideSpeak

SlideSpeak's own marketing states the thesis better than any analyst: *"AI agents are brilliant designers with amnesia."*

**Job 3 — Recover context on onboarding, without interrupting a human.**
> "Yesterday I got Posthog access and was trying to understand some stuff, glen surfaced Sarah's context and was very very very helpful, would recommend" — KJ, MTS, Composio

**Job 4 — Stop engineering docs from drifting away from the code.**
> "Falconer prevents our documentation from drifting out of sync with our codebase as engineers ship new products and features. The result is like giving every team member a senior en[gineer]..." — Dan Hanson, Product Manager, Middesk

> "From day one, Falconer has felt like a superpower. It transformed our scattered documentation into a unified, living brain. As we rapidly scale our engineering team at Thatch, it gives me confidence th[at]..." — Adam Stevenson, Co-founder & President, Thatch

**Job 5 — Rip out the wiki nobody used.**
Case study title: *"How Payabli replaced Confluence with Falconer in two days."*
> "I see engineers sharing Falconer links all day now. We never saw that with other tools. There's the proof." — Casey Smith, Director of Documentation, Payabli

Vori's stated complaint about Notion search: *"not great... organization was also just generally terrible."*

**Job 6 — Avoid a build the team cannot staff.**
> "Reliable data ingestion, search, monitoring, and tuning-for a small team, putting it together would have taken months. Hyperspell had a complete solution out of the box and saved us the heavy lift." — Arjun Athreya, CTO, Hobbes

> "We tested them out, and Supermemory had the best results. Even if you're building your own memory system, you should build it on top of Supermemory." — Max Peters, Founder, Adapta

**Job 7 — Keep a domain corpus current as the world changes.**
> "The team helped me build a custom knowledge base of building codes and regulations that I could upload, query, and keep updated as regulations changed." — Marko Lazic, CEO, Luccid

**Job 8 — Memory as the reason people pay.**
> "I'm considering changing the model to pay-first just because of how good the memory is." — Daniel, Founder, Flow

> "A thousand times better than Mem0." / "Every time it was indexing something, it wouldn't add it to the memories" — Zaid Mukaddam, Founder, Scira AI

**Job 9 — Delegate whole workflows to a mixed human/agent team.**
> "50% of my workday gets done like magic with Trace – tasks, teams, and models all perfectly in sync." — Hovhannes Ghevondyan, Co-Founder, Trag

> "2x the productivity across our entire department, which adds up to a full month of work saved." — Mert Deveci, Founder, GodmodeHQ

> "I typed the compliance overlooking process...and it kicked out a full workflow, split up for AI agents and humans, and I could tweak everything in seconds." — Mariam Grigoryan, Agentplace

**Job 10 — Developer experience, plainly.**
> "The absolute best dev ex tool I've used since the invention of the text editor." — Jon, Co-Founder & CTO, Zaplar
> "It just works and works well. Love using it" — Frank, Co-Founder & CTO, Amorphic Labs

---

## 5. The two-tier market

**Tier 1 — what startup vendors actually sell.** Hyperspell, Glen, Falconer, Supermemory, Trace, Cognee, Honcho, Poth Labs, Graphify, Coworker and Agently show a combined 37 customers: median under 15 people, mostly YC W24–S26, technically-led, and buying in days rather than quarters (Payabli replaced Confluence "in two days"). The signer is a founder or an engineer.

**Tier 2 — what mature vendors show on a logo wall.** Mem0 displays Microsoft, NVIDIA, Adobe, Lenovo, Schlumberger, AWS and Vercel. Cognee displays Microsoft, Adobe, Apple, Baidu, Shopify, AWS — plus the University of Wyoming. Honcho displays Microsoft, NVIDIA, Atlassian, Coinbase, Rippling, Polymarket, Phantom, the University of Michigan and the University of Toronto. Zep displays Twin Health, Axtria, HoneyBook, Thrive AI Health. Letta displays 11x, Kognitos, Bilt and Hunt Club. Interloom displays Zurich Insurance; Colrows displays Pfizer and SSP Group plc; MIRIX displays Intuit; Naboo displays Lemonade and Melio; Granola displays Figma, Ramp, Brex, Vanta, Zapier, Spotify and Y Combinator itself.

**What the split actually says.** The tier-2 logos are mostly *not buyers of the same product*. The dossier flags this repeatedly: AWS is "a competitor in the agent-memory category"; NVIDIA and Qualcomm are "platform/silicon partnership[s]"; Microsoft, Adobe and Apple are "NOT an agent-memory ICP"; Y Combinator is "the investor, not a customer." Two universities and one grant-funded special-education research group are not a commercial segment. Tier 2 is a **credibility surface built from integrations, partnerships and design-partner pilots** — and it is only reachable with things an early-stage entrant does not have: on-prem/VPC (Naboo, Graphify), RBAC and permission-scoping (Hyperspell, In Parallel), audit trails (Coworker), bi-temporal fact validity (Sentra, Zep), and a security review process.

**Implication for an early-stage entrant:** play tier 1 exclusively. It is where named humans put quotes on the record, where a two-day rip-and-replace is possible, where the buyer is one person, and where 42 of the 73 competing vendors have failed to land a single advertised customer. Tier 2 is a 12–18 month enterprise sales build that Zep, Mem0, Cognee and Interloom are already funding. The only bridge between them is the growth-stage fintech band — Payabli, Thatch, Middesk, Vori, Corgi — companies with 125–350 people that still buy like startups because an engineering leader signs.

---

## 6. Trigger events — the state a company is in when it buys

1. **Headcount roughly doubled inside 18 months, and docs did not keep up.** Thatch went from ~72 to 200+ team members in about 18 months with 29 roles still open, and Stevenson's quote names the exact fear ("as we rapidly scale our engineering team"). Payabli tripled since 2023 to 125+ with ~50 engineers and a documentation function of essentially one person.
2. **The sanctioned wiki is dead.** Payabli's Confluence was mandated and unused; knowledge lived in Google Docs and Slack. Vori's engineering knowledge was split across six tools — Notion, Slack, Linear, GitHub, Google Docs — with Notion search the specific complaint.
3. **They already built memory and want out.** The highest-conviction trigger in the dossier. Adapta was maintaining its own memory systems and found it pulled focus from the core product. Flow built on Mem0 first and it broke under high-volume multi-document context. Scira switched vendors outright. A team that has *tried* is pre-qualified; a team that hasn't will still argue "we'll just build it."
4. **A fresh round plus an open-roles page.** Vori's $22M Series B (May 2026), Eragon's $12M seed with 4 open MTS roles, Nous Research with ~10 open roles, AgentMail's $6M seed (March 2026).
5. **Support surface exceeds headcount.** AgentMail: ~10 people fielding developer support across docs, Discord, email and a large SEO blog, against constantly-shipping product docs.
6. **A new person cannot self-serve context.** The Composio moment: new tool access, no idea what happened before, a colleague's prior work sitting undiscoverable.
7. **The product's agent hits its memory ceiling at the paywall.** Flow: memory "was the only important part for the product to go public." OpenNote: session fragmentation was "fatal for a tutoring product." This is a launch/monetization blocker, not an efficiency purchase — it closes fastest.
8. **Coding-agent sprawl.** Amorphic's two founders build "almost entirely via coding agents." Glen ingests Claude Code, Codex and Cursor sessions; Mosaic syncs 14 coding agents into one shared drive. Two or more coding agents in a team is a mechanical qualifying signal.
9. **A multi-tenant grounding requirement appears.** Hobbes must ground its sales agent in each customer's docs, help center and recorded calls, per tenant, kept current. That is a build the customer cannot postpone and cannot easily staff.

---

## 7. Anti-persona — who is conspicuously absent

- **Anyone over ~350 people.** The anchor set's ceiling is Corgi at ~250–350. Every Fortune-500-scale name in the dossier — Pfizer, Zurich, Microsoft, Adobe, Apple, Baidu, Lenovo, Schlumberger, Electronic Arts, Intuit, Spotify, Qualcomm, NVIDIA — appears **only** in the context set, on mature vendors' logo walls, and several are explicitly flagged as partnerships or competitors rather than customers.
- **The non-tech operators the vertical AI companies sell to.** This is the sharpest absence in the dossier. Zaplar sells to independent hoteliers; Vori to independent grocers; Fleetline to trucking fleets; Luccid to building-material manufacturers; Corgi to SMBs. **Not one hotel, grocer, fleet, or manufacturer appears as a buyer.** The company brain reaches the physical economy only wrapped inside a vertical AI vendor. Selling directly to that layer is selling to someone with no AI stack and no buyer.
- **Non-technical buyer titles.** Zero CIOs, zero heads of ops, zero chiefs of staff, zero HR or L&D buyers, zero procurement contacts across 17 named individuals. The closest thing to a non-engineering buyer is Casey Smith, Director of Documentation at Payabli — and she reports into an engineering org of ~50.
- **Services firms and agencies.** One exception exists and it is in the context tier: Hunt Club (executive search) on Letta's wall. No consultancies, no agencies, no law firms.
- **Institutions.** Universities appear three times (Michigan, Toronto, Wyoming) — all context tier, all on infra vendors' walls, all almost certainly research usage rather than commercial deployment.
- **Regulated incumbents.** Lemonade, Zurich, Pfizer, SSP Group: context only. The anchor-set analogues are AI-native *challengers* to those incumbents (Corgi, Seapoint, Middesk), not the incumbents themselves.
- **Companies with no agent.** UnCircuit is the single anchor whose site contains zero occurrences of "AI," "agent," "model" or "LLM" — and its evidence is logo-wall-only. It is the shape of a false positive.

---

## 8. Vendor positioning map — 73 vendors and where the wedge is

The 73 rows split roughly **31 "company brain" / 34 "agent memory infra"** (the list contains at least six duplicate entities — Zep/Zep AI, Letta ×2, Hindsight ×2, Memori ×3, Basic Memory ×2 — so distinct vendors are closer to 63–65).

**Axis 1 — scope.** *Personal* (Atlaso, "one memory for every AI you use"; Memobase user profiles; Basic Memory; Evermind user-owned portable memory; Mem0, explicitly "scoped per-user/per-agent") versus *organizational* (Memory Store, "one shared memory for your teammates, and agents"; RoryPlans; Compendium; Wato; Sentra; Mosaic). Personal is crowded and commoditizing. Org scope is the actual category and has far fewer credible entrants.

**Axis 2 — form.** *SDK / API primitive* (Mem0, Zep, Letta, Supermemory, Cognee, Honcho, Graphlit, LangMem, LlamaIndex, xmemory, Maximem, memU) versus *packaged product a team logs into* (Hyperspell, Glen, Almanac, Slite, Falconer, Coworker, Pensieve, Gyld, Trace, Webair). **Every anchor citation with a company-size profile block and a rip-out narrative came from the packaged side** (Falconer). Every "a thousand times better than X" switching story came from the SDK side (Supermemory).

**Axis 3 — what gets ingested.** Chat logs (Mem0, Memobase) → *execution traces* (Memori: "persistent memory from agent trace, not just conversation"; Hindsight: "what an agent did, what went wrong, what humans corrected"; Blume clusters repeated corrections into rules) → *coding-agent sessions* (Glen, Mosaic, ByteRover, Blume, Graphify — five vendors, filling fast) → *business SaaS connectors* (Hyperspell, Gyld, Agently, Almanac, Pensieve, Lore, Jedify, Trace — near-identical Slack/Notion/Drive/GitHub lists, the most undifferentiated lane in the market) → *ambient capture* (screenpipe, MIRIX screen capture, In Parallel joining meetings, Memory Store on Granola transcripts).

**Axis 4 — substrate.** Markdown/git-native and local-first (GBrain, Basic Memory, Sylph "a Git repo you fork," Evermind, ByteRover, Cerenovus, Modern Relay's Omnigraph) versus hosted graph (Zep, Cognee, Naboo, Jedify, Saphenia, Interloom) versus **learned weights** — Engram alone, training "a compact, continuously-improving per-customer memory."

**Axis 5 — governance.** Almost nobody has it, and the few who do are aiming squarely at tier 2: Sentra (bi-temporal tracking, commitment tracking, contradiction detection), Zep (fact-validity windows), Naboo (on-prem/VPC, RBAC), In Parallel (permission-scoped and cited), Coworker (audit trail), Saphenia (financial services and pharma), Hyperspell (permission-aware graph).

**The commoditization threat is above and below.** Hyperscalers are entering the primitive (Cloudflare Agent Memory with typed Facts/Events/Instructions/Tasks; AWS, flagged in the dossier as a category competitor). And frameworks bundle memory for free: Mastra ships message history on by default plus working memory, Letta rewrites its own context, LangMem is LangChain's SDK, and in the anchor set alone Raycast (Memory + Profile), Wordware ("compounding context"), Agentplace (memory listed in its llms.txt) and Nous Research (built a Honcho integration) have already built or bundled it. **Eight of 37 anchors carry a build-it-themselves flag — a ~20% false-positive rate on any naive target list.**

**The open wedge.** Two things are true simultaneously: **42 of 73 vendor rows advertise no customer at all** in this evidence set, and the entire proven-revenue surface of the category is concentrated in a handful of vendors with specific, checkable jobs. Falconer alone supplies 6 of 37 anchors and 4 of the 18 named-human quotes, with the only case studies carrying industry, location and company-size profile blocks — because it sells one narrow, painful, verifiable job (engineering docs that drift from the codebase) with a named incumbent to rip out (Confluence, Notion). Glen supplies 5 anchors but the thinnest quotes ("It just works and works well"), because "institutional learning layer" is not a job anyone budgets for. The wedge is therefore **not** another Slack/Notion/Drive connector brain — that lane holds at least nine near-identical vendors (Gyld, Agently, Pensieve, Almanac, Lore, Compendium, Memory Store, Hyper, Company Brain) and produced almost no quoted customers. It is a **specific job with a named incumbent to displace, sold to a 10–200 person AI-native company, closable in days by one engineer.** The two least-contested versions: **(a) post-DIY conversion** — teams that already built memory and are maintaining it under protest (Adapta, Flow, Scira are the proof, and Adapta's quote is the ready-made sales line); and **(b) tenant-scoped customer memory that the buyer resells** — Hobbes, Luccid, SlideSpeak and Adapta all need it, only Hyperspell and Cognee show any evidence of winning it, and it is memory the customer *charges for*, which changes the willingness to pay entirely.

---

## 9. Targeting criteria — a checkable filter for a 50–100 company CRM

**Must clear all five:**
1. **Ships an LLM agent in production**, in-product or in the engineering loop. Verify: a named agent, an `/agents` page, an MCP server, or an "AI-native" claim on the homepage. (37/37 anchors pass; UnCircuit — zero occurrences of "AI," "agent," "model," "LLM" on-site — is the reference false positive.)
2. **Headcount 8–200.** Below 8 → self-serve only (Scira is one person and indie; it converts but will not pay). Above 200 → tier 2, needs SOC 2 / RBAC / VPC (Corgi, Thatch are the stretch edge).
3. **Founded 2019 or later, OR repositioned as AI-native since 2024.** The retrofit cases are real buyers: Vori (founded 2019, "AI native operating system" repositioning 2025–26), Payabli (founded 2020, Amigo agent suite July 2026), Upbound ("Humans govern. Agents consume. Machines execute.").
4. **A technical buyer is identifiable by name.** Founder/co-founder, CTO, VP Eng, engineering manager, or a documentation/DevEx owner. If the only reachable contact is ops, HR or procurement, deprioritize — zero anchor precedent.
5. **Knowledge is provably scattered:** three or more of Slack, Notion/Confluence, Linear/Jira, GitHub, Google Docs, Discord, plus coding-agent sessions. (Vori named six.)

**Any one of these promotes to priority:**
6. Raised inside 12 months **and** ≥5 open engineering roles (Thatch: 29 open; Nous: ~10; Eragon: 4).
7. Headcount ≥2× in 18 months (Thatch ~72→200+; Payabli tripled since 2023).
8. Public evidence of a memory/wiki complaint or an existing paid tool: Confluence, Notion, Mem0, or a homegrown system (Payabli, Vori, Scira, Flow, Adapta).
9. Fewer than 2 FTEs owning documentation while running >30 engineers (Payabli: ~50 engineers, one Director of Documentation).
10. Two or more coding agents in use (Claude Code / Codex / Cursor).
11. Public support surface larger than headcount — docs + Discord + email + content, under 15 people (AgentMail).
12. Multi-tenant product where the agent must be grounded in each customer's corpus (Hobbes, Luccid, SlideSpeak).

**Any one of these disqualifies:**
13. **Ships its own memory primitive as a product feature.** Mastra (working memory on by default), Letta, Raycast (Memory + Profile in Pro), Wordware, Agentplace, Nous Research. ~20% of the anchor set.
14. **Sells the substrate underneath you** — vector DBs, retrieval frameworks (Chroma; the dossier explicitly flags this citation as suspect).
15. **>500 people or publicly traded.** Tier 2.
16. **Non-tech operator** — hotel, grocery chain, trucking fleet, manufacturer, clinic. Zero anchor precedent.
17. **Dead or acquired in the last 12 months.** Re-verify quarterly; the observed decay rate is 3 of 37 per year.

**Suggested list composition**, mirroring the anchor distribution: ~30% agent infra/dev tools, ~25% consumer/prosumer AI, ~20% vertical agentic SaaS, ~15% AI-native fintech/regulated (the highest-ACV band), ~10% GTM agents. **Highest-yield sourcing pool:** YC W24–S26 (12 of 37 anchors), plus the logo walls of Falconer, Glen, Supermemory, Hyperspell, Trace, Cognee and Honcho — those seven vendors account for 31 of the 37 anchors and have already done the qualifying work.

---

## 10. Confidence and gaps

**High confidence:**
- The buyer is small, AI-native and technically led, and the signer is a founder or engineering leader. 17/17 named individuals are technical or product; zero exceptions.
- The two-tier split is real and structural. Every enterprise and institutional logo sits with mature vendors; every 1–15 person company sits with startup vendors. No crossover.
- Non-tech operators and >350-person organizations are absent from the anchor set entirely.

**Medium-high:**
- The six archetypes — clustered from the dossier's own category labels, not imposed. Boundary cases exist (Mission Inbox spans infra and GTM; SlideSpeak spans prosumer and infra).

**Medium:**
- Firmographic bands. Three anchors have unknown headcount (Praktika, Adapta, Chroma) and four carry ranges spanning 3× (Cluely 20–70, AGI Inc 15–50, Vela 2–15, Composio 11–50). Funding is "unknown" for 16 of 37 — absence of a disclosed round is not absence of capital.
- Trigger events. Derived from roughly six full case studies (Payabli, Vori, Thatch, Middesk, Scira, Flow, Adapta) plus inference across the rest.

**Low confidence / real gaps:**
- **Evidence is asymmetric.** 18 of 37 anchors carry a named human and a verbatim quote; **19 are logo-wall-only or explicitly ambiguous.** A logo proves nothing about payment. Falconer's hero strip carries *no* "trusted by" heading at all, so Fleetline and Seapoint are inferred customers. Mastra appears on Mem0's marquee while Mem0 also lists it under `/integrations` and publishes a competitive comparison page. Chroma may be part of Honcho's own stack. Eragon↔Hyperspell is a mutual citation. Treat roughly half the anchor set as *usage-shaped signal*, not proven revenue.
- **Zero pricing, ACV, seat-count or contract data anywhere.** Nothing in this dossier supports a revenue model or a price point.
- **One retention data point** (Scira switching Mem0→Supermemory) and no churn data on any vendor. The one measurable durability signal is negative: 8% of the anchor set died or was acquired within ~18 months.
- **Geography is underdetermined.** Five anchors have confirmed locations. No distribution claim is defensible; treat the Bay Area/YC skew as a sourcing artifact of who publishes case studies, not a finding.
- **Founding dates are missing for most anchors**; age is inferred from batch labels and round dates.
- **No stack-composition data.** Not one anchor is shown buying two products in this category, so nothing here says whether a company brain and a memory SDK coexist or compete inside the same account.
- **The dominant bias is selection.** These are the customers vendors chose to advertise: happy, logo-friendly, AI-native, YC-adjacent, and free to be named. Every buyer under NDA — which is most of tier 2 — is invisible by construction. The context set is the visible shadow of that population, and most of it is unverifiable as paying. Any segment described here as "absent" may be absent from *marketing*, not from the market.