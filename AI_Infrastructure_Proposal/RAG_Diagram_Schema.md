# RAG Architecture Diagram - Copy This ASCII

## DIAGRAM 2: RAG Architecture & Integration

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    RAG KNOWLEDGE BACKBONE                                             │
├─────────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                       │
│  ┌─────────────┐    ┌──────────────────────────────┐    ┌─────────────────────────────────────────┐ │
│  │DATA SOURCES │    │    PROCESSING PIPELINE       │    │         CORE RAG ENGINE                 │ │
│  │             │    │                              │    │                                         │ │
│  │• DRW Docs   │───→│ Document    → Chunking    →  │───→│  ┌─────────────────────────────────┐   │ │
│  │• Databases  │    │ Processing    Embedding      │    │  │    GCP Vector Search            │   │ │
│  │• APIs       │    │              Generation      │    │  │    (Vector Database)            │   │ │
│  │• Real-time  │    │                              │    │  └─────────────────────────────────┘   │ │
│  │  Data       │    └──────────────────────────────┘    │                                         │ │
│  └─────────────┘                                        │  ┌─────────────────────────────────┐   │ │
│                                                         │  │    Hybrid Search Engine         │   │ │
│                                                         │  │  • Semantic Similarity          │   │ │
│                                                         │  │  • Keyword Matching             │   │ │
│                                                         │  │  • Business Rules               │   │ │
│                                                         │  └─────────────────────────────────┘   │ │
│                                                         │                                         │ │
│                                                         │  ┌─────────────────────────────────┐   │ │
│                                                         │  │    Reranking Service            │   │ │
│                                                         │  └─────────────────────────────────┘   │ │
│                                                         └─────────────────────────────────────────┘ │
│                                                                            │                         │
│                                                                            ▼                         │
│  ┌─────────────────────────────────────────────────────────────────────────────────────────────────┐ │
│  │                            INTEGRATION WITH ALL 4 DRW REQUIREMENTS                             │ │
│  ├─────────────────────────────────────────────────────────────────────────────────────────────────┤ │
│  │                                                                                                 │ │
│  │ ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────────────────┐ │ │
│  │ │  24-Hour Model  │  │   Fine-Tuning   │  │   Specialized   │  │    Ergonomic Workflows     │ │ │
│  │ │   Integration   │  │   Integration   │  │     Models      │  │                             │ │ │
│  │ │                 │  │                 │  │                 │  │                             │ │ │
│  │ │• New models →   │  │• RAG context →  │  │• Domain-specific│  │• Pre-built RAG components   │ │ │
│  │ │  Standardized   │  │  Training data  │  │  retrieval      │  │• Template queries           │ │ │
│  │ │  RAG API        │  │• Improved models│  │• Specialized    │  │• Visual workflow builder    │ │ │
│  │ │• Instant domain │  │  enhance RAG    │  │  ranking        │  │• Business-friendly ops      │ │ │
│  │ │  knowledge      │  │                 │  │                 │  │                             │ │ │
│  │ └─────────────────┘  └─────────────────┘  └─────────────────┘  └─────────────────────────────┘ │ │
│  └─────────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                     │                                                │
│                                                     ▼                                                │
│  ┌─────────────────────────────────────────────────────────────────────────────────────────────────┐ │
│  │                                OUTPUT & USAGE                                                   │ │
│  │                                                                                                 │ │
│  │     ┌─────────────────┐         ┌─────────────────┐         ┌─────────────────────────────┐   │ │
│  │     │  Chat Interface │         │ Workflow Engine │         │      API Endpoints          │   │ │
│  │     │                 │         │                 │         │                             │   │ │
│  │     │• RAG-enhanced   │         │• Knowledge-     │         │• External integrations      │   │ │
│  │     │  responses      │         │  powered agents │         │• Third-party systems        │   │ │
│  │     │• Context-aware  │         │• Autonomous     │         │• Custom applications        │   │ │
│  │     │  conversations  │         │  workflows      │         │                             │   │ │
│  │     └─────────────────┘         └─────────────────┘         └─────────────────────────────┘   │ │
│  └─────────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                       │
└─────────────────────────────────────────────────────────────────────────────────────────────────────┘

                              CONTINUOUS LEARNING LOOP
                    User Interactions → Feedback → Improved Retrieval → Better Responses
```

## Visual Notes for Your Diagram Tool:
- Use different colors for each major section (Data Sources, Processing, Core Engine, Integration, Output)
- Make arrows bold and directional
- Highlight "RAG KNOWLEDGE BACKBONE" as the central theme
- Use consistent styling with your DIAGRAM 1