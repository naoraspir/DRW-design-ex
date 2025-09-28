# AI/ML Technology Stack

## Core AI/ML Technologies Enabling the Platform

### Model Serving & Inference

**vLLM + TensorRT**: High-performance model serving

- **vLLM**: Optimized LLM inference with dynamic batching
- **TensorRT**: GPU acceleration for specialized models
- **Why**: Efficient inference for production workloads

### ML Frameworks

**PyTorch or Hugging Face**: Model development and deployment

- **PyTorch**: Fine-tuning framework with full control
- **Hugging Face**: Simplified fine-tuning with pre-built pipelines
- **Why**: Both support fine-tuning and specialized model creation

### Vector & Knowledge Storage

**GCP Vector Search + Pinecone**: Vector storage options

- **Vector Search**: Managed, scalable production vector database
- **Pinecone**: Alternative for specialized use cases
- **Why**: Powers RAG workflows with reliable retrieval

### MLOps & Experiment Tracking

**Vertex AI + MLflow**: Model lifecycle management
- **Vertex AI**: Managed training, deployment, and monitoring
- **MLflow**: Experiment tracking and model versioning
- **Why**: Enables fine-tuning infrastructure and specialized model management

### Agent & Workflow Runtime

**LangGraph + Redis**: Agentic workflow execution
- **LangGraph**: Agent state management and planning
- **Redis**: Session persistence and workflow state
- **Why**: Powers ergonomic agentic workflows with memory and reasoning

## Technology Integration Pattern

```text
PyTorch/Transformers → vLLM/TensorRT → Vector Search → LangGraph → User Interface
       ↓                    ↓              ↓           ↓
   MLflow/Vertex        Model Serving   RAG Engine   Agent Runtime
```

## Why This Stack

**GCP-Native**: Leverages managed services for reliability and scale
**Performance-Optimized**: vLLM and TensorRT for production inference
**Agent-Ready**: LangGraph enables true agentic capabilities
**Enterprise-Grade**: MLflow and Vertex AI for production MLOps

This stack directly enables all 4 platform capabilities through integrated, production-ready AI/ML technologies.