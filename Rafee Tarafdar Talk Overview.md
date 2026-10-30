# Rafee Tarafdar on AI Fatigue, Token Guzzlers, and Slop — Talk Overview

- **Speaker:** Rafee Tarafdar, Chief Technology Officer, Infosys
- **Interviewer:** Jeff Kavanaugh, Head, Infosys Knowledge Institute
- **Event:** Infosys Connect conference, Los Angeles
- **Series:** Unlocking AI Value: Insights from the Top (Infosys Knowledge Institute)
- **Length:** 10:57
- **Video:** https://play.vidyard.com/QzSvMxJYc8EUcSkNmSp4qw

---

## At a glance
- **Main message:** AI value comes from speed, and five anti-patterns stand in the way.
- **The five anti-patterns:** AI fatigue, token guzzlers, AI slop, commoditization and the comfort trap.
- **Technical answer:** abstract every layer that can change, from models to data platforms, following "abstract, isolate, and standardize."
- **Limit:** abstraction can never be complete. The move from prompts to skills forced refactoring anyway.
- **Decision tool:** judge each layer of the stack on its own maturity, from research to commoditized utility, and then try it, wait, buy it or plug it in.
- **People side:** the hard parts are changing mindsets and finding use cases beyond productivity. Start with micro-change in a few teams.
- **Recommendation:** democratize innovation, spread it across the organization, and focus on value.

---

## 1. The starting point: speed (0:36)
Asked about the biggest focus for Infosys and its clients, Rafee says the priority is to "accelerate with speed, because … that's when the value will get delivered." Jeff sums it up as "no more three-year ERP implementations," and Rafee agrees.

---

## 2. The five anti-patterns (0:55–3:29)
These are habits that block AI value, "patterns that aren't healthy," as Jeff puts it. Rafee names a remedy for each in one closing sentence (3:08) but does not explain the remedies further. "AI vitality," the "clinic-based approach" and "harness" are not defined in the interview.

| # | Anti-pattern | What goes wrong | His remedy | Time |
|---|---|---|---|---|
| 1 | **AI fatigue** | Endless pilots and experiments, with AI changing so fast it feels like a treadmill that never stops | AI vitality | 1:04 |
| 2 | **Token guzzlers** | Agentic implementations that aren't optimized. Some were rolled out and then pulled back because they were slow and consumed too much | Cost-aware architecture | 1:35 |
| 3 | **AI slop** | Much of what AI generates has no value in cost, revenue or accuracy | A clinic-based approach | 2:07 |
| 4 | **Commoditization** | AI vendors are productizing many capabilities, so those capabilities no longer set anyone apart | Context and harness | 2:20 |
| 5 | **Comfort trap** | "For 20 years, I've done this way" thinking | An exponential mindset | 2:54 |

### Anti-pattern 1: AI fatigue
- Organizations are worn out by pilots and experiments, and by how fast AI itself changes: "for three years … it's like running on a treadmill with changes that are constantly happening, and it is not stopping."
- They need "a right way to deal with these new changes": a way to identify value for the enterprise, then prioritize and scale.
- **Remedy:** AI vitality.
- Later in the talk (3:48) he links his architecture answer back to this anti-pattern. The technical response to constant change is to "abstract anything that can change" (see section 3).

### Anti-pattern 2: Token guzzlers
- "Most of the agentic implementations are also not very optimized." Infosys is "already seeing that some of them rolled out, and then they had to pull it back" because they were slow and consumed a lot. "It's not very efficient."
- **Remedy:** manage token guzzlers with a cost-aware architecture.

### Anti-pattern 3: AI slop
- "A lot of what is generated may not be of value." Value here means cost, revenue or accuracy.
- **Remedy:** a clinic-based approach.

### Anti-pattern 4: Commoditization
- AI vendors are productizing many capabilities, "which means a lot of commoditization is happening."
- Enterprises then create value "by managing their business context and applying it to these AI models and agents to drive higher accuracy and value."
- Jeff adds that the enterprise has to carry the burden of tailoring a vendor's product to its own situation. Rafee agrees: "Context."
- **Remedy:** context and harness.

### Anti-pattern 5: Comfort trap
- AI needs a mindset change: "you have to come out of your comfort trap. For 20 years, I've done this way, and we can't continue doing the same way."
- **Remedy:** move to "this exponential way", an exponential mindset.

---

## 3. An architecture built to evolve (3:31–5:38)
Jeff and Rafee co-wrote the book *The Live Enterprise*, which has a chapter on the "digital runway" and evolving architecture. Jeff asks how to design an architecture that can evolve for AI. Rafee answers by going back to AI fatigue: "how do I abstract anything that can change?"

He lists the layers to abstract:

| Layer | What he says |
|---|---|
| **Models** | "Choose model based on the purpose": small, mid-size or frontier. In other words, use several models ("poly model") |
| **Agent frameworks** | "The agent framework themselves are evolving," so you need "the ability to choose any agent framework," for example Google ADK, LangGraph or AWS Strands |
| **Agent runtimes** | The runtimes "which run these agents" |
| **Cloud AI platforms** | "Different AI platforms on each of the cloud" |
| **Business, enterprise and data platforms** | The platforms "that have to be connected" |

- **The principle:** across this ecosystem, use standards and "the philosophy of abstract, isolate, and standardize." Then, "as and when things change, you have the ability to pick the best."
- **The limit (5:07):** "You can't expect 100% abstraction. So some of it you will have to refactor." His example: "Two years back we used to talk about prompts. Now we are saying, 'Okay, instead of prompts, we need to do skills.'" Skills are "a different manifestation," but the standards are moving towards them, "and that's how everybody is now building it."

---

## 4. Each layer matures at its own pace (5:38–7:00)
Jeff asks whether the pace of change will settle down. Rafee answers layer by layer: "Models are today more or less fairly stabilized. But if I go to agent layer, then there is a lot of evolution that is happening." So each layer of the stack has to be judged on its own maturity.

He places each technology on a four-stage maturity map, which he calls a "four-dimensional map":

| Stage | What it means | What to do |
|---|---|---|
| 1. **Research** | Very early and still evolving | These are "things in research which you try" |
| 2. **Custom** | You are largely doing custom development, and it is still changing | Decide: "Do I wait? Do I do something or not do something?" |
| 3. **Productized** | Available as a product | "A good way, because you don't have to build it" |
| 4. **Commoditized utility** | Mature | "You can plug and play change" |

---

## 5. What holds enterprises back (7:00–8:33 and 9:06–10:09)

**Three struggles among his peers:**
1. Changing mindsets, which "takes a little longer."
2. Finding AI use cases "that can deliver value beyond productivity."
3. Getting more into production, with "velocity in the engineering process."

CTOs are "probably more comfortable with the third." The first two are change management. Jeff suggests that sounds like the COO's job. Rafee says it is "everybody's responsibility," because "unless everybody changes, this change is not possible." Leadership can drive the change, but everyone has to go through it.

**Why progress is slow.** He wouldn't call it getting things wrong; "the process is taking a little longer":
- **Handling risk:** managing AI risks across different areas takes time. "The decisions take longer. The approvals take longer," so the cycle gets longer. He agrees with Jeff that companies may not be moving aggressively enough, or iterating enough.
- **Use cases:** the focus started with individual productivity and is now moving to team productivity, "but then we need to now move beyond that."

---

## 6. How to change mindsets: micro-change (8:33)
Going back to *The Live Enterprise*, Rafee recommends a micro-change approach: "start driving change in few teams, few areas, perfect it, drive it, and then keep scaling it across." Jeff adds that this lets each change fit its team's context. With the future not yet written, progress is incremental: "there is no zero to one or zero to 100."

---

## 7. His one recommendation for the next 9–12 months (10:09)
"Democratize innovation and drive distributed innovation across the organization, and then focus on value." The conversation closes on "Value is your North Star," and Rafee agrees: "Yes."

---

## Timeline

| Time | Topic |
|---|---|
| 0:00 | Introduction |
| 0:36 | Speed as the main focus |
| 0:55 | The five anti-patterns |
| 3:08 | The five remedies |
| 3:31 | Designing an architecture that can evolve |
| 5:07 | Limits of abstraction: prompts → skills |
| 5:38 | Maturity by layer: models vs. agents |
| 6:12 | The four-stage maturity map |
| 7:00 | What peers struggle with |
| 8:33 | Micro-change |
| 9:06 | Why progress is slow |
| 10:09 | Recommendation for the next 9–12 months |

---

## A model-engineering reading (commentary, not from the talk)
These notes are my own, not Rafee's. They cover how his points could translate into engineering practice, and where they are open to debate.

**Turning the anti-patterns into engineering practice**
- **AI fatigue:** put one stable internal interface in front of models and agent frameworks, and keep model choice in configuration. Keep an eval suite too, so swapping a model is a measured decision rather than a rewrite.
- **Token guzzlers:**
  - Route each task to the smallest model that passes its evals.
  - Cache repeated context, and retrieve what's needed rather than stuffing the context window.
  - Cap agent loop steps and tool calls.
  - Track cost per successful task, not per call.

  Venky Iyengar's talk in the same series adds a related point: keep input tokens high relative to output tokens.
- **AI slop:** tie evals to the value measures Rafee names (cost, revenue, accuracy), and check outputs before they reach users.
- **Commoditization:** treat the harness (tools, skills, retrieval, guardrails, evals) and your enterprise context as your IP. That is the part that doesn't come in the vendor's box.
- **Comfort trap:** mostly an organizational problem. Micro-change maps naturally onto shipping small, measured improvements in a few teams first.

**Points to debate**
- **"Models are fairly stabilized."** Model APIs have converged, but model behaviour shifts with each release, and prompts or skills tuned for one model don't always carry over to another. A model abstraction only works if it comes with evals that show whether a swap is safe.
- **"You can't expect 100% abstraction."** Agreed. That argues for thin adapters and good tests, so refactoring is cheap when the next shift arrives (as prompts → skills did). Heavy abstraction layers that try to predict those shifts are less useful.

**Related talks in the series**
- **Venky Iyengar**, *Quality Engineering as the AI Trust Layer*: testing probabilistic AI systems, the "context mesh" knowledge graph, and the ratio of input to output tokens.
- **Venkat G**, *Moving Customer Care Beyond Service*: tokenomics as a challenge at enterprise scale.
- **Shishank Gupta**, *Unlocking AI Value Beyond Copilot*: models will become a utility, and context is the IP.
- **Suyash Awasthi**, *Turning AI Investment into Measurable Enterprise Value*: models are "one of the seven layers of AI."

---

## Sources and accuracy
- This overview is based on the Whisper large-v3 transcript, cross-checked against Vidyard's own captions. Quotes have been lightly cleaned of filler words such as "uh" and "you know."
- Both transcripts misspell his name ("Rafi Parftar", "Rafi Farukhdar"). The official title spells it Rafee Tarafdar. Both also render "agent runtimes" as "agent run types."
- Local files:
  - `videos\Rafee Tarafdar on AI Fatigue, Token Guzzlers, and Slop [QzSvMxJYc8EUcSkNmSp4qw].mp4`
  - `transcripts\Rafee Tarafdar on AI Fatigue, Token Guzzlers, and Slop [QzSvMxJYc8EUcSkNmSp4qw].txt`
- See also `Video Notes.md` and `Series Overview.md`.
