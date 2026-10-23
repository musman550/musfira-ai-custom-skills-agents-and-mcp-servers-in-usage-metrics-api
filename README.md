# Musfira AI Custom skills, agents, and MCP servers in usage metrics API - By Musfira AI

> Curated, written, and published by **Musfira AI**.

## Overview

Custom skills, agents, and MCP servers in usage metrics API are a new feature that allows organizations to track and analyze various aspects of their usage metrics, including the names of the skills, custom agents, Model Context Protocol (MCP) servers, slash commands, and plugins they create. This feature is significant because it provides a more comprehensive understanding of an organization's usage patterns, enabling them to identify trends, optimize their workflows, and make data-driven decisions. By tracking these specific components, organizations can gain a deeper insight into their technology stack and the activities that occur within it. This information is particularly valuable for organizations that rely heavily on their technology infrastructure, such as IT departments or software development teams.

**Source reference:** [https://github.blog/changelog/2026-10-22-custom-skills-agents-and-mcp-servers-in-usage-metrics-api](https://github.blog/changelog/2026-10-22-custom-skills-agents-and-mcp-servers-in-usage-metrics-api)
**Published:** 2026-10-23

## Key Features

Concrete scenario of someone using it

For example, a marketing team at a large e-commerce company might use this feature to track the usage of custom agents, such as those responsible for sending promotional emails or creating social media campaigns. They might also be interested in monitoring the usage of Model Context Protocol (MCP) servers, which are used to handle complex business logic and data processing tasks. Additionally, they might be tracking the usage of specific slash commands, such as `/orders/new` or `/products/new`, which are used to manage orders and products. By analyzing these custom components, the marketing team can gain a better understanding of how their technology is being used and identify areas for improvement.

## Use Cases

The usage metrics API provides a centralized platform for tracking custom skills, agents, and MCP servers. Custom skills can be used to automate repetitive tasks or to create custom workflows. MCP servers can be used to handle complex business logic and data processing tasks. Slash commands can be used to manage orders and products, and are commonly used in e-commerce platforms. By tracking these custom components, organizations can gain a more comprehensive understanding of their technology infrastructure.

## Quickstart

### Python

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

### n8n Workflow

Import `workflow.json` into your n8n instance via **Workflows > Import from File**.

### Local LLM (Ollama)

```bash
ollama pull llama3
ollama run llama3
```

Q: What is the purpose of the usage metrics API?
A: The usage metrics API is designed to track and analyze various aspects of an organization's usage patterns, including custom skills, agents, Model Context Protocol (MCP) servers, slash commands, and plugins.

Q: How does the usage metrics API enable organizations to track custom components?
A: The usage metrics API provides a centralized platform for tracking custom skills, agents, and MCP servers, as well as other custom components, enabling organizations to gain a more comprehensive understanding of their technology infrastructure.

Q: What is the potential impact of the usage metrics API on organizational decision-making?
A: By analyzing the usage metrics data, organizations can gain insights into their technology usage and identify areas for improvement, enabling them to make data-driven decisions that optimize their workflows and achieve their business goals.

## FAQ

One example of a real-world use case is a software development team using this feature to track the usage of custom agents responsible for testing and debugging their code. Another example is a marketing team using the API to track the usage of Model Context Protocol (MCP) servers for managing orders and products. A third example is a customer support team using the API to track the usage of custom skills and agents for troubleshooting and resolving customer issues.

## Repository Structure

```
.
├── main.py
├── requirements.txt
├── workflow.json
├── ui/
│   └── index.html
└── README.md
```

## About Musfira AI

Musfira AI builds automation systems, AI agents, and YouTube automation pipelines for
creators and businesses across Pakistan and India.

- 🌐 Website: [https://musfiraai.com](https://musfiraai.com)
- ▶️ YouTube: [Automate With Musfira AI](https://www.youtube.com/@automatewithmusfiraai)
- 💼 LinkedIn: [https://www.linkedin.com/in/musfira-ai-b3218b39b](https://www.linkedin.com/in/musfira-ai-b3218b39b)
- 📸 Instagram: [https://instagram.com/musma_n55](https://instagram.com/musma_n55)
- 📍 Location: [Google Maps](https://share.google/kJchUsfQyABVLghSF)
- 💬 WhatsApp: [Chat with us](https://wa.me/923217358096)
- 📞 Call: [+923217358096](tel:+923217358096)

---

*This repository is part of Musfira AI's daily AI trend tracking series. Star ⭐ this repo
and follow the links above for daily updates on AI models, n8n workflows, and local LLM tools.*
