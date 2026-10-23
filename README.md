# Ícaro Glauco

### Autonomous AI for practical B2B work

My current work explores how foundation models, explicit business-system models, and persistent memory can operate together inside autonomous B2B applications. The architecture is **framework-agnostic**; the focus is the coordination of these concepts in real business workflows.

```mermaid
flowchart LR
  subgraph B2B["B2B operating context"]
    FM["Foundation model<br/>interpretation and generation"]
    SM["System model<br/>business state and rules"]
    MEM["Persistent memory<br/>continuity over time"]
    APP["Autonomous application<br/>framework-agnostic"]
    FLOW["Business workflows<br/>tools, review, outcomes"]

    FM --> APP
    SM --> APP
    MEM <--> APP
    APP --> FLOW
    FLOW --> MEM
  end

  classDef concept fill:#edf3ff,stroke:#5271b8,color:#18294b,stroke-width:1.5px;
  classDef app fill:#213d68,stroke:#213d68,color:#ffffff,stroke-width:2px;
  classDef workflow fill:#edf7f2,stroke:#4f8d72,color:#173c2c,stroke-width:1.5px;
  class FM,SM,MEM concept;
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
