
# Part VIII — Agent Architecture

The Agent Architecture defines the cognitive ecosystem through which architectural reasoning is performed within ACKB.

Rather than relying upon a monolithic artificial intelligence system, ACKB distributes reasoning across multiple specialized cognitive agents collaborating through a common Architectural Knowledge Base.

Each agent possesses distinct expertise while sharing the same Cognitive Core, Knowledge Model and Memory Architecture.

This separation enables scalability, explainability and long-term maintainability.

A fundamental principle introduced in ACKB v3.1 is the separation between **reasoning** and **knowledge persistence**.

Reasoning agents generate architectural understanding.

Persistent knowledge is managed exclusively through governed repository operations.

This distinction preserves the integrity of the Architectural Knowledge Base while allowing unrestricted cognitive exploration.

---

# 19. Agent Taxonomy

ACKB defines a taxonomy of specialized cognitive agents.

The taxonomy is intentionally extensible.

New agents may be incorporated without modifying the underlying cognitive architecture provided they comply with the common cognitive contracts defined by this specification.

Agents are classified according to their primary cognitive responsibilities.

---

## 19.1 Coordination Agents

Coordination Agents organize reasoning across the complete architectural project.

They do not replace specialized expertise.

Instead, they orchestrate collaborative cognition.

### Project Coordinator

The Project Coordinator represents the persistent cognitive identity of a project.

Its responsibilities include:

- maintaining project goals;
- constructing Working Memory;
- activating relevant knowledge;
- selecting Interpretative Frameworks;
- selecting Design Frameworks;
- delegating reasoning tasks;
- integrating specialized conclusions;
- preserving cognitive coherence.

Every project shall possess one persistent Project Coordinator.

---

## 19.2 Knowledge Agents

Knowledge Agents acquire, organize and enrich architectural knowledge.

Examples include:

- Reference Agent;
- Knowledge Ingestion Agent;
- Knowledge Discovery Agent;
- Knowledge Consolidation Agent.

These agents transform information into structured Knowledge Objects but do not directly modify the persistent repository.

---

## 19.3 Analysis Agents

Analysis Agents investigate specific aspects of architectural reality.

Typical examples include:

- Place Analysis Agent;
- Environmental Analysis Agent;
- Material Analysis Agent;
- Structural Analysis Agent;
- Heritage Analysis Agent;
- Cost Analysis Agent;
- Regulatory Analysis Agent.

Their outputs become inputs for higher-order reasoning.

---

## 19.4 Design Agents

Design Agents support architectural creation.

Examples include:

- Strategy Agent;
- Concept Agent;
- Sketch Agent;
- Spatial Agent;
- Structural Design Agent;
- Envelope Agent.

These agents propose architectural alternatives while maintaining complete traceability to the knowledge that generated them.

---

## 19.5 Validation Agents

Validation Agents evaluate architectural proposals against explicit criteria.

Examples include:

- Compliance Agent;
- Sustainability Agent;
- Accessibility Agent;
- BIM Validation Agent;
- Documentation Agent.

Validation Agents support decision-making without replacing architectural judgement.

---

## 19.6 Organizational Agents

Organizational Agents preserve the long-term integrity of ACKB.

Examples include:

- Knowledge Manager;
- Repository Auditor;
- Metadata Validator;
- Governance Agent;
- Synchronization Agent.

Unlike reasoning agents, Organizational Agents operate primarily on repository integrity rather than project design.

---

# 20. Agent Contracts

Every cognitive agent shall communicate through standardized semantic contracts.

Agent Contracts define the minimum information required for reliable collaboration.

This ensures interoperability regardless of implementation technology or AI model.

Agent Contracts describe cognitive interactions rather than software APIs.

---

## 20.1 Cognitive Request

Every reasoning request should specify:

- Goal;
- Task;
- Context;
- required Knowledge;
- active Frameworks;
- constraints;
- expected outputs.

The request establishes the cognitive boundaries of the reasoning process.

---

## 20.2 Cognitive Response

Every reasoning response should provide:

- conclusions;
- supporting reasoning;
- confidence level;
- activated knowledge;
- references;
- assumptions;
- detected knowledge gaps;
- proposed repository updates.

Reasoning results remain explainable and traceable.

---

## 20.3 Knowledge Proposal

A fundamental principle of ACKB v3.1 is that reasoning agents do **not** modify the repository directly.

Instead, they submit **Knowledge Proposals**.

A Knowledge Proposal may contain:

- new Knowledge Objects;
- updated metadata;
- proposed Interpretative Frameworks;
- proposed Design Frameworks;
- repository relationships;
- version updates;
- confidence assessment.

Knowledge Proposals become inputs to the Knowledge Manager.

---

## 20.4 Cognitive Integrity

Agent Contracts preserve semantic integrity throughout distributed reasoning.

Every cognitive interaction should remain:

- explainable;
- reproducible;
- traceable;
- version-aware;
- compatible with repository governance.

---

# 21. Agent Communication

Architectural reasoning emerges from collaboration rather than isolated computation.

ACKB therefore defines communication protocols supporting continuous cognitive interaction between specialized agents.

Communication is knowledge-centered rather than message-centered.

Agents exchange structured cognitive entities instead of arbitrary textual conversations.

---

## 21.1 Shared Cognitive Language

All agents communicate using the concepts defined by the Cognitive Core.

Examples include:

- Knowledge Objects;
- Interpretative Frameworks;
- Design Frameworks;
- Decisions;
- Constraints;
- Opportunities;
- Hypotheses.

This common language enables interoperability across heterogeneous implementations.

---

## 21.2 Context Sharing

Before initiating reasoning, the Project Coordinator constructs a shared Working Memory.

Rather than accessing the entire repository, agents receive only the knowledge relevant to the current task.

Dynamic context construction minimizes cognitive overload while improving reasoning quality.

---

## 21.3 Collaborative Reasoning

Reasoning frequently requires multiple specialized agents.

For example:

```text
Project Coordinator
        │
        ├──────────────┐
        │              │
        ▼              ▼
Place Analysis     Reference Agent
        │              │
        └──────┬───────┘
               ▼
        Strategy Agent
               │
               ▼
         Sketch Agent
               │
               ▼
      Knowledge Proposal
               │
               ▼
      Knowledge Manager
```

Architectural understanding emerges from the integration of complementary expertise.

---

## 21.4 Asynchronous Collaboration

Agents may operate simultaneously.

The Project Coordinator integrates partial reasoning as it becomes available.

This asynchronous model enables efficient exploration of complex architectural problems while maintaining complete traceability.

---

# 22. Knowledge Manager

The Knowledge Manager is the only cognitive component authorized to perform persistent modifications to the ACKB Repository.

This architectural principle represents one of the most significant governance mechanisms introduced in ACKB v3.1.

Reasoning agents generate architectural knowledge.

The Knowledge Manager determines whether that knowledge becomes part of organizational memory.

By separating reasoning from persistence, ACKB preserves repository integrity while allowing unrestricted cognitive exploration.

The Knowledge Manager functions as the cognitive kernel of the Architectural Knowledge Base.

---

## 22.1 Responsibilities

The Knowledge Manager is responsible for:

- validating repository updates;
- maintaining metadata consistency;
- preserving semantic integrity;
- managing repository versions;
- maintaining the Knowledge Graph;
- coordinating memory synchronization;
- recording repository history.

Every persistent modification shall pass through the Knowledge Manager.

---

## 22.2 Validation

Before accepting any Knowledge Proposal, the Knowledge Manager evaluates:

- semantic consistency;
- metadata completeness;
- relationship integrity;
- duplicate detection;
- version compatibility;
- governance compliance.

Only validated proposals become persistent knowledge.

---

## 22.3 Version Control

The Knowledge Manager preserves the complete historical evolution of every cognitive object.

Repository updates shall never overwrite existing knowledge without preserving previous versions.

Version history remains permanently accessible.

---

## 22.4 Repository Integrity

The repository should remain semantically coherent despite continuous evolution.

Integrity responsibilities include:

- identifier uniqueness;
- relationship consistency;
- metadata validation;
- schema compatibility;
- memory synchronization;
- archival management.

Repository integrity has priority over repository growth.

---

## 22.5 Metadata Validation

Every persistent entity shall satisfy the metadata schemas defined in Part III.

The Knowledge Manager verifies:

- mandatory attributes;
- semantic consistency;
- framework relationships;
- provenance information;
- traceability metadata.

Metadata quality directly influences reasoning quality.

---

## 22.6 Knowledge Graph Maintenance

The Architectural Knowledge Base is represented internally as a continuously evolving semantic knowledge graph.

The Knowledge Manager maintains:

- semantic relationships;
- inheritance structures;
- dependency graphs;
- framework networks;
- reasoning lineage;
- knowledge lineage.

The Knowledge Graph constitutes the cognitive infrastructure supporting all architectural reasoning.

---

## 22.7 Audit Logging

Every persistent repository operation shall generate an immutable audit record.

Audit logs include:

- operation type;
- timestamp;
- responsible agent;
- originating proposal;
- affected objects;
- previous versions;
- validation outcome.

Audit Logging guarantees transparency, reproducibility and long-term organizational accountability.

---

## Repository Modification Principle

A fundamental architectural rule governs every ACKB implementation:

```text
Reasoning Agents
        │
        ▼
Knowledge Proposal
        │
        ▼
Knowledge Manager
        │
        ▼
Repository Validation
        │
        ▼
ACKB Repository
```

No reasoning agent shall directly modify persistent knowledge.

This separation ensures that the Architectural Knowledge Base remains a coherent, traceable and trustworthy cognitive system despite decades of continuous evolution and collaboration between humans and artificial intelligence agents.