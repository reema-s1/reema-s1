<div align="center">

# Reema Sarkar

**AI agents for operations · observability · data platforms**

<a href="https://reema-s1.netlify.app/"><img src="https://img.shields.io/badge/blog-reema--s1.netlify.app-c3b1e1?style=flat&logo=netlify&logoColor=white" /></a>
<a href="mailto:reemasarks@gmail.com"><img src="https://img.shields.io/badge/reemasarks@gmail.com-f4a7b9?style=flat&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/reema-sarkar-0601a02b8/"><img src="https://img.shields.io/badge/LinkedIn-a7c7e7?style=flat&logo=linkedin&logoColor=white" /></a>

</div>

### about me

CS undergrad at PES University, Bangalore (class of 2027).

I learn things by building them. Lately that means building AI agents that take toil off the people running a platform:
an agent that triages a broken pipeline and posts the cause and the runbook in Slack before anyone opens a log,
and the dashboards that show whether the platform (and the agent) is actually healthy.

I care about AI tools I can trust. My agents run on read-only tools, ask a human before they change anything,
and get scored against ground truth and a non-AI baseline. I build with Claude Code, and I review what it writes before it ships.

I also write about what I learn while building: one concept at a time, in plain English, at **[reema-s1.netlify.app](https://reema-s1.netlify.app/)**.

### projects

**AI for platform support**

- **[Beacon](https://github.com/reema-s1/Beacon)**: an AI support copilot for an Airflow data platform. Prometheus alerts trigger an LLM agent that finds the root cause and runbook and posts them to Slack. It also includes a Slack bot for self-service, Grafana dashboards and an MCP server.
- **[pulse](https://github.com/reema-s1/pulse)**: an observability platform for AI agents. It traces every LLM and tool call and shows error rate, latency and cost on a dashboard, with root-cause analysis for failed runs.
- **[AutoFix](https://github.com/reema-s1/AutoFix)**: an LLM agent that diagnoses and fixes failing builds and tests in a plan → act → observe loop.

**LLM reliability**

- **[corrective-rag](https://github.com/reema-s1/corrective-rag)**: RAG that checks its own retrieval before answering. Beacon uses this approach to find runbooks.
- **[selfcheckgpt-hallucination-detection](https://github.com/reema-s1/selfcheckgpt-hallucination-detection)**: catches LLM hallucinations without access to the model's internals.

**Systems**

- **[quorum](https://github.com/reema-s1/quorum)**: a distributed key-value store with replication and quorum reads and writes, built to see what really happens when a node dies halfway through a write.

### stack

**Agents / LLMs**
<br/>
<img src="https://img.shields.io/badge/LLM%20Agents-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/Tool%20Calling-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/MCP-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/RAG-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/FAISS-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/LLM--as--judge-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/Claude%20Code-c3b1e1?style=flat&logo=anthropic&logoColor=white" />

**Observability / Data Platform**
<br/>
<img src="https://img.shields.io/badge/Prometheus-f4a7b9?style=flat&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-f4a7b9?style=flat&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Alertmanager-f4a7b9?style=flat" />
<img src="https://img.shields.io/badge/Apache%20Airflow-f4a7b9?style=flat&logo=apacheairflow&logoColor=white" />

**APIs / Chat**
<br/>
<img src="https://img.shields.io/badge/Slack%20API-b5d8cc?style=flat&logo=slack&logoColor=white" />
<img src="https://img.shields.io/badge/Webhooks-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/REST%20APIs-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/FastAPI-b5d8cc?style=flat&logo=fastapi&logoColor=white" />

**Backend / Infra**
<br/>
<img src="https://img.shields.io/badge/Python-a7c7e7?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-a7c7e7?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-a7c7e7?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-a7c7e7?style=flat&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/React-a7c7e7?style=flat&logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/pytest-a7c7e7?style=flat&logo=pytest&logoColor=white" />
