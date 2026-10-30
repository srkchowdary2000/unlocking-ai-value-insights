# Unlocking AI Value: Insights from the Top — Video Notes

Source page: https://www.infosys.com/iki/videos/unlocking-ai-value-insights-top.html
15 interviews, about 3 hours in total. Jeff Kavanaugh (Head, Infosys Knowledge Institute) recorded all of them at the Infosys Connect conference in Los Angeles.

Files:
- `videos\`: 1080p MP4, Vidyard captions (`.vtt`) and metadata (`.info.json`) for each video
- `transcripts\`: Whisper large-v3 output as timestamped `.txt`, `.srt` and `.plain.txt`

Names and roles below come from Infosys's own video descriptions. The figures are as the speakers stated them.

## Index

| # | Speaker | Role | Length | One-line takeaway |
|---|---|---|---|---|
| 1 | Salil Parekh | CEO, Infosys | 6:15 | The tech is proven; deploy at scale now, and reskill rather than lay off |
| 2 | Rafee Tarafdar | CTO, Infosys | 10:57 | Five anti-patterns block value; abstract every layer of the stack |
| 3 | Shaji Mathew | CHRO, Infosys | 15:49 | Ambidextrous talent plus a Y-shaped career architecture |
| 4 | Bal Shukla | Head of Business Transformation & AI, Financial Services | 11:42 | Banks are compressing 3–5-year core overhauls into about 18 months |
| 5 | Karmesh Vaswani | Global Head, Consumer Goods, Retail & Logistics | 13:26 | Asset cost down 95% means 50× more personalization; consumers will shop through agents |
| 6 | Samik Ghatak | Client Services Head, Travel & Hospitality | 11:02 | Frictionless travel comes from invisible optimization and shared data |
| 7 | Vikram Meghal | Global Head of Engineering, Networks/CMT | 11:20 | Autonomous networks, edge AI, and telcos as sovereign "intelligent utilities" |
| 8 | Venkat G | Head, AI Customer Service Experience | 10:38 | Turn customer care from a cost into a source of revenue |
| 9 | Mayank Agarwal | Head of Cybersecurity, Americas | 15:59 | Guardrails are the brakes that let you go faster; plan resilience in minutes, not days |
| 10 | Venky Iyengar | Global Head, Quality Engineering & Cloud | 10:57 | Quality engineering is the AI trust layer; build a "context mesh" |
| 11 | Shishank Gupta | Global Practice Head, Microsoft AI & Digital Workplace | 9:21 | Copilot is the starting point, not the end; organizational context is the moat |
| 12 | Suyash Awasthi | President, Simplus (Salesforce) | 10:15 | Partner onboarding cut from 16–20 days to hours; four kinds of "debt" |
| 13 | Skyler Mattson | CEO, WongDoody | 11:24 | $150 → $0.09 per asset; co-create with clients and design for AI agents |
| 14 | Ben Ko | Head, Kaleidoscope Innovation | 15:46 | AI adoption is a trust and change-management problem |
| 15 | Kate Maloney | Executive Director, Infosys Foundation USA | 14:02 | A learning-to-career pipeline for an AI-ready workforce |

---

## A. Enterprise leadership

### 1. Salil Parekh on Unlocking Enterprise Value from AI (6:15)
CEO, Infosys · `f7DL2o7rRhDWM3L9CBamPE`
- **Two dimensions of value:**
  - **Growth:** target customers much more narrowly and scale that up.
  - **Efficiency:** agents, customer service, supply chain.
- **Boards are asking** what step-function change AI enables. The answer: make AI fit the organization's culture, deploy with speed, and scale up foundation models and platforms quickly. Work that took weeks or months now takes days, hours or minutes.
- **Infosys itself:** it is reskilling all teams and has no layoffs planned. It recruited about 20,000 college graduates last year. Its people's knowledge of clients, combined with new tools, creates a flywheel.
- **Six broad AI service areas**, including AI engineering, agent building and code modernization, all built on Topaz Fabric.
- **Advice:** "The technology has already proven itself. This is the time to do these things at scale." Expect ups and downs along the way.

### 2. Rafee Tarafdar on AI Fatigue, Token Guzzlers, and Slop (10:57)
CTO, Infosys · `QzSvMxJYc8EUcSkNmSp4qw`
- **Speed delivers value:** no more three-year ERP programs.
- **Five anti-patterns and their remedies:**
  - AI fatigue → "AI vitality"
  - token guzzlers (some agentic rollouts were pulled back as too slow and costly) → cost-aware architecture
  - AI slop → a "clinic-based approach"
  - commoditization → business context and harness
  - the comfort trap → an exponential mindset
- **Evolving architecture:** abstract, isolate and standardize across layers:
  - models (several, from small to frontier)
  - agent frameworks (Google ADK, LangGraph, AWS Strands)
  - runtimes
  - cloud AI platforms
  - enterprise and data platforms

  Full abstraction is impossible, though: the shift from prompts to skills forced refactoring anyway.
- **Maturity differs by layer.** Models are fairly stable; the agent layer is not. Map each technology as research → custom → productized → commoditized utility, then decide whether to build, buy or wait.
- **Where peers struggle:** mindset change, use cases beyond productivity, and velocity into production. Risk reviews and approvals stretch the cycle.
- **Advice:** start with *micro-change* in a few teams (from *The Live Enterprise*), then scale. Democratize innovation, and make value the North Star.

### 3. Shaji Mathew on Building an AI-First Workforce (15:49)
CHRO, Infosys · `h4ttZQQxriVL9tUsNWegwj`
- **Strategy with three pillars:**
  1. An **ambidextrous organization**: AI-augmented talent at scale, plus deep engineering and domain experts.
  2. A **Y-shaped career architecture**.
  3. **AI-first enablement** across the whole company.
- **Building depth:**
  - premium campus hiring in India (up to ₹21 lakh)
  - specialist-programmer and "frontier talent" tracks
  - bridge programs
  - a new assessment center of excellence with a five-point method
- **Moving from jobs to capabilities:** a "Capability Quotient" measures technology, domain, foundational (for example project management and estimation) and societal (soft) skills.
- **How the Y works:** everyone starts on a common base. After a few years the left branch holds AI-augmented technology project managers and the right branch holds specialists. Moving across, and every step up the right branch, requires passing an assessment and brings different pay. A flat expert tier sits above it, with roles such as Distinguished Technology Engineer. HR benchmarked about 20 companies when designing it.
- **Scale of enablement:**
  - AI Aware: about 90% of staff have completed it
  - AI Builders: about 50,000 people
  - AI Masters: a few hundred, invitation-only, six-month certification
  - the Mysore foundation program redesigned AI-first
  - sales leaders trained on Claude, Gemini and Cursor
- **Advice to other HR heads:** everyone is upskilling, but few redesign career architecture as part of the operating model. Models are available to everyone; the human transformation is what differentiates.

---

## B. Industries

### 4. Bal Shukla on Why Agentic AI Is Rewriting the Rules of Financial Services (11:42)
Head of Business Transformation & AI, Financial Services · `V3mZy4BzBkZtWmFYxo2X5g`
- **Banks are reimagining every process:**
  - onboarding: weeks → days or hours (including family offices)
  - complaints and disputes: 5–8 days → within a day
  - financial advisors with intelligence at their fingertips
  - contact centers that are "AI first, humans as needed"
- **The iceberg:** core banking, mortgage, payments and wealth systems run on legacy mainframes, often several cores after acquisitions. Agentic AI pulls out the rules buried in that code, so overhauls that took 3–5 years now take about 18 months ("hollow the core").
- **Next wave:** proactive alerts instead of insufficient-funds fees, and agentic commerce with human-in-the-loop entitlement limits ("auto-pay on steroids").
- **Three ingredients:**
  1. Lay the rails (foundations).
  2. A change-management operating model; he calls change management about 80% of the work.
  3. Lab-based iteration that tolerates early failure. One bank took six months just for contact-center knowledge management.
- **People:** everyone up to the CEO must use AI tools personally ("until you do it yourself…").
- **Product cycles:** product management has gone from six months to a few weeks, and market testing from 12 months to 3–6.

### 5. Karmesh Vaswani on Reimagining Consumer Goods and Retail with AI (13:26)
Global Head, Consumer Goods, Retail & Logistics · `MtegGexYm1YYd61T7Nxp9L`
- About 70% of the value between a product's cost and its shelf price is spent moving it from manufacturer through retailer to consumer. AI, both digital and physical, can shrink that.
- **Case:** an FMCG company reaching 3 billion consumers produces 19 million digital assets. Infosys's AI studios for translation, adaptation and imagery cut the cost from about $100 to under $2 per asset (95% lower). That allows 50× more personalization for the same spend. In-house headcount was unchanged, while the agencies of record have to raise their value to stay relevant.
- **Competition:** the industry will consolidate. Personalization shrinks the gaps that let so many brands coexist, and the cycle from consumer insight to action gets much faster.
- **Logistics becomes multi-modal and data-driven:** shelves and video feeds talk to warehouses, transporters, labor scheduling and robots, with humans in the lead.
- **Macro view:** S&P 500 companies employed about 7,000 people per $1B of sales in the 1990s and about 2,500 in 2025. That could fall to about 500 in 3–5 years. Can you achieve a 3–5× productivity gain before a competitor does?
- **The consumer of tomorrow** has agents working for them, so brands must appeal to those agents across product, price, promotion and place. He is optimistic, provided there is responsible governance.

### 6. Samik Ghatak on Unlocking AI Value in Travel and Hospitality (11:02)
Client Services Head, Travel & Hospitality · `93TK4BSK2KizmRCc5evdsS`
- **The goal is frictionless travel.** For example, a car is matched before arrival for suitcase size, family or accessibility needs, and a digital concierge handles the handoff.
- **Optimizations travelers never see:**
  - full flights and tuned fares
  - cargo routing
  - cabin temperature
  - single-engine taxiing and choice of cruise altitude
  - hotels scheduling which lift banks run
- **Baggage tracking** has cut missed-bag rates dramatically, even across thousands of bags a day. Travelers also get guidance in their own language and context at airports.
- **Next:** airline, airport, ground transport and Uber sharing data so travelers no longer switch between apps.
- **Security:** he cites the Starwood loyalty-data breach. With "Mythos" and frontier models, the internal systems and the perimeter both need guarding, and AI enables edge-based perimeter security.
- **People:** contact centers become proactive and AI-assisted, but physical recovery, such as finding a bag in a pile of 10,000, still needs humans. A good data foundation "allows you to do all the fun stuff."

### 7. Vikram Meghal on AI-Powered Networks and the Future of Telecommunications (11:20)
Global Head of Engineering, Networks/CMT · `WyhoAQqv44xaCZE2EQcWEj`
- **Autonomous networks:** most telcos are at autonomy level 2. The work under way moves them to level 3+, and level 4 is a 2–3-year journey.
- **Intelligence moves from the cloud to the edge.** The network sits between cloud and consumer, so it must get smarter. TM Forum is pushing equipment makers to interoperate at the level of intelligence, not just protocols.
- **Use cases:**
  - prioritizing a critical call over gaming or streaming
  - a surge of machine-initiated traffic (industrial IoT, vehicles)
  - automatically isolating network segments under cyberattack
- **People:** deliver technology and operations together so tools get adopted. Ask "does a human need to do this?" New roles will appear in network operations.
- **Winners:** telcos that become trusted, sovereign "intelligent utilities" and sell priced intelligence. They missed out in the IoT and over-the-top era.
- **Advice:** a dual-speed strategy. Use AI to take cost out of legacy operations, and build new capabilities at the speed customers now expect (for example, over-the-top TV eroded pay TV).

---

## C. Functions and capabilities

### 8. Venkat G on Moving Customer Care Beyond Service (10:38)
Head, AI Customer Service Experience · `QyH1a6VrfYeF27TTtkuDbD`
- **Shift customer care from a service cost to revenue** (upsell, cross-sell, retention), with AI and people together.
- **Contact centers survived mobile** because they sit at the *edge* of the enterprise, and tech investment went to the core first. Now comes the "smart agentic front door."
- **By sector:**
  - retail and banking: upsell
  - B2B manufacturing: amplify human account reps with digital twins and single-call resolution
  - healthcare: stays people-centric, AI-amplified
- **Wait times** come from people-led capacity planning; "when is / what is / can I" queries scale through bots. Move from deflection to in-call agentic resolution, and ultimately to predictive, proactive care.
- **Obstacles:**
  1. **Data.** At one large client, a third of calls had no reason code.
  2. **Integration with complex systems.** "Why is my bill high?" needs reasoning across systems.
  3. **Scale:** performance, guardrails, latency and tokenomics.
- **People:** "people with AI vs. people without AI." Healthy firms will redeploy staff; cash-strapped firms will cut.

### 9. Mayank Agarwal on Securing AI and Scaling Cyber Defense (15:59)
Head of Cybersecurity, Americas · `LucwVzaVcWX8vwpguogPza`
- **Guardrails are the brakes that let a race car go faster.** There are two plays: *protect the AI* (models, data, agent identity, outputs) and *use AI for cyber*.
- **Results:**
  - a GRC agent cut cyber-audit preparation from 4–4.5 months to under 1
  - SOC investigations went from 12 hours–3 days to under 2 hours
  - at a chip maker, AI triage now escalates only the few alerts that need plant teams
- **Five CISO responsibilities:**
  1. threats, including supply-chain and IoT
  2. converting threats into risk (mitigate, transfer, accept) and reporting to the board
  3. compliance (SOX, PCI DSS, HIPAA, privacy)
  4. cyber resilience, which differs from business continuity and disaster recovery
  5. a secure user experience
- **Boards care** because one incident can cut market cap by 25–30%.
- **"Mythos"** (he has held about 25 client conversations in under five weeks): frontier models, including Mythos, Opus 4.7, GPT-5.5 and Clearwing, can chain low-severity vulnerabilities into a critical one. Defenders have the same capability. His response:
  - get visibility of critical vulnerability chains
  - remediate, transfer the risk, or add compensating controls
  - plan resilience in *minutes*, not days
  - make the whole enterprise aware

### 10. Venky Iyengar on Quality Engineering as the AI Trust Layer (10:57)
Global Head, Quality Engineering & Cloud · `Ecv635TBmJF7uq2z6yPdoN`
- **"A tale of two cities":**
  - AI *for* quality engineering on deterministic software will shrink services revenue.
  - Quality engineering *for* probabilistic AI systems will grow tremendously.
- **Trust is the biggest barrier to adoption,** so quality engineering is central to responsible AI. AI does the typing; humans do the critical thinking.
- **Built a taxonomy of AI failure modes** from enterprise deployments, and tests under edge conditions with messy real-world data.
- **Utility client:** an AI agent answering "why is my bill so high?" was tested with simulated conditions (summer, guests at home), which stopped wrong answers reaching customers.
- **Internal result:** across the top 100 clients, 25% more throughput in 12 months with the same headcount.
- **The driver is a "context mesh"** (or "digital brain"): a knowledge graph of the client's systems and tacit knowledge. It produces fewer, more accurate tests and fewer tokens. Keep input tokens high relative to output tokens: that means higher accuracy at lower cost.
- **Next 6–12 months:** hundreds of testing agents. Without a context mesh, agents "run wild" and drift in production. Build control planes and observability for token use and agent performance.

### 11. Shishank Gupta on Unlocking AI Value Beyond Copilot (9:21)
Global Practice Head, Microsoft AI & Digital Workplace · `zPXnbt7Ay4W5BzSa8uiiUm`
- **Copilot-style tools** (summarizing email and meetings) made people comfortable with AI. They are the *starting point*. Agentic AI reimagines business processes and produces insights humans could never generate in time.
- **Context is the moat.** Word, Excel, Outlook, SharePoint, OneDrive, Teams and Windows permissions hold rich user and organizational context, which enables AI tailored to each role. Models will become a utility; context is your IP.
- **Microsoft's head start comes from spanning four layers:**
  1. productivity (Teams, Outlook)
  2. data (Fabric)
  3. security (Purview, Defender)
  4. cloud (Azure) and business apps (Dynamics)

  Whether it capitalizes on that "is for time to tell."
- **Digital workplace:** onboarding, learning, devices and ticketing become personalized and self-healing, with tickets auto-raised.
- **Next 9–12 months:** the value is consistency of experience and always-current information, not just cost savings. Good experiences drive adoption.
- **People:** junior roles get redefined, not removed. People become mentors and guides who build agents, maintain them and keep them from going rogue.

### 12. Suyash Awasthi on Turning AI Investment into Measurable Enterprise Value (10:15)
President, Simplus (Infosys's Salesforce subsidiary) · `borB77RGMY1k3LHXQgp7XF`
- **Clients have moved from buying AI to demanding a measurable return.** Value comes from process reinvention, new markets and new revenue, not only efficiency.
- **Case:** a top-3 networking-equipment maker had a Big Four strategy deck it couldn't execute. A Topaz Fabric session using the client's own context produced an executable MVP. About 95% of partner onboarding (due diligence, risk scoring) can be automated, cutting it from 16–20 days to hours. The work also flags partners not to do business with.
- **Models are one of seven layers of AI;** start from goals and work backward. He quotes Infosys's chairman: legacy modernization is an $11.8 trillion addressable market.
- **Four kinds of debt** (technical, process, data and strategy) add up to a risk of "digital bankruptcy."
- **Adoption needs a top-down mandate plus bottom-up uptake;** otherwise it is "theatrics" and slideware. Working apps can now arrive in days or weeks.
- **Humans stay in decisions** because of model sycophancy, hallucination and non-determinism.
- **Advice:** choose the right partner and AI stack amid a flood of point solutions, and focus on data ("garbage in, garbage out"). Data scientists and domain experts stay essential.

### 13. Skyler Mattson on Unlocking AI Value Through Creativity and Personalization (11:24)
CEO, WongDoody · `iWfAafVgTtnneVB2rTwGaT`
- **Content at scale:** a shoot that cost millions and took six weeks can now be done in a day for pennies. For a global CPG brand with hundreds of sub-brands, cost fell from about $150 to $0.09 per asset. The content is also better: personalized content is 25% more likely to be clicked and bought. WongDoody, DX and DNA together create, deploy and measure the assets.
- **Creative teams are empowered, not cut;** their jobs get "bigger and more interesting." The real question is what you do with the time saved, because faster and cheaper alone is a race to the bottom.
- **Winners co-create with clients.** WongDoody builds each client a "brand OS" fitted to its own workflows. If nobody adopts it, no value is unlocked.
- **Automotive example (Mitsubishi Canada):** content follows the car someone configured on the website, so the dealer already knows them: "a handshake, not a handoff."
- **Design for agents too:** shoppers increasingly ask ChatGPT, so brands are moving TV budgets to influencers for third-party endorsements. Unready data is a top barrier.
- **Talent is the key risk:** reskill, don't replace. Combine top-down direction with bottom-up "playgrounds" and trust, and hire for curiosity.

### 14. Ben Ko on Why AI Adoption Is a Trust Problem (15:46)
Head, Kaleidoscope Innovation (product design and engineering) · `z9UogqGxowQZm8oEVfJKTQ`
- **AI makes unstructured, in-the-head expertise usable.** An operating room is full of what nurses, technicians and administrators know. Kaleidoscope spans digital AI and physical AI (surgical robotics, warehouses), and pharma and clinical trials.
- **Adoption is a change-management and trust problem,** not just usability. Design researchers embed with workers and turn resistance into advocacy by solving their real problems.
- **Measured outcomes:** one metric up 28% from automation, and decisions 15% faster from interpretable data. Physical AI only pays off when robots connect to warehouse management, manufacturing execution and ERP systems.
- **Barriers:** IP, patentability and patient-data concerns. Tools like Topaz Fabric run inside the client's own environment, which has won over legal and compliance teams.
- **Excited about:** democratizing product development, from natural language to manufacturable CAD. "Design *with*, not design *for*": nurses and factory associates co-design. He sees a cycle from CAD to 3D print to machining to testing in a mock operating room in a couple of hours.
- **Agents:** dropping them into existing processes makes things faster; redesigning processes around them is the exponential gain.
- **Regulation:** the FDA restricts continuously learning models because they diverge from what was approved. He also cites Francis Collins on patient-specific gene therapy, and asks how to make that scalable and affordable.

---

## D. Society and talent pipeline

### 15. Kate Maloney on Building America's AI Ready Workforce (14:02)
Executive Director, Infosys Foundation USA · `XM2vsT5qzzSG5bGu72vfKH`
- **The foundation is expanding** from K-12 to a new *workforce readiness and talent development* pillar, a full learning-to-career pipeline. It covers students, community-college learners, people changing jobs and veterans moving to civilian work.
- **Last year:** 1.2 million students and 16,000+ teachers. The Pathfinders Summer Institute, in its 9th year, will train 1,600 teachers to bring computer science and AI into classrooms.
- **Infosys Springboard:**
  - free, with 13,000 offerings (mostly Skillsoft content, refreshed monthly)
  - white-labeled microsites for specific groups
  - completion certificates people can post on LinkedIn
- **Micro-internships** (6–8 weeks) give community-college students real industry challenges. One challenge with an energy company asked how AI could mitigate a cyberattack on the grid, and it led to job offers. This matters for first-generation students without social capital.
- **Exploring:** apprenticeships for trades meeting physical AI, plus employee volunteering.
- **Advice:** know your clients' purpose and ESG goals, and bridge them with the foundation's. "We are the ultimate human-centered design unit."

---

## Common threads across the series
1. **Value beyond productivity.** Individual and team productivity is only the start; the gains come from process reinvention and revenue (Rafee, Shishank, Venkat, Suyash, Bal, Ben).
2. **Speed and scale now.** "Do it at scale" (Salil). 3–5 years → 18 months (Bal). Days or weeks, not months or years (Suyash). Run two speeds at once (Vikram).
3. **Context and data are the moat.** Business context (Rafee), organizational context (Shishank), the context mesh (Venky), untagged calls (Venkat), data readiness (Skyler, Samik, Suyash).
4. **Token economics are a design constraint.** Token guzzlers (Rafee), tokenomics (Venkat), input/output ratio and observability (Venky).
5. **Trust and guardrails enable speed.** Brakes (Mayank), quality engineering as the trust layer (Venky), IP, privacy and regulators (Ben), sycophancy (Suyash).
6. **Frontier-model cyber risk ("Mythos").** Chained vulnerabilities and resilience in minutes (Mayank), perimeter security (Samik), auto-isolating networks (Vikram).
7. **Near-free content makes hyper-personalization viable.** $150 → $0.09 (Skyler) and $100 → under $2 (Karmesh).
8. **Design for AI agents as customers.** ChatGPT shopping (Skyler), consumers' agents (Karmesh), agentic commerce (Bal).
9. **Reskill, don't replace; change management is the real work.** No layoffs and 20,000 graduate hires (Salil), the Y-architecture (Shaji), change management at 80% of the work (Bal), bottom-up plus top-down (Suyash, Skyler), the foundation's pipeline (Kate).
