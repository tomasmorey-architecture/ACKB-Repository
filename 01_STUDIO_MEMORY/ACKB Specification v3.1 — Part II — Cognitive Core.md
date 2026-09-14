
# Part II — Cognitive Core

The Cognitive Core defines the fundamental cognitive architecture upon which every ACKB implementation is built.

It describes the abstract reasoning model shared by human architects and artificial intelligence agents during the architectural design process.

Rather than prescribing specific algorithms or implementation strategies, the Cognitive Core establishes the universal cognitive components required for the construction, interpretation, transformation and preservation of architectural knowledge.

Every specialized agent defined within ACKB shall reason according to this common cognitive model.

---

# 4. Cognitive Core

The Cognitive Core represents the minimum set of cognitive components required to support architectural reasoning.

Each component performs a distinct role while remaining semantically connected to the others.

Together they describe the complete lifecycle of architectural thought.

---

## 4.1 Goal

A Goal represents the desired future state that motivates architectural reasoning.

Goals define why a cognitive process exists.

They provide direction for every subsequent reasoning activity while remaining independent from specific implementation strategies.

Goals may originate from:

- the client;
- the architect;
- project constraints;
- organizational objectives;
- environmental requirements;
- regulatory conditions.

Goals remain relatively stable throughout a project, although they may evolve as new knowledge emerges.

---

## 4.2 Task

A Task represents a bounded cognitive activity performed in order to advance one or more goals.

Tasks transform goals into executable reasoning processes.

Unlike goals, tasks are temporary and have clearly defined inputs, outputs and completion criteria.

Examples include:

- analysing a site;
- studying precedents;
- generating conceptual alternatives;
- evaluating regulations;
- producing structural hypotheses;
- validating design decisions.

Multiple tasks may contribute simultaneously to a single goal.

---

## 4.3 Context

Context represents all information required to correctly interpret a task.

Architectural reasoning is inherently contextual.

The same information may lead to different conclusions depending on the project, location, culture, regulations or design intentions.

Context may include:

- project characteristics;
- geographical conditions;
- historical background;
- environmental conditions;
- client requirements;
- previous decisions;
- organizational knowledge;
- active hypotheses;
- available references.

Within ACKB, Context is continuously reconstructed as new knowledge becomes available.

---

## 4.4 Reasoning

Reasoning is the cognitive process through which knowledge is transformed into architectural understanding.

Reasoning integrates:

- existing knowledge;
- contextual information;
- interpretative frameworks;
- design frameworks;
- constraints;
- objectives.

Rather than representing isolated logical operations, reasoning is understood as a progressive exploration of architectural possibilities.

Reasoning may produce:

- new knowledge;
- hypotheses;
- design alternatives;
- decisions;
- questions;
- knowledge gaps.

---

## 4.5 Knowledge

Knowledge represents validated architectural understanding.

Unlike raw information, knowledge possesses semantic meaning within a specific architectural context.

Knowledge may originate from:

- observations;
- documents;
- conversations;
- simulations;
- previous projects;
- architectural precedents;
- human expertise;
- AI analysis.

Knowledge forms the intellectual foundation upon which reasoning operates.

---

## 4.6 Memory

Memory provides persistent continuity for architectural reasoning.

Its purpose is not merely to store information but to preserve the evolution of understanding.

Memory records:

- knowledge;
- decisions;
- reasoning;
- interpretations;
- relationships;
- provenance;
- historical evolution.

Memory enables architectural intelligence to extend beyond individual sessions, projects or AI models.

---

## 4.7 Reflection

Reflection represents the recursive evaluation of previous reasoning.

Architectural design is inherently iterative.

Reflection allows both architects and AI agents to:

- reconsider assumptions;
- identify inconsistencies;
- discover missing knowledge;
- compare alternatives;
- improve previous conclusions.

Reflection transforms experience into organizational learning.

---

## 4.8 Decision

A Decision represents a deliberate commitment to a particular architectural direction.

Every decision should be supported by explicit reasoning and traceable knowledge.

ACKB distinguishes decisions from conclusions.

A conclusion describes understanding.

A decision commits future design activities.

Decisions may subsequently evolve as additional knowledge becomes available.

---

## 4.9 Explanation

Explanation provides human-readable justification for cognitive processes.

Every significant reasoning outcome should remain explainable.

An explanation may include:

- supporting evidence;
- reasoning steps;
- assumptions;
- constraints;
- rejected alternatives;
- confidence levels.

Explainability constitutes one of the fundamental principles of ACKB and enables transparent collaboration between architects and AI agents.

---

# 5. Cognitive Objects

Cognitive Objects are the persistent entities through which architectural knowledge is represented inside ACKB.

Each object encapsulates a specific form of knowledge together with its metadata, semantic relationships and lifecycle.

Collectively, Cognitive Objects constitute the building blocks of the Architectural Knowledge Base.

---

## 5.1 Knowledge Object

The Knowledge Object (KO) is the fundamental unit of architectural knowledge.

Each Knowledge Object represents a single coherent idea, observation, principle or fact that can be independently understood and reused.

Knowledge Objects should be:

- atomic;
- semantically coherent;
- uniquely identifiable;
- independently traceable;
- reusable across projects.

---

## 5.2 Composite Knowledge Object

A Composite Knowledge Object represents the structured integration of multiple Knowledge Objects into a higher-order concept.

Examples include:

- Place Models;
- Design Strategies;
- Conceptual Narratives;
- Material Systems;
- Environmental Models.

Composite Objects preserve the relationships between their constituent knowledge while enabling higher-level reasoning.

---

## 5.3 Memory Object

A Memory Object represents persistent organizational memory.

Unlike Knowledge Objects, Memory Objects emphasize continuity over factual content.

Examples include:

- lessons learned;
- office methodologies;
- design principles;
- historical project evolution.

---

## 5.4 Decision Object

Represents a persistent architectural decision together with:

- supporting knowledge;
- reasoning;
- alternatives considered;
- responsible agents;
- timestamps;
- confidence level.

Decision Objects provide the basis for project traceability.

---

## 5.5 Reasoning Object

Captures the reasoning process itself.

Rather than storing only conclusions, ACKB preserves how conclusions were reached.

Reasoning Objects may contain:

- logical sequences;
- inference chains;
- evaluation criteria;
- unresolved questions;
- confidence assessments.

---

## 5.6 Conversation Object

Represents structured human–AI interactions that generate architectural knowledge.

Conversations are treated as first-class knowledge sources rather than transient chat histories.

Relevant conversations may subsequently generate Knowledge Objects.

---

## 5.7 Reference Object

Represents external knowledge sources.

Examples include:

- books;
- scientific papers;
- regulations;
- historical archives;
- precedents;
- maps;
- BIM models;
- interviews.

Reference Objects preserve bibliographic information together with the architect's interpretation of their relevance.

---

## 5.8 Constraint Object

Represents conditions that restrict architectural possibilities.

Constraints may be:

- legal;
- environmental;
- structural;
- economic;
- cultural;
- temporal;
- programmatic.

Explicit representation of constraints improves reasoning transparency.

---

## 5.9 Opportunity Object

Represents conditions that expand architectural possibilities.

Unlike constraints, opportunities identify latent project potential.

Examples include:

- landscape qualities;
- existing structures;
- material reuse;
- climatic advantages;
- social value.

---

## 5.10 Hypothesis Object

Represents provisional architectural assumptions.

Hypotheses support exploratory reasoning before validation.

They remain explicitly distinguishable from validated knowledge.

---

## 5.11 Interpretation Object

An Interpretation Object captures the conceptual meaning assigned to architectural knowledge.

It represents how architects understand places, materials, historical contexts or environmental phenomena.

Interpretations may evolve throughout the project lifecycle.

Multiple interpretations may coexist simultaneously.

---

## 5.12 Framework Object

Framework Objects represent stable conceptual structures used to organize reasoning.

Examples include:

- Interpretative Frameworks;
- Design Frameworks;
- Evaluation Frameworks;
- Decision Frameworks.

Framework Objects enable consistent reasoning across projects while remaining reusable organizational assets.

---

# 6. Cognitive Relationships

Architectural knowledge acquires meaning through relationships.

ACKB therefore models not only cognitive objects but also the semantic connections that link them into coherent knowledge networks.

These relationships constitute the foundation of the ACKB Knowledge Graph.

---

## 6.1 Knowledge Dependencies

Defines prerequisite relationships between Knowledge Objects.

A dependency indicates that one object relies upon another for its interpretation or validity.

Dependencies enable consistent reasoning while preventing isolated knowledge fragments.

---

## 6.2 Traceability

Every cognitive object shall preserve explicit links to:

- its origin;
- supporting evidence;
- contributing agents;
- previous versions;
- derived objects;
- affected decisions.

Traceability enables complete reconstruction of architectural reasoning.

---

## 6.3 Semantic Inheritance

Certain cognitive objects inherit properties from more general concepts.

Inheritance reduces redundancy while maintaining semantic consistency throughout the repository.

Examples include:

- project principles inheriting studio principles;
- project frameworks inheriting organizational frameworks;
- specialized knowledge inheriting domain knowledge.

---

## 6.4 Interpretative Relationships

Interpretative Relationships connect Knowledge Objects with the conceptual frameworks through which they acquire meaning.

These relationships explicitly represent the architect's interpretative process.

Examples include:

- "interprets";
- "supports interpretation";
- "reframes";
- "contextualizes";
- "extends".

Interpretative relationships constitute one of the principal innovations introduced in ACKB v3.1.

---

## 6.5 Design Relationships

Design Relationships connect interpretation with architectural action.

They describe how conceptual understanding influences design decisions.

Typical relationships include:

- "guides";
- "motivates";
- "informs";
- "generates";
- "constrains";
- "enables".

These relationships bridge the transition from understanding to intervention.

---

## 6.6 Knowledge Lineage

Knowledge evolves continuously.

Knowledge Lineage preserves the complete genealogy of every cognitive object.

Lineage records:

- origin;
- evolution;
- transformations;
- derived knowledge;
- merged knowledge;
- archived knowledge.

Knowledge Lineage enables long-term organizational learning while preserving historical continuity.

---

## Cognitive Integrity

The Cognitive Core establishes the abstract reasoning architecture shared by all ACKB implementations.

Every specialized agent, repository operation and knowledge workflow defined in subsequent parts of this specification shall preserve the integrity of the Cognitive Core.

By separating cognitive concepts from implementation details, ACKB ensures that architectural knowledge remains stable, interpretable and reusable despite future technological evolution.