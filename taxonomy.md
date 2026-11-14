# Conceptual Taxonomy & OntoLogic Class Hierarchy

- **Total Taxonomy Categories:** 25
- **Top-Level Root Domains:** 5
- **Canonical Concepts Cataloged:** 30
- **Total Corpus Documents Indexed:** 45

## 1. Taxonomy Hierarchy Summary Table

| Category Path | OntoLogic Class URI | Technology Area | Linked Docs | Linked Chunks |
|---|---|---|---|---|
| **Hardware & Semiconductor Systems** | `ontologic:HardwareSemiconductorSystems` | Semiconductor Engineering | 30 | 72 |
| **Hardware & Semiconductor Systems > AI Accelerators** | `ontologic:AIAccelerators` | AI Hardware Accelerators | 21 | 37 |
| **Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors** | `ontologic:BuiltInPerformanceMonitors` | On-Chip Telemetry & Runtime Monitoring | 10 | 20 |
| **Hardware & Semiconductor Systems > Memory & Interconnects** | `ontologic:MemoryAndInterconnects` | Memory Subsystems & Chiplets | 15 | 23 |
| **Hardware & Semiconductor Systems > EDA & Hardware Verification** | `ontologic:EDAAndVerification` | Electronic Design Automation | 22 | 49 |
| **Hardware & Semiconductor Systems > EDA & Hardware Verification > Formal Verification Languages & Assertions** | `ontologic:FormalVerificationLanguages` | Formal Verification & Specification Languages | 13 | 31 |
| **Security & Resilience** | `ontologic:SecurityAndResilience` | Hardware & AI Security | 39 | 96 |
| **Security & Resilience > Hardware Fault Attacks > Bit-Flip Attacks** | `ontologic:BitFlipAttacks` | Adversarial Fault Injection | 7 | 15 |
| **Security & Resilience > Memory Safety & Software Capabilities** | `ontologic:MemorySafetySoftwareCapabilities` | Language & Runtime Memory Safety | 13 | 21 |
| **Security & Resilience > Runtime Fault Localization & Recovery** | `ontologic:RuntimeFaultLocalizationRecovery` | Self-Healing & Fault-Tolerant AI | 12 | 16 |
| **Artificial Intelligence & Machine Learning** | `ontologic:ArtificialIntelligenceMachineLearning` | AI & Machine Learning | 31 | 74 |
| **Artificial Intelligence & Machine Learning > Deep Neural Networks** | `ontologic:DeepNeuralNetworks` | Deep Learning Architectures | 29 | 54 |
| **Artificial Intelligence & Machine Learning > Deep Neural Networks > Language Models & Efficient Attention** | `ontologic:LanguageModelsAndAttention` | Large Language Models & Attention Mechanisms | 2 | 2 |
| **Artificial Intelligence & Machine Learning > Deep Neural Networks > Novel & State-Space Architectures** | `ontologic:NovelAndStateSpaceArchitectures` | Alternative & State-Space Architectures | 4 | 6 |
| **Artificial Intelligence & Machine Learning > Reasoning, Agents & Retrieval** | `ontologic:ReasoningAgentsAndRetrieval` | Agentic Systems & Reasoning | 19 | 26 |
| **Artificial Intelligence & Machine Learning > Interpretability, Calibration & Evaluation** | `ontologic:InterpretabilityAndEvaluation` | Mechanistic Interpretability & Model Evaluation | 0 | 0 |
| **Artificial Intelligence & Machine Learning > Probabilistic, Diffusion & Multimodal Vision** | `ontologic:ProbabilisticDiffusionAndVision` | Multimodal Vision & Probabilistic Generative Models | 3 | 3 |
| **Security & Resilience > AI Alignment, Guardrails & Agent Security** | `ontologic:AIAlignmentAndAgentSecurity` | AI Alignment & Agentic Security | 17 | 36 |
| **AI Policy, Governance & Human-AI Systems** | `ontologic:AIPolicyGovernanceAndHumanAI` | AI Governance, Policy & Human-AI Interaction | 2 | 3 |
| **Formal Methods & Automated Reasoning** | `ontologic:FormalMethodsAutomatedReasoning` | Automated Reasoning & Mathematical Logic | 29 | 65 |
| **Formal Methods & Automated Reasoning > Neuro-Symbolic Deduction & Guardrail Verification** | `ontologic:NeuroSymbolicDeductionAndVerification` | Neuro-Symbolic Logic & Neural Verification | 6 | 17 |
| **Formal Methods & Automated Reasoning > SAT & SMT Solvers** | `ontologic:SATAndSMTSolvers` | SAT & SMT Decision Procedures | 13 | 22 |
| **Formal Methods & Automated Reasoning > SAT & SMT Solvers > Software Verification & Symbolic Execution** | `ontologic:SoftwareVerificationSymbolicExecution` | Software Verification & Program Analysis | 6 | 9 |
| **Formal Methods & Automated Reasoning > SAT & SMT Solvers > Graph Theory Modulo Theories** | `ontologic:GraphTheoryModuloTheories` | Graph Analysis & Combinatorial Optimization | 4 | 7 |
| **Formal Methods & Automated Reasoning > Knowledge Representation & Ontologies** | `ontologic:KnowledgeRepresentationOntologies` | Ontologies & Description Logic | 13 | 18 |

## 2. Detailed Category Breakdown & Linked Documents

### Hardware & Semiconductor Systems (`ontologic:HardwareSemiconductorSystems`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems`
- **Parent Category:** `Root Domain`
- **Technology Area:** Semiconductor Engineering
- **Description:** Integrated circuits, semiconductor manufacturing nodes, and hardware architectures.
- **Linked Documents (30):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### AI Accelerators (`ontologic:AIAccelerators`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems > AI Accelerators`
- **Parent Category:** `Hardware & Semiconductor Systems`
- **Technology Area:** AI Hardware Accelerators
- **Description:** Specialized hardware datapaths and neural engines for executing AI workloads.
- **Linked Documents (21):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Built-in Performance Monitors (`ontologic:BuiltInPerformanceMonitors`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors`
- **Parent Category:** `Hardware & Semiconductor Systems > AI Accelerators`
- **Technology Area:** On-Chip Telemetry & Runtime Monitoring
- **Description:** Lightweight on-chip telemetry counters and runtime monitors integrated into accelerator datapaths.
- **Linked Documents (10):**
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Memory & Interconnects (`ontologic:MemoryAndInterconnects`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems > Memory & Interconnects`
- **Parent Category:** `Hardware & Semiconductor Systems`
- **Technology Area:** Memory Subsystems & Chiplets
- **Description:** On-package memory, DRAM/SRAM subsystems, and die-to-die interconnects.
- **Linked Documents (15):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### EDA & Hardware Verification (`ontologic:EDAAndVerification`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems > EDA & Hardware Verification`
- **Parent Category:** `Hardware & Semiconductor Systems`
- **Technology Area:** Electronic Design Automation
- **Description:** Electronic design automation, logic synthesis, formal semantics, and verification.
- **Linked Documents (22):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)

### Formal Verification Languages & Assertions (`ontologic:FormalVerificationLanguages`)

- **Full Hierarchy Path:** `Hardware & Semiconductor Systems > EDA & Hardware Verification > Formal Verification Languages & Assertions`
- **Parent Category:** `Hardware & Semiconductor Systems > EDA & Hardware Verification`
- **Technology Area:** Formal Verification & Specification Languages
- **Description:** Hardware specification, assertion, and formal modeling languages (SVA, PSL, UCLID5, Kami, ChiselFV) and automated assertion synthesis.
- **Linked Documents (13):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Security & Resilience (`ontologic:SecurityAndResilience`)

- **Full Hierarchy Path:** `Security & Resilience`
- **Parent Category:** `Root Domain`
- **Technology Area:** Hardware & AI Security
- **Description:** System security, adversarial threat modeling, and fault resilience.
- **Linked Documents (39):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2508.00500`](index.html#doc=arxiv-2508.00500) — [ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.19356`](index.html#doc=arxiv-2607.19356) — [NEXUS: Structured Runtime Safety for Tool-Using LLM Agents](https://arxiv.org/abs/2607.19356) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-backslash-agentic-endpoint-security-top7`](index.html#doc=note-2026-backslash-agentic-endpoint-security-top7) — [Top 7 Agentic Endpoint Security Companies CISOs Should Evaluate in 2026 (Backslash Security)](https://www.backslash.security/blog/top-7-agentic-endpoint-security-companies) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-csa-agentjacking-mcp-sentry`](index.html#doc=note-2026-csa-agentjacking-mcp-sentry) — [Agentjacking: MCP Injection Hijacks AI Coding Agents (Cloud Security Alliance research note)](https://labs.cloudsecurityalliance.org/research/csa-research-note-agentjacking-mcp-sentry-injection-20260612/) (`note`, status: `to-read`, priority: `high`)
  - [`note-2026-darkreading-ai-coding-tools-endpoint`](index.html#doc=note-2026-darkreading-ai-coding-tools-endpoint) — [How AI Coding Tools Crushed the Endpoint Security Fortress (Dark Reading)](https://www.darkreading.com/application-security/ai-coding-tools-endpoint-security) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`note-2026-lasso-securing-ai-on-endpoints`](index.html#doc=note-2026-lasso-securing-ai-on-endpoints) — [Securing AI on Endpoints: How to Govern AI Tools, Coding Agents, and MCP Connections (Lasso Security)](https://www.lasso.security/blog/securing-ai-on-endpoints-how-to-govern-ai-tools-coding-agents-and-mcp-connections) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-pillar-ai-coding-agent-security-tools`](index.html#doc=note-2026-pillar-ai-coding-agent-security-tools) — [Best AI Coding Agent Security Tools for the Enterprise (2026) (Pillar Security)](https://www.pillar.security/blog/best-ai-coding-agent-security-tools-for-the-enterprise-2026) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-zenity-device-based-ai-security`](index.html#doc=note-2026-zenity-device-based-ai-security) — [Device-Based AI Security: Protecting Endpoint AI Agents (Zenity)](https://zenity.io/academy/device-based-ai-security) (`note`, status: `to-read`, priority: `medium`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Bit-Flip Attacks (`ontologic:BitFlipAttacks`)

- **Full Hierarchy Path:** `Security & Resilience > Hardware Fault Attacks > Bit-Flip Attacks`
- **Parent Category:** `Security & Resilience`
- **Technology Area:** Adversarial Fault Injection
- **Description:** Memory-level bit-flip perturbations (including Rowhammer) that corrupt weights or pointer metadata.
- **Linked Documents (7):**
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Memory Safety & Software Capabilities (`ontologic:MemorySafetySoftwareCapabilities`)

- **Full Hierarchy Path:** `Security & Resilience > Memory Safety & Software Capabilities`
- **Parent Category:** `Security & Resilience`
- **Technology Area:** Language & Runtime Memory Safety
- **Description:** Compiler and runtime memory-safety mechanisms, capability pointers, and bounds metadata.
- **Linked Documents (13):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.33748`](index.html#doc=arxiv-2610.33748) — [A Rowhammer attack on Fil-C's software capabilities](https://arxiv.org/abs/2610.33748) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Runtime Fault Localization & Recovery (`ontologic:RuntimeFaultLocalizationRecovery`)

- **Full Hierarchy Path:** `Security & Resilience > Runtime Fault Localization & Recovery`
- **Parent Category:** `Security & Resilience`
- **Technology Area:** Self-Healing & Fault-Tolerant AI
- **Description:** Online anomaly localization and statistical weight repair without full model retraining.
- **Linked Documents (12):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2508.00500`](index.html#doc=arxiv-2508.00500) — [ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.19356`](index.html#doc=arxiv-2607.19356) — [NEXUS: Structured Runtime Safety for Tool-Using LLM Agents](https://arxiv.org/abs/2607.19356) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Artificial Intelligence & Machine Learning (`ontologic:ArtificialIntelligenceMachineLearning`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning`
- **Parent Category:** `Root Domain`
- **Technology Area:** AI & Machine Learning
- **Description:** Machine learning models, training/inference pipelines, and statistical algorithms.
- **Linked Documents (31):**
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2508.00500`](index.html#doc=arxiv-2508.00500) — [ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.08605`](index.html#doc=arxiv-2605.08605) — [Lattice Deduction Transformers](https://arxiv.org/abs/2605.08605) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.19356`](index.html#doc=arxiv-2607.19356) — [NEXUS: Structured Runtime Safety for Tool-Using LLM Agents](https://arxiv.org/abs/2607.19356) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-backslash-agentic-endpoint-security-top7`](index.html#doc=note-2026-backslash-agentic-endpoint-security-top7) — [Top 7 Agentic Endpoint Security Companies CISOs Should Evaluate in 2026 (Backslash Security)](https://www.backslash.security/blog/top-7-agentic-endpoint-security-companies) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Deep Neural Networks (`ontologic:DeepNeuralNetworks`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Deep Neural Networks`
- **Parent Category:** `Artificial Intelligence & Machine Learning`
- **Technology Area:** Deep Learning Architectures
- **Description:** Deep neural network architectures including CNNs, Vision Transformers, and Large Language Models.
- **Linked Documents (29):**
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2508.00500`](index.html#doc=arxiv-2508.00500) — [ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.08605`](index.html#doc=arxiv-2605.08605) — [Lattice Deduction Transformers](https://arxiv.org/abs/2605.08605) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2607.19356`](index.html#doc=arxiv-2607.19356) — [NEXUS: Structured Runtime Safety for Tool-Using LLM Agents](https://arxiv.org/abs/2607.19356) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2610.08739v2`](index.html#doc=arxiv-2610.08739v2) — [BARE-AI: Bit-Flip Attack Resilience in AI Hardware through Built-in Performance Monitors](https://arxiv.org/abs/2610.08739v2) (`academic_paper`, status: `reading`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)
  - [`techpaper-2026-eda-formal-monitors`](index.html#doc=techpaper-2026-eda-formal-monitors) — [Pre-Silicon Formal Verification of On-Chip Telemetry Monitors Against Fault Injection](https://arxiv.org/abs/2610.08739v2) (`technical_paper`, status: `to-read`, priority: `medium`)
  - [`techpaper-2026-hbm-chiplet-resilience`](index.html#doc=techpaper-2026-hbm-chiplet-resilience) — [Cross-Layer Resilience for HBM and UCIe Chiplet AI Accelerators Under Targeted Bit-Flip Faults](https://semiengineering.com/) (`technical_paper`, status: `to-read`, priority: `medium`)

### Language Models & Efficient Attention (`ontologic:LanguageModelsAndAttention`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Deep Neural Networks > Language Models & Efficient Attention`
- **Parent Category:** `Artificial Intelligence & Machine Learning > Deep Neural Networks`
- **Technology Area:** Large Language Models & Attention Mechanisms
- **Description:** Large language model pretraining, scaling laws, tokenization, KV-cache compression, and efficient attention mechanisms.
- **Linked Documents (2):**
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)

### Novel & State-Space Architectures (`ontologic:NovelAndStateSpaceArchitectures`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Deep Neural Networks > Novel & State-Space Architectures`
- **Parent Category:** `Artificial Intelligence & Machine Learning > Deep Neural Networks`
- **Technology Area:** Alternative & State-Space Architectures
- **Description:** Sub-quadratic state-space models (Mamba, RWKV), Kolmogorov-Arnold Networks (KAN), recurrent-depth reasoners, and theoretical foundations.
- **Linked Documents (4):**
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.08605`](index.html#doc=arxiv-2605.08605) — [Lattice Deduction Transformers](https://arxiv.org/abs/2605.08605) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`semieng-2026-bare-ai-monitors`](index.html#doc=semieng-2026-bare-ai-monitors) — [On-Chip Monitors Detect Bit-Flip Attacks in AI Accelerators (UF, UT Dallas, RPI)](https://semiengineering.com/on-chip-monitors-detect-bit-flip-attacks-in-ai-accelerators-uf-ut-dallas-rpi/) (`technical_article`, status: `read`, priority: `high`)

### Reasoning, Agents & Retrieval (`ontologic:ReasoningAgentsAndRetrieval`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Reasoning, Agents & Retrieval`
- **Parent Category:** `Artificial Intelligence & Machine Learning`
- **Technology Area:** Agentic Systems & Reasoning
- **Description:** Chain-of-thought and latent reasoning, autonomous multi-agent orchestration, tool use, and retrieval-augmented generation (RAG).
- **Linked Documents (19):**
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2508.00500`](index.html#doc=arxiv-2508.00500) — [ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-backslash-agentic-endpoint-security-top7`](index.html#doc=note-2026-backslash-agentic-endpoint-security-top7) — [Top 7 Agentic Endpoint Security Companies CISOs Should Evaluate in 2026 (Backslash Security)](https://www.backslash.security/blog/top-7-agentic-endpoint-security-companies) (`note`, status: `to-read`, priority: `medium`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Interpretability, Calibration & Evaluation (`ontologic:InterpretabilityAndEvaluation`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Interpretability, Calibration & Evaluation`
- **Parent Category:** `Artificial Intelligence & Machine Learning`
- **Technology Area:** Mechanistic Interpretability & Model Evaluation
- **Description:** Mechanistic interpretability, feature superposition, model calibration, and benchmark evaluation.
- **Linked Documents (0):**
  - *(No documents currently matched in this category)*

### Probabilistic, Diffusion & Multimodal Vision (`ontologic:ProbabilisticDiffusionAndVision`)

- **Full Hierarchy Path:** `Artificial Intelligence & Machine Learning > Probabilistic, Diffusion & Multimodal Vision`
- **Parent Category:** `Artificial Intelligence & Machine Learning`
- **Technology Area:** Multimodal Vision & Probabilistic Generative Models
- **Description:** Diffusion models, probabilistic programming, variational inference, and multimodal vision-language systems.
- **Linked Documents (3):**
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)

### AI Alignment, Guardrails & Agent Security (`ontologic:AIAlignmentAndAgentSecurity`)

- **Full Hierarchy Path:** `Security & Resilience > AI Alignment, Guardrails & Agent Security`
- **Parent Category:** `Security & Resilience`
- **Technology Area:** AI Alignment & Agentic Security
- **Description:** AI safety alignment, adversarial red teaming, prompt-injection defense, formal guardrail verification, and agentic runtime security.
- **Linked Documents (17):**
  - [`arxiv-2404.01833`](index.html#doc=arxiv-2404.01833) — [Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.01143`](index.html#doc=arxiv-2605.01143) — [A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.04785`](index.html#doc=arxiv-2605.04785) — [AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`note-2026-zenity-device-based-ai-security`](index.html#doc=note-2026-zenity-device-based-ai-security) — [Device-Based AI Security: Protecting Endpoint AI Agents (Zenity)](https://zenity.io/academy/device-based-ai-security) (`note`, status: `to-read`, priority: `medium`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### AI Policy, Governance & Human-AI Systems (`ontologic:AIPolicyGovernanceAndHumanAI`)

- **Full Hierarchy Path:** `AI Policy, Governance & Human-AI Systems`
- **Parent Category:** `Root Domain`
- **Technology Area:** AI Governance, Policy & Human-AI Interaction
- **Description:** International AI legislation, risk management standards (NIST AI RMF, ISO/IEC, EU AI Act), compute governance, and human-AI decision-making.
- **Linked Documents (2):**
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2607.22619`](index.html#doc=arxiv-2607.22619) — [How to Catch a GPU: A Taxonomy of Verification and Enforcement Mechanisms for International AI Agreements](https://arxiv.org/abs/2607.22619) (`academic_paper`, status: `to-read`, priority: `medium`)

### Formal Methods & Automated Reasoning (`ontologic:FormalMethodsAutomatedReasoning`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning`
- **Parent Category:** `Root Domain`
- **Technology Area:** Automated Reasoning & Mathematical Logic
- **Description:** Boolean satisfiability (SAT), Satisfiability Modulo Theories (SMT), automated theorem proving, and formal decision procedures.
- **Linked Documents (29):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.00454`](index.html#doc=arxiv-2601.00454) — [Defensive M2S: Training Guardrail Models on Compressed Multi-turn Conversations](https://arxiv.org/abs/2601.00454) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.11247`](index.html#doc=arxiv-2602.11247) — [Peak + Accumulation: A Proxy-Level Scoring Formula for Multi-Turn LLM Attack Detection](https://arxiv.org/abs/2602.11247) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23100`](index.html#doc=arxiv-2604.23100) — [ProofLoop: From Language to Logic — Bridging LLMs and Formal Representations for RTL Assertion Generation](https://arxiv.org/abs/2604.23100) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.08605`](index.html#doc=arxiv-2605.08605) — [Lattice Deduction Transformers](https://arxiv.org/abs/2605.08605) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.01738`](index.html#doc=arxiv-2606.01738) — [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2606.01738) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2606.03136`](index.html#doc=arxiv-2606.03136) — [PsychoPass: Geometric Profiling of Multi-Turn Adversarial LLM Conversations](https://arxiv.org/abs/2606.03136) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2609.26751`](index.html#doc=arxiv-2609.26751) — [EquivSVA: A Formally Verified Dataset of Behavioral Assertions Across Equivalent RTL Implementations](https://arxiv.org/abs/2609.26751) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`note-2026-ai-security-trajectory-monitoring-report`](index.html#doc=note-2026-ai-security-trajectory-monitoring-report) — Personal Research Report: Trajectory Monitoring for Multi-Turn Escalation (Crescendo) and Endpoint AI Agent Security (`note`, status: `read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-csa-agentjacking-mcp-sentry`](index.html#doc=note-2026-csa-agentjacking-mcp-sentry) — [Agentjacking: MCP Injection Hijacks AI Coding Agents (Cloud Security Alliance research note)](https://labs.cloudsecurityalliance.org/research/csa-research-note-agentjacking-mcp-sentry-injection-20260612/) (`note`, status: `to-read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-ai-security-endpoint-perspective-and-trackin`](index.html#doc=research-ai-security-endpoint-perspective-and-trackin) — [Research Synthesis: AI security: endpoint perspective, and tracking the trajectory of AI sessions, chats and transactions to detect crescendo and escalation attacks](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Neuro-Symbolic Deduction & Guardrail Verification (`ontologic:NeuroSymbolicDeductionAndVerification`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning > Neuro-Symbolic Deduction & Guardrail Verification`
- **Parent Category:** `Formal Methods & Automated Reasoning`
- **Technology Area:** Neuro-Symbolic Logic & Neural Verification
- **Description:** Neuro-symbolic translation to First-Order Logic, abstract-interpretation lattice deduction transformers, and formal certification of neural guardrails.
- **Linked Documents (6):**
  - [`arxiv-2509.25239`](index.html#doc=arxiv-2509.25239) — [A Formal Comparison Between Chain of Thought and Latent Thought](https://arxiv.org/abs/2509.25239) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2605.08605`](index.html#doc=arxiv-2605.08605) — [Lattice Deduction Transformers](https://arxiv.org/abs/2605.08605) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2605.10901`](index.html#doc=arxiv-2605.10901) — [Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)

### SAT & SMT Solvers (`ontologic:SATAndSMTSolvers`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning > SAT & SMT Solvers`
- **Parent Category:** `Formal Methods & Automated Reasoning`
- **Technology Area:** SAT & SMT Decision Procedures
- **Description:** Conflict-Driven Clause Learning (CDCL) SAT engines and DPLL(T) SMT solvers over bit-vectors, arrays, strings, linear arithmetic, and algebraic datatypes.
- **Linked Documents (13):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2603.19163`](index.html#doc=arxiv-2603.19163) — [cuGenOpt: A GPU-Accelerated General-Purpose Metaheuristic Framework for Combinatorial Optimization](https://arxiv.org/abs/2603.19163) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Software Verification & Symbolic Execution (`ontologic:SoftwareVerificationSymbolicExecution`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning > SAT & SMT Solvers > Software Verification & Symbolic Execution`
- **Parent Category:** `Formal Methods & Automated Reasoning > SAT & SMT Solvers`
- **Technology Area:** Software Verification & Program Analysis
- **Description:** SAT/SMT-backed symbolic execution, bounded software model checking, deductive verification, and automated test generation.
- **Linked Documents (6):**
  - [`arxiv-1610.00502`](index.html#doc=arxiv-1610.00502) — [A Survey of Symbolic Execution Techniques for Software Development and Verification](https://arxiv.org/abs/1610.00502) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2208.03699`](index.html#doc=arxiv-2208.03699) — [UCLID5: Multi-Modal Formal Modeling, Verification, and Synthesis](https://arxiv.org/abs/2208.03699) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`openreview-sec-bench-2025`](index.html#doc=openreview-sec-bench-2025) — [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://openreview.net/pdf?id=QQhQIqons0) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Graph Theory Modulo Theories (`ontologic:GraphTheoryModuloTheories`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning > SAT & SMT Solvers > Graph Theory Modulo Theories`
- **Parent Category:** `Formal Methods & Automated Reasoning > SAT & SMT Solvers`
- **Technology Area:** Graph Analysis & Combinatorial Optimization
- **Description:** SMT decision procedures equipped with native graph predicates (reachability, shortest path, max-flow, acyclicity) for graph analysis and network synthesis.
- **Linked Documents (4):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2604.23338`](index.html#doc=arxiv-2604.23338) — [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

### Knowledge Representation & Ontologies (`ontologic:KnowledgeRepresentationOntologies`)

- **Full Hierarchy Path:** `Formal Methods & Automated Reasoning > Knowledge Representation & Ontologies`
- **Parent Category:** `Formal Methods & Automated Reasoning`
- **Technology Area:** Ontologies & Description Logic
- **Description:** Formal ontologies, Description Logics (OWL, EL, ALC), SHACL shape validation, and SAT/SMT-driven TBox/ABox consistency and subsumption reasoning.
- **Linked Documents (13):**
  - [`arxiv-1402.4677`](index.html#doc=arxiv-1402.4677) — [MonoSAT: Modulo Theories for Graphs, Networks, and Geometry](https://arxiv.org/abs/1402.4677) (`academic_paper`, status: `read`, priority: `high`)
  - [`arxiv-1507.01763`](index.html#doc=arxiv-1507.01763) — [SAT and SMT-Based Automated Reasoning for Description Logics and Formal Ontologies](https://arxiv.org/abs/1507.01763) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2201.04663`](index.html#doc=arxiv-2201.04663) — [cvc5: A Versatile and Industrial-Strength SMT Solver](https://arxiv.org/abs/2201.04663) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2503.19174`](index.html#doc=arxiv-2503.19174) — [AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL](https://arxiv.org/abs/2503.19174) (`academic_paper`, status: `reading`, priority: `high`)
  - [`arxiv-2506.10597`](index.html#doc=arxiv-2506.10597) — [SoK: Evaluating Jailbreak Guardrails for Large Language Models](https://arxiv.org/abs/2506.10597) (`academic_paper`, status: `to-read`, priority: `medium`)
  - [`arxiv-2601.17548`](index.html#doc=arxiv-2601.17548) — [Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems](https://arxiv.org/abs/2601.17548) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.13237`](index.html#doc=arxiv-2602.13237) — [NL2LOGIC: AST-Guided Translation of Natural Language into First-Order Logic with Large Language Models](https://arxiv.org/abs/2602.13237) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`arxiv-2602.16935`](index.html#doc=arxiv-2602.16935) — [DeepContext: Stateful Real-Time Detection of Multi-Turn Adversarial Intent Drift in LLMs](https://arxiv.org/abs/2602.16935) (`academic_paper`, status: `to-read`, priority: `high`)
  - [`note-2026-cross-layer-bitflip-synthesis`](index.html#doc=note-2026-cross-layer-bitflip-synthesis) — [Synthesis Note: Cross-Layer Bit-Flip Resilience Across AI Accelerators and Capability Runtimes](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`note-2026-csa-agentjacking-mcp-sentry`](index.html#doc=note-2026-csa-agentjacking-mcp-sentry) — [Agentjacking: MCP Injection Hijacks AI Coding Agents (Cloud Security Alliance research note)](https://labs.cloudsecurityalliance.org/research/csa-research-note-agentjacking-mcp-sentry-injection-20260612/) (`note`, status: `to-read`, priority: `high`)
  - [`note-2026-kitsumiko-formal-neurosymbolic-bridge`](index.html#doc=note-2026-kitsumiko-formal-neurosymbolic-bridge) — [Synthesis Note: Neuro-Symbolic Deduction, Formal Guardrail Certification, and Hardware-Verified AI (Curated from kitsumiko/papers)](https://github.com/kitsumiko/papers) (`note`, status: `read`, priority: `high`)
  - [`research-formal-verification-languages-in-chip-and-se`](index.html#doc=research-formal-verification-languages-in-chip-and-se) — [Research Synthesis: Formal verification languages in chip and semiconductor design](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)
  - [`research-sat-and-smt-solvers-applications-in-software`](index.html#doc=research-sat-and-smt-solvers-applications-in-software) — [Research Synthesis: SAT and SMT solvers applications in software development, graph analysis, and ontologies](https://github.com/bsommers/reading-db) (`note`, status: `read`, priority: `high`)

## 3. Canonical Concept Catalog

| Concept ID | Label | Technology Area | Taxonomy Path | Related Concepts |
|---|---|---|---|---|
| `concept:bare-ai` | **BARE-AI Framework** | On-Chip Telemetry & Runtime Monitoring | `Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors` | `concept:apc`, `concept:pulse`, `concept:asi`, `concept:bit-flip-attack` |
| `concept:bit-flip-attack` | **Bit-Flip Attack (BFA)** | Adversarial Fault Injection | `Security & Resilience > Hardware Fault Attacks > Bit-Flip Attacks` | `concept:bare-ai`, `concept:dnn`, `concept:rowhammer` |
| `concept:rowhammer` | **Rowhammer DRAM Disturbance Attack** | Adversarial Fault Injection | `Security & Resilience > Hardware Fault Attacks > Bit-Flip Attacks` | `concept:bit-flip-attack`, `concept:fil-c`, `concept:ecc` |
| `concept:fil-c` | **Fil-C Software Capabilities (InvisiCaps)** | Language & Runtime Memory Safety | `Security & Resilience > Memory Safety & Software Capabilities` | `concept:rowhammer`, `concept:bit-flip-attack` |
| `concept:apc` | **AI Performance Counters (APCs)** | On-Chip Telemetry & Runtime Monitoring | `Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors` | `concept:bare-ai`, `concept:pulse`, `concept:activation-statistics` |
| `concept:pulse` | **PULSE Detector** | On-Chip Telemetry & Runtime Monitoring | `Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors` | `concept:bare-ai`, `concept:apc` |
| `concept:asi` | **Activation Shift Index (ASI)** | Self-Healing & Fault-Tolerant AI | `Security & Resilience > Runtime Fault Localization & Recovery` | `concept:bare-ai`, `concept:activation-statistics` |
| `concept:activation-statistics` | **Layer Activation Statistics** | On-Chip Telemetry & Runtime Monitoring | `Hardware & Semiconductor Systems > AI Accelerators > Built-in Performance Monitors` | `concept:apc`, `concept:asi` |
| `concept:dnn` | **Deep Neural Networks (DNNs, ViTs, LLMs)** | Deep Learning Architectures | `Artificial Intelligence & Machine Learning > Deep Neural Networks` | `concept:bit-flip-attack`, `concept:ai-accelerator`, `concept:llm-formal-verification` |
| `concept:ai-accelerator` | **AI Hardware Accelerator** | AI Hardware Accelerators | `Hardware & Semiconductor Systems > AI Accelerators` | `concept:apc`, `concept:bare-ai`, `concept:dnn` |
| `concept:ecc` | **Error Correcting Codes (ECC)** | Self-Healing & Fault-Tolerant AI | `Security & Resilience > Runtime Fault Localization & Recovery` | `concept:bit-flip-attack`, `concept:bare-ai`, `concept:rowhammer` |
| `concept:sva` | **SystemVerilog Assertions (SVA) & PSL** | Formal Verification & Specification Languages | `Hardware & Semiconductor Systems > EDA & Hardware Verification > Formal Verification Languages & Assertions` | `concept:uclid5`, `concept:llm-formal-verification` |
| `concept:uclid5` | **UCLID5, Kami & ChiselFV Formal Hardware Languages** | Formal Verification & Specification Languages | `Hardware & Semiconductor Systems > EDA & Hardware Verification > Formal Verification Languages & Assertions` | `concept:sva`, `concept:llm-formal-verification` |
| `concept:llm-formal-verification` | **Automated & Agentic RTL Assertion Synthesis (AssertionForge, ProofLoop)** | Formal Verification & Specification Languages | `Hardware & Semiconductor Systems > EDA & Hardware Verification > Formal Verification Languages & Assertions` | `concept:sva`, `concept:uclid5`, `concept:dnn` |
| `concept:sat-smt-solvers` | **SAT & SMT Solvers (Z3, cvc5, CDCL, DPLL(T))** | SAT & SMT Decision Procedures | `Formal Methods & Automated Reasoning > SAT & SMT Solvers` | `concept:symbolic-execution`, `concept:monosat-graph-smt`, `concept:ontology-smt-reasoning`, `concept:uclid5` |
| `concept:symbolic-execution` | **Symbolic Execution & Software Verification (KLEE, CBMC, Dafny)** | Software Verification & Program Analysis | `Formal Methods & Automated Reasoning > SAT & SMT Solvers > Software Verification & Symbolic Execution` | `concept:sat-smt-solvers`, `concept:fil-c` |
| `concept:monosat-graph-smt` | **Graph Theory Modulo Theories (MonoSAT)** | Graph Analysis & Combinatorial Optimization | `Formal Methods & Automated Reasoning > SAT & SMT Solvers > Graph Theory Modulo Theories` | `concept:sat-smt-solvers`, `concept:ontology-smt-reasoning` |
| `concept:ontology-smt-reasoning` | **Ontology & Description Logic Reasoning via SAT/SMT (OWL, EL, SHACL)** | Ontologies & Description Logic | `Formal Methods & Automated Reasoning > Knowledge Representation & Ontologies` | `concept:sat-smt-solvers`, `concept:monosat-graph-smt`, `concept:nl2logic-fol` |
| `concept:nl2logic-fol` | **Neuro-Symbolic NL-to-First-Order Logic Translation (NL2LOGIC)** | Neuro-Symbolic Logic & Neural Verification | `Formal Methods & Automated Reasoning > Neuro-Symbolic Deduction & Guardrail Verification` | `concept:sat-smt-solvers`, `concept:ontology-smt-reasoning`, `concept:lattice-deduction` |
| `concept:lattice-deduction` | **Abstract-Interpretation Lattice Deduction Transformers** | Neuro-Symbolic Logic & Neural Verification | `Formal Methods & Automated Reasoning > Neuro-Symbolic Deduction & Guardrail Verification` | `concept:nl2logic-fol`, `concept:sat-smt-solvers`, `concept:formal-guardrails` |
| `concept:formal-guardrails` | **Formal Verification of Neural Guardrail Classifiers** | Neuro-Symbolic Logic & Neural Verification | `Formal Methods & Automated Reasoning > Neuro-Symbolic Deduction & Guardrail Verification` | `concept:lattice-deduction`, `concept:agentic-security`, `concept:dnn` |
| `concept:agentic-security` | **Agentic AI Security, Prompt Injection & Red Teaming (SEC-bench, GOAT)** | AI Alignment & Agentic Security | `Security & Resilience > AI Alignment, Guardrails & Agent Security` | `concept:formal-guardrails`, `concept:symbolic-execution`, `concept:agentic-reasoning` |
| `concept:trajectory-monitoring` | **Multi-Turn Escalation (Crescendo) & Session-Level Trajectory Monitoring** | AI Alignment & Agentic Security | `Security & Resilience > AI Alignment, Guardrails & Agent Security > Session & Trajectory Monitoring` | `concept:agentic-security`, `concept:formal-guardrails`, `concept:endpoint-agent-security` |
| `concept:endpoint-agent-security` | **Endpoint Security for AI Coding Agents, MCP & Agent Telemetry** | AI Alignment & Agentic Security | `Security & Resilience > AI Alignment, Guardrails & Agent Security > Endpoint & Agent Runtime` | `concept:agentic-security`, `concept:trajectory-monitoring` |
| `concept:agentic-reasoning` | **Chain-of-Thought, Latent Reasoning & Multi-Agent Orchestration** | Agentic Systems & Reasoning | `Artificial Intelligence & Machine Learning > Reasoning, Agents & Retrieval` | `concept:lattice-deduction`, `concept:agentic-security`, `concept:dnn` |
| `concept:flash-attention-llm` | **LLM Scaling, Efficient Attention & Speculative Decoding** | Large Language Models & Attention Mechanisms | `Artificial Intelligence & Machine Learning > Deep Neural Networks > Language Models & Efficient Attention` | `concept:dnn`, `concept:ai-accelerator` |
| `concept:ssm-kan-architectures` | **State-Space Models (Mamba, RWKV) & Kolmogorov-Arnold Networks (KAN)** | Alternative & State-Space Architectures | `Artificial Intelligence & Machine Learning > Deep Neural Networks > Novel & State-Space Architectures` | `concept:dnn`, `concept:lattice-deduction` |
| `concept:mechanistic-interpretability` | **Mechanistic Interpretability, Superposition & Model Calibration** | Mechanistic Interpretability & Model Evaluation | `Artificial Intelligence & Machine Learning > Interpretability, Calibration & Evaluation` | `concept:dnn`, `concept:formal-guardrails` |
| `concept:diffusion-multimodal` | **Diffusion Models, Probabilistic Programming & Multimodal Vision** | Multimodal Vision & Probabilistic Generative Models | `Artificial Intelligence & Machine Learning > Probabilistic, Diffusion & Multimodal Vision` | `concept:dnn` |
| `concept:ai-policy-governance` | **AI Governance, Regulatory Frameworks & Human-AI Interaction** | AI Governance, Policy & Human-AI Interaction | `AI Policy, Governance & Human-AI Systems` | `concept:agentic-security` |
