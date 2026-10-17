<div align="center">

<a href="https://bytebunkerlabs.ai"><img src="https://bytebunkerlabs.ai/og.png" alt="ByteBunker Labs — run serious AI models on hardware you own" width="820"></a>

### Own your AI, end to end. Nothing leaves your network.

A security research &amp; product studio building private, self-hosted AI infrastructure.

<p>
<a href="https://bytebunkerlabs.ai"><img src="https://img.shields.io/badge/Website-bytebunkerlabs.ai-0E5C45?style=flat-square" alt="Website"></a>
<a href="https://blog.bytebunkerlabs.ai"><img src="https://img.shields.io/badge/Blog-field%20notes-0E5C45?style=flat-square" alt="Blog"></a>
<a href="https://docs.bytebunkerlabs.ai"><img src="https://img.shields.io/badge/Docs-searchable-0E5C45?style=flat-square" alt="Docs"></a>
<a href="https://huggingface.co/bytebunker"><img src="https://img.shields.io/badge/Hugging%20Face-bytebunker-0E5C45?style=flat-square&amp;logo=huggingface&amp;logoColor=white" alt="Hugging Face"></a>
<a href="https://x.com/bytebunkerlabs"><img src="https://img.shields.io/badge/X-%40bytebunkerlabs-0E5C45?style=flat-square&amp;logo=x&amp;logoColor=white" alt="X"></a>
</p>

<sub><b>No account · No telemetry · Your machines only · Keys stay yours</b></sub>

</div>

---

## What we ship

ByteBunker is one app for every layer of running AI on machines you own — serve models, watch every GPU, chat, script, and delegate. No cloud in between.

| | |
|---|---|
| **[ByteBunker](https://bytebunkerlabs.ai)** | The app for AI you own: serve and stop models on your own machines, watch every GPU, chat with tools and files, script it all from a terminal with `bb`, schedule jobs, and hand goals to agents. Free for macOS and Windows. |
| **[dgx-serve](https://github.com/bytebunkerlabs/dgx-spark-serve)** | One command, `rack`, to serve open models on a DGX Spark (or several, as one model), an NVIDIA Linux box, a Windows PC through WSL2, or an Apple-silicon Mac. |
| **ByteBunker Agents** | Hand a goal to agents on a worker you own, each one walled in a throwaway container. Early access. |
| **[fits](https://fits.bytebunkerlabs.ai)** | Will it fit? How fast? A fit calculator, a filename decoder, and the napkin math behind running open models on your own hardware. |
| **[Docs](https://docs.bytebunkerlabs.ai)** | Every screen, setting and command of ByteBunker and dgx-serve, written down and searchable. |
| **[Blog](https://blog.bytebunkerlabs.ai)** | Field notes and build logs on running open models on hardware you control — measured, not guessed. |

## Open source

| Repo | What it is |
|---|---|
| **[dgx-spark-serve](https://github.com/bytebunkerlabs/dgx-spark-serve)** | The `rack` serving layer: minimal Docker + scripts to run large models on one machine or several, with phased runbooks and benchmarks committed. |
| **[bytebunker-console](https://github.com/bytebunkerlabs/bytebunker-console)** | The playground console: streaming chat with reasoning and tool calls, MCP servers managed from the UI, live cluster telemetry — one file of stdlib Python, one page of vanilla JS, no build step. |
| **[nemotron-mlx-quant](https://github.com/bytebunkerlabs/nemotron-mlx-quant)** | Reproduce NVIDIA's Nemotron Bolt 74B as 4-bit MLX, first-party, from the BF16 release — extract, quantize, and verify it's numerically equivalent to the reference. [Weights →](https://huggingface.co/bytebunker/NVIDIA-Nemotron-3.5-Bolt-74B-A9B-MLX-4bit) |
| **[dgx-spark-setup](https://github.com/bytebunkerlabs/dgx-spark-setup)** | Modular, idempotent setup for an NVIDIA DGX Spark (GB10): vLLM + gateway, RAG store, fine-tuning workspace, monitoring, and a staged two-Spark cluster. |
| **[macbunker](https://github.com/bytebunkerlabs/macbunker)** | Encrypted daily snapshots and one-command restore for a Mac — dotfiles, SSH keys, Brewfile, macOS defaults and every git repo — into iCloud Drive. |

We also contribute to **[TensorFold](https://github.com/ashhart/TensorFold)**, the Apple-silicon serving engine behind our fastest Mac inference.

## From the blog

- [**A day-one port:** NVIDIA's Nemotron Bolt 74B on a Mac, at 45 tok/s](https://blog.bytebunkerlabs.ai/posts/nemotron-bolt-74b-on-a-mac/)
- [**The keeper of the treasury:** agents that read your data and keep it home](https://blog.bytebunkerlabs.ai/posts/keeper-of-the-treasury/)
- [More field notes →](https://blog.bytebunkerlabs.ai)

<div align="center">
<sub>© 2026 ByteBunker Labs · <a href="https://bytebunkerlabs.ai">bytebunkerlabs.ai</a> · Founded by Mo (<a href="https://github.com/trickyfalcon">@trickyfalcon</a>)</sub>
</div>
