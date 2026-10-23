# Ícaro Glauco

### Reconstructive linguistic re-education for capable AI

At the center of my work is **reconstructive linguistic re-education**: developing an LLM from its raw, near-baseline language capability toward useful, domain-grounded performance. The broader direction joins that capability with business-system models and persistent memory in **framework-agnostic B2B applications**.

```mermaid
flowchart TB
  RAW["Raw, near-baseline<br/>LLM capability"] --> RE["Reconstructive linguistic<br/>re-education"] --> CAP["Useful, domain-grounded<br/>language capability"]

  subgraph B2B["B2B operating context"]
    SM["System model<br/>business state and rules"]
    MEM["Persistent memory<br/>continuity over time"]
    APP["Autonomous application<br/>framework-agnostic"]
    FLOW["Business workflows<br/>tools, review, outcomes"]

    CAP --> APP
    SM --> APP
    MEM <--> APP
    APP --> FLOW
    FLOW --> MEM
  end

  classDef source fill:#f2f3f5,stroke:#818894,color:#252a33,stroke-width:1.5px;
  classDef reconstruction fill:#fff1df,stroke:#c47b26,color:#57350e,stroke-width:2px;
  classDef concept fill:#edf3ff,stroke:#5271b8,color:#18294b,stroke-width:1.5px;
  classDef app fill:#213d68,stroke:#213d68,color:#ffffff,stroke-width:2px;
  classDef workflow fill:#edf7f2,stroke:#4f8d72,color:#173c2c,stroke-width:1.5px;
  class RAW source;
  class RE reconstruction;
  class CAP,SM,MEM concept;
  class APP app;
  class FLOW workflow;
```

## Current project work

| Project | What is taking shape |
| --- | --- |
| [Prumo Licitações](https://github.com/glaucodeveloper/prumo-licitacoes) | A procurement workspace that finds public notices, connects them to company profiles, and supports document review across official sources. |
| [JUCEB Conhecimentos](https://github.com/glaucodeveloper/juceb-conhecimentos) | Curated company, tax, and fiscal knowledge for Bahia, prepared for memory-based research workflows. |
| [Lumira](https://github.com/glaucodeveloper/lumira-frontend-cognoscere) | An interactive education and competency-learning prototype, presented through a navigable product lab. |

## Patent area

Autonomous AI applications for B2B operations with persistent memory.

## Links

[Website](https://icaroglauco.online) · [GitHub repositories](https://github.com/glaucodeveloper?tab=repositories) · [Email](mailto:icaroglaucooliveira@gmail.com)
