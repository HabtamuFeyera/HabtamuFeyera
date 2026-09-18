<!-- HERO HEADER WITH ANIMATED WAVE & TYPING EFFECT -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0284c7,100:06b6d4&height=220&section=header&text=Habtamu%20Feyera&fontSize=42&fontAlignY=36&desc=Generative%20AI%20Engineer%20%7C%20Autonomous%20Agent%20Architect&descFontSize=19&descAlignY=58&fontColor=ffffff" width="100%" alt="Header Banner" />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=%E2%9A%A1+Architecting+Autonomous+Multi-Agent+Workflows;%F0%9F%94%8D+Building+Enterprise+Hybrid+RAG+Pipelines;%F0%9F%A7%A0+Fine-Tuning%2C+DSPy+%26+Model+Evaluation;%F0%9F%9A%80+Deploying+Production-Grade+LLMOps+Pipelines" alt="Typing SVG" />
  </a>

  <br/>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/habtamu-feyera-2447a917b/)
  [![Upwork](https://img.shields.io/badge/Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01b3a683f95e6cb332)
  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@habtamufeyer02)
  [![Twitter/X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Fey9487Feyera)
  [![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:habtamufeyera95@gmail.com)

  <br/><br/>
</div>

---

## ⚡ About Me

```python
class GenerativeAIEngineer:
    def __init__(self):
        self.name = "Habtamu Feyera"
        self.role = "Generative AI & Agentic Systems Engineer"
        self.location = "Addis Ababa, Ethiopia"
        self.specialties = [
            "Autonomous Multi-Agent Orchestration (LangGraph, CrewAI)",
            "Enterprise Hybrid RAG (Dense + Sparse + Re-ranking)",
            "Model Alignment & Systemic Evaluation (Ragas, TruLens)",
            "Low-Latency Inference & Production LLMOps"
        ]

    def build_system(self, specification: dict) -> "ProductionGradeAI":
        return autonomous_agent_pipeline(
            specification, 
            guardrails="strict", 
            eval_metrics=["faithfulness", "answer_relevance"]
        )
```

---

## 🏗️ Production AI System Architecture

```mermaid
flowchart LR
    User(["👤 User Query / API"]) --> Gateway["⚡ FastAPI Gateway"]
    Gateway --> Orchestrator{"🤖 LangGraph Orchestrator"}

    subgraph MultiAgent ["Autonomous Agent Layer"]
        Orchestrator --> Agent1["Planner & Task Decomposer"]
        Orchestrator --> Agent2["Tool & Code Execution Agent"]
        Orchestrator --> Agent3["Critic & Self-Correction Agent"]
    end

    subgraph HybridRAG ["Enterprise Hybrid RAG Pipeline"]
        Orchestrator --> RAG["Retrieval Controller"]
        RAG --> Dense[("Dense Semantic Vector DB")]
        RAG --> Sparse[("Sparse BM25 Index")]
        Dense --> ReRank["Cross-Encoder Re-ranker"]
        Sparse --> ReRank
    end

    MultiAgent --> Guardrails["🛡️ Guardrails & Evaluation (Ragas/TruLens)"]
    ReRank --> Guardrails
    Guardrails --> Output(["✨ Verified Production Response"])

    classDef darkCard fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc;
    classDef blueCard fill:#0369a1,stroke:#38bdf8,stroke-width:2px,color:#ffffff;
    class User,Gateway,Orchestrator,Guardrails,Output darkCard;
    class Agent1,Agent2,Agent3,RAG,Dense,Sparse,ReRank blueCard;
```

---

## 🛠️ Core Engineering Pillars

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Autonomous Multi-Agent Workflows</h3>
      <ul>
        <li><b>Stateful Architectures:</b> Cyclic graphs, memory persistence, dynamic routing, and sub-agent delegates using <b>LangGraph</b> & <b>CrewAI</b>.</li>
        <li><b>Deterministic Tool Calling:</b> Structured JSON validation, sandbox code execution, and Human-in-the-Loop (HITL) authorization gates.</li>
        <li><b>Self-Correction:</b> ReAct thought-action loops, reflection cycles, and automatic error backtracking.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔍 Enterprise RAG & Hybrid Retrieval</h3>
      <ul>
        <li><b>Multi-Stage Retrieval:</b> Dense semantic search (OpenAI / BGE) + Sparse BM25 + Cross-Encoder Re-ranking (Cohere / FlashRank).</li>
        <li><b>Intelligent Indexing:</b> Hierarchical chunks, parent-document retrievers, and multi-vector tables.</li>
        <li><b>Context Engineering:</b> Semantic caching, context compression, and hallucination reduction guardrails.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎯 Model Alignment, Fine-Tuning & Eval</h3>
      <ul>
        <li><b>Parameter-Efficient Tuning:</b> PEFT, LoRA, and QLoRA on domain-specific datasets.</li>
        <li><b>Prompt Optimization:</b> Declarative, algorithmic prompt compilation with <b>DSPy</b>.</li>
        <li><b>Automated Benchmarking:</b> End-to-end evaluation with <b>Ragas</b>, <b>TruLens</b>, and synthetic test datasets.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ LLMOps & Production Infrastructure</h3>
      <ul>
        <li><b>High-Throughput Serving:</b> <b>FastAPI</b>, <b>vLLM</b>, and <b>Ollama</b> for low-latency inference.</li>
        <li><b>Telemetry & Tracing:</b> Full trace observability via <b>LangSmith</b> and <b>Arize Phoenix</b>.</li>
        <li><b>Cloud Native:</b> Microservices containerized with Docker, deployed on Kubernetes, AWS, and GCP.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Interactive Project Deep Dives

<details open>
  <summary><b>⚖️ Autonomous Contract Lawyer — Contract QA RAG System</b></summary>
  <br/>
  
  > *Production-focused legal intelligence assistant built to parse, query, cross-examine, and verify complex legal agreements.*

  * **Repository:** [`HabtamuFeyera/contract_QA_Rag_project`](https://github.com/HabtamuFeyera/contract_QA_Rag_project)
  * **Core Innovations:**
    * Hierarchical parent-child document chunking preserving high-level clauses and atomic obligations.
    * Hybrid retrieval (Vector + BM25) coupled with cross-encoder re-ranking to capture subtle legal definitions.
    * Strict citation ground truth verification eliminating hallucinations on liability clauses.
  * **Tech Stack:** `Python` • `LangChain` • `Vector Database` • `FastAPI` • `Jupyter Notebook`
</details>

<details open>
  <summary><b>🕸️ LangGraph Agent UI — Stateful Multi-Agent Visualizer</b></summary>
  <br/>
  
  > *Full-stack reactive interface engineered for monitoring and interacting with cyclic multi-agent graphs in real time.*

  * **Repository:** [`HabtamuFeyera/langgraph-agent-ui`](https://github.com/HabtamuFeyera/langgraph-agent-ui)
  * **Core Innovations:**
    * Real-time WebSocket streaming of agent reasoning steps, state transitions, and token streams.
    * Human-In-The-Loop (HITL) interactive pause/resume mechanism for approving tool actions.
    * Granular state machine inspector showing live node execution histories.
  * **Tech Stack:** `Python` • `LangGraph` • `FastAPI` • `React` • `WebSockets`
</details>

<details open>
  <summary><b>🧠 GenAI-Agents — Modular Reasoning & Tool-Use Engine</b></summary>
  <br/>
  
  > *Extensible multi-agent framework powered by state-of-the-art LLMs with structured thought-action-observation loops.*

  * **Repository:** [`HabtamuFeyera/GenAI-Agents`](https://github.com/HabtamuFeyera/GenAI-Agents)
  * **Core Innovations:**
    * ReAct loop implementation with deterministic fallback handlers and error recovery.
    * Dynamic tool registry supporting calculation engines, live web retrieval, and custom API connectors.
    * Multi-model support across OpenAI, Anthropic, and Google Gemini endpoints.
  * **Tech Stack:** `Python` • `GPT-4 / Claude / Gemini API` • `Asyncio` • `Tool Calling`
</details>

---

## 💻 Technical Arsenal & Ecosystem

<div align="center">
  <!-- Interactive Animated Skill Icons -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,fastapi,docker,kubernetes,gcp,aws,postgres,redis,git,linux,react,nodejs&theme=dark" alt="Skill Icons" />
  </a>
  <br/><br/>

  <!-- Specialized AI & LLM Badges -->
  <p>
    <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
    <img src="https://img.shields.io/badge/LangGraph-23272A?style=flat-square&logo=diagram-next&logoColor=white" alt="LangGraph" />
    <img src="https://img.shields.io/badge/LlamaIndex-000000?style=flat-square&logo=databricks&logoColor=white" alt="LlamaIndex" />
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
    <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
    <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant" />
    <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white" alt="Pinecone" />
    <img src="https://img.shields.io/badge/ChromaDB-FF5722?style=flat-square&logo=circle&logoColor=white" alt="ChromaDB" />
    <img src="https://img.shields.io/badge/LangSmith-008080?style=flat-square&logo=speedtest&logoColor=white" alt="LangSmith" />
    <img src="https://img.shields.io/badge/DSPy-0284C7?style=flat-square&logo=probot&logoColor=white" alt="DSPy" />
  </p>
</div>

---

## 📊 Live GitHub Activity & Analytics

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=HabtamuFeyera&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Habtamu's GitHub Stats" height="175" />
      </td>
      <td>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=HabtamuFeyera&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="175" />
      </td>
    </tr>
  </table>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HabtamuFeyera&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>

---

## ✍️ Publications & Articles

I regularly author technical deep-dives into Agentic Workflows, Hybrid Retrieval, and LLMOps:
* 🌐 **Read my articles on [Medium (@habtamufeyer02)](https://medium.com/@habtamufeyer02)**

---

## 🤝 Let's Build Together

Whether you are looking to architect an **Autonomous Multi-Agent Workflow**, deploy an **Enterprise RAG System**, or need specialized consulting on **Generative AI Solutions**, feel free to reach out:

<div align="center">
  <a href="https://www.upwork.com/freelancers/~01b3a683f95e6cb332">
    <img src="https://img.shields.io/badge/Hire%20Me%20on-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/habtamu-feyera-2447a917b/">
    <img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:habtamufeyera95@gmail.com">
    <img src="https://img.shields.io/badge/Direct-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0284c7,100:06b6d4&height=120&section=footer" width="100%" alt="Footer Banner" />
</div>
