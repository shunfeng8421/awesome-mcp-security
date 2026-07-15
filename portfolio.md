# Security Researcher Portfolio — shunfeng8421

**GitHub**: [github.com/shunfeng8421] | **CVE**: 2 original | **Papers**: 2

---

## 🔍 Vulnerability Discovery

| CVE | Type | CWE | Impact |
|------|------|------|------|
| cherrystudio-qq-mcp #1 | Path Traversal | CWE-22 | Arbitrary file read (CVSS 7.5) |
| cherrystudio-qq-mcp #2 | SSRF | CWE-918 | Internal network scanning (CVSS 6.5) |

**Verified PoCs**: 18/18 (exploit-arsenal library)

---

## 💣 Exploit Library

18 self-written exploits covering: Redis, Kong, Splunk, Next.js, MCP Inspector, PostgreSQL, Gitea, n8n, LiteLLM, mitmproxy, SimpleHelp, ingress-nginx, Roundcube, FreePBX, Craft CMS + 2 original cherrystudio

→ [github.com/shunfeng8421/exploit-library](https://github.com/shunfeng8421/exploit-library)

---

## 🧠 MCP Security Research

**First empirical study of MCP server security** — audited 35 servers across 4 languages

| Finding | Value |
|------|------|
| Vulnerability rate | 4% (2/50) |
| Attack surfaces | 6 (20+ sub-types) |
| npm ecosystem scan | 460+ packages — verified secure |

→ [awesome-mcp-security](https://github.com/shunfeng8421/awesome-mcp-security)

---

## 📊 Papers

1. **Prompt Injection is Not an AI Problem** (2026) — Experimental proof: defense must be at MCP tool layer, not prompt layer
2. **An Empirical Study of MCP Server Security** (2026) — 6 attack surfaces from 30+ audits

---

## 🔧 Tools

| Tool | Language | Purpose |
|------|------|------|
| [mcp-scan](https://github.com/shunfeng8421/mcp-scan) | Python | Automated MCP security assessment (v1.2, 6 attack surfaces) |
| [awesome-mcp-security](https://github.com/shunfeng8421/awesome-mcp-security) | MD/JS | MCP security docs + knowledge graph (91 nodes) |
| [exploit-library](https://github.com/shunfeng8421/exploit-library) | Python | 18 verified exploits |

---

## ⚙️ Automated Pipeline

```
09:00 daily-scan → dependency back-check
10:00 NVD sync → new CVE intelligence  
12:00 audit-pipeline → scan→reason→report
      npm-batch-scan → every 2 hours, 7 keywords
```

---

## 📐 Skills

| Skill | Level |
|------|------|
| Python security auditing | Expert |
| Semgrep rule authoring (41 rules, 7 languages) | Advanced |
| Fuzzing (template + coverage-guided) | Intermediate |
| Binary reverse engineering | Intermediate |
| Network protocol analysis | Intermediate |
| Memory exploitation | Intermediate |
| Solidity smart contract auditing | Basic |

---

## 🔗 Links

- GitHub: [shunfeng8421](https://github.com/shunfeng8421)
- Tools: [mcp-scan](https://github.com/shunfeng8421/mcp-scan) | [exploit-library](https://github.com/shunfeng8421/exploit-library)
- Research: [awesome-mcp-security](https://github.com/shunfeng8421/awesome-mcp-security)
