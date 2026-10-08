### Andrew P Hunter

I'm a systems architect and builder working where applied AI meets low-level systems: LLM inference, GPU kernels and C++ performance, with governed AI platforms on top. I write the code: C++, Rust, Python, TypeScript, C#.

Founder and principal researcher at **[Plainsight Systems](https://github.com/plainsight-systems)**, an independent research vehicle for edge-native and on-device AI.

**Selected work**
- **[Charlotte](https://github.com/plainsight-systems/charlotte)**: an LLM inference harness that runs open-weight models entirely in the browser. C++ compiled to WebAssembly, every step on the GPU through WebGPU; Qwen3 0.6B decodes at 270 tok/s in Chrome on an M3 Max. *([live demo](https://plainsight-systems.github.io/charlotte/) · [debrief](https://github.com/plainsight-systems/charlotte/blob/main/docs/debrief.md))*
- **[Seymour](https://github.com/plainsight-systems/seymour)**: an interactive tour of why LLM inference spends its time waiting on memory: GPU cutaways, a stage-by-stage forward pass, and serving on NVIDIA and AMD accelerators, all driven by one deterministic roofline model. *([live demo](https://plainsight-systems.github.io/seymour/))*
- **[cpp-perf-guidelines](https://github.com/plainsight-systems/cpp-perf-guidelines)**: low-level C++ performance guidelines served to coding agents over MCP, 157 guidelines across 13 categories, with external adoption.
- **Rust MCP servers** (Redis, LanceDB vector search) in the [Plainsight Systems org](https://github.com/plainsight-systems).

**Currently**
- **Research ([Ariadne](https://github.com/plainsight-systems/ariadne)):** whether a transformer's vocabulary size and embedding dimension can be derived instead of tuned. Working towards an information-theoretic approach to attention.
- **On-device inference:** hand-rolled C++ harnesses on the silicon they run on, no ML frameworks in the hot path. Air-gapped mixture-of-experts inference at about 80 to 90 tok/s on Apple Silicon (M3); AMD Strix Halo under research.
- **Next:** a real-time path tracer whose sampling kernels share a shape with attention, and an article series that builds a transformer from an empty program in C#.
- **Governed AI platforms:** LLM gateways, agent frameworks, retrieval and evaluation infrastructure, written and run in production.

**Elsewhere**
[andrewphunter.com](https://andrewphunter.com) · [LinkedIn](https://www.linkedin.com/in/andrewphunter) · [ORCID](https://orcid.org/0009-0005-7613-8019) · [Plainsight Systems](https://github.com/plainsight-systems)
