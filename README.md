# Hi, I'm Grivn 👋

Engineer by day, onchain by conviction.

I build **distributed systems** and tools for **AI agents**, with a background in BFT consensus and an interest in **DeFi**.

Currently building [**mnemon**](https://mnemon.dev): persistent memory for AI agents, with graph-based recall and the host LLM as supervisor. I also build [**dsh-mnemon**](https://github.com/omdsh-dev/dsh-mnemon), composable memory for DeepSeek Harness.

[Projects](#-what-im-building) · [Research](#-research) · [Background](#-background) · [Contributions](#-contributions) · [X / @grivn_eth](https://x.com/grivn_eth)

---

## 🔨 What I'm building

| Project | Description | Stats |
|---|---|---|
| [mnemon](https://github.com/mnemon-dev/mnemon)<br>[Homepage](https://mnemon.dev) | Persistent memory for AI agents in a single Go binary, with graph-based recall and host-LLM supervision. | <nobr><a href="https://github.com/mnemon-dev/mnemon/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/mnemon-dev/mnemon?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/mnemon-dev/mnemon/forks"><img alt="forks" src="https://img.shields.io/github/forks/mnemon-dev/mnemon?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [dsh-mnemon](https://github.com/omdsh-dev/dsh-mnemon) | Composable three-tier memory for DeepSeek Harness, with pluggable sources and strategies. | <nobr><a href="https://github.com/omdsh-dev/dsh-mnemon/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/omdsh-dev/dsh-mnemon?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/omdsh-dev/dsh-mnemon/forks"><img alt="forks" src="https://img.shields.io/github/forks/omdsh-dev/dsh-mnemon?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [phalanx](https://github.com/Grivn/phalanx) | Byzantine fault-tolerant mempool with fair transaction ordering. | <nobr><a href="https://github.com/Grivn/phalanx/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/Grivn/phalanx?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/Grivn/phalanx/forks"><img alt="forks" src="https://img.shields.io/github/forks/Grivn/phalanx?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [normalizejson](https://github.com/Grivn/normalizejson) | Go package for normalizing JSON keys and values with templates. | <nobr><a href="https://github.com/Grivn/normalizejson/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/Grivn/normalizejson?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/Grivn/normalizejson/forks"><img alt="forks" src="https://img.shields.io/github/forks/Grivn/normalizejson?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |

---

## 📄 Research

### Mnemon: Raw Records, Fast Judgments, Slow Thoughts

[Paper](https://arxiv.org/abs/2609.36059) · [PDF](https://arxiv.org/pdf/2609.36059) · [Code, prompts & run records](https://github.com/Grivn/mnemon-memory-agent)

A memory agent that preserves raw, dated conversations and separates fast evidence judgments (System 1, **Jev**) from search planning and reasoning (System 2, **LLM**). It builds a compact evidence view when a question arrives, with a background index for broader conversation recall.

- **With GPT-4.1-mini:** 91.7% on LoCoMo and 83.8% on LongMemEval-S, using under 4k context tokens per question.
- **With a reasoning model:** 92.2% on LoCoMo and 94.4% on LongMemEval-S.
- **Scaling:** on BEAM, per-question cost grows by just 1.11× as history grows from 100K to 10M tokens.

---

## 🧠 Background

- 🎓 ZJU & WHU
- 💼 Engineer @ [ByteDance](https://github.com/bytedance) — AI agents · MCP · microservices · observability · AIOps · root cause analysis
- ⛓️ Previously: consensus protocol R&D @ [Hyperchain](https://www.hyperchain.cn/en/)
- 📄 Research: long-term memory for AI agents · fair ordering in BFT consensus protocols
- ⚡ Tech: Go · Python · MCP

---

## 🤝 Contributions

<details>
<summary>Open-source projects I've contributed to</summary>

| Project | Description | Stats |
|---|---|---|
| [dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) | Plugin and skin collection for DeepSeek Harness Web UI — task board, Git graph, remote mobile UI, usage stats, and more | <nobr><a href="https://github.com/zhu1090093659/dsh-web-ui/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/zhu1090093659/dsh-web-ui?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/zhu1090093659/dsh-web-ui/forks"><img alt="forks" src="https://img.shields.io/github/forks/zhu1090093659/dsh-web-ui?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [dsh-usage-stats](https://github.com/Ychris12138/dsh-usage-stats) | Token usage heatmaps, per-model breakdowns, and DeepSeek account balance for DSH Web UI | <nobr><a href="https://github.com/Ychris12138/dsh-usage-stats/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/Ychris12138/dsh-usage-stats?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/Ychris12138/dsh-usage-stats/forks"><img alt="forks" src="https://img.shields.io/github/forks/Ychris12138/dsh-usage-stats?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | Wrap Gemini CLI, Claude Code, Codex, Qwen as OpenAI/Claude-compatible API | <nobr><a href="https://github.com/router-for-me/CLIProxyAPI/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/router-for-me/CLIProxyAPI?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/router-for-me/CLIProxyAPI/forks"><img alt="forks" src="https://img.shields.io/github/forks/router-for-me/CLIProxyAPI?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [mcp-go](https://github.com/mark3labs/mcp-go) | Go implementation of the Model Context Protocol (MCP) | <nobr><a href="https://github.com/mark3labs/mcp-go/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/mark3labs/mcp-go?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/mark3labs/mcp-go/forks"><img alt="forks" src="https://img.shields.io/github/forks/mark3labs/mcp-go?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [DIA](https://github.com/diadata-org/diadata) | Open-source financial data platform for digital assets | <nobr><a href="https://github.com/diadata-org/diadata/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/diadata-org/diadata?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/diadata-org/diadata/forks"><img alt="forks" src="https://img.shields.io/github/forks/diadata-org/diadata?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [cometbft](https://github.com/cometbft/cometbft) | Byzantine fault-tolerant state machine replication engine (fork of Tendermint Core) | <nobr><a href="https://github.com/cometbft/cometbft/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/cometbft/cometbft?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/cometbft/cometbft/forks"><img alt="forks" src="https://img.shields.io/github/forks/cometbft/cometbft?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [bamboo](https://github.com/gitferry/bamboo) | Source code for the ICDCS 2022 paper "Dissecting the Performance of Chained-BFT" | <nobr><a href="https://github.com/gitferry/bamboo/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/gitferry/bamboo?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/gitferry/bamboo/forks"><img alt="forks" src="https://img.shields.io/github/forks/gitferry/bamboo?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |
| [blockchain_conference_paper](https://github.com/jianyu-niu/blockchain_conference_paper) | Curated list of blockchain academic papers by conference and year | <nobr><a href="https://github.com/jianyu-niu/blockchain_conference_paper/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/jianyu-niu/blockchain_conference_paper?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;labelColor=24292f&amp;color=ffdf5d"></a>&nbsp;<a href="https://github.com/jianyu-niu/blockchain_conference_paper/forks"><img alt="forks" src="https://img.shields.io/github/forks/jianyu-niu/blockchain_conference_paper?style=flat-square&amp;logo=git&amp;logoColor=white&amp;label=forks&amp;labelColor=24292f&amp;color=54aeff"></a></nobr> |

</details>

---

## 🌐 Onchain

DeFi analyst | $HYPE · $PENDLE | Believer in the free movement of value

- 🐦 [@grivn_eth](https://x.com/grivn_eth)
