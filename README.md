# Kyusun Cho

**AI Engineer @ PlantyNet** — on-device deepfake detection, agentic LLM systems, and the MLOps that keeps them running in production.
M.S. in Computer Science (AI), Korea University · Advised by Prof. Seungryong Kim.

I work across two halves of the same problem: the research that makes a model good, and the systems
that make it useful. Lately that means shipping vision models into Android apps, orchestrating
multi-agent RAG over a 1,400-magazine archive, and rebuilding the pipelines underneath both.

As an engineer I keep returning to the same three questions: why a system behaves the way it does,
how an idea becomes something useful, and what to improve next. I write through those on my
[blog](https://kyusuncho.github.io).

---

## Education

**M.S. in Computer Science (Artificial Intelligence)** · Korea University `2022.03 – 2025.02`
Advisor: [Seungryong Kim](https://cvlab.korea.ac.kr)

**B.S. in Statistics** · Korea University `2018.03 – 2022.02`

---

## Experience

**AI Engineer** · [PlantyNet](https://kyusuncho.github.io/blog/work/plantynet/) — Seongnam, South Korea
`2025.02 – present`

- **On-device deepfake detection** shipped to Android via TFLite — trained on a large-scale corpus
  of real and synthetic faces, with a Korean-face subset added to close a domain gap.
- **Research platform rebuild** on Ray, DVC, Lightning, Hydra, and W&B, replacing a script-driven
  workflow and cutting both experiment turnaround and GPU usage.
- **Multi-agent magazine RAG chatbot** — a LangGraph routing orchestrator delegating to article-QA
  and recommendation agents over hybrid Milvus retrieval (bge-m3 dense + Korean BM25), with layered
  RAGAS evaluation separating routing, retrieval, context, and generation quality.
- **Agentic content pipeline** for OCR correction, summarization, translation, and web-view
  generation. An ExpeL-style experience memory raised processing success rates, and knowledge
  distillation into a lightweight classifier cut LLM inference cost.
- **Knowledge-graph recommender** (in progress) — LLM facet tagging into a Neo4j content graph,
  with Personalized PageRank candidate generation and contextual-bandit exploration.

**Visiting Researcher** · [Queen Mary University of London](https://kyusuncho.github.io/blog/work/qmul/) — London, United Kingdom
`2024.08 – 2024.11`

Object-centric 3D reconstruction from monocular video — recovering per-object geometry and semantics
with 3D Gaussian Splatting, then evaluating robot navigation and manipulation in the reconstructed scene.

**Graduate Researcher** · Korea University Computer Vision Lab — Seoul, South Korea
`2022.03 – 2025.02`

Real-time audio-driven 3D talking heads, 3D pose-conditioned diffusion for person re-identification,
and pose-estimation/sensor-fusion indicators for dementia screening. TA for Samsung Electronics
internal courses on diffusion models and 3D reconstruction.

---

## Tech Stack

**ML & Research**

[![My Skills](https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv&theme=dark)](https://skillicons.dev)

`Lightning` · `Hydra` · `Weights & Biases` · `ONNX` · `TFLite / LiteRT`

**LLM & Agents**

`LangGraph` · `LangChain` · `vLLM` · `RAGAS` · `Langfuse` · `Arize Phoenix`

**Backend & Data**

[![My Skills](https://skillicons.dev/icons?i=fastapi,django,spring,postgres,supabase,redis,rabbitmq&theme=dark)](https://skillicons.dev)

`DuckDB` · `Milvus` · `Neo4j`

**MLOps**

[![My Skills](https://skillicons.dev/icons?i=docker&theme=dark)](https://skillicons.dev)

`Docker Compose` · `Airflow` · `MLflow` · `Dagster` · `Ray Data` · `DVC` · `Triton`

**Infra & Observability**

[![My Skills](https://skillicons.dev/icons?i=aws,linux,grafana,prometheus,git,github&theme=dark)](https://skillicons.dev)

**Mobile**

[![My Skills](https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark)](https://skillicons.dev)

---

## Publications

### GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting
*ACM Multimedia 2024* · first author · `3D` `gaussian-splatting` `talking-head` `real-time`
Encodes 3D Gaussian attributes into a shared implicit feature that speech audio can steer,
rendering pose-controllable talking heads at up to 120 FPS.
[Project](https://cvlab-kaist.github.io/GaussianTalker/) · [Paper](https://arxiv.org/abs/2404.16012v2) · [Code](https://github.com/cvlab-kaist/GaussianTalker) · [Notes](https://kyusuncho.github.io/blog/publication/gaussiantalker/)

### Talk3D: High-Fidelity Talking Portrait Synthesis via Personalized 3D Generative Prior
*ICCV 2025 Workshop* · first author · `3D` `talking-portrait` `NeRF` `generative-prior`
[Project](https://cvlab-kaist.github.io/Talk3D/) · [Paper](https://arxiv.org/abs/2403.20153) · [Code](https://github.com/cvlab-kaist/Talk3D) · [Notes](https://kyusuncho.github.io/blog/publication/talk3d/)

### 3D GAN Inversion with Pose Optimization
*WACV 2023* · first author · `3D` `GAN-inversion` `NeRF` `editing`
[Project](https://3dgan-inversion.github.io/) · [Paper](https://arxiv.org/abs/2210.07301) · [Code](https://github.com/cvlab-kaist/3DGAN-Inversion) · [Notes](https://kyusuncho.github.io/blog/publication/3dgan-inversion/)

### AE-NeRF: Auto-Encoding Neural Radiance Fields for 3D-Aware Object Manipulation
*arXiv 2022* · `3D` `NeRF` `auto-encoder` `disentanglement`
[Paper](https://arxiv.org/abs/2204.13426) · [Notes](https://kyusuncho.github.io/blog/publication/ae-nerf/)

---

## GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=kyusuncho&show_icons=true&hide_border=true&include_all_commits=true&theme=github_dark">
  <img height="165" alt="Kyusun Cho's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=kyusuncho&show_icons=true&hide_border=true&include_all_commits=true&theme=default">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=kyusuncho&layout=compact&hide_border=true&theme=github_dark">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kyusuncho&layout=compact&hide_border=true&theme=default">
</picture>

<sub>Cards by [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) · icons by [skill-icons](https://github.com/tandpfun/skill-icons)</sub>

---

## Elsewhere

[Website & blog](https://kyusuncho.github.io) · [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) · kyustorm7@gmail.com
