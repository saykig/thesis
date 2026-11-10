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

## 10 November 2026 — military instruments and decision speed

**Sara's original question:** “what advancements in military instrument are closing the "kill chain" or the ooda loop?”

**Edited for clarity:** Which advances in military systems shorten the OODA cycle or the targeting “kill chain,” and at which steps do they change the role of human judgment?

### Answer:

Modern military advancements are rapidly collapsing the traditional **OODA Loop** (Observe, Orient, Decide, Act) and closing the "kill chain" (traditionally framed as Find, Fix, Track, Target, Engage, Assess). Because modern threats like hypersonic missiles and coordinated drone swarms operate at speeds that overwhelm human cognitive capacity, the military is transitioning from manual, sequential loops to **automated, machine-speed "kill webs"**. [[1](https://www.researchgate.net/publication/371220126_Mapping_Artificial_Intelligence_to_the_Naval_Tactical_Kill_Chain), [2](https://timesofindia.indiatimes.com/defence/news/kill-webs-drones-and-less-guesswork-how-indias-armed-forces-are-using-ai-in-combat/articleshow/134543080.cms), [3](https://breakingdefense.com/2025/04/decision-making-at-the-speed-of-relevance-modernizing-the-ooda-loop-for-todays-threats/)]

The primary technological instruments driving this shift across each phase of the loop include:

**1. Observe: Ubiquitous Sensing & Federated Data Fabrics**

Traditionally, a single platform (like a scout plane) observed a target and passed it down a chain. Today, the military uses platform-agnostic sensing networks to ingest billions of data signals simultaneously. [[1](https://www.netscout.com/what-is/jadc2), [2](https://www.youtube.com/watch?v=LyrfrRySL-U&t=26), [3](https://www.airuniversity.af.edu/Portals/10/ASOR/Journals/Volume-2_Number-1/Cantrell.pdf)]

- **Distributed Sensing Grids:** Low-Earth Orbit (LEO) satellite constellations, autonomous unmanned aerial vehicles (UAVs), and passive radio frequency (RF) sensors act as the "eyes and ears" of the battlefield. [[1](https://www.youtube.com/shorts/avTteGr5PII), [2](https://www.airuniversity.af.edu/Portals/10/ASOR/Journals/Volume-2_Number-1/Cantrell.pdf)]
- **Federated Data Fabrics:** Open-architecture frameworks—such as the [**Joint All-Domain Command and Control (JADC2)**](https://www.netscout.com/what-is/jadc2) initiative—treat data as an independent asset. Instead of getting stuck in data silos, raw information from an Army ground sensor, a Navy destroyer, or an Air Force jet is instantly fed into a unified network. [[1](https://www.rti.com/blog/jadc2-the-ooda-loop), [2](https://www.missiledefenseadvocacy.org/defense-systems/joint-all-domain-command-and-control-jadc2/), [3](https://www.netscout.com/what-is/jadc2)]

**2. Orient: AI-Driven Sensor Fusion & Computer Vision**

The "Orient" phase is the biggest historical bottleneck because humans must sift through massive data text, video, and radar feeds. AI instruments now achieve **"Data Fusion"** at the tactical edge. [[1](https://www.leonardodrs.com/news/thought-leadership/how-ai-and-machine-learning-strengthen-defense-sensing-and-mission-systems/), [2](https://www.airuniversity.af.edu/Wild-Blue-Yonder/Articles/Article-Display/Article/3118712/decision-advantage-in-competition/), [3](https://www.netscout.com/what-is/jadc2)]

- **AI Targeting Software:** Platforms like the Pentagon’s [**Maven Smart System**](https://www.cnn.com/2026/05/07/politics/us-military-ai-law-iran) leverage computer vision algorithms to automatically identify, categorize, and track potential military targets across multiple systems simultaneously. [[1](https://www.cnn.com/2026/05/07/politics/us-military-ai-law-iran)]
- **Parallel Edge Computing:** Instruments like [**Leonardo DRS**](https://www.leonardodrs.com/news/thought-leadership/how-ai-and-machine-learning-strengthen-defense-sensing-and-mission-systems/)'s [**SAGEcore™**](https://www.leonardodrs.com/news/thought-leadership/how-ai-and-machine-learning-strengthen-defense-sensing-and-mission-systems/) process radar, passive RF, and infrared intelligence in parallel right on the combat vehicle, instantly mapping out a single, coherent picture of the battlespace despite adversarial camouflage or weather. [[1](https://www.youtube.com/watch?v=vQH-dSEsEfo), [2](https://www.leonardodrs.com/news/thought-leadership/how-ai-and-machine-learning-strengthen-defense-sensing-and-mission-systems/)]
- **Predictive Modeling:** Advanced algorithms cross-reference decades of adversary troop movements with real-time weather and topography apps to predict enemy positions up to 48 hours in advance, allowing forces to anticipate threat positions before they even arrive. [[1](https://www.youtube.com/watch?v=jTgAe_I3Px0), [2](https://timesofindia.indiatimes.com/defence/news/kill-webs-drones-and-less-guesswork-how-indias-armed-forces-are-using-ai-in-combat/articleshow/134543080.cms)]

**3. Decide: Machine-Speed Recommender Systems**

Instead of operators manually calculating how to respond, algorithmic warfare instruments provide instant **triage and course-of-action (COA) recommendations**. [[1](https://assets.kpmg.com/content/dam/kpmgsites/in/pdf/2026/10/battlefield-of-the-future-how-ai-is-transforming-warfare.pdf), [2](https://www.rti.com/blog/the-ooda-loop-in-modern-defense-systems)]

- **Automated Asset-Target Pairing:** AI recommendation engines evaluate all available friendly weapons against identified threats. If an Army command node identifies a threat, the system automatically calculates if an airborne fighter jet, a maritime vessel, or a ground artillery unit is best positioned to neutralize it, presenting the optimal choice to a commander.
- **"Human-on-the-Loop" Supervision:** Command systems are transitioning human operators from being *in* the loop (manually executing every step) to *on* the loop. The software autonomously manages the targeting workflows, reducing the human's role to a rapid "approve/deny" checkpoint for lethal authorization. [[1](https://luftled.info/stuck-between-real-and-ideal-the-ooda-loop-and-military-ai/), [2](https://www.afcea.org/signal-media/cyber-edge/decision-advantage-left-kill-chain), [3](https://www.youtube.com/watch?v=q5f44iXiQws), [4](https://www.airuniversity.af.edu/Portals/10/ASOR/Journals/Volume-2_Number-1/Cantrell.pdf), [5](https://www.missiledefenseadvocacy.org/defense-systems/joint-all-domain-command-and-control-jadc2/), [6](https://www.cnn.com/2026/05/07/politics/us-military-ai-law-iran), [7](https://www.youtube.com/watch?v=jTgAe_I3Px0)]

**4. Act: Mesh Networks & Autonomous Effects**

The final step is the machine-to-machine transfer of data from the sensor directly to the weapon system. [[1](https://www.afcea.org/signal-media/cyber-edge/decision-advantage-left-kill-chain)]

- **Sensor-to-Shooter Automation:** Digital architectures allow an AI targeting system to pass exact fire-control coordinates straight to a missile launcher or artillery unit without voice coordination or manual data entry.
- **Loitering Munitions & Swarms:** Autonomous weapon systems can be launched into an area and dynamically adjust their paths mid-flight based on real-time data updates piped directly into their guidance systems. [[1](https://breakingdefense.com/2025/04/decision-making-at-the-speed-of-relevance-modernizing-the-ooda-loop-for-todays-threats/), [2](https://www.afcea.org/signal-media/cyber-edge/decision-advantage-left-kill-chain), [3](https://www.netscout.com/what-is/jadc2), [4](https://luftled.info/stuck-between-real-and-ideal-the-ooda-loop-and-military-ai/)]

**The Paradigm Shift: From a "Loop" to a "Vector"**

The compounding effect of these instruments is changing the very nature of military strategy. Military scholars note that the OODA loop is collapsing from a *circular, reflective system* that adapts via feedback into a **"predict-act" vector**. By using AI to accurately predict an adversary's actions and immediately executing a counter-response, modern militaries are attempting to bypass the time-consuming process of human deliberation entirely, moving at "machine speed" to paralyze the enemy's ability to react. [[1](https://warroom.armywarcollege.edu/articles/untying-ooda-loop/), [2](https://www.linkedin.com/posts/tim-de-zitter_%3F-%3F%3F%3F%3F%3F%3F-%3F%3F%3F%3F%3F%3F%3F-%3F%3F%3F%3F%3F%3F-activity-7513466894410993664-6lPH), [3](https://www.airuniversity.af.edu/Wild-Blue-Yonder/Articles/Article-Display/Article/3118712/decision-advantage-in-competition/)]

Would you like to explore a specific aspect of this acceleration? For instance, I can provide more details on:

- How the **U.S. JADC2** or **Air Force ABMS** frameworks connect these systems in real-world exercises.
- The **ethical and legal debates** surrounding human-on-the-loop targeting.
- How adversaries use **counter-AI tactics** (like data poisoning) to disrupt this automated process.

## 10 November 2026 — deterrence theory

**Sara's original follow-up question:** “waht does this do in cahnging or not changing/or ahving to update the ucrrent itneiroantl realtions framwork theory, deterrence?”

**Edited for clarity:** If AI-enabled military systems shorten the time between detection and action, under what conditions would that change deterrence and crisis stability between states, and where would existing deterrence theory still explain the outcome?

### Answer:

The collapse of the OODA loop into machine-speed execution presents a profound challenge to traditional **International Relations (IR) frameworks, specifically Deterrence Theory**.

Because traditional deterrence relies heavily on human psychology, communication, and deliberate choice, the introduction of automated, algorithmic warfare is fundamentally rewriting how states prevent—or accidentally start—conflicts.

Here is how these advancements are disrupting, breaking, or forcing updates to current deterrence frameworks.

---

**1. The Crisis of "Rational Actor" Models**

Classical deterrence theory (built by theorists like Thomas Schelling) assumes that states are **rational actors** that make calculated decisions based on cost-benefit analyses.

- **The Reality Shift:** In a machine-speed environment, human cognitive processing becomes the weak link. If a state waits for human deliberation, it loses. Consequently, states are outsourcing the *Orient* and *Decide* phases to AI recommender systems.
- **The IR Impact:** Deterrence now depends on how a machine algorithm calculates risk, rather than how a human statesman does. IR theory must shift from analyzing a leader's psychology to auditing an adversary's algorithmic logic, training data biases, and automated thresholds for escalation.

**2. The Death of Strategic "Pauses" and Communication**

Traditional deterrence relies on signaling. During the Cuban Missile Crisis, the days-long delay in communications allowed both sides to interpret signals, offer off-ramps, and back down.

- **The Reality Shift:** When the kill chain is closed in seconds or minutes, the luxury of time evaporates. If an AI system detects a perceived incoming hypersonic swarm, its automated defensive protocols may trigger immediate retaliatory strikes before a diplomat can even pick up a phone.
- **The IR Impact:** This compresses the **escalation ladder**. IR theory traditionally viewed escalation as a series of deliberate, controllable choices. Machine-speed loops turn escalation into a binary switch—moving from peace to total kinetic conflict instantly, bypassing the possibility of crisis communication.

**3. "Flash Wars" and the Accidental Escalation Trap**

In the financial world, automated trading algorithms occasionally interact in unexpected ways, causing a catastrophic "flash crash" in milliseconds. IR theorists are deeply worried about the military equivalent: **Flash Wars**.

- **The Reality Shift:** If Nation A's automated sensor-to-shooter web interacts with Nation B's automated defensive web, a minor glitch, a misinterpretation of a routine training exercise, or a minor cyber skirmish could trigger an autonomous chain reaction of strikes and counter-strikes.
- **The IR Impact:** Deterrence theory is ill-equipped for automated spirals. Traditionally, deterrence fails because an aggressor *chooses* to strike. In a flash war scenario, deterrence fails purely due to **systemic interaction**. IR frameworks must adapt to account for "systemic stability" between competing algorithms, rather than just political intent.

**4. Entanglement: Conventional and Nuclear Blur**

Closing the kill chain requires ubiquitous sensing. These "eyes and ears" grids do not distinguish well between a nation's conventional military assets and its strategic nuclear deterrent.

- **The Reality Shift:** As JADC2-style frameworks automatically map out an adversary's entire military posture to optimize targeting paths, they inadvertently target or threaten nuclear command and control (NC2) nodes, early-warning radars, or mobile missile launchers.
- **The IR Impact:** An adversary may interpret a highly efficient, automated conventional operation as a preemptive strike against their nuclear arsenal. This **entanglement** creates a "use-it-or-lose-it" dilemma, drastically lowering the threshold for nuclear escalation and breaking the firewall that deterrence theory historically placed between conventional and nuclear conflict.

**5. From "Punishment" to "Denial via Automation"**

Historically, deterrence is split into two categories:

1. **Deterrence by Punishment:** Threatening to inflict unacceptable costs on the enemy if they attack (e.g., Mutually Assured Destruction).
2. **Deterrence by Denial:** Making an attack so difficult and costly to execute that the enemy doesn't bother trying.

- **The Reality Shift:** Because machine-speed kill webs are designed to completely paralyze an attacker’s offensive capabilities instantly, the focus is shifting heavily toward **extreme Deterrence by Denial**.
- **The IR Impact:** While this sounds stabilizing, it actually creates a fierce arms race. If Nation A believes its automated kill web can deny any attack, it may become emboldened and aggressive. Conversely, Nation B, fearing its offensive capabilities are entirely nullified, may feel pressured to strike first before Nation A’s system becomes fully impenetrable.

---

**The Ultimate Update: "Algorithmic Deterrence"**

International Relations theory is forced to pivot from **structural realism** (focused on the balance of physical power) to **cybernetic/algorithmic realism**.

Deterrence in the 21st century is no longer just about who has the biggest missile or the most soldiers; it is about **whose network architecture possesses the superior processing speed, data integrity, and algorithmic resilience.**

To explore how this impacts global stability further, would you like to look into:

- **"Algorithmic Arms Control":** Is it possible to create treaties or verification mechanisms for AI-driven kill chains?
- **The Stability-Instability Paradox:** How automated conventional superiority might paradoxically make nuclear brinkmanship more appealing to weaker states.
- **Specific case studies:** How these compressed loops are affecting the geopolitical dynamics between the US and China in the Taiwan Strait.

## Research handling

The two answers above are preserved as supplied research material, including their claims and links. Their sources and factual assertions have not been independently verified for this ledger. The questions remain open; no theory revision or case is selected. A useful next step is to choose one documented system and decision episode, measure which part of the process changes, and distinguish its observed operation from claims about strategic effects. The [broader ledger](../RESEARCH_LEDGER.md) tracks Q22 and Q25–Q26.
