<div align="center">

<h1>
  Hey, I'm Hekal
  <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="32" alt="wave" />
</h1>

<!-- Typing animation. Lines are separated by ";" and spaces are "+".
     Tweak visually at https://readme-typing-svg.demolab.com/demo/ -->
<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=620&lines=Security+%2F+Platform+Engineer+%40+SOC;Learning+to+bring+AI+into+detections%2C+automation+%26+SOAR;Teaching+agents+to+triage+so+I+can+sleep;Humans+decide%2C+AI+does+the+paperwork" alt="Typing animation" />
</a>

</div>

<br />

## 🛡️ About me

<!-- Optional: a GIF on the right. Uncomment and paste a URL
     (e.g. from giphy.com/search/hacker-typing or tenor.com/search/cybersecurity).
<img align="right" width="320" src="PASTE_GIF_URL_HERE" alt="gif" />
-->

- 🤖 Actively learning where AI actually earns its keep in a SOC — experimenting with **LLM-assisted triage**, enrichment summaries, and **AI-drafted detections** to see what holds up against real alerts
- 🧩 Coming from **use cases, SOAR playbooks, and procedures**, and figuring out how an AI layer fits on top of them without breaking what already works
- ⚙️ Currently exploring **agentic SOAR playbooks** that pull context from SIEM, EDR, and threat intel via **MCP** — and learning where the human in the loop belongs
- 📐 Learning to treat AI like any other detection: logged, measured against analyst ground truth, and never trusted just because the output sounds confident
- ⚡ Fun fact: I'm teaching an LLM to draft detections, and learning the hard way how many times a human still has to rewrite them

<br clear="right" />

## 🛠️ Tech stack

**AI & agents**

<!-- Swap in whatever you actually use. Logos come from shields.io + simple-icons. -->
<div align="center">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Anthropic%20API-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic API" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</div>

**Security tooling**

<div align="center">
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk" />
  <img src="https://img.shields.io/badge/Splunk%20SOAR-65A637?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk SOAR" />
  <img src="https://img.shields.io/badge/Elastic%20SIEM-005571?style=for-the-badge&logo=elastic&logoColor=white" alt="Elastic" />
  <img src="https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=for-the-badge" alt="Microsoft Sentinel" />
  <img src="https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=for-the-badge" alt="MITRE ATT&CK" />
  <img src="https://img.shields.io/badge/Sigma-1E90FF?style=for-the-badge" alt="Sigma" />
  <img src="https://img.shields.io/badge/YARA-8B0000?style=for-the-badge" alt="YARA" />
  <img src="https://img.shields.io/badge/TheHive-FFB400?style=for-the-badge&logoColor=black" alt="TheHive" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
</div>

**Platform & automation**

<!-- Pick icons from https://skillicons.dev — full list in the repo README. -->
<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,bash,powershell,linux,docker,kubernetes,git,githubactions,ansible,terraform,postgres,elasticsearch,grafana,regex,md&perline=8" alt="Platform and automation tooling" />
  </a>
</div>

## 🧪 What I'm experimenting with

| Project | What it does | Stack | Status |
|---|---|---|---|
| [ai-triage-agent](https://github.com/haikalaiman-dev/ai-triage-agent) | LLM agent that enriches alerts from SIEM, EDR, and TI, scores them, and writes the analyst summary — containment stays behind a human approve step | Python · Claude API · MCP · Splunk SOAR | 🟢 Active |
| [detection-copilot](https://github.com/haikalaiman-dev/detection-copilot) | Turns threat intel and ATT&CK techniques into draft SPL/Sigma detections with test events, delivered as a PR for review | Python · Sigma · GitHub Actions | 🟢 Active |
| [soc-mcp-server](https://github.com/haikalaiman-dev/soc-mcp-server) | MCP server exposing scoped, read-only SIEM search, case lookup, and TI enrichment tools to any LLM client | Python · MCP · Splunk REST API | 🟡 In progress |
| [ai-eval-harness](https://github.com/haikalaiman-dev/ai-eval-harness) | Scores AI triage against analyst ground truth: precision, missed escalations, and hallucinated IOCs, tracked per model and prompt version | Python · pandas · Grafana | 🟡 In progress |
| [runbook-drafter](https://github.com/haikalaiman-dev/runbook-drafter) | Generates first-draft runbooks and SOPs from playbook logic and past incidents; humans edit, CI publishes | Python · MkDocs | 🔵 Exploring |

## 🔬 Deep dives right now

- 🧪 **Evaluating LLMs for security work** — building eval sets so "it seems to work" becomes a number the SOC lead can sign off on
- 🔐 **Agent guardrails** — scoped tool permissions, approval gates, audit trails, and what "least privilege" means for a model
- 🎣 **Prompt injection as an attack surface** — an agent that reads phishing emails is reading attacker-controlled input
- 🏠 **Local models for sensitive data** — Ollama and vLLM for logs that aren't allowed to leave the building
- 🎯 **Purple teaming AI detections** — atomic tests to prove AI-drafted rules fire before anyone trusts them

## 🤝 Let's connect

<div align="center">
  <a href="https://linkedin.com/in/1haikalaiman">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://TBD">
    <img src="https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Blog" />
  </a>
  <a href="mailto:dev.haikalaiman@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br />

<!-- Contribution snake: generated daily by .github/workflows/snake.yml
     into an "output" branch. After adding the workflow, run it once
     manually from the Actions tab so the images exist. -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/haikalaiman-dev/haikalaiman-dev/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/haikalaiman-dev/haikalaiman-dev/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/haikalaiman-dev/haikalaiman-dev/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<div align="center">
  <sub>Built with ☕, SPL, and an LLM that is not allowed to close tickets on its own.</sub>
</div>
