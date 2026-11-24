# Andrew Hunter

I'm a systems architect, engineering leader, and builder. I've led engineering teams and platform transformations in payments and telecom, and I build the AI platforms, agent workflows, and software that go with that work. Before software became my full-time career, I served in Navy nuclear operations, where I also wrote C++ tools for reactor plant chemistry and training.

I run **[Plainsight Systems](https://plainsight-systems.com/)** to work through questions that interest me. How does a model's internal computation become the words we read? What changes when we design for the hardware actually running it? Those questions take me through inference engines, interpretability experiments, GPU rendering, and information theory. I write up the reasoning alongside the code so other people can follow the work.

## Things to explore

- **[Frizzle](https://frizzle.plainsight-systems.com/)** lets you reach inside a running language model. Pin neurons, change their values, and compare the reply with the one it would have written. Gemma 3 1B runs entirely in your browser, with React and TypeScript over a C++/WebAssembly engine using WebGPU. [Code](https://github.com/plainsight-systems/frizzle).

- **[AI on AWS](https://github.com/AndrewPHunter/ai-on-aws)** is a runnable local reference application for understanding agents as part of a larger system. It covers tool calls, retrieval, delegated authority, evaluation, and failure recovery, with write-ups explaining the decisions. I use it as a teaching reference with engineers at Consumer Cellular.

- **[Dolittle](https://dolittle.plainsight-systems.com/)** explores natural language descriptions of a model's internal activations. Read an interpretation, edit it, and compare what Qwen3 8B generates with and without the intervention. The C++ engine runs on CUDA and Metal. [Code](https://github.com/plainsight-systems/dolittle).

- **[Charlotte](https://charlotte.plainsight-systems.com/)** is an LLM inference engine for the browser, built in C++ and WebGPU. It is where I work through the machinery of inference, from loading quantized weights to GPU kernels and streaming generation. Its engine also provided Frizzle's starting point. [Code](https://github.com/plainsight-systems/charlotte).

- **[Serenity](https://serenity.plainsight-systems.com/)** approaches GPU performance through rendering, investigating techniques that also matter to inference. The path tracer gives that work a visible result, with implementations for NVIDIA GPUs and Apple Silicon and measured accounts of what helped, what didn't, and why. [Code](https://github.com/plainsight-systems/serenity).

- **[Ariadne](https://github.com/plainsight-systems/ariadne)** studies what finite receivers can represent and use. It brings information theory, geometry, and computational limits together to investigate the foundations of attention and inference, through mathematical work and experiments.

## Writing and teaching

- **[Let's Build a Transformer!](https://cradle.plainsight-systems.com/)** grows a transformer inference engine from an empty C# program, including the GPU kernels. Each lesson adds something that runs, with the math introduced when we need it.
- **[Architecting with Claude](https://advisory.andrewphunter.com/resources/architecting-with-claude/)** is my workshop series on planning, architecture, testing, and engineering judgment when working with coding agents. I've used it with teams at Consumer Cellular.
- **[Transformation Under Scale](https://andrewphunter.com/series/transformation-under-scale/)** and **[Governance Under Scale](https://andrewphunter.com/series/governance-under-scale/)** cover the organizational side: understanding an existing estate, sequencing change, and making governance useful to delivery.

## Elsewhere

[Personal site](https://andrewphunter.com/) · [Plainsight Systems](https://plainsight-systems.com/) · [Project repositories](https://github.com/plainsight-systems) · [LinkedIn](https://www.linkedin.com/in/andrewphunter/) · [ORCID](https://orcid.org/0009-0005-7613-8019)
