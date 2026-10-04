# Awesome-CI-CD-Automation

## Awesome-CI-CD-Automation

# Awesome-CI-CD-Automation

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Build Pipelines, Deployment Automation & Release Orchestration*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CI/CD Automation**. These tools help development teams automate building, testing, and deploying software — enabling faster, more reliable releases through continuous integration and continuous delivery.

**Examples** include Azure Pipelines, GitHub Actions, GitLab CI/CD, CircleCI, Travis CI, TeamCity, Jenkins, Bitrise, Argo Workflows, and Buildkite (the category leaders).

**Open-source emphasis**: CI/CD has one of the **most mature open-source ecosystems in DevOps**. **Jenkins** remains the most widely deployed CI server with **46.99% market share** across 94,806 companies . **GitLab CI/CD** is the leading unified platform, with GitLab recording **$955 million in FY2026 revenue** . **Argo Workflows** dominates Kubernetes-native CI/CD, while **Drone**, **Woodpecker**, **Tekton**, and **GoCD** provide self-hosted alternatives for teams seeking full control. This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global CI/CD tools and pipeline automation market is estimated at **~$11.85B in 2026**, growing at a **14.12% CAGR** toward **$22.92B by 2031** . The sector is **moderately fragmented** — Jenkins holds 46.99% share by customer count, but GitLab, GitHub Actions, Azure DevOps, and CircleCI each command significant enterprise segments . Cloud solutions captured **62.11% share in 2025**, while hybrid adoption grows at 15.76% through 2031 as regulated industries split sensitive workloads between on-premises and cloud burst capacity . No single vendor holds a winner-take-all position; enterprise buyers typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[GitHub Actions](https://github.com/features/actions)** | Native CI/CD in GitHub with 6,000+ marketplace Actions. | **Linux 2-core**: $0.006/min (was $0.008, -25% Jan 2026); **Windows 2-core**: $0.010/min; **macOS**: $0.062/min. Self-hosted runners: **$0.002/min** platform charge (March 2026) . | **Public repos: free unlimited**. Private repos: 2,000 min/month (Free), 3,000 (Pro), 50,000 (Enterprise) . | **~$331.8B revenue (FY2026)**  |
| **[GitLab CI/CD](https://about.gitlab.com/)** | Unified DevOps platform with built-in CI/CD, security, and project management. | **Premium**: $29/user/month (billed annually); **Ultimate**: $99/user/month. Compute minutes beyond quota: $10 per 1,000 minutes. | **Free tier**: 400 compute minutes/month, 5-user limit on private groups, 10 GiB storage. **Open source projects**: 50,000 compute minutes/month free . | **$955M revenue (FY2026)**  |
| **[Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines/)** | Microsoft's CI/CD service within Azure DevOps. | **Microsoft-hosted parallel job**: $40/month per extra job; **Self-hosted parallel job**: $15/month per extra job (unlimited minutes). First 5 users free, then $6/user/month . | **1 Microsoft-hosted job** (1,800 min/month) + **1 self-hosted job** (unlimited minutes). **Open source**: 10 free parallel jobs . | **~$331.8B revenue (Microsoft FY2026)**  |
| **[CircleCI](https://circleci.com/)** | Cloud-native CI/CD known for Docker layer caching and parallelism. | **Performance**: Custom credit-based pricing. Free tier: 30,000 credits/month, 5 active users, 1 GB network, 2 GB storage . | **Free**: 30,000 credits/month, 5 users, 30 concurrent Docker jobs, 5 self-hosted runners, 5 flaky test detections . | **~$1.7B valuation, $312.5M raised**  |
| **[Travis CI](https://travis-ci.com/)** | Early cloud CI pioneer with GitHub integration. | **Usage-Based**: $15/month (35,000 Linux build credits, 80 concurrent jobs); **Unlimited**: $78/month; **Server**: $34/month . | **Open Source**: Free for OSS repos with credit allotment . | **Private (acquired by Idera, 2019)** |
| **[TeamCity](https://www.jetbrains.com/teamcity/)** | JetBrains' CI/CD server with strong build configuration management. | **On-Premises Enterprise**: ~$2,800/year (¥19,600 CNY); **Cloud**: ~$17.60/committer/month (¥123.33 CNY, min 3 committers). **Professional (On-Prem)**: Free forever . | **Professional (On-Prem)**: Free forever, unlimited users, 3 build agents, 100 build configurations. **Cloud**: 14-day free trial. **Open source**: Free license available . | **Private (JetBrains, ~$500M+ revenue est.)** |
| **[Bitrise](https://www.bitrise.io/)** | Mobile-first CI/CD for iOS and Android. | **Developer**: ~$36/month; **Team**: ~$229/month; **Velocity**: ~$499/month. Enterprise: custom. Vendr data shows mid-sized teams (10–50 devs) typically pay **$12K–$30K/year** . | **Hobby**: Free for personal projects with limited builds. **30-day free trial** for paid plans . | **Private (~$100M+ raised)** |
| **[Buildkite](https://buildkite.com/)** | Hybrid CI/CD — agents on your infrastructure, UI in cloud. | **Pro**: $30/active-user/month (unlimited concurrency, 2,000 Linux vCPU-minutes/month, 250 managed tests) . | **Personal**: Free, 1 user, 3 concurrent jobs, 1 self-hosted agent, 90-day retention, 50,000 test executions. **30-day All Access Trial** (no credit card) . | **Private (~$70M+ raised)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Jenkins](https://github.com/jenkinsci/jenkins)** — The most widely deployed open-source automation server. 1,800+ plugins. 46.99% market share across 94,806 companies. | [![Stars](https://img.shields.io/github/stars/jenkinsci/jenkins?style=social&color=white)](https://github.com/jenkinsci/jenkins/stargazers) | ~24,000 |
| **[Drone CI](https://github.com/drone/drone)** — Container-native CI/CD with simple YAML. Apache-2.0 community edition. | [![Stars](https://img.shields.io/github/stars/drone/drone?style=social&color=white)](https://github.com/drone/drone/stargazers) | ~32,000 |
| **[Argo Workflows](https://github.com/argoproj/argo-workflows)** — Kubernetes-native workflow engine for parallel job orchestration. CNCF graduated. | [![Stars](https://img.shields.io/github/stars/argoproj/argo-workflows?style=social&color=white)](https://github.com/argoproj/argo-workflows/stargazers) | ~15,500 |
| **[Dagger](https://github.com/dagger/dagger)** — Programmable CI/CD engine running pipelines in containers. Portable across local and CI. | [![Stars](https://img.shields.io/github/stars/dagger/dagger?style=social&color=white)](https://github.com/dagger/dagger/stargazers) | ~13,800 |
| **[Tekton](https://github.com/tektoncd/pipeline)** — Kubernetes-native CI/CD building blocks. CD Foundation. | [![Stars](https://img.shields.io/github/stars/tektoncd/pipeline?style=social&color=white)](https://github.com/tektoncd/pipeline/stargazers) | ~8,500 |
| **[Concourse](https://github.com/concourse/concourse)** — Pipeline-based CI with strong visualization. | [![Stars](https://img.shields.io/github/stars/concourse/concourse?style=social&color=white)](https://github.com/concourse/concourse/stargazers) | ~7,500 |
| **[GoCD](https://github.com/gocd/gocd)** — Continuous delivery server with value stream mapping. | [![Stars](https://img.shields.io/github/stars/gocd/gocd?style=social&color=white)](https://github.com/gocd/gocd/stargazers) | ~7,200 |
| **[Woodpecker CI](https://github.com/woodpecker-ci/woodpecker)** — Lightweight community fork of Drone. Multi-forge support. | [![Stars](https://img.shields.io/github/stars/woodpecker-ci/woodpecker?style=social&color=white)](https://github.com/woodpecker-ci/woodpecker/stargazers) | ~5,000 |
| **[Agola](https://github.com/agola-io/agola)** — Self-hosted CI/CD with Docker and Kubernetes backends. | [![Stars](https://img.shields.io/github/stars/agola-io/agola?style=social&color=white)](https://github.com/agola-io/agola/stargazers) | ~1,500 |
| **[Kraken CI](https://github.com/kraken-ci/kraken)** — Modern self-hosted CI with Starlark/Python workflows. Scalable to thousands of executors. | [![Stars](https://img.shields.io/github/stars/kraken-ci/kraken?style=social&color=white)](https://github.com/kraken-ci/kraken/stargazers) | ~500 |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CI/CD platforms handle source code, secrets, and deployment credentials; ensure proper access controls, secret management, and compliance with organizational security policies.
- **Open-source reality**: The CI/CD ecosystem is **exceptionally mature and production-proven** in open source. **Jenkins** remains the most widely deployed CI server (46.99% market share), while **Argo Workflows** dominates Kubernetes-native pipelines. **GitLab CI/CD** and **GitHub Actions** provide integrated commercial alternatives with generous free tiers. The open-source path is **genuinely viable** for virtually every CI/CD scenario, from single-developer projects to enterprise deployments.

---

**Made for DevOps engineers, platform teams, SREs, and software developers.**
Let's make CI/CD automation more open, transparent, and efficient.
