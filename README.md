<p align="center">
  <img src="banner/banner.svg" alt="Leon Achata — Software Engineer, GenAI Systems" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/leonachata"><img src="https://img.shields.io/badge/LinkedIn-leonachata-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:leonyemin@gmail.com"><img src="https://img.shields.io/badge/Email-leonyemin%40gmail.com-D97757?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Montevideo%2C%20UY-161412?style=flat-square" alt="Montevideo, Uruguay" />
  <img src="https://img.shields.io/badge/Languages-EN%20(C2)%20·%20ES%20·%20PT-161412?style=flat-square" alt="Languages" />
</p>

## About me

I'm a **Software Engineer** who designs and ships production systems end to end — from typed Python and TypeScript backends to cloud infrastructure and the web front ends that sit on top. My specialty is **Generative AI**: LLM agents, RAG pipelines and workflow automation built to enterprise standards of reliability, security and scale.

Currently I'm a **GenAI Engineer at TCS, working on enterprise projects for Apple**, where I lead the design and delivery of LLM-powered automation that connects internal tools into end-to-end workflows, alongside engineering teams across the Americas and APAC.

```python
leon = {
    "role":      "Software Engineer · GenAI Systems",
    "now":       "GenAI Engineer @ TCS — enterprise projects for Apple",
    "builds":    ["LLM agents", "RAG pipelines", "APIs & backends", "full-stack web apps"],
    "ships_on":  ["AWS", "Docker", "Kubernetes (EKS)"],
    "studying":  "B.Sc. Software Engineering — Universidad Católica del Uruguay",
}
```

## What I work on

- **Agentic systems** — multi-agent orchestration with LangGraph, Google ADK and MCP; native tool calling, planning, self-correction and human-in-the-loop flows.
- **RAG & retrieval** — structure-aware ingestion, hybrid retrieval (dense + BM25 + learned sparse), cross-encoder reranking, cited answers and retrieval evals.
- **Backend engineering** — typed, tested services in Python (FastAPI, Pydantic) and TypeScript (Node.js), REST and GraphQL APIs, SQL and NoSQL data models.
- **Full-stack products** — Next.js / React front ends connected to AI backends, with streaming UIs, from prototype to production.
- **Cloud & DevOps** — containerized deployments on AWS (EKS, Lambda, Bedrock, S3, IoT Core, CloudWatch), infrastructure as code with AWS CDK and Terraform, CI/CD.
- **Data engineering** — PySpark pipelines and data processing for analytics and model workloads.

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/LeonAchata/SQL-Agent"><img src="https://raw.githubusercontent.com/LeonAchata/SQL-Agent/main/docs/ui.png" alt="SQL Agent UI" /></a>
      <h3><a href="https://github.com/LeonAchata/SQL-Agent">SQL Agent</a></h3>
      <p>Ask any SQL database questions in plain language. Schema-agnostic catalog via SQLAlchemy, a <b>sqlglot AST guard</b> plus read-only execution, a self-repair loop, PII masking and an <b>execution-accuracy benchmark</b> against gold SQL. Streams every step to a Next.js UI.</p>
      <p><a href="https://github.com/LeonAchata/SQL-Agent/actions/workflows/ci.yml"><img src="https://github.com/LeonAchata/SQL-Agent/actions/workflows/ci.yml/badge.svg" alt="CI" /></a><br/><sub>LangGraph · Claude · FastAPI · Next.js · PostgreSQL / MySQL / SQLite</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/LeonAchata/DocuChat-AI"><img src="https://raw.githubusercontent.com/LeonAchata/DocuChat-AI/main/docs/ui.png" alt="DocuChat UI" /></a>
      <h3><a href="https://github.com/LeonAchata/DocuChat-AI">DocuChat</a></h3>
      <p>Grounded answers from your documents. <b>Dense + BM25 + SPLADE</b> hybrid retrieval fused with RRF, cross-encoder reranking, MMR, a <b>corrective-RAG loop that abstains</b> when evidence is weak, and Claude native citations down to the sentence.</p>
      <p><a href="https://github.com/LeonAchata/DocuChat-AI/actions/workflows/ci.yml"><img src="https://github.com/LeonAchata/DocuChat-AI/actions/workflows/ci.yml/badge.svg" alt="CI" /></a><br/><sub>LangGraph · Claude · pgvector · ONNX · Next.js</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/LeonAchata/Toolbox-Gateway"><img src="https://raw.githubusercontent.com/LeonAchata/Toolbox-Gateway/main/docs/ui.png" alt="Toolbox Gateway console" /></a>
      <h3><a href="https://github.com/LeonAchata/Toolbox-Gateway">Toolbox Gateway</a></h3>
      <p>Self-hosted platform for tool-using agents: an <b>LLM gateway</b> putting OpenAI, Gemini and Bedrock behind one API with native tool calling, a toolbox served over JSON and <b>native MCP</b>, and a console that traces every call with latency, tokens and cost.</p>
      <p><a href="https://github.com/LeonAchata/Toolbox-Gateway/actions/workflows/ci.yml"><img src="https://github.com/LeonAchata/Toolbox-Gateway/actions/workflows/ci.yml/badge.svg" alt="CI" /></a><br/><sub>LangGraph · MCP · FastAPI · WebSockets · Docker</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/LeonAchata/InvoiceParser-AI"><img src="https://raw.githubusercontent.com/LeonAchata/InvoiceParser-AI/main/docs/screenshot-light.png" alt="InvoiceParser AI UI" /></a>
      <h3><a href="https://github.com/LeonAchata/InvoiceParser-AI">InvoiceParser AI</a></h3>
      <p>Drop an invoice in <b>17 formats</b> (scanned PDFs, phone photos, UBL XML, e-mails with attachments) and a vision LLM fills the form. Deterministic checks validate totals, tax and RUC check digits, and flag what needs a human look.</p>
      <p><a href="https://github.com/LeonAchata/InvoiceParser-AI/actions/workflows/ci.yml"><img src="https://github.com/LeonAchata/InvoiceParser-AI/actions/workflows/ci.yml/badge.svg" alt="CI" /></a><br/><sub>LangGraph · Vision LLMs · FastAPI · SQLite</sub></p>
    </td>
  </tr>
</table>

### More systems

| Project | What it is | Built with |
| --- | --- | --- |
| [**AWS RAG System**](https://github.com/LeonAchata/AWS-RAG-System) | Serverless RAG on AWS: pgvector + full-text search fused with RRF, Bedrock reranking, Claude cited answers, idempotent event-driven ingestion, alarms, dashboards and X-Ray tracing. | AWS CDK · Lambda · Bedrock · PostgreSQL |
| [**Local RAG Agent**](https://github.com/LeonAchata/Local-RAG-Agent) | Fully offline Q&A over your files: structure-aware legal chunking, hybrid retrieval, incremental re-indexing and a built-in eval (Hit@k, MRR). No API keys, nothing leaves the machine. | Ollama · ChromaDB · Python package |
| [**RoutePlanner AI**](https://github.com/LeonAchata/RoutePlanner-AI) | Paste stops as free text, get the proven-optimal visiting order: Held-Karp DP up to 12 stops, OR-Tools guided local search beyond, on directed real travel-time matrices. | LangGraph · Google Maps · OR-Tools |
| [**CardioSync**](https://github.com/LeonAchata/CardioSync) | ESP32 Holter monitor: 250 Hz FreeRTOS ECG sampling, mutual-TLS MQTT to AWS IoT Core, direct-to-S3 uploads and serverless ECG filtering with R-peak detection. | C++ · AWS IoT · Terraform |

### How I build

Every repository above follows the same bar:

- **Tested without secrets** — test suites mock the LLM and external APIs, so anyone can clone and run them; CI runs on every push.
- **Typed and validated** — Pydantic schemas at every boundary, strict typing where it pays off.
- **Measured, not assumed** — retrieval and agent quality are tracked with benchmarks (execution accuracy, Hit@k, MRR) instead of vibes.
- **Safe by default** — read-only execution, least-privilege roles and credentials, guards on model output, graceful degradation when a dependency fails.
- **Reproducible** — Docker Compose or infrastructure as code (CDK, Terraform), one-command setup and documented architecture.

## Tech stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=python,ts,js,bash,c&theme=dark" alt="Python, TypeScript, JavaScript, Bash, C" />
</p>

**Backend & web**
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,nextjs,react,tailwind,graphql&theme=dark" alt="FastAPI, Node.js, Next.js, React, Tailwind, GraphQL" />
</p>

**Data**
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite&theme=dark" alt="PostgreSQL, MySQL, MongoDB, Redis, SQLite" />
</p>

**Cloud & DevOps**
<p>
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,terraform,githubactions,git,linux&theme=dark" alt="AWS, Azure, Docker, Kubernetes, Terraform, GitHub Actions, Git, Linux" />
</p>

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)
![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=flat-square&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

## Experience

| Role | Company | Period |
| --- | --- | --- |
| **GenAI Engineer** — enterprise LLM workflow automation, RAG and agent orchestration | TCS · client: Apple | Mar 2026 – present |
| **AI Engineer** — multi-agent systems (LangGraph, MCP) deployed on AWS EKS/Bedrock | JLR Analytics | Sep 2025 – Feb 2026 |
| **AI/ML Developer** — LLM agents and RAG pipelines for research workloads | Universidad Peruana Cayetano Heredia | Apr 2025 – Sep 2025 |
| **AI/ML Developer · Data Scientist** — NLP models, transformers, data pipelines | Cardiomed SAC | Oct 2023 – Mar 2025 |
| **Data Scientist · Data Analyst** | Asociación Educativa Waymaku | Jan 2020 – Oct 2023 |

## Certifications

![AWS Certified AI Practitioner](https://img.shields.io/badge/AWS-Certified%20AI%20Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure Fundamentals](https://img.shields.io/badge/Azure-Fundamentals%20(AZ--900)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![IBM Machine Learning](https://img.shields.io/badge/IBM-Machine%20Learning%20Professional-052FAD?style=flat-square&logo=ibm&logoColor=white)
![DataCamp Associate AI Engineer](https://img.shields.io/badge/DataCamp-Associate%20AI%20Engineer-03EF62?style=flat-square&logo=datacamp&logoColor=black)

---

<p align="center"><sub>Open to freelance projects and collaborations — reach out on <a href="https://www.linkedin.com/in/leonachata">LinkedIn</a> or by <a href="mailto:leonyemin@gmail.com">email</a>.</sub></p>
