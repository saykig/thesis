# AI military decisions — research ledger

These entries record Sara's questions and research leads. The 10 November material came from a Google Gemini answer supplied by Sara; its cited links and factual assertions have **not** been verified here. It is a prompt for source checking, not evidence that a capability was fielded or changed behavior.

## 5 November 2026 — human judgment in military command

**Sara's question:** Are human–AI interactions challenging theater-level decisions made by military officers?

Rereading her personal site's “About me” page renewed this interest; a Google AI Overview screenshot prompted questions about OODA and Maven. The overview is a lead, not evidence.

| Area | Proposed mechanism or issue | Evidence status and next test |
|---|---|---|
| Decision cycle | Faster AI recommendations may leave less time for officers to interpret, challenge or override outputs; automation bias could make approval formal. | “Maven goes against OODA” and “hours become seconds” are unverified. Trace an actual decision workflow and its timing, overrides and outcome. |
| European dependence | Private suppliers might control data access, model changes, evaluation or training in a way that matters to European or NATO decisions. | Identify a documented European deployment and contractual or operational control. Ukraine, the Arctic and China are possible contexts, not evidence of European Maven use. |
| Human behavior and dual use | Trust, attention and responsibility may vary with interface design and defensive, offensive or civilian use. | Check whether behavioural findings transfer to command settings and specify the relevant legal obligations. |

**Starting sources and limits from the original note:**

- [U.S. Department of Defense contract notice (2024)](https://www.defense.gov/News/Contracts/Contract/Article/3910169/) records a U.S. Army licence for Palantir's Maven Smart System; it does not establish European adoption or effects on officers.
- [Ingvild Bode, *Human-Machine Interaction and Human Agency in the Military Domain* (2025)](https://www.cigionline.org/publications/human-machine-interaction-and-human-agency-in-the-military-domain/) develops distributed agency; conceptual rather than a Maven outcome study.
- [ICRC, *Decisions, Decisions, Decisions* (2024)](https://www.icrc.org/en/publication/decisions-decisions-decisions-computation-and-artificial-intelligence-military-decision) discusses military decision support and human decisions about force.
- [European Defence Agency, *Trustworthiness for AI in Defence* (2025)](https://eda.europa.eu/docs/default-source/brochures/taid-white-paper-final-09052025.pdf) offers a defence evaluation framework, not proof of field performance.
- [EU AI Act, Article 2(3)](https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng) excludes systems used exclusively for military, defence or national-security purposes from that Act's scope. Mixed uses and other law require separate analysis.

**Rival explanation:** A decision may change because of doctrine, staffing, better sensors, training or command authority rather than the AI recommendation itself.

**Next discriminating step:** find a European deployment and an episode showing how officers used, challenged or relied on outputs, with records sufficient to separate observed behavior from announcements.

## 10 November 2026 — what shortens decision and targeting cycles?

**Sara's question, edited for clarity:** Which advances in military systems shorten the OODA cycle or the targeting “kill chain,” and at which steps do they change the role of human judgment?

**Gemini's proposed map, as research leads:** OODA's observe/orient/decide/act is not identical to find/fix/track/target/engage/assess. “Closing” a chain could mean shorter latency, more connected systems, fewer handoffs or delegated authority; these must be measured separately.

| Stage | Instruments or practices Gemini named | What to verify |
|---|---|---|
| Observe and find/track | Distributed satellites, UAVs and passive RF sensors; cross-service data sharing associated with JADC2. | Which sensors are actually linked, how fast, and under whose release authority? A programme vision is not an operational result. |
| Orient and fix/identify | Computer vision, sensor fusion and edge computing; Maven Smart System and a vendor's SAGEcore were offered as examples. | What tasks do deployed versions perform, with what error rates, human review and documented use? Distinguish target recognition from verified identification. |
| Decide and target | Course-of-action recommendations and weapon–target pairing. | Are recommendations merely displayed, or do they allocate assets? Who can reject them, and how much time do they have? |
| Act, engage and assess | Digital sensor-to-shooter links, loitering munitions and swarms. | What transfer, firing authorization, autonomy and post-strike assessment are demonstrated in the chosen case? Do not infer autonomous lethal action from a data link. |

Gemini further claimed a shift from a “loop” to a “predict-act vector,” predictive positions 48 hours ahead, and broadly “machine-speed” execution. Treat these as **unverified generalizations**, not established performance. OODA retains feedback by definition; a system's prediction does not eliminate the need to observe or reassess. “Human-on-the-loop” describes one possible allocation of authority, not a proven universal transition.

**Starting leads to inspect:** [U.S. DoD JADC2 overview](https://www.defense.gov/News/Releases/Release/article/2970094/dod-announces-release-of-jadc2-implementation-plan/) for institutional aims; [DoD Maven contract notice](https://www.defense.gov/News/Contracts/Contract/Article/3910169/) for procurement; [Leonardo DRS account](https://www.leonardodrs.com/news/thought-leadership/how-ai-and-machine-learning-strengthen-defense-sensing-and-mission-systems/) as a vendor claim; [Air University discussion](https://www.airuniversity.af.edu/Wild-Blue-Yonder/Articles/Article-Display/Article/3118712/decision-advantage-in-competition/) for conceptual framing. The institutional and vendor sources can establish their own descriptions, not the claimed operational effects. The listed sources still need close reading against a case.

**Rival explanation:** Better networking, command arrangements or conventional automation might shorten the interval without AI; added classification, verification or approval steps might preserve or lengthen it.

**Next discriminating step:** select one system and map timestamps, data handoffs, recommendation, approval and action from a documented exercise or operation. Compare its actual workflow with a defined baseline.

## 10 November 2026 — implications for deterrence

**Sara's follow-up question, edited for clarity:** If AI-enabled military systems shorten the time between detection and action, under what conditions would that change deterrence and crisis stability between states, and where would existing deterrence theory still explain the outcome?

This narrows the issue to a mechanism and outcome. It does not presume a new theory is needed. Gemini's answer asserted that machine-speed systems would overturn rational-actor models, erase diplomatic pauses, create “flash wars,” blur conventional and nuclear targets, and shift deterrence toward automated denial. Its proposed label “algorithmic realism” is not adopted as a scholarly framework here.

| Candidate mechanism from Gemini | Conditional hypothesis to investigate | Rival or limiting condition |
|---|---|---|
| Compressed deliberation and signaling | A shorter response window could reduce time to interpret intentions or communicate an off-ramp. | States may impose human authorization, delays, hotlines or rules that preserve time; software speed is not political decision speed. |
| Interacting automated systems | Misclassification or reciprocal defensive reactions could create an inadvertent escalation pathway. | Fail-safes and command separation may stop propagation; a “flash war” analogy is not evidence of one. |
| Conventional–nuclear entanglement | Strikes or interference affecting dual-use warning or command assets could be read as a threat to nuclear forces. | The risk predates AI; assess whether new sensing or targeting materially changes it in a specified dyad. |
| Deterrence by denial | Faster detection and interception could make an attack appear less likely to succeed. | Effectiveness, credibility, adversary beliefs and possible incentives to preempt all matter; capability claims alone do not show deterrence. |
| Human and algorithmic interaction | Recommendations might shape the options leaders see, their confidence or response thresholds. | Leaders may disregard them; classical deterrence already considers uncertainty, credibility and organizational limits beyond a simple rational-actor caricature. |

**Evidence status:** These are hypotheses generated from the Gemini response, not observed outcomes. Claims that escalation becomes a binary switch, diplomats lose all time, or strategic theory “breaks” are too categorical. Keep **deterrence** (an adversary's expectations before action) distinct from **escalation** (changes during a crisis or conflict).

**Starting literature to inspect:** [Schelling, *Arms and Influence*](https://yalebooks.yale.edu/book/9780300002218/arms-and-influence/) for coercion and communication; [James M. Acton, “Escalation through Entanglement”](https://carnegieendowment.org/russia-eurasia/posts/2018/12/escalation-through-entanglement-how-the-vulnerability-of-command-and-control-systems-raises-the-risks-of-an-inadvertent-nuclear-war) for conventional–nuclear command-and-control risk; [SIPRI, *Impact of Artificial Intelligence on Strategic Stability and Nuclear Risk*](https://www.sipri.org/publications/2019/research-reports/impact-artificial-intelligence-strategic-stability-and-nuclear-risk-volume-i-euro-atlantic) for AI and strategic stability. These are reading leads, not a completed review.

**Next discriminating step:** choose a dyad, European relevance, a system function and a crisis decision. Identify what the opponent could observe and believe, the authority to act, and whether response time or escalation choices demonstrably changed. A study of deterrence failure requires a different outcome measure from a study of officer judgment.

This interest does not select the paper's question, case or method. The [broader ledger](../RESEARCH_LEDGER.md) records Q22 and the new Q25–Q26.
