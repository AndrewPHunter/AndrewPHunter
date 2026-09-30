### Andrew P Hunter

I build and architect at the layer where **applied AI meets low-level systems** — governed AI platforms up top, hand-rolled inference and GPU kernels underneath — and I stay hands-on in the code: **Rust, C++, Python, TypeScript, C#**.

Founder & Principal Researcher at **[Plainsight Systems](https://github.com/plainsight-systems)**, an independent research vehicle for edge-native and on-device AI.

**Currently building & researching**
- **On-device LLM inference** — hand-rolled C++ inference harnesses targeting the silicon they actually run on, no ML frameworks in the hot path. Air-gapped mixture-of-experts inference at ~80–90 tok/s on Apple Silicon (M3); higher-VRAM operator-owned hardware (AMD Strix Halo) under research.
- **Custom GPU kernels** — WebGPU/WGSL and Metal/MLX for quantized inference (fused dequant + GEMV, fused ops, attention). *(publishing soon)*
- **Governed AI platforms** — LLM gateways, agent frameworks, retrieval/RAG, and evaluation infrastructure, written and run in production.

**Selected work**
- **[Seymour](https://github.com/plainsight-systems/seymour)** — an interactive tour of why LLM inference spends its time waiting on memory: GPU cutaways, a stage-by-stage forward pass, and serving challenges on NVIDIA and AMD accelerators, all driven by one deterministic roofline model. *([live demo](https://plainsight-systems.github.io/seymour/))*
- **[cpp-perf-guidelines](https://github.com/plainsight-systems/cpp-perf-guidelines)** — a low-level C++ performance-guidelines corpus, with external adoption.
- **Rust MCP servers** (Redis, LanceDB vector search) — in the [Plainsight Systems org](https://github.com/plainsight-systems).
- **[NeuralAscent](https://github.com/AndrewPHunter/NeuralAscent)** — the arc from Rosenblatt's Perceptron (1957) to Vaswani's Transformer (2017), implemented in C# with no ML framework.

**Elsewhere**
[andrewphunter.com](https://andrewphunter.com) · [LinkedIn](https://www.linkedin.com/in/andrewphunter) · [ORCID](https://orcid.org/0009-0005-7613-8019) · [Plainsight Systems](https://github.com/plainsight-systems)
