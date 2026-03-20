# Philosophical Framework Diagram

How Stoic and CBT concepts layer onto developmental stages.

---

## Framework Application Across Stages

```mermaid
graph TB
    subgraph "Core Principles (Timeless)"
        P1[Dichotomy of Control<br/>Epictetus]
        P2[Truth & Articulation<br/>Peterson]
        P3[Maintenance of Local Order<br/>Peterson / Harvard]
    end

    subgraph "Stage 0-2: Foundation (0-12mo)"
        S0A[Parental modeling of<br/>emotional regulation]
        S0B[Constant narration<br/>language exposure]
        S0C[Predictable environment<br/>consistent routines]
    end

    subgraph "Stage 3-4: Introduction (12-36mo)"
        S1A[Gentle redirection<br/>'What can you do now?']
        S1B[Word before action<br/>communication attempts required]
        S1C[Clean-up routine<br/>participatory order]
    end

    subgraph "Stage 5: Explicit Teaching (3-5yr)"
        S2A[Named concept<br/>'Things I can/can't change']
        S2B[Tell me exactly<br/>what happened]
        S2C[Own your space<br/>expanded responsibility]
    end

    subgraph "Stage 6: Analytical Application (5-7yr)"
        S3A[Applied to stories<br/>history, social life]
        S3B[Defended positions<br/>dialectic discussion]
        S3C[Full domain mastery<br/>time management, chores]
    end

    P1 --> S0A --> S1A --> S2A --> S3A
    P2 --> S0B --> S1B --> S2B --> S3B
    P3 --> S0C --> S1C --> S2C --> S3C

    style P1 fill:#4a90d9,color:#fff
    style P2 fill:#d94a4a,color:#fff
    style P3 fill:#4ad94a,color:#000
```

## Teaching Method Evolution

```mermaid
graph LR
    subgraph "Method"
        M1[Modeling<br/>Parent demonstrates]
        M2[Redirection<br/>Parent applies for child]
        M3[Co-Application<br/>Parent and child together]
        M4[Guided Practice<br/>Child applies with help]
        M5[Independent Application<br/>Child applies alone]
    end

    M1 -->|"0-12mo"| M2
    M2 -->|"12-24mo"| M3
    M3 -->|"24-36mo"| M4
    M4 -->|"3-5yr"| M5

    subgraph "Cognitive Basis"
        V1[Vygotsky: Zone of<br/>Proximal Development]
        V2[Scaffolding decreases<br/>as competence increases]
    end

    V1 -.-> M3
    V1 -.-> M4
    V2 -.-> M5
```

## Emotional Regulation Pathway

```mermaid
graph TD
    A[External Event<br/>Something happens] --> B[Emotion Arises<br/>Automatic, valid, felt]
    B --> C{Gap<br/>The Stoic Moment}
    C -->|Untrained| D[Reactive Response<br/>Tantrum, aggression,<br/>withdrawal, shutdown]
    C -->|Trained| E[Awareness<br/>'I notice I'm feeling X']
    E --> F[Assessment<br/>'Can I control what happened?']
    F -->|No| G[Acceptance<br/>'I can't change that']
    F -->|Yes| H[Action Plan<br/>'Here's what I'll do']
    G --> I[Redirect<br/>'What CAN I control?']
    I --> H
    H --> J[Articulate<br/>State the plan clearly]
    J --> K[Act<br/>Chosen response]

    style C fill:#f9c74f,color:#000
    style E fill:#90be6d,color:#000
```

## The Articulation Ladder

```mermaid
graph BT
    A["Points and grunts<br/>(12-15mo)"] --> B["Single words<br/>(15-24mo)"]
    B --> C["Two-word phrases<br/>(24-30mo)"]
    C --> D["Simple sentences<br/>(30-36mo)"]
    D --> E["'Tell me what happened'<br/>(3-4yr)"]
    E --> F["'Tell me exactly what happened'<br/>(4-5yr)"]
    F --> G["'I think X because Y'<br/>(5-6yr)"]
    G --> H["Defended positions,<br/>dialectic discussion<br/>(6-7yr)"]

    style A fill:#e0e0e0
    style H fill:#4a90d9,color:#fff
```

## Integration: How the Three Principles Reinforce Each Other

```mermaid
graph TD
    subgraph "Daily Life Example: Lost Toy"
        E1[Child can't find toy<br/>Gets upset]
        E2[Dichotomy: Can you<br/>control that it's lost? No]
        E3[Articulation: Can you<br/>tell me where you last had it?]
        E4[Order: If it was put<br/>back in its place, would<br/>this have happened?]
        E5[Resolution: Let's look<br/>together, then make sure<br/>it goes back in its spot]
    end

    E1 --> E2
    E2 --> E3
    E3 --> E4
    E4 --> E5

    subgraph "Skills Practiced"
        S1[Emotional regulation]
        S2[Precise communication]
        S3[Executive function]
        S4[Problem solving]
    end

    E2 -.-> S1
    E3 -.-> S2
    E4 -.-> S3
    E5 -.-> S4
```
