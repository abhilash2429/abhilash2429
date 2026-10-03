### Hey, I'm Abhilash

19, third-year CS (AI & ML) at GRIET Hyderabad. I build agents, retrieval systems and real-time voice pipelines, and I care about proving they work: evals against baselines, tests, citations that get checked before an answer goes out.

Looking for **AI engineering internships**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhilashreddymanda)
[![Portfolio](https://img.shields.io/badge/abhilash24.me-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://abhilash24.me)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhilashreddy2429@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=abhilash2429&style=for-the-badge&color=555555&label=PROFILE+VIEWS)

#### Stack

[![Stack](https://skillicons.dev/icons?i=py,ts,js,swift,c,fastapi,pytorch,sklearn,nodejs,nextjs,react,tailwind,postgres,mongodb,redis,docker,azure,cloudflare,vercel,git,linux&perline=11)](https://skillicons.dev)

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)

---

#### What I've built

**[Macky](https://github.com/abhilash2429/Macky)** · voice assistant that lives in the macOS notch · [site](https://heymacky.vercel.app) · [demo](https://youtu.be/SIRyFt7ISx0)
<br><sub>Swift · GPT-Realtime · Cloudflare Workers · Azure AI Foundry · MCP</sub>
- Real-time push-to-talk pipeline: audio capture, streamed responses, speech output, interruption and reconnect handling.
- Background job harness that runs sub-agents concurrently on long tasks, with live progress, cancellation, mid-task steering and restart after sleep.
- Calendar, Reminders, screen capture and cursor control on macOS, plus Slack, Gmail and Spotify over MCP.

**[M-RAG](https://github.com/abhilash2429/M-Rag-B)** · multimodal retrieval over hardware datasheets
<br><sub>Python · FastAPI · FAISS · Azure OpenAI · MinerU · Next.js</sub>
- 4-stage ingestion (parse, caption, embed, index) that makes figures and tables searchable. Resumable and cache-backed. 25 PDFs, 1,800+ pages.
- 61.5% correct on figure/table questions against 0% for a text-only baseline on the same codepath, with no drop on prose questions.
- FastAPI service streaming agent stages over SSE with page-level citations. 100 tests.

**[DeepRead](https://github.com/abhilash2429/DeepRead)** · turns ML papers into implementation briefings · [live](https://deep-read-seven.vercel.app)
<br><sub>FastAPI · LangGraph · Azure OpenAI · PostgreSQL · Next.js</sub>
- Multi-agent pipeline: PDF or arXiv ID in, six-section implementation briefing streamed out.
- Cited Q&A on hybrid BM25 + embedding retrieval. Answers whose quotes don't match the source chunk get rejected and revised.
- Adversarial audit that labels every claim in a briefing as supported, unsupported or contradicted, with page-linked evidence.

**[Oversight Arena](https://github.com/abhilash2429/overSight_Arena)** + **[GitMergeEnv](https://github.com/abhilash2429/GitMergeEnv-)** · RL environments for LLM agents · [writeup](https://abhilash24.me/blog/blog-post)
<br><sub>Python · OpenEnv · GRPO · Qwen2.5-3B</sub>
- GitMergeEnv: merge-conflict resolution env with three difficulty tiers, a deterministic grader and shaped rewards. Cleared Round 1 solo out of 52,000+.
- Oversight Arena: five-stage coding pipeline (requirements, codegen, tests, security review, deploy) with hidden-flaw and colluding-pair modes. Trained Qwen2.5-3B against it with GRPO.

**[Intelli-Credit](https://github.com/abhilash2429/Intelli-Credit)** · credit appraisal engine · [live](https://intelli-credit-kappa.vercel.app)
<br><sub>FastAPI · Celery · Redis · PostgreSQL · Qdrant · XGBoost · PySpark</sub>

---

#### Open source

- [pipecat-ai/pipecat#6024](https://github.com/pipecat-ai/pipecat/pull/6024) · keep the OpenAI Realtime receive loop alive and report dead connections
- [kornia/kornia#5361](https://github.com/kornia/kornia/pull/5361) · fix container `isinstance` checks under `torch.compile` on torch 2.5.1

#### Hackathons

- **Winner**, TCS AI Hackathon, TCS Technology Day (Jul 2026)
- **Grand Finalist**, Meta x PyTorch x OpenEnv x Scaler Hackathon (May 2026)
- **Finalist**, IIT Hyderabad Innovation Hackathon (Mar 2026)
