# 🚀 Microsoft AI Genius Season 6 — Episode 3 Resources

### Episode 3 | From legacy modernization to AI operations

> Modernize applications and operate AI systems at scale with self-healing agents and enterprise-grade operational intelligence.

📅 **Episode page:** [Microsoft Reactor — Event 27641](https://developer.microsoft.com/en-us/reactor/events/27641/)  
📺 **Series page:** [Microsoft AI Genius Series — Season 6](https://developer.microsoft.com/en-us/reactor/series/S-1720/) (Architect → Measure → **Operate**)

Modernizing legacy applications at scale is only half the journey. The AI systems that follow need continuous monitoring, fast incident response, and dependable day-to-day operations, without adding to the engineering burden. This session follows that path end to end: **modernize legacy applications** with automated, reviewable upgrades, then **operate and scale AI systems** with self-healing agents.

---

## 📚 Contents

- [What you'll learn](#-what-youll-learn)
- [Part 1 — Legacy app modernization](#-part-1--legacy-app-modernization)
  - [.NET — ContosoUniversity](#net--contosouniversity)
  - [Java — Supply Chain (multi-repo)](#java--supply-chain-multi-repo)
- [Part 2 — AI operations with Azure SRE Agent](#-part-2--ai-operations-with-azure-sre-agent)
- [Documentation & further reading](#-documentation--further-reading)

---

## 🎯 What you'll learn

- How to scale legacy application assessments and upgrades with **Copilot Modernize CLI**
- How **stacked pull requests** make large automated migrations easier to review
- How **Azure SRE Agent** helps diagnose issues and propose tested remediations
- How to track operational impact using token efficiency, recovery time, and acceptance signals

**Technologies used:** Azure SRE Agent · Copilot App Modernization Agent & Modernize CLI · Stacked Pull Requests · Human-in-the-Loop Governance Patterns

---

## 🏗️ Part 1 — Legacy app modernization

### .NET — ContosoUniversity

A classic ASP.NET app used to demo assessment and upgrade with GitHub Copilot app modernization.

| Resource | Link |
|---|---|
| ContosoUniversity sample | [Azure-Samples/dotnet-migration-copilot-samples › ContosoUniversity](https://github.com/Azure-Samples/dotnet-migration-copilot-samples/tree/main/ContosoUniversity) |

### Java — Supply Chain (multi-repo)

A multi-repository Java application used to demo modernization across repos with the Modernize CLI and stacked pull requests.

| Component | Repository |
|---|---|
| 🖥️ Backend | [hellosnow/SupplyChain-Backend](https://github.com/hellosnow/SupplyChain-Backend) |
| 🌐 Frontend | [hellosnow/SupplyChain-Frontend](https://github.com/hellosnow/SupplyChain-Frontend) |
| ⚙️ Worker | [hellosnow/SupplyChain-Worker](https://github.com/hellosnow/SupplyChain-Worker) |

---

## 🤖 Part 2 — AI operations with Azure SRE Agent

A hands-on lab that deploys an app on AKS with PostgreSQL, injects faults, and lets Azure SRE Agent diagnose and remediate them.

| Resource | Link |
|---|---|
| Zava AKS + PostgreSQL lab | [microsoft/sre-agent › labs/zava-aks-postgres](https://github.com/microsoft/sre-agent/tree/main/labs/zava-aks-postgres) |
| SRE Agent repo (more labs & samples) | [microsoft/sre-agent](https://github.com/microsoft/sre-agent) |

---

## 📖 Documentation & further reading

| Topic | Link |
|---|---|
| GitHub Copilot app modernization (Java) | [Microsoft Learn](https://learn.microsoft.com/en-us/azure/developer/github-copilot-app-modernization/overview) |
| GitHub Copilot app modernization (.NET) | [Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/core/porting/github-copilot-app-modernization/overview) |
| GitHub Copilot Modernization Agent | [Microsoft Learn](https://learn.microsoft.com/en-us/azure/developer/github-copilot-app-modernization/modernization-agent/overview) |
| Modernize CLI (releases & tutorials) | [microsoft/modernize-cli](https://github.com/microsoft/modernize-cli) |
| Azure SRE Agent | [Microsoft Learn](https://learn.microsoft.com/en-us/azure/sre-agent/overview) |

---

<sub>💬 Questions or feedback? Join the conversation on the [session page](https://developer.microsoft.com/en-us/reactor/events/27641/).</sub>
