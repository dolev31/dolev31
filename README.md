<div align="center">

# Ido Levy

Research on LLM agents at **IBM** and the **Weizmann Institute of Science**:<br>
what agents pursue without being asked, and how safely they act.

[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Ido%20Levy-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=Ok_7M80AAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-idolevi31-0A66C2)](https://www.linkedin.com/in/idolevi31/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-dolev31-FFD21E)](https://huggingface.co/dolev31)
[![New paper](https://img.shields.io/badge/New%20paper-project%20page-1B5EA8)](https://dolev31.github.io/ProactiveInquirer/)

</div>

---

### ⚡ TabAgent: Distilling LLM Agent Components into Cheap Classifiers · 2026

**Ido Levy**, Segev Shlomov, Avi Yaeli, Nir Mashkif, Asaf Adi, Yinon Goldstein, Eilam Shapira, Leshem Choshen

<a href="https://github.com/dolev31/TabAgent"><img src="https://dolev31.github.io/TabAgent/assets/social-card.png" width="100%" alt="TabAgent: replace an LLM agent's closed-set decisions with a cheap classifier trained from its own logs"></a>

Agents call a frontier LLM again and again for closed-set decisions: which tools to shortlist, which skill or
application to use, where to route. TabAgent replaces that call with a compact classifier trained on the agent's
own successful runs, leaving the rest of the agent intact. On tool shortlisting it recovers essentially all of the
tools the GPT-5.4 shortlister used on its successful runs, at about 10³× lower latency and 10⁵× lower cost per call.

[![Stars](https://img.shields.io/github/stars/dolev31/TabAgent?style=social)](https://github.com/dolev31/TabAgent)
[![PyPI](https://img.shields.io/pypi/v/tabagent?label=pip%20install%20tabagent)](https://pypi.org/project/tabagent/)

[Paper](https://arxiv.org/abs/2602.16429) ·
[Project page](https://dolev31.github.io/TabAgent/) ·
[Code](https://github.com/dolev31/TabAgent) ·
[Models 🤗](https://huggingface.co/dolev31/tabagent-skillsbench-skill-selection)

### 🔎 Asking for What Was Never Requested: Horizontal and Vertical Proactivity in Agents · 2026

**Ido Levy**, Asaf Yehudai, Segev Shlomov, Asaf Adi, Leshem Choshen

<a href="https://dolev31.github.io/ProactiveInquirer/"><img src="https://dolev31.github.io/ProactiveInquirer/assets/social_preview.png" width="100%" alt="Asking for What Was Never Requested: one customer request handled by the same model, prompted and trained with Q&amp;D"></a>

What should an LLM agent pursue that the user never asked for? Need graphs measure it without a
model judge, and Q&D trains it from the consequences of its own questions. The trained 8B questioner
recovers 90% of the required evidence where the same model, prompted, recovers 78%, and it more than
doubles retail task success in a τ²-bench customer-service agent it was never trained on.

[![Stars](https://img.shields.io/github/stars/dolev31/ProactiveInquirer?style=social)](https://github.com/dolev31/ProactiveInquirer)

[Paper](https://arxiv.org/abs/2609.37236) ·
[Project page](https://dolev31.github.io/ProactiveInquirer/) ·
[Code](https://github.com/dolev31/ProactiveInquirer) ·
[Model 🤗](https://huggingface.co/dolev31/ProactiveInquirer-Qwen3-8B)

### 🛡️ ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents · 2024

**Ido Levy**, Ben Wiesel, Sami Marreed, Alon Oved, Avi Yaeli, Segev Shlomov

A benchmark for evaluating the safety and trustworthiness of web agents in enterprise scenarios.

[![Stars](https://img.shields.io/github/stars/segev-shlomov/ST-WebAgentBench?style=social)](https://github.com/segev-shlomov/ST-WebAgentBench)

[Paper](https://arxiv.org/abs/2410.06703) ·
[Website](https://sites.google.com/view/st-webagentbench/home) ·
[Code](https://github.com/segev-shlomov/ST-WebAgentBench) ·
[Leaderboard](https://huggingface.co/spaces/ST-WebAgentBench/st-webagentbench-leaderboard) ·
[Dataset](https://huggingface.co/datasets/ST-WebAgentBench/st-webagentbench)

### 🧩 CUGA: an open-source generalist agent for the enterprise · contributor

[![Stars](https://img.shields.io/github/stars/cuga-project/cuga-agent?style=social)](https://github.com/cuga-project/cuga-agent)

An agent harness for complex tasks on the web and APIs, with OpenAPI and MCP integrations, a
composable architecture, reasoning modes and policy-aware features.

[Website](https://cuga.dev) · [Code](https://github.com/cuga-project/cuga-agent)
