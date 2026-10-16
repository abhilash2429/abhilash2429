<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f3b5c,100:2f81f7&height=190&section=header&text=Abhilash%20Reddy&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Applied%20AI%20Engineer%20%C2%B7%20Agents%20%C2%B7%20Evals%20%C2%B7%20Backend&descAlignY=58&descSize=17" width="100%" alt="Abhilash Reddy"/>

<a href="https://abhilash24.me"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=900&color=2F81F7&center=true&vCenter=true&width=620&lines=Agents+that+check+their+own+work;Every+design+choice+backed+by+an+eval;Retrieval+with+citations+that+resolve;Open+to+full-time+remote+roles" alt="Agents, evals and backend"/></a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhilashreddymanda)
[![Portfolio](https://img.shields.io/badge/abhilash24.me-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://abhilash24.me)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhilashreddy2429@gmail.com)

</div>

### About me

- I build AI products end to end: the agent, the eval that proves it works, and the backend that keeps it running.
- I measure before I claim. My projects ship with held-out benchmarks, ablations and per-query cost.
- Python for most of it, TypeScript for the web, Swift when it has to live on a Mac.
- I contribute upstream to [pipecat](https://github.com/pipecat-ai/pipecat/pull/6024) and [kornia](https://github.com/kornia/kornia/pull/5361).
- Open to **full-time remote** roles in applied AI and backend engineering.

### Stack

<div align="center">

[![Stack](https://skillicons.dev/icons?i=py,ts,swift,fastapi,pytorch,nodejs,nextjs,react,postgres,redis,docker,aws,azure,cloudflare,git,linux&perline=8)](https://skillicons.dev)

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![GRPO](https://img.shields.io/badge/RL-GRPO-555555?style=flat-square)

</div>

### What I've built

- **[Bladerunner](https://github.com/abhilash2429/BladeRunner)**: a watchdog for agent fleets. It reads traces, pauses an agent that breaks policy, proves the violation with cited spans, patches the guardrail and confirms the fix, with no human in the loop. On 102 held-out traces it cuts false alarms from 40% to 5% (precision 0.39 to 0.90). On 858 AgentDojo runs from agents I didn't build, precision goes from 0.69 to 0.88.
- **[Enterprise Search](https://github.com/abhilash2429/enterprise-search-rag)**: cited answers over 512K company documents. Scores 67.9 vs 47.7 for BM25 on a held-out test split I ran once (+20.1, 95% CI +15.7 to +24.5), at $0.0028 per question. Exposed as an MCP server.
- **[Macky](https://github.com/abhilash2429/Macky)**: a voice assistant in the Mac notch. Hold a key, say what you want, and it acts across your apps, handing long jobs to a background agent. ([site](https://heymacky.vercel.app), [demo](https://youtu.be/SIRyFt7ISx0))
- **[Oversight Arena](https://github.com/abhilash2429/overSight_Arena)**: one model supervises five coding agents and learns to catch failures that look like successes. Trained Qwen2.5-3B on it with GRPO. ([writeup](https://abhilash24.me/blog/blog-post))
- **[DeepRead](https://github.com/abhilash2429/DeepRead)**: drop in an ML paper, get a plan for implementing it. The Q&A agent checks its own citations and rewrites answers that don't hold up. ([live](https://deep-read-seven.vercel.app))
- **[AfterCare](https://github.com/abhilash2429/afterCare)**: photograph an Indian hospital discharge summary, get a picture-and-voice medicine schedule in your language. Built on AWS Lambda, Textract, Bedrock and DynamoDB. ([live](https://main.d2nozesb14q5me.amplifyapp.com))
- **[M-RAG](https://github.com/abhilash2429/Multimodal-Rag)**: RAG over hardware datasheets that reads the figures and tables too. It gets 61.5% of those questions right. Text-only got none.

<table>
<tr>
<td valign="top" width="50%">

### Open source

- [pipecat-ai/pipecat#6024](https://github.com/pipecat-ai/pipecat/pull/6024)<br><sub>keeps the OpenAI Realtime receive loop alive and reports connections that died</sub>
- [kornia/kornia#5361](https://github.com/kornia/kornia/pull/5361)<br><sub>fixes `isinstance` checks in augmentation containers so they compile on torch 2.5.1</sub>

</td>
<td valign="top" width="50%">

### Hackathons

- **[Winner](https://drive.google.com/file/d/10CNecnstq9_I7sGFySNo0rsbjeyZCStA/view)** · TCS AI Hackathon<br><sub>Jul 2026 · beat about 30 teams</sub>
- **[Grand Finalist](https://drive.google.com/file/d/1WuTUidWNzSoFeN349NXxyhVj-Tt4AKbd/view)** · Meta x PyTorch x OpenEnv x Scaler<br><sub>May 2026 · top 0.1% of 52,000+</sub>
- **[Finalist](https://drive.google.com/file/d/12bqjwjR-m-M1cy7cO535n9wDSOPxa5L8/view)** · IIT Hyderabad Innovation Hackathon<br><sub>Mar 2026</sub>

</td>
</tr>
</table>

### Latest writing

<!-- BLOG-POST-LIST:START -->
- [Oversight Arena: Training an LLM to Catch the AI Failures That Look Like Successes](https://abhilash24.me/blog/blog-post)
- [You Stopped Thinking, Robert. You&#39;re a Prompster Now](https://abhilash24.me/blog/you-stopped-thinking-robert)
<!-- BLOG-POST-LIST:END -->

More at [abhilash24.me/blog](https://abhilash24.me/blog)

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abhilash2429/abhilash2429/output/github-contribution-grid-snake-dark.svg">
  <img alt="Contribution graph snake" src="https://raw.githubusercontent.com/abhilash2429/abhilash2429/output/github-contribution-grid-snake.svg">
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f81f7,50:1f3b5c,100:0d1117&height=110&section=footer" width="100%" alt=""/>

</div>
