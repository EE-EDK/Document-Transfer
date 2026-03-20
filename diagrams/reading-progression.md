# Reading Progression Diagram

Book complexity and reading method mapped to cognitive development stages.

---

## Reading Method Progression

```mermaid
graph TD
    subgraph "Method Evolution"
        M1["Passive Listening<br/>0-6 months<br/>Prosody, rhythm, phoneme exposure"]
        M2["Interactive Listening<br/>6-18 months<br/>Pointing, naming, turn pages"]
        M3["Active Dialogic<br/>18-36 months<br/>PEER/CROWD method, retelling"]
        M4["Analytical Discussion<br/>3-5 years<br/>Character analysis, moral reasoning"]
        M5["Dialectic Reading<br/>5-7 years<br/>Defended positions, written response"]
    end

    M1 --> M2 --> M3 --> M4 --> M5
```

## Book Complexity Progression

```mermaid
graph LR
    subgraph "Content Complexity"
        B1["High-contrast images<br/>No narrative"]
        B2["Single objects<br/>Simple labels"]
        B3["Simple narrative<br/>Cause-effect"]
        B4["Character + consequence<br/>Simple moral"]
        B5["Archetypal narratives<br/>Complex morals"]
        B6["Historical/biographical<br/>Philosophical analysis"]
    end

    B1 -->|"0-3mo"| B2
    B2 -->|"3-12mo"| B3
    B3 -->|"12-24mo"| B4
    B4 -->|"2-4yr"| B5
    B5 -->|"4-7yr"| B6
```

## Cognitive Basis for Reading Stages

```mermaid
graph TD
    subgraph "Piaget's Cognitive Stages"
        P1["Sensorimotor<br/>0-2 years<br/>Learning through senses and action"]
        P2["Preoperational<br/>2-7 years<br/>Symbolic thinking, language explosion"]
        P3["Concrete Operational<br/>7+ years<br/>Logical reasoning about concrete events"]
    end

    subgraph "Reading Alignment"
        R1["Sensory books<br/>Texture, contrast, sound"]
        R2["Object permanence books<br/>Flaps, peek-a-boo"]
        R3["Narrative + pretend<br/>Stories with characters"]
        R4["Moral reasoning<br/>Fables, myths"]
        R5["Analytical<br/>History, biography"]
    end

    P1 --> R1
    P1 --> R2
    P2 --> R3
    P2 --> R4
    P3 --> R5

    subgraph "Philosophical Integration"
        PH1["Stories model<br/>emotional regulation"]
        PH2["Characters demonstrate<br/>dichotomy of control"]
        PH3["Discussion requires<br/>precise articulation"]
        PH4["Analysis develops<br/>defended reasoning"]
    end

    R3 -.-> PH1
    R4 -.-> PH2
    R4 -.-> PH3
    R5 -.-> PH4
```

## The Five Questions — Reading Discussion Framework

Applied from Stage 4 (18-36 months) onward, with increasing sophistication:

```mermaid
graph TD
    Q1["1. What happened?<br/>(Factual narration)"]
    Q2["2. What did the character choose?<br/>(Identifying decisions)"]
    Q3["3. What could they control?<br/>What couldn't they?<br/>(Dichotomy of Control)"]
    Q4["4. Did they tell the truth?<br/>(Articulation analysis)"]
    Q5["5. What happened as a result?<br/>(Consequence assessment)"]

    Q1 --> Q2 --> Q3 --> Q4 --> Q5

    Q5 --> EXT["Extension Questions"]
    EXT --> E1["What would you have done?"]
    EXT --> E2["How does this connect to your life?"]
    EXT --> E3["Was anyone responsible for what happened?"]

    style Q3 fill:#4a90d9,color:#fff
    style Q4 fill:#d94a4a,color:#fff
```

## Independent Reading Progression

```mermaid
gantt
    title Reading Independence Timeline
    dateFormat YYYY-MM
    axisFormat %b %Y

    section Parent Reads Aloud
    Sole reader (all content)            :2026-03, 2031-03
    Complex content (read-aloud)         :2031-03, 2033-03

    section Child Participation
    Points to pictures                   :2026-09, 2027-06
    "Reads" from memory                  :2028-06, 2029-06
    Recognizes letters and sight words   :2029-06, 2031-03
    Reads simple sentences               :2031-03, 2031-09
    Reads independently (easy books)     :2031-06, 2032-06
    Fluent independent reading           :2032-06, 2033-03

    section Discussion Complexity
    Names objects in pictures            :2027-03, 2028-03
    Answers simple questions             :2028-03, 2029-03
    Retells stories                      :2029-03, 2030-03
    Analyzes character choices           :2030-03, 2031-06
    Defends opinions with evidence       :2031-06, 2033-03
    Written reading responses            :2032-03, 2033-03
```
