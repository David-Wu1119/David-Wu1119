# Yanze (David) Wu

I build and test ML infrastructure, with a focus on inference systems, reliability, and reproducible evaluation.

I am a computer science major and mathematics minor at NYU, expecting to graduate in May 2027. I am interested in Fall 2027 PhD research in ML systems, as well as backend infrastructure and developer-tools engineering.

## Selected merged contributions

- [Hugging Face Transformers #47238](https://github.com/huggingface/transformers/pull/47238): fixed half-precision `torch.compile` failures in DETR-family position embeddings and added a compiled-dtype regression test.
- [marimo #10100](https://github.com/marimo-team/marimo/pull/10100): restored completion fallback after Jedi analysis failures and removed duplicate analysis.
- Home Assistant: improved [Tuya startup recovery](https://github.com/home-assistant/core/pull/176124), [LG ThinQ service error handling](https://github.com/home-assistant/core/pull/176501), and [LinkPlay discovery](https://github.com/home-assistant/core/pull/176123).

## Projects

- [AgentCI Guard](https://github.com/David-Wu1119/agentci-guard): an experimental TypeScript static analyzer for GitHub Actions workflows that run AI agents. It models workflow permissions and reachability and emits diagnostics with explicit analysis limits. [Release v0.6.2](https://github.com/David-Wu1119/agentci-guard/releases/tag/v0.6.2) · [Demo](https://github.com/David-Wu1119/agentci-guard/blob/main/docs/demo.gif).
- [TraceBench](https://github.com/David-Wu1119/tracebench): workload and measurement infrastructure for studying ML serving behavior, with reproduction instructions and scoped experimental evidence in the repository.
- [CloudTune](https://cloudtune.org/): my private ML-systems research testbed for job orchestration, failure recovery, and verifiable execution receipts. The code is private; it is an experimental system.

## Research interests

How should an inference change be evaluated when throughput, latency, output requirements, and run-to-run variation all matter? I am interested in building reproducible experiments and failure cases that make those trade-offs explicit.

I am seeking supervised ML-systems research opportunities and useful open-source implementation work.

[LinkedIn](https://www.linkedin.com/in/yanzewu/) · [Email](mailto:yw7566@nyu.edu)
