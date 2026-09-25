# Hi, I'm Jieyu (Alice) Lian

**Applied AI engineer building reliable LLM, RAG, and agent systems.**

[**Visit my portfolio →**](https://whitesungun876.github.io/) · [LinkedIn](https://www.linkedin.com/in/jieyulian/)

I hold an M.Sc. in IT & Cognition from the University of Copenhagen. I turn AI product ideas into working prototypes, combining retrieval, evaluation, API integration, and human-centred design.

**I can work independently**, taking ownership of scoping, implementation, and validation while keeping collaborators informed. **I am willing to relocate to Amsterdam** for an Applied AI, AI Solutions, or AI product engineering role.

## From prototype to decision

These examples use technical evaluation feedback, not claimed customer validation. Delivery times and customer adoption are not asserted.

### GitHub Opportunity Miner

- **Delivered:** A runnable FastAPI + Next.js prototype turning GitHub issues into source-linked opportunity cards, buyer hypotheses, and validation plans, with deterministic mock demos.
- **Evaluation feedback:** The documented badcase suite checks weak evidence, duplicate opportunities, and unsupported willingness-to-pay claims. A recorded live run processed 38 GitHub items and produced one card passing the pipeline's validation rules—not proof of market demand.
- **Decision:** Separate evidence quality from commercial validation. Keep willingness to pay as a hypothesis, and distinguish build, validate, watch, and reject recommendations.

[Code and evaluation approach](https://github.com/whitesungun876/Opportunity-Mining-Agent)

### Fund Facts Cross-Check

- **Delivered:** An AI-assisted CLI prototype comparing two models' claims against synthetic fund factsheets. I selected the problem scope and model pair; Codex drafted the implementation and ran the checks.
- **Evaluation feedback:** The documented checks cover 43 unit tests and 27 fixed cases. Deliberately broken unit normalisation and evidence gating trigger regression failures. I personally compared saved live claims and quotations with the synthetic sources and reviewed the mutation results.
- **Decision:** Check source support independently of model agreement. Keep a narrow, controlled-language prototype; HTTP serving and authentication remain deferred.

[Demo](https://whitesungun876.github.io/fund-facts-cross-check/) · [Contribution and AI-use disclosure](https://github.com/whitesungun876/fund-facts-cross-check/blob/main/AI_USE.md)

## Featured work

| Project | What it demonstrates | Evidence |
| --- | --- | --- |
| [RAGOps Lens](https://github.com/whitesungun876/RAGOps-Lens) | Production-style RAG evaluation platform using FastAPI, PostgreSQL/pgvector, Qdrant, Docker, and Azure observability. | 70-case evaluation suite, confidence-gated fallback, 45 unit tests, retrieval/latency/cost analytics. |
| [GitHub Opportunity Miner](https://github.com/whitesungun876/Opportunity-Mining-Agent) | Full-stack LangGraph agent that converts GitHub evidence into traceable product opportunities and validation plans. | FastAPI + Next.js, GitHub GraphQL, Azure deployment, telemetry, and scheduled regression evaluation. |
| [From Retrieval Alignment to Realised Utility](https://github.com/whitesungun876/retrieval-alignment-realised-utility) | Reproducible M.Sc. thesis experiments on experience retrieval for an LLM agent in TextWorldExpress CookingWorld. | Frozen protocols, outcome files, verification code, statistical analyses, checksums, and the submitted thesis. |
| [FaultLine](https://github.com/whitesungun876/faultline) | Adversarial failure mining and deterministic reliability measurement for tool-using LLM agents. | Reproducible boundary cases, solvability proofs, programmatic checkers, tier comparisons, and archived traces. |
| [GazeRAG](https://github.com/whitesungun876/GazeRAG) | Hybrid retrieval research using radiologists' eye gaze as interpretable anatomical priors. | BM25 + dense retrieval, gaze-aware reranking, sensitivity analysis, and MRR/nDCG/Recall evaluation. |
| [CareMind](https://github.com/whitesungun876/Gemma4-Hackathon-ShangHai/tree/main/submissions/2026/track_C/CareMind) | Edge/cloud care-agent product for dementia family caregivers. | Mobile demos, structured care workflows, Cloud Run agent backend, and a public hackathon submission. |

## Project directory

- **Reliable LLM, RAG & agents:** [RAGOps Lens](https://github.com/whitesungun876/RAGOps-Lens), [Opportunity Miner](https://github.com/whitesungun876/Opportunity-Mining-Agent), [FaultLine](https://github.com/whitesungun876/faultline), [Budget-Aware Deep Research Agent](https://github.com/whitesungun876/deep-research-agent)
- **AI safety & verifiable systems:** [InjectiveLens Agent Guard](https://github.com/whitesungun876/InjectiveLens-Agent-Guard), [MantleLens Wallet Guard](https://github.com/whitesungun876/mantlelens-wallet-guard), [RoboProof Demo](https://github.com/whitesungun876/roboproof-demo)
- **Research, multimodal & human-centred AI:** [M.Sc. thesis materials](https://github.com/whitesungun876/retrieval-alignment-realised-utility), [GazeRAG](https://github.com/whitesungun876/GazeRAG), [Multimodal Speech Emotion Recognition](https://github.com/whitesungun876/ser_multimodal_project), [Multilingual Text Detoxification](https://github.com/whitesungun876/Multilingual-Text-Detoxification-), [Glimmer](https://github.com/whitesungun876/Glimmer)
- **Learning in public:** [LLM Zoomcamp 2026](https://github.com/whitesungun876/llm-zoomcamp-2026-code)

See the [full categorized project index](PROJECTS.md) for research projects, product prototypes, and earlier ML coursework.

## Technical focus

- **LLM applications:** RAG, agent/tool calling, LangGraph, Dify, structured outputs, confidence gating, safety guardrails
- **Evaluation & observability:** golden datasets, recall@k, MRR, regression tests, failure analysis, latency and cost monitoring, MLflow, Application Insights
- **Backend & cloud:** Python, FastAPI, PostgreSQL, pgvector, Qdrant, Docker, Azure, Google Cloud Run
- **Product interfaces:** TypeScript, React, Next.js, API integration, human-centred AI workflows

[LinkedIn](https://www.linkedin.com/in/jieyulian/) · Willing to relocate to Amsterdam
