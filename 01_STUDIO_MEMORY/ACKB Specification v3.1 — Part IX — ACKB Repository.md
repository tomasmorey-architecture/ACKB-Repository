
# Part IX — ACKB Repository

The ACKB Repository constitutes the persistent cognitive memory of the Architectural Knowledge Base.

Its purpose is not merely to store files or documents, but to preserve architectural understanding in a structured, traceable and reusable form.

Although many implementations may use conventional directory structures, databases or graph technologies, the repository is defined conceptually as a **Persistent Cognitive Repository**.

Every persistent cognitive object stored within the repository participates in a continuously evolving semantic knowledge graph.

Consequently, repository organization is defined independently of any specific storage technology.

---

# 23. Repository Architecture

The Repository Architecture defines the logical organization of persistent architectural knowledge.

Knowledge is organized according to cognitive purpose rather than document type.

The repository is composed of four principal domains.

Each domain possesses distinct responsibilities while remaining semantically connected to the others.

---

## 23.1 Studio Memory

Studio Memory preserves organizational knowledge accumulated across multiple projects.

Its contents represent the long-term intellectual capital of the architectural practice.

Typical contents include:

- methodologies;
- design principles;
- organizational standards;
- reusable frameworks;
- validated lessons learned;
- governance policies;
- agent profiles;
- office experience.

Studio Memory evolves continuously as completed projects contribute validated organizational knowledge.

---

## 23.2 Project Memory

Project Memory preserves the complete cognitive evolution of an individual architectural project.

Rather than storing isolated documents, Project Memory captures the project's architectural understanding.

Typical contents include:

- project context;
- Place Models;
- Interpretative Frameworks;
- Design Frameworks;
- hypotheses;
- decisions;
- strategies;
- concepts;
- outputs;
- project-specific references.

Project Memory constitutes the principal reasoning environment of the Project Coordinator.

---

## 23.3 Knowledge Library

The Knowledge Library contains reusable knowledge independent from individual projects.

Typical contents include:

- books;
- scientific papers;
- regulations;
- standards;
- architectural precedents;
- technical manuals;
- environmental references;
- historical documentation.

The Knowledge Library preserves external knowledge together with extracted metadata, Knowledge Objects and Reference Intent.

Knowledge within the library may support multiple projects simultaneously.

---

## 23.4 Agent Working Memory

Agent Working Memory stores temporary cognitive states required during reasoning.

Unlike persistent repository domains, Working Memory is dynamic.

Typical contents include:

- active context;
- selected Knowledge Objects;
- temporary hypotheses;
- intermediate reasoning;
- active conversations;
- incomplete analyses;
- proposed repository updates.

Working Memory is continuously reconstructed by the Project Coordinator and discarded after reasoning concludes.

Only validated knowledge may become persistent.

---

## Repository Organization

A conceptual implementation may be represented as follows:

```text id="z2q81h"
ACKB Repository
│
├── 01_STUDIO_MEMORY
│
├── 02_PROJECT_MEMORY
│
├── 03_KNOWLEDGE_LIBRARY
│
└── 04_AGENT_WORKING_MEMORY
```

This directory hierarchy represents one possible implementation.

The conceptual repository model remains independent from physical storage technology.

---

# 24. Repository Operations

The Repository supports a standardized set of cognitive operations.

Operations manipulate persistent cognitive objects rather than arbitrary files.

Every operation shall preserve semantic consistency, traceability and repository integrity.

---

## 24.1 Read

Retrieves persistent cognitive objects together with:

- metadata;
- relationships;
- version history;
- supporting references;
- associated frameworks.

Reading shall never modify repository state.

---

## 24.2 Create

Creates new persistent cognitive objects.

Creation requires:

- validated metadata;
- semantic identifiers;
- repository location;
- provenance information.

New objects remain fully traceable from their origin.

---

## 24.3 Update

Updates existing cognitive objects while preserving complete version history.

Updates may affect:

- metadata;
- relationships;
- framework associations;
- confidence levels;
- semantic classifications.

Previous versions shall remain permanently accessible.

---

## 24.4 Archive

Archives knowledge that is no longer actively used while preserving historical continuity.

Archiving never implies deletion.

Archived knowledge remains available for future interpretation and organizational learning.

---

## 24.5 Merge

Combines related cognitive objects into more coherent knowledge structures.

Merge operations may produce:

- Composite Knowledge Objects;
- consolidated frameworks;
- integrated reference systems;
- organizational methodologies.

Merge operations preserve complete Knowledge Lineage.

---

## 24.6 Rollback

Restores previous repository states when necessary.

Rollback operations shall preserve:

- historical integrity;
- audit records;
- version history;
- repository consistency.

Rollback represents controlled repository evolution rather than knowledge deletion.

---

## Repository Integrity

Every repository operation shall satisfy the following principles:

- semantic consistency;
- metadata completeness;
- version preservation;
- traceability;
- governance compliance.

Persistent modifications are performed exclusively through the Knowledge Manager.

---

# 25. Knowledge Ingestion

Knowledge Ingestion defines the cognitive workflow through which external information becomes persistent architectural knowledge.

The objective of Knowledge Ingestion is not document storage.

Its objective is the transformation of information into structured architectural understanding.

Every ingestion workflow should preserve provenance, interpretation and reasoning.

---

## 25.1 Information Sources

Knowledge may originate from multiple external sources.

Examples include:

- documents;
- books;
- scientific publications;
- regulations;
- drawings;
- BIM models;
- GIS datasets;
- photographs;
- interviews;
- conversations;
- websites;
- simulation outputs.

Each source represents information rather than knowledge.

Knowledge emerges only after interpretation.

---

## 25.2 Metadata Extraction

The first cognitive stage consists of extracting descriptive metadata.

Typical metadata includes:

- title;
- authors;
- publication information;
- document type;
- project association;
- semantic categories;
- source reliability;
- provenance.

Metadata provides the semantic identity required for repository management.

---

## 25.3 Knowledge Extraction

Knowledge Extraction identifies architectural understanding contained within the source.

Examples include:

- observations;
- concepts;
- principles;
- precedents;
- constraints;
- opportunities;
- decisions;
- hypotheses.

Knowledge is extracted independently from document structure.

The objective is semantic understanding rather than textual indexing.

---

## 25.4 Knowledge Objects

Validated knowledge is transformed into structured Knowledge Objects.

Each Knowledge Object receives:

- unique identifier;
- metadata;
- semantic relationships;
- provenance;
- confidence assessment;
- version information.

Knowledge Objects become reusable cognitive entities within the repository.

---

## 25.5 Interpretative Frameworks

Knowledge extraction alone is insufficient.

The ingestion workflow also identifies the interpretative significance of the acquired knowledge.

Whenever appropriate, the workflow generates:

- Reference Intent;
- Interpretative Frameworks;
- Design Framework associations;
- Project Interpretative System relationships.

This capability represents one of the principal innovations introduced by ACKB v3.1.

The repository preserves not only knowledge but also architectural understanding.

---

## 25.6 Repository Update

Following validation by the Knowledge Manager, accepted Knowledge Proposals become persistent repository objects.

Repository updates may include:

- creation of Knowledge Objects;
- metadata updates;
- framework creation;
- semantic relationship updates;
- Knowledge Graph maintenance;
- memory synchronization.

Every update remains fully auditable.

---

## Knowledge Ingestion Pipeline

The complete ingestion workflow is represented by the following cognitive pipeline:

```text id="y2e7tm"
Document
      │
      ▼
Metadata Extraction
      │
      ▼
Knowledge Extraction
      │
      ▼
Knowledge Objects
      │
      ▼
Reference Intent
      │
      ▼
Interpretative Frameworks
      │
      ▼
Project Interpretative System
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

This pipeline illustrates the central principle of ACKB:

Information is never stored directly as organizational knowledge.

Instead, external information is progressively transformed into structured, interpretable and reusable architectural intelligence through a governed cognitive process that preserves provenance, reasoning and long-term organizational learning.