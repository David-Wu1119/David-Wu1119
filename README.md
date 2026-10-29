# Yanze (David) Wu

I fix correctness bugs in ML infrastructure: inference servers, training frameworks, and benchmark harnesses. I study computer science at NYU with a minor in mathematics, and I am looking for 2027 new-grad roles in ML infrastructure and backend engineering.

## Merged upstream work

Counts as of October 2026. Many of these changes were developed with AI coding assistants.

- **llm-d** ([benchmark](https://github.com/llm-d/llm-d-benchmark/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged), 29 merged; [inference simulator](https://github.com/llm-d/llm-d-inference-sim/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged), 11): report and metric fixes, e.g. [keeping each endpoint's request count in the EPP request distribution](https://github.com/llm-d/llm-d-benchmark/pull/2111).
- **[EvalScope](https://github.com/modelscope/evalscope/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged)** (55 merged): benchmark prompt and scoring fixes, e.g. [including the passage and candidates in ArxivRollBench cloze prompts](https://github.com/modelscope/evalscope/pull/1951).
- **[Xinference](https://github.com/xorbitsai/inference/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged)** (34 merged): model-catalog fixes, e.g. [restoring the official Qwen2.5-Coder chat template](https://github.com/xorbitsai/inference/pull/5894).
- **[TorchTitan](https://github.com/pytorch/torchtitan/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged)** (9 merged): training correctness, e.g. [using Llama 3.2's RoPE scaling factor for the 1B and 3B flavors](https://github.com/pytorch/torchtitan/pull/5528).
- **[GuideLLM #1194](https://github.com/vllm-project/guidellm/pull/1194)**: fixed percentiles landing one rank high from cumulative-sum rounding.
- **[Hugging Face Transformers #47238](https://github.com/huggingface/transformers/pull/47238)**: fixed half-precision `torch.compile` failures in DETR-family position embeddings and added a compiled-dtype regression test.
- **[Home Assistant](https://github.com/home-assistant/core/pulls?q=is%3Apr+author%3ADavid-Wu1119+is%3Amerged)** (31 merged): integration startup and error-handling fixes, e.g. [Tuya startup recovery](https://github.com/home-assistant/core/pull/176124).

## Projects

- [AgentCI Guard](https://github.com/David-Wu1119/agentci-guard): an experimental TypeScript static analyzer for GitHub Actions workflows that run AI agents. It models workflow permissions and reachability and emits diagnostics with explicit analysis limits. [Release v0.7.0](https://github.com/David-Wu1119/agentci-guard/releases/tag/v0.7.0) · [Demo](https://github.com/David-Wu1119/agentci-guard/blob/main/docs/demo.gif).
- [TraceBench](https://github.com/David-Wu1119/tracebench): a replay-sufficiency benchmark for ML decision evidence, with reproduction instructions and scoped experimental evidence in the repository.
- [CloudTune](https://cloudtune.org/): an early ML infrastructure project for supervised fine-tuning on customer-operated infrastructure, failure recovery, and portable signed execution receipts. The public research preview includes an illustrative receipt-verification demo; the application and source remain private.

## Research interests

How should an inference change be evaluated when throughput, latency, output requirements, and run-to-run variation all matter? I am interested in building reproducible experiments and failure cases that make those trade-offs explicit.

[LinkedIn](https://www.linkedin.com/in/yanzewu/) · [Email](mailto:yw7566@nyu.edu)
