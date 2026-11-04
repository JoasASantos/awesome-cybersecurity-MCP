# 🧠 Awesome MCP - Model Context Protocol for Cybersecurity & Reverse Engineering

A curated list of tools, servers, and resources related to the **Model Context Protocol (MCP)**, focused on cybersecurity, reverse engineering, Shodan automation, GitHub Actions, OWASP ZAP, IDA Pro, and more.

> **MCP** is an open protocol for connecting AI applications to external tools and data sources. MCP servers expose tools, prompts, or resources; clients access them. See the [official protocol documentation](https://modelcontextprotocol.io/introduction). This list includes both MCP servers and security tools that inspect or constrain supported MCP interactions.

---

## 📚 Table of Contents

- [🛠️ MCP Servers for Pentesting & Security](#️-mcp-servers-for-pentesting--security)
- [🔬 Reverse Engineering & IDA MCPs](#-reverse-engineering--ida-mcps)
- [🌐 Shodan & Web Security MCPs](#-shodan--web-security-mcps)
- [⚙️ DevSecOps / GitHub Actions MCPs](#️-devsecops--github-actions-mcps)
- [📽️ Demos and Videos](#-demos-and-videos)
- [🌍 Official Sites and Docs](#-official-sites-and-docs)
- [💡 Other Notable MCP Projects](#-other-notable-mcp-projects)

---

## 🛠️ MCP Servers for Pentesting & Security

- [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server)  
  MCP server designed for static APK analysis using Jadx, enabling remote command execution.

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)  
  A curated list of useful MCP servers for various purposes such as pentesting and automation.

- [cyproxio/mcp-for-security](https://github.com/cyproxio/mcp-for-security)  
  Offensive security-focused modular command platform for vulnerability testing.

- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security)  
  Simple and extensible MCP base for building custom security automation tools.

- [DMontgomery40/pentest-mcp](https://github.com/DMontgomery40/pentest-mcp)  
  Structured MCP platform supporting full-scope pentesting, including scanners and exploit tools.

- [bernik-bot/ichi-mcp](https://github.com/bernik-bot/ichi-mcp)  
  Free, keyless MCP server for the Internet Cyber Health Index (ICHI) — exposes the current internet-wide threat band (NORMAL to CRITICAL), numeric score, recent critical-vulnerability advisories, and source-feed health with no API key required. Disclosure: maintained for ICHI's creator.

---

## 🔬 Reverse Engineering & IDA MCPs

- [MxIris-Reverse-Engineering/ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server)  
  MCP server for sending remote commands to IDA Pro, useful for automating reverse engineering tasks.

- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp)  
  Advanced integration with IDA Pro enabling scripted analysis via an MCP interface.

---

## 🌐 Shodan & Web Security MCPs

- [ADEOSec/mcp-shodan](https://github.com/ADEOSec/mcp-shodan)  
  MCP platform using Shodan for discovering and categorizing exposed internet assets.

- [shadsidd/Owasp-Zap-MCP-Server-Demo](https://github.com/shadsidd/Owasp-Zap-MCP-Server-Demo)  
  Demo MCP server with OWASP ZAP integration for automated web vulnerability scanning.

---

## ⚙️ DevSecOps / GitHub Actions MCPs

- [sammcj/mcp-snyk](https://github.com/sammcj/mcp-snyk)  
  MCP integration with [Snyk](https://snyk.io) to detect vulnerabilities in open source dependencies.

- [awslabs/mcp](https://github.com/awslabs/mcp)  
  Official AWS project for modular pipeline management with plugin-based security modules.

- [quantakrypto/pqc-tools](https://github.com/quantakrypto/pqc-tools)  
  MCP server providing post-quantum cryptography (PQC) readiness tools — scans code and dependencies for quantum-vulnerable RSA/ECDSA/ECDH ("harvest now, decrypt later"), plans migration, and verifies fixes. Deterministic, offline, zero runtime deps; Apache-2.0, on npm and the official MCP registry.

- [bernik-bot/ichi-threat-level-action](https://github.com/bernik-bot/ichi-threat-level-action)  
  GitHub Action that reads the ICHI internet-wide cyber threat band in CI/CD pipelines and optionally fails the job when the band meets or exceeds a configured threshold (e.g., HIGH or CRITICAL). Zero API keys needed; uses ICHI's public API. Disclosure: maintained for ICHI's creator.

---

## 📽️ Demos and Videos

- [YouTube - MCP Server Walkthrough](https://www.youtube.com/watch?v=zIlzty7VexY)  
  Video walkthrough showing how to deploy and use an MCP server for security testing.

---

## 🌍 Official Sites and Docs

- [MCP Cybersecurity Official](https://mcpcybersecurity.com/)  
  Official site with documentation, examples, and plugin templates for building your own MCPs.

---

## 💡 Other Notable MCP Projects

- [open-webui/mcpo](https://github.com/open-webui/mcpo)  
  Web UI framework to interface with various MCP backends and orchestrate security modules.

- [hashgraph-online/hol-guard](https://github.com/hashgraph-online/hol-guard)  
  Open-source, local-first security controls for supported AI agent actions, including MCP tool calls. It is a security layer for agent integrations, not an MCP server or a guarantee of coverage for every client.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request with more MCP tools, servers, integrations, or educational content.  
This repository aims to centralize knowledge around **MCPs** and accelerate development of modular cyber platforms.

---

## ⭐ License

This awesome list is licensed under the [MIT License](LICENSE).


