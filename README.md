# David Nicol

CTO & Technical Lead at [Bravyn](https://bravyn.ai) - building AI-powered leadership coaching. Hands-on tech leader specialising in conversational AI, multi-agent orchestration, RAG architectures, and context engineering.

I build things end-to-end: from infrastructure (AWS/Terraform/Kubernetes) through backend systems to AI pipelines and user experience. Career spanning fintech, video delivery (local and broadcast IP), e-commerce, and now AI/ML.

### What I'm working on

**[Bravyn](https://bravyn.ai)** - AI leadership coaching platform with full-screen avatar-based coaching on iOS and Android. React Native, on-device speech recognition and synthesis (native modules), Python/FastAPI, multi-agent orchestration, streaming inference, LLM observability, Ruby on Rails, AWS

<p align="center">
  <img src="images/bravyn-coaching-recognition.png" alt="Bravyn avatar coaching — recognised speech rendered live in the voice toolbar" width="240" />
  <img src="images/bravyn-coaching-transcript.png" alt="Bravyn avatar coaching — live transcript of a coaching conversation over the full-screen avatar" width="240" />
</p>

<p align="center"><sub>Real-time avatar coaching: on-device speech recognition and voice synthesis drive a full-screen avatar, with the live transcript over the scene and recognised speech surfaced in the voice bar.</sub></p>

**[RefTracker](https://github.com/dznicol/reftracker)** - computer vision + Gemini pipeline that tracks rugby referees and explains their decisions. YOLOv8, BoTSORT/CLIP-ReID, OpenCV, Supervision

<p align="center">
  <img src="images/reftracker-tracking.gif" alt="Colour-first referee tracking shown at three zoom levels: wide, match area, and close-up" width="480" />
</p>

<p align="center"><sub>YOLOv8 person detection picks the referee by their unique kit (shirt) colour every frame, falling back to multi-object tracking (BoTSORT + CLIP-ReID) when the colour isn't separable. Velocity clamping to real running speeds, camera-motion compensation, and teleport detection (rejecting physically impossible between-frame jumps) keep the marker locked to the right person — who is only ~40px tall in the original 1920×1080 footage. The three panels are a single tracking pass shown at three zoom levels.</sub></p>

### Research

- **Effective Conversational Closure in Supportive Dialogue** (with Ruyi Wang et al.) - pre-publication, targeting EMNLP 2026 Industry Track. A four-dimensional latent-space classifier that steers a coaching model at inference time, addressing maintenance bias and termination inertia. Production system outperforms baseline models across 85% of real sessions.

### Areas of focus

- **AI/ML** - LLM application development, multi-agent orchestration, RAG, context engineering, evaluation and safety pipelines, conversational AI, computer vision
- **Infrastructure** - AWS, Terraform, Docker, Kubernetes, IP networking, video delivery
- **Product** - 0-to-1 product architecture, UX-driven development, full-stack delivery

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dznicol/)
