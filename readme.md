<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Web Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/steel-dev/awesome-web-agents/actions/workflows/lint.yaml/badge.svg)](https://github.com/steel-dev/awesome-web-agents/actions/workflows/lint.yaml)

<!-- subtitle -->

A curated list of tools, frameworks, and resources for building AI agents that can browse and interact with the web.

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="steel_hero.png" />
</a>

<!-- description -->

A comprehensive collection of browser automation tools, AI-powered web agents, and related resources for building autonomous systems that can navigate and interact with websites.

</div>

<!-- TOC -->

## Contents

- [Awesome Web Agents  ](#awesome-web-agents--)
  - [Contents](#contents)
  - [Browsers for AI](#browsers-for-ai)
  - [Autonomous Web Agents](#autonomous-web-agents)
  - [AI Web Automation Tools](#ai-web-automation-tools)
    - [Dev Tools](#dev-tools)
  - [AI Web Crawlers](#ai-web-crawlers)
  - [Web Search \& Query Tools](#web-search--query-tools)
  - [Benchmarks \& Research](#benchmarks--research)
  - [Tutorials \& Guides](#tutorials--guides)
  - [Follow](#follow)
  - [Contributing](#contributing)
    - [Contributors](#contributors)

<!-- CONTENT -->

<!--
## Featured (new releases)

- [Apple](https://apple.com) - Apple as a placeholder.
- [Opera Agentic Feature](https://techcrunch.com/2025/03/03/opera-announces-a-new-agentic-feature-for-its-browser/) - Opera announces a new agentic feature for its browser, showcasing innovative web agent integration.

-->
## Browsers for AI

Cloud-hosted browser environments and APIs specifically designed for AI agents to interact with web pages seamlessly.

- [Apify](https://apify.com/) - Cloud platform for web automation and scraping with support for LLM-powered agents. _(Paid)_
- [Browserbase](browserbase.com) - Closed-source headless browser API. _(Paid)_
- [Browserless](https://www.browserless.io) - Browser-as-a-service enabling you to use headless Chrome via simple APIs. _(Paid)_

## Autonomous Web Agents

AI agents that autonomously navigate and interact with the web through a user-friendly interface.

- [Surf.new](https://surf.new) - An open-source playground for interaction with different web agents. ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/surf.new?style=social)
- [Browser-Use](https://www.browser-use.com) - Toolkit that bridges AI and the browser. ![GitHub Repo stars](https://img.shields.io/github/stars/Browser-Use/browser-use?style=social)
- [Axiom.ai](https://axiom.ai) - No-code browser automation tool that can be powered by AI. Users can create bots to click through sites, scrape data, and perform web-based workflows via a visual builder (with options to integrate LLM decisions). _(Paid)_
- [Dendrite](https://dendrite.ai) - Framework-agnostic platform for building reliable web agents. Focuses on atomic actions (click, type, etc.) with support for authentication, data extraction, and multi-factor flows. Aims to integrate with any stack to add web automation capabilities to your AI. _(Private Beta, Paid)_
- [Runner H](https://www.hcompany.ai/) - Autonomous web assistant.
- [Harpa.ai](https://harpa.ai/) - Browser-based autonomous navigation assistant.
- [Starizon.ai](https://starizon.ai/) - Innovative web copilot.
- [WebVoyager (Agent)](https://github.com/MinorJerry/WebVoyager) - Vision-enabled web agent.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Configure and deploy autonomous AI agents in your browser for web research and data extraction. _(Open-source)_ ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social)
- [Automa](https://github.com/AutomaApp/Automa) - No-code browser automation tool for automating repetitive tasks like form filling and data extraction. ![GitHub Repo stars](https://img.shields.io/github/stars/AutomaApp/Automa?style=social)
- [doBrowser](https://www.dobrowser.io) - An AI-powered Chrome extension that understands natural language and takes actions in your browser on your behalf.
- [Proxy by Convergence](https://convergence.ai) - Proxy is your AI-powered digital assistant that explores the web and executes tasks through simple conversation. _(Free Plan)_
- [OpenAI Operator](https://openai.com/index/introducing-operator/) - OpenAI's operator tool for automation.
- [Google Project Mariner](https://deepmind.google/technologies/project-mariner/) - An innovative web automation project.

## AI Web Automation Tools

Tools, frameworks and libraries that translate natural language instructions into web interactions.

- [Agent-E](https://github.com/EmergenceAI/Agent-E) - Agent-driven automation framework with advanced HTML DOM distillation and multi-agent architecture. ![GitHub Repo stars](https://img.shields.io/github/stars/EmergenceAI/Agent-E?style=social)
- [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) - Experimental open-source application showcasing GPT-4's capabilities for autonomous task completion and web browsing. ![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT?style=social)
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - Simplified version of Task-Driven Autonomous Agent using OpenAI and Pinecone APIs. ![GitHub Repo stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=social)
- [LaVague](https://www.lavague.ai/) - A framework for developing AI web agents. ![GitHub Repo stars](https://img.shields.io/github/stars/lavague-ai/LaVague?style=social)
- [LLamaIndex](https://github.com/jerryjliu/llama_index) - Framework for connecting LLMs with external data for web scraping and data extraction. ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=social)
- [LLM Scraper](https://github.com/mishushakov/llm-scraper) - Uses LLMs for intelligent scraping and content understanding. ![GitHub Repo stars](https://img.shields.io/github/stars/mishushakov/llm-scraper?style=social)
- [PulsarRPA](https://github.com/platonai/pulsarRPA) - AI-powered RPA tool for browser-based automation. ![GitHub Repo stars](https://img.shields.io/github/stars/platonai/pulsarRPA?style=social)
- [Skyvern-AI](https://www.skyvern.com/) - Framework to automate browser-based workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern?style=social)
- [Stagehand](https://www.stagehand.dev/) - AI web browsing framework. ![GitHub Repo stars](https://img.shields.io/github/stars/browserbase/stagehand?style=social)
- [Tarsier](https://github.com/reworkd/tarsier) - Vision utilities library for web interaction agents. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/tarsier?style=social)
- [VimGPT](https://github.com/ishan0102/vimGPT) - Experimental project using GPT-4 Vision to browse the web via the Vimium extension. Accepts natural language goals and visually interprets pages to click links, fill fields, etc., all with keyboard-only (vim-like) control. _(Open-source)_ ![GitHub Repo stars](https://img.shields.io/github/stars/ishan0102/vimGPT?style=social)
- [WebAgent (OpenAgents)](https://github.com/xlang-ai/OpenAgents) - The web-browsing agent module of the OpenAgents platform (HKU). Enables autonomous navigation of websites via natural language, as part of a larger multi-modal agent framework. _(Open-source)_ ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=social)
- [Langchain Playwright toolkit](https://python.langchain.com/docs/integrations/tools/playwright/#use-within-an-agent) - Toolkit integration with AI agents.
- [Cekura.io](https://www.cekura.io/) - New AI web automation tool.
- [Kura](https://www.trykura.com/) - AI web automation platform.
- [Runcopycat](https://www.runcopycat.com/) - No-code browser automation copilot.
- [Bardeen.ai](https://bardeen.ai) - Chrome extension to run AI-powered browser automations.
- [Automina](https://automina.app/) - No-code AI automation tool with drag-and-drop interface for building and sharing web automation workflows. _(Free tier, Paid plans)_
- [Strawberry Browser](https://www.strawberrybrowser.com/) - Personal assistant that sits in your browser and gets shit done.
- [Highlight](https://highlightai.com/) - Highlight AI lets models understand your desktop activity. Get stuff done faster.

### Dev Tools
- [Steel.dev](https://steel.dev) - Open-source headless browser API built specifically for AI agents and apps. ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=social)
- [Omniparser](https://microsoft.github.io/OmniParser/) - Tool for parsing and automation.

## AI Web Crawlers

Autonomous crawlers that leverage AI to navigate websites and extract content.

- [FireCrawl](https://www.firecrawl.dev/) - AI-driven web crawling platform for structured data extraction. _(Open-source engine, Paid service)_
- [Crawel4AI](crawl4ai.com) - Open-source LLM Friendly Web Crawler & Scraper. ![GitHub Repo stars](https://img.shields.io/github/stars/unclecode/crawl4ai?style=social)
- [GPT Scraper](https://github.com/asyml/gpt-scraper) - Uses GPT models to interpret and extract data from complex web pages. ![GitHub Repo stars](https://img.shields.io/github/stars/asyml/gpt-scraper?style=social)
- [Reworkd](https://reworkd.com) - No-code web data extraction solution using agentic AI. _(Private Beta, Paid)_
- [WebScrapeGPT](https://github.com/miguelgfierro/webscrapegpt) - Uses GPT models to extract structured information from web pages. ![GitHub Repo stars](https://img.shields.io/github/stars/miguelgfierro/webscrapegpt?style=social)

## Web Search & Query Tools

Utilities that help agents search the web or query web data via natural language.

- [AgentQL](https://www.agentql.com/) - A query language and toolkit that makes the web AI-ready. _(Closed-source, Free tier)_
- [GQLPT.dev](https://gqlpt.dev) - GraphQL Plain Text – Leverages AI to translate natural language into GraphQL queries. Includes client SDKs and CLI for interfacing with APIs using plain English. _(Free, Closed-source)_
- [GraphQL.Chat](https://graphql.chat) - Chat-based interface for GraphQL APIs. Enables an AI agent to converse with a GraphQL endpoint using natural language. _(Free, Closed-source)_
- [Serper.dev](https://www.serper.dev) - Search API that provides Google Search results for LLM agents. _(Paid)_
- [Jina.ai](https://jina.ai/) - Neural search platform for web data.
- [Exa.ai](https://exa.ai) - Semantic Search Engine for AI.

## Benchmarks & Research

Datasets, benchmarks, and notable research efforts for evaluating and advancing web-capable AI agents.

- [Bananalyzer](https://github.com/reworkd/bananalyzer) - Open-source evaluation framework for web-based AI agents. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/bananalyzer?style=social)
- [Mind2Web](https://osu-nlp-group.github.io/Mind2Web) - A large-scale dataset for generalist web agents. _(Open-source)_
- [MiniWoB++](https://miniwob.farama.org) - A classic suite of 104 mini web browser tasks in a synthetic environment. Frequently used to train and evaluate early web agents. _(Open-source)_
- [ST-WebAgentBench](https://github.com/SafeAILab/WebAgentBench) - A benchmark focused on the Safety & Trustworthiness of web agents. _(Open-source)_
- [WebArena](https://webarena.dev) - A realistic, self-hostable web environment for autonomous agents. Includes official leaderboard tracking agent performance. _(Open-source)_
- [WebCanvas](https://github.com/web-canvas/webcanvas) - An online evaluation framework for dynamic web environments. Tests agents on live websites. _(Open-source)_
- [WebGPT](https://openai.com/research/webgpt) - OpenAI's browser-assisted question-answering research project. _(Research, 2021)_
- [WebShop](https://webshop-pnlp.github.io) - A simulated e-commerce shopping environment with 1.18M real Amazon products. _(Open-source)_
- [WebVoyager (Benchmark)](https://github.com/MinorJerry/WebVoyager) - Vision-enabled web agent using GPT-4V for real-world website interaction. _(Research, 2024)_
- [WorkArena](https://github.com/ServiceNow/WorkArena) - A suite of 33 browser-based tasks for enterprise "knowledge worker" scenarios. _(Open-source)_

## Tutorials & Guides

Resources for learning how to build, deploy, or utilize AI web agents.

- [Build an AI Browser Agent](https://dzone.com/articles/build-ai-browser-agent-llms-playwright-browser-use) - Step-by-step guide to create an AI that browses the web using Playwright and the Browser-Use library.
- [Install & Run Browser-Use Locally](https://aleksandarhaber.com/install-and-run-browser-use-ai-agents-locally-using-ollama/) - Instructions on installing the open-source Browser-Use agent with a local LLM.
- [Build a Browser Agent with DeepSeek](https://nodeshift.com/blog/build-a-browser-use-agent-with-deepseek-a-step-by-step-guide) - Walks through deploying a Browser-Use web UI agent powered by the DeepSeek model on a cloud VM.
- [How to Build AI Agents That Can Use Any Website](https://dev.to/charles_maddock/how-to-build-ai-agents-that-can-use-any-website-cpb) - Overview of tools and approaches for web agents, using the Dendrite SDK as an example.

<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/steel-dev/awesome-web-agents/graphs/contributors)!
