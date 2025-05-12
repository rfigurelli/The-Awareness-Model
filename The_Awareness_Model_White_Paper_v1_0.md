# The Awareness Model: Layered Cognition in Real and Artificial Agents

**White Paper v1.0.4**  
**Author:** Rogério Figurelli  
**Date:** May 11, 2025

## Executive Summary

This white paper introduces a novel layered model that delineates the relationships among the brain’s physiology, the mind’s cognitive processes, and the emergence of consciousness. To demonstrate the model's real-world utility, three applied scenarios are explored: a virtual assistant interacting with a driver, a clinician coordinating with an AI in a hospital, and an asymmetric awareness situation on an airplane between an awake and a sleeping passenger.

This white paper introduces a novel layered model that delineates the relationships among the brain’s physiology, the mind’s cognitive processes, and the emergence of consciousness. By organizing these elements into hierarchical levels, the framework clarifies how different states of awareness arise and interact in both biological and artificial systems.

The model distinguishes between unconscious (U₀–U₂), preconscious (C₁–C₃), and conscious (C₄–C₇) layers, each associated with specific neural substrates and functional roles. This stratification enables precise mapping of cognitive activities, from basic sensory processing to self-reflective thought.

A core proposition is the model’s applicability to artificial intelligence development. By mirroring human cognitive layering, AI architectures can support graded awareness and feedback loops, fostering more realistic, adaptive, and human-like behavior in autonomous agents.

The framework also addresses state-dependent interactions—such as awake, asleep, or impaired conditions—demonstrating how communication channels between agents open or close based on each entity’s level activation. These insights inform therapeutic approaches, human–machine interfaces, and multi-agent coordination.

Comparative analysis with established theories (Global Workspace, Integrated Information, Predictive Coding \[4] \[4]) reveals that this model’s explicit hierarchical structuring and state‐conditional channels offer a unique perspective, complementing existing neurocognitive paradigms.

Finally, the white paper outlines architectural guidelines and use cases, spanning neuroscience research, AI implementation, robotics, and speculative applications like artificial consciousness and brain–computer integration, underscoring the model’s versatility and innovative potential.

## 1. Introduction

The layered model is not only a theoretical framework but also a practical tool, as illustrated in three use-case scenarios later in this paper. These examples provide tangible demonstrations of how each layer functions across contexts—autonomous driving, clinical collaboration, and mixed-consciousness social environments.

The exploration of how the brain’s physical structures give rise to mental processes and conscious experience remains a central challenge in cognitive science. Traditional approaches often treat these domains separately, hindering holistic understanding \[1]\[2].

This white paper proposes a unified layered model that integrates neural substrates, cognitive functions, and conscious awareness within a single framework. By defining explicit layers, we aim to bridge gaps between biology, psychology, and computational design.

The framework draws inspiration from the brain’s hierarchical organization, where lower regions handle basic sensory and reflexive tasks while higher cortical areas support complex reasoning and self‐reflection. Translating this into a conceptual stack facilitates clarity \[6].

Moreover, the model incorporates dynamic state changes—awake, asleep, or impaired—to reflect real-world conditions. This allows for analysis of phenomena such as sleep cognition, anesthesia, and disorders of consciousness within the same structure.

A critical advantage is the model’s direct applicability to artificial intelligence. By implementing analogous layers and feedback loops, AI systems can achieve more nuanced perception, decision‐making, and social interaction capabilities, closer to human‐like consciousness \[7].

Finally, this introduction outlines the paper’s organization: problem statement, proposed solutions, core principles, comparative analysis, architecture overview, use cases, and references, providing a roadmap for researchers and practitioners.

## 2. Problem Statement

The model is applied to three illustrative cases, revealing how the lack of structured cognitive layering hinders effective human–machine collaboration, especially when agents are in different awareness states or roles. For instance, coordination between an alert driver and a virtual assistant requires precise attention management across layers, just as in a clinical setting where a physician and AI collaborate in real time.

Despite advances in neuroscience and artificial intelligence, there is no widely adopted framework that simultaneously models the brain’s physiology, the mind’s algorithmic processes, and the emergence of conscious awareness in a hierarchical, state‐dependent manner.

This gap impedes our ability to design AI systems that authentically replicate human cognitive and social behaviors, as most architectures lack explicit layering of unconscious, preconscious, and conscious functions.

Furthermore, therapeutic interventions for disorders of consciousness and sleep‐related cognitive dysfunctions suffer from fragmented models that fail to capture inter‐level dynamics and agent‐to‐agent communication constraints under varying states.

A comprehensive model is needed to standardize analysis across research, clinical, and engineering domains, enabling consistent mapping of cognitive phenomena and guiding the development of next‐generation AI and neurotechnology.

## 3. Proposed Solutions

These solutions are not abstract—they are mapped to operational contexts in this paper’s scenarios. Whether it’s enhancing driver-vehicle interaction, supporting diagnostics in medicine, or interpreting interpersonal dynamics in public spaces, each principle (e.g., layer segmentation, communication gating, and biological plausibility) is exemplified in detail.

1. **Hierarchical Layer Definition:** Segregate cognitive functions into three main tiers—Unconscious (U₀–U₂), Preconscious (C₁–C₃), and Conscious (C₄–C₇)—each with delineated roles and neural correlates.
2. **State‐Dependent Activation:** Define global states (Awake, Asleep, Impaired) that modulate layer activation thresholds.
3. **Directional Communication Channels:** Model inter‐agent interactions via directed channels at each layer.
4. **Biological Plausibility \[6]:** Ground each layer in empirical neuroscience findings.
5. **Artificial Implementation Blueprint:** Provide guidelines for embedding the model into AI systems.
6. **Therapeutic Mapping:** Link layer dysfunctions to clinical symptoms and behaviors.
7. **Multi‐Agent Coordination:** Optimize communication across agents with different states.
8. **Scalability:** Ensure the framework works from individual agents to large networks.
9. **Validation Framework:** Outline experimental methods to test the model.
10. **Ethical Considerations:** Examine the implications of building layered AI consciousness.

## 4. Core Principles and the Wisdom Equation

Before delving into real-world scenarios, it's useful to preview the table-based schema that underpins this layered model. The model is structured as a matrix with each row corresponding to a cognitive layer (from U₀ to C₇) and each column representing agent-environment interactions. These include:

* **Environment A / B**: External conditions perceived by Agent A and Agent B
* **Channel A / B**: Input/output modalities (e.g., sensory signals, motor outputs)
* **Person A / B**: Internal processing at a given cognitive level
* **Channel X**: Communication bridge between agents at the same level

This framework enables side-by-side comparison of how two agents engage across cognitive layers. Here is a blank template of the table used in scenario modeling:

```markdown
|------------|-------|-----------------------------|-----------|---------------------|------------------|------------------------|----------------|--------------------------|
| Domain     | Level | Environment A               | Channel A | Person A            | Channel X        | Person B               | Channel B      | Environment B            |
|------------|-------|-----------------------------|-----------|---------------------|------------------|------------------------|----------------|--------------------------|
| —          | State |                             |           |                     |                  |                        |                |                          |
| Conscious  | C₇    |                             |           |                     |                  |                        |                |                          |
| Conscious  | C₆    |                             |           |                     |                  |                        |                |                          |
| Conscious  | C₅    |                             |           |                     |                  |                        |                |                          |
| Mind       | C₄    |                             |           |                     |                  |                        |                |                          |
| Mind       | C₃    |                             |           |                     |                  |                        |                |                          |
| Mind       | C₂    |                             |           |                     |                  |                        |                |                          |
| Mind       | C₁    |                             |           |                     |                  |                        |                |                          |
| Brain      | U₂    |                             |           |                     |                  |                        |                |                          |
| Brain      | U₁    |                             |           |                     |                  |                        |                |                          |
| Brain      | U₀    |                             |           |                     |                  |                        |                |                          |
|------------|-------|-----------------------------|-----------|---------------------|------------------|------------------------|----------------|--------------------------|
```

This matrix is a flexible analytical tool that supports both diagnostic modeling and AI system design. Each cell in the matrix reflects the role or signal present at a particular cognitive layer and side of interaction (Agent A or B, or their environment). For example:

* At level **C₅**, 'Person A' might show 'Typing intention', while 'Person B' might indicate 'Route re-evaluation', reflecting internal processes in a digital assistant scenario.
* At level **U₁**, 'Channel A' could be 'Odor' from a nearby coffee cup, while 'Person A' might show 'Comfort tagging', indicating subconscious affective processing.
* At level **C₂**, both agents might activate 'Alert detection' and 'Engine noise processing', respectively, if a sudden vehicle vibration is detected.

The **'Environment A/B'** columns reflect external stimuli such as 'Dashboard lights', 'In-flight menus', or 'Hospital monitors'. The **'Channel A/B'** columns capture how each agent receives or sends information—via keyboard input, tactile feedback, or visual symbols. The **'Channel X'** column denotes any level-specific exchange of information or signaling between agents—such as a spoken command, gesture, or digital data packet.

Through this format, the table allows us to observe how two entities—human or artificial—are differently or jointly engaged across various cognitive functions and levels of awareness. It becomes especially useful when comparing states (e.g., one awake, one asleep) or roles (e.g., clinician vs. AI assistant) to assess opportunities for synchrony, conflict, or support. In the next section, we fill in this structure with real-world examples, demonstrating its versatility and insight across diverse applications.

This section outlines the foundational logic and mathematical grounding for the layered model. Each principle captures a different aspect of how consciousness and cognition emerge from structured levels, modulated by internal and external factors.

### 4.1 Layered Reflection: Intelligence as Structure

Higher cognition emerges through the activation of increasingly abstract layers that build on the outputs of more primitive layers. Cognitive phenomena like planning or introspection are not isolated—they depend on the activity and integrity of lower layers.

### 4.2 Dynamic Modulation: Consciousness as Activation

Global states (Awake, Asleep, Impaired) alter the activation thresholds and responsiveness of each layer. This is formally represented by the following equation:

**Layer Activation Function**
Aᵢ = Θ(σᵢ − θᵢ(S))

Where:

* Aᵢ ∈ {0, 1}: binary activation of layer i
* Θ: Heaviside step function
* σᵢ: input salience score
* θᵢ(S): activation threshold modulated by state S

This models how certain layers deactivate during sleep or impairment and reactivate when sufficient input salience is reached.

**Addressing the Hard Problem of Consciousness**

While the hard problem of consciousness—as posed by Chalmers [9]—raises questions about how and why subjective experience arises from physical processes, the proposed model introduces a quantitative pathway to approach this issue. By explicitly modeling activation thresholds (θᵢ) and input salience (σᵢ) across hierarchical cognitive layers, the framework offers a structured mechanism to correlate qualitative states (such as introspection, agency, or qualia) with measurable neural and computational dynamics. Although it does not claim to solve the hard problem, this formalization narrows the gap between first-person phenomenology and third-person data by providing an operational map where conscious content emerges only when layered activation surpasses context-dependent thresholds. This layered activation logic allows for testable predictions and artificial simulations that can gradually illuminate the mechanisms underpinning subjective awareness.

### 4.3 Reciprocal Interaction

Cognitive processes depend on feedback mechanisms both within and between layers. Lower layers feed data upward (e.g., sensory signals), while higher layers return modulating influence (e.g., predictions, decisions). These feedback loops sustain coherence and adaptability.

### 4.4 Translational Applicability: Toward Wisdom

The layered model is designed for real-world impact, bridging the gap between cognitive science theory and applied engineering. It translates seamlessly into various domains:

* **In neuroscience**, it provides a framework to model disorders of consciousness by mapping functional deficits to specific cognitive layers. The U₀–C₇ stratification allows researchers to isolate disruptions in reflexes, memory, attention, or higher-level self-awareness.
* **In artificial intelligence**, it guides the design of modular systems with embedded awareness. Each cognitive function is compartmentalized, allowing machine agents to mirror human-like perception, memory, focus, and metacognition.
* **In clinical diagnostics**, the model helps decode behavioral symptoms (e.g., anosognosia, ADHD, vegetative states) through mapped dysfunctions in layers like C₂ (attention) or C₆ (self-monitoring).
* **In human–machine interaction**, interfaces can be dynamically tailored based on the active cognitive layer of the user—alerting, suppressing, or augmenting signals depending on whether the user is focused, distracted, or fatigued.

These applications are exemplified in this paper’s scenarios: an autonomous driver with a virtual assistant, a physician collaborating with a medical AI, and a shared airplane cabin between two passengers in different global states.

The relationship among these components—structure (intelligence), dynamic modulation (consciousness), and applied benefit—can be synthesized as the Equation of Wisdom \[8]:

**W = I^C**

Where:

* **W** = Wisdom, the outcome of layered intelligence modulated by conscious integration.
* **I** = Intelligence, defined as the system’s cognitive structure and processing depth.
* **C** = Consciousness, acting as a multiplier or amplifier based on self-awareness and state sensitivity.

This expression aligns with the model’s premise: true autonomy and ethical sophistication arise not merely from raw processing power, but from calibrated consciousness that governs when and how that intelligence is applied across layers and states. involving an autonomous driver with a virtual assistant, a physician collaborating with a medical AI, and asymmetric awareness in shared environments like airplanes.

## 5. Comparative Analysis

This model integrates ideas from several cognitive and neuroscience theories but introduces a structured, original approach through explicit layering, global state modulation, and inter-agent cognitive communication. The table below highlights how this model compares to well-known frameworks:

| Model                                             | Structured Layers | Global State Modulation | Inter-Agent Communication | Practical Applications |
| ------------------------------------------------- | ----------------- | ----------------------- | ------------------------- | ---------------------- |
| **Proposed Layered Model**                        | ✅                 | ✅                       | ✅                         | ✅                      |
| Global Workspace Theory (Baars, Dehaene) \[1]\[2] | ⚠️ Partial        | ✅                       | ❌                         | ✅                      |
| Integrated Information Theory (Tononi) \[3]       | ❌                 | ⚠️ Implicit             | ❌                         | ⚠️ Limited             |
| Predictive Coding (Friston) \[4]                  | ⚠️ Implicit       | ✅                       | ❌                         | ✅                      |
| Layered Reference Model (Wang)                    | ✅                 | ⚠️ Implicit             | ❌                         | ✅                      |
| Society of Mind (Minsky)                          | ⚠️ Modular        | ❌                       | ⚠️ Partial                | ✅                      |

**Key Advantages of This Model:**

* Integrates biological grounding and computational clarity.
* Explicitly models global state transitions (e.g., awake/asleep/impaired).
* Supports agent-to-agent information flow conditioned on cognitive layer alignment.
* Designed for direct application in neuroscience, AI, diagnostics, and robotics.

This comprehensive, integrative design distinguishes the proposed model and enables it to serve as both a conceptual and practical framework for layered cognition in both biological and artificial systems.

## 6. Architecture Overview

The architecture consists of the following modules:

* **U₀–U₂ (Brain):** Reflexes, presence detection, pattern routines
* **C₁–C₃ (Mind):** Memory, attention, language/representation
* **C₄–C₇ (Consciousness):** Focus, planning, narrative, self-monitoring
* **State Manager:** Regulates activation thresholds
* **Communication Bus:** Connects layers and agents through directed channels

## 7. Layered Model and Illustrative Scenarios

The layered model is structured across eleven distinct levels, from U₀ to C₇, each corresponding to specific cognitive or neural functions. These levels are grouped into three primary domains:

* **Brain (U₀–U₂)**: Unconscious processing and reflexive responses.
* **Mind (C₁–C₃)**: Preconscious mechanisms such as memory, attention, and symbolic understanding.
* **Consciousness (C₄–C₇)**: Higher-order processes including planning, self-monitoring, and metacognition.

Each layer can be engaged or disengaged depending on the global state (e.g., awake, asleep, impaired), and each may interact with internal modules or external agents via directed communication channels. The tables below illustrate how this model operates in two applied domains.

### Scenario 1: Virtual Assistant and Autonomous Driver Interaction

This scenario models a dual-agent cognitive interaction in a real-world driving context enhanced by a virtual assistant. Person A (the driver) is operating a vehicle while simultaneously interacting with a digital assistant for tasks like email review and navigation. Person B (the assistant) is implemented as an artificial agent with layered awareness, responding in real time based on user inputs and contextual cues.

The assistant's cognitive layers (especially C₅–C₇) engage in planning and interpreting human input, while the driver exhibits awareness of both road and digital cues. This situation demonstrates the value of separating layer-dependent communication—highlighting how focus, attention, and context switching are modulated differently between human and machine.

```markdown
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
| Domain     | Level | Environment A               | Channel A | Person A           | Channel X       | Person B               | Channel B     | Environment B           |
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
| —          | State | Virtual                     | On        | Awake              | On               | Awake                  | Idle           | Real                     |
| Conscious  | C₇    | Email client UI headline    | —         | Internal narrative | —                | Driving plan update    | —              | In-dash nav summary      |
| Conscious  | C₆    | Inbox folder list           | —         | Self-monitoring    | —                | Hazard anticipation    | —              | Turn-by-turn prompt      |
| Conscious  | C₅    | Draft window with cursor    | Keyboard  | Typing intention   | Think (A → B)    | Route re-evaluation    | ← GPS          | Map display on HUD       |
| Mind       | C₄    | Focused text field          | —         | Attention spotlight| —                | Road scanning          | —              | Forward road view        |
| Mind       | C₃    | Visible keyboard keys       | Visual    | Symbolic parsing   | —                | Traffic sign recognition| ← Windshield  | Road ahead               |
| Mind       | C₂    | Notification chime          | Audio     | Alert detection    | Look (A ↔ B)     | Engine noise processing| ← Engine       | Engine vibration         |
| Mind       | C₁    | Recent email tooltip        | —         | Context recall     | —                | Route memory recall    | —              | GPS “next turn” recall   |
| Brain      | U₂    | Chair cushion pressure      | —         | Postural reflex    | Talk (A ↔ B)     | Grip adjustment        | ← Steering     | Steering feedback        |
| Brain      | U₁    | Coffee aroma from mug       | Odor      | Comfort tagging    | —                | Wind smell perception  | ← Exhaust      | Exhaust fumes            |
| Brain      | U₀    | Screen backlight glow       | Light     | Presence detection | —                | Dashboard monitoring   | ← Dashboard    | Dash illumination        |
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
```

This table demonstrates how two agents (one human and one artificial) operate across different cognitive levels while interacting in real time. Despite both being in an “awake” state, their cognitive bandwidth, processing modalities, and reflex-response mechanisms differ, illustrating the layered model's power in capturing such asymmetries.

### Scenario 2: Hospital Care with Medical AI Support

This scenario captures a high-stakes collaborative interaction between a human clinician (Person A) and an advanced medical AI system (Person B). The setting is a hospital, where real-time decisions based on vital signs, test results, and patient history must be made. The physician dynamically engages across nearly all cognitive layers, interpreting complex stimuli and drawing from memory, reasoning, and internal narratives. Meanwhile, the AI system operates across its own functional layers—processing structured data, generating suggestions, and communicating outputs through natural language channels.

The table below illustrates the alignment and differences in how layers are activated and interact between the two agents. This use case underscores the model’s strength in modeling inter-agent cognition and highlights how AI can provide meaningful support when properly structured within layered awareness logic.

```markdown
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
| Domain     | Level | Environment A               | Channel A | Person A           | Channel X       | Person B              | Channel B     | Environment B             |
|------------|-------|-----------------------------|-----------|---------------------|------------------|------------------------|----------------|----------------------------|
| —          | State | Hospital                    | On        | Awake              | On               | Alert                 | Connected      | ICU Monitor               |
| Conscious  | C₇    | Patient chart summary       | Voice     | Diagnostic planning| → Query          | AI reasoning engine    | ← NLP Module | Diagnostic suggestions     |
| Conscious  | C₆    | Recent test results          | —         | Hypothesis testing | → Context       | Pattern matcher       | ← Record system | Prior symptom history     |
| Conscious  | C₅    | Prescription notes           | Keyboard  | Instruction creation| Think (A → B)    | Dosage calculator      | ← Pharmacology | Medication database       |
| Mind       | C₄    | Visual inspection of patient | Visual    | Clinical focus     | → Attention      | Vital anomaly alert   | ← Sensor       | Skin/motor response       |
| Mind       | C₃    | Label on blood sample        | Visual    | Code recognition   | —                | Sample classification | ← Database     | Blood test thresholds     |
| Mind       | C₂    | Beeping from ECG             | Audio     | Risk detection     | ↔ Monitor Link  | Tachycardia detection | ← Sensor       | Heartbeat rhythm          |
| Mind       | C₁    | Previous case memory         | —         | Recall patterns    | —                | Case base reference   | ← DB Query    | Past patient data         |
| Brain      | U₂    | Chair tilt while examining   | Touch     | Balance reflex     | Talk (A ↔ B)     | Grasp tool adjustment | ← Arm sensor   | Robotic arm feedback      |
| Brain      | U₁    | Alcohol scent detection       | Odor      | Infection alert    | —                | Contamination analysis| ← Chem sensor  | Airborne samples          |
| Brain      | U₀    | Monitor glow at night        | Light     | Presence recognition| —                | Ambient status update | ← Light sensor | Room lighting              |
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
```

This table demonstrates how structured inter-agent communication and decision-making can be mapped onto layered cognitive processes, enabling traceability and better interface design in clinical environments.

### Scenario 3: Awake Passenger and Sleeping Companion on an Airplane

This scenario presents a common yet cognitively asymmetric context: one individual (Person A) is fully awake during a flight and actively engaged with their internal and external environment, while their adjacent companion (Person B) is asleep. The model is useful here to distinguish how communication, sensory intake, and mental processing diverge across both agents due to their respective global states (Awake vs. Asleep).

The awake individual exhibits activity in conscious and preconscious layers, interacting with the flight environment, making decisions, and optionally attempting low-level communication with the sleeping partner. Meanwhile, the sleeping person operates predominantly within unconscious layers, with reduced responsiveness and internal state dynamics (e.g., REM dreaming, postural adjustments).

```markdown
|------------|-------|-----------------------------|-----------|--------------------|------------------|-------------------------|----------------|--------------------------|
| Domain     | Level | Environment A              | Channel A | Person A            | Channel X       | Person B             | Channel B     | Environment B           |
|------------|-------|-----------------------------|-----------|--------------------|------------------|------------------------|----------------|--------------------------|
| —          | State | Airplane cabin              | On        | Awake              | —                | Asleep                | Off            | Ambient engine hum       |
| Conscious  | C₇    | Travel itinerary            | —         | Internal planning  | —                | Dreamlike imagery     | —              | Subconscious content     |
| Conscious  | C₆    | In-flight menu              | Visual    | Reflective choice  | —                | —                     | —              | —                        |
| Conscious  | C₅    | Booking confirmation email  | Memory    | Recall details     | Whisper (A → B)  | No conscious access   | —              | —                        |
| Mind       | C₄    | Armrest button panel        | Tactile   | Manual control     | —                | REM signals           | —              | Sleep physiology         |
| Mind       | C₃    | Overhead sign               | Visual    | Symbol recognition | —                | —                     | —              | —                        |
| Mind       | C₂    | Cabin crew announcement     | Auditory  | Alert parsing      | —                | Partial processing     | —              | Auditory residue         |
| Mind       | C₁    | Seatbelt light memory       | —         | Habit recall       | —                | —                     | —              | —                        |
| Brain      | U₂    | Seat pressure               | Touch     | Postural shift     | Shared (U)       | Breathing adjustment   | —              | Reclined posture         |
| Brain      | U₁    | Coffee aroma in cabin       | Odor      | Comfort tagging    | —                | Reduced olfactory      | —              | Neutral stimuli          |
| Brain      | U₀    | Cabin lighting dimmed       | Light     | Circadian sync     | —                | Sleep initiation       | —              | Cabin atmosphere         |
|------------|-------|-----------------------------|-----------|---------------------|------------------|-------------------------|----------------|--------------------------|
```

This table illustrates how the awake passenger maintains full sensory and cognitive engagement, ranging from planning (C₇) to comfort-based tagging (U₁), while the sleeping companion shows muted input-output dynamics. The scenario highlights the importance of state-aware inter-agent modeling, especially in shared environments where communication potential depends on both parties’ activation layers.

## 8. Use Cases

This section categorizes how the layered model is being or could be applied across various domains. Each application demonstrates how different layers support specific types of decision-making, perception, or communication depending on state and scenario.

### Current Applications

* **Neuroscience Research Platforms:** Simulate or analyze how different brain states (e.g., sleep, coma, anesthesia) affect layer activity and consciousness.
* **Cognitive Robotics:** Design robots that modulate behavior and awareness using unconscious, preconscious, and conscious-like tiers.
* **Clinical Diagnostics:** Improve interpretation of cognitive and neurological disorders by mapping symptoms to specific layer disruptions.
* **Human–Machine Interfaces:** Create adaptive interfaces that respond to the user’s active cognitive layer (e.g., switching to simpler prompts when user attention is low).

### Future and Speculative Applications

* **Artificial Consciousness Agents**
* **Brain–Computer Symbiosis**
* **Adaptive Education Systems**
* **Augmented Reality Interfaces**

## 9. References

\[1] Baars, B. J. (1988). *A Cognitive Theory of Consciousness*. Cambridge University Press.

\[2] Dehaene, S., & Naccache, L. (2001). Toward a cognitive neuroscience of consciousness: basic evidence and a workspace framework. *Cognition*, 79(1–2), 1–37.

\[3] Tononi, G. (2004). An information integration theory of consciousness. *BMC Neuroscience*, 5(1), 42.

\[4] Friston, K. (2010). The free-energy principle: a unified brain theory? *Nature Reviews Neuroscience*, 11(2), 127–138.

\[5] Weng, J. (2022). A Developmental Network Model of Conscious Learning in Biological Brains. *IEEE Transactions on Cognitive and Developmental Systems*, 14(1), 1–12.

\[6] Grossberg, S. (2021). *Conscious Mind, Resonant Brain: How Each Brain Makes a Mind*. Oxford University Press.

\[7] Hawkins, J. (2004). *On Intelligence*. Times Books.

\[8] Figurelli, R. (2024). *The Equation of Wisdom: An Intuitive Approach to Balancing AI and Human Values*. Kindle Edition.

\[9] Chalmers, D. J. (1995). Facing up to the problem of consciousness. *Journal of Consciousness Studies*, 2(3), 200–219.

## 10. License

Creative Commons Attribution 4.0 International (CC BY 4.0)
© 2025 Rogério Figurelli. This is a conceptual framework provided “as is” without warranty.
