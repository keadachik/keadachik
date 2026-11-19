## Hi, I'm Ken Adachi

Customer-facing enterprise architect in Tokyo with 20+ years in enterprise IT (IBM, Salesforce, Microsoft, ServiceNow, Dynatrace).
I help enterprises adopt observability and AI-assisted incident investigation, and I care about one question for every AI agent: **is it running, and is it right?**

What I work on now:

- Designing agentic workflows that stay trustworthy: deterministic queries for facts, the LLM to explain, people to confirm
- Evaluating agents against faults I inject myself, so the right answer is known before the agent runs
- Tracing and evaluating LLM applications with OpenTelemetry, Dynatrace and Arize Phoenix

### Featured work

| Repository | What it shows |
|---|---|
| [dynatrace-ai-observability-notes](https://github.com/keadachik/dynatrace-ai-observability-notes) | Testing Dynatrace's AI agents (SRE Agent, Kubernetes Troubleshooting) against known faults; adapting workflow templates so that DQL does the math and the LLM only writes; reproducing seven failure modes of a multi-agent Bedrock app and comparing what Dynatrace and Phoenix can see |
| [swift-fraud-pipeline-observability](https://github.com/keadachik/swift-fraud-pipeline-observability) | Tracing an agentic SWIFT fraud-screening pipeline with Phoenix, which revealed that the LLM's HOLD decision was never used downstream; golden tests and LLM-as-a-judge |
| [release-validation-dynatrace-lab](https://github.com/keadachik/release-validation-dynatrace-lab) | Automating release validation: CI sends a deployment event, a workflow scores the new version with Site Reliability Guardian (availability, latency, error logs, canary diff, Davis events, SAST) and emails the verdict; tested through staging-to-production promotion and rollback |
| [postfix-deferred-dynatrace-lab](https://github.com/keadachik/postfix-deferred-dynatrace-lab) | Reproducing a Microsoft 365 outage against a real postfix MTA, then turning mail logs into queue metrics and alerts with OneAgent log ingest and OpenPipeline |
| [oneagent-log-module-cpu-quota-lab](https://github.com/keadachik/oneagent-log-module-cpu-quota-lab) | Testing a new OneAgent feature that caps log-collection CPU: measuring CPU, ingest lag and completeness (4.49M lines, none lost) to show how to choose a limit |
| [jvm-agent-memory-lab](https://github.com/keadachik/jvm-agent-memory-lab) | Measuring what drives a JVM APM agent's memory overhead (load vs. code executed vs. JIT) on Kubernetes, with a no-agent control group |

All are written in Japanese; the first two include an English summary.

### Learning

- **Certifications:** CKA, CKAD, TOGAF Standard 9.2, Open Agile Architecture Practitioner, Azure Solutions Architect Expert ([Credly](https://www.credly.com/users/ken-adachi.ba926f51))
- **Udacity, 2025–2026:** Agentic AI (Nanodegree), Agentic AI for Financial Services, Model Context Protocol, Agentic Workflows with Google ADK, Agentic Engineering with Claude Agent SDK, AgentOps, LLMOps, AI Security GRC, AI Threat Modeling, AI Red Teaming, AWS Cloud Architect (Nanodegree)
- **Earlier course projects (archived):** [ML Engineer capstone (2019)](https://github.com/keadachik/Machine-Learning-Nanodegree-Capstone-Project) · [Kafka + Spark streaming (2020)](https://github.com/keadachik/sfcrime) · [Microservices on Kubernetes (2020)](https://github.com/keadachik/udagram) · [CI/CD to Azure (2021)](https://github.com/keadachik/flask-ml-azure-serverless) · [Data analysis (2025)](https://github.com/keadachik/udacity-dsblogpost)

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/ken-adachi-b007b07)

<sub>Views here are my own and do not represent my employer.</sub>
