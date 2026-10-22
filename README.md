<a href="https://www.deepanshuweb.in" target="_blank"><img src="https://github.com/symaticvisuals/symaticvisuals/blob/main/assets/banner.png?raw=true" alt="Deepanshu Goel" /></a>

<h1 align="center">Hi 👋, I'm Deepanshu</h1>

<p align="center">
Forward Deployed Engineer at Heizen and Founding Engineer at GIKSN Research.<br/>
I build LLM and multi-agent systems that customers run in production, and I stay with each one from the discovery workshop to deployment.
</p>

<p align="center">
  <a href="https://www.deepanshuweb.in"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-deepanshuweb.in-111111?style=for-the-badge" /></a>
  <a href="https://www.linkedin.com/in/deepanshuweb"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-deepanshuweb-0A66C2?style=for-the-badge" /></a>
  <a href="https://twitter.com/thedeepanshuweb"><img alt="X" src="https://img.shields.io/badge/thedeepanshuweb-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="https://github.com/symaticvisuals"><img alt="GitHub followers" src="https://img.shields.io/github/followers/symaticvisuals?style=for-the-badge" /></a>
</p>

## Work

My main project at Heizen is FlowOS, an enquiry-to-quotation platform for an industrial instrumentation manufacturer. Their sales team now runs its quoting on it, from a customer email in a shared Microsoft 365 inbox to a priced quotation PDF. An LLM pipeline reads each enquiry, OCRs the attachments, and cites the lines it used, and code decides which product and price each line gets.

I've written up three other builds, anonymized by client:

- [Spoken findings into radiology reports](https://www.deepanshuweb.in/work/case-03-radiology-spoken-findings-to-reports): live dictation becomes a structured, template-grounded report, at a cost low enough to run on every study. Heizen, 12 weeks.
- [Construction schedules from a document dump](https://www.deepanshuweb.in/work/case-02-construction-schedule-from-documents): contracts, drawings, and bills of quantities go in, and a schedule a scheduler can import into Primavera P6 comes out. Heizen, 16 weeks.
- [Business rules as data](https://www.deepanshuweb.in/work/case-01-rules-as-data): the backend of a lifecycle CRM shared by nine teams, where a rule change is configuration and needs no deploy. 12 weeks.

Before Heizen I was a full stack developer at MAGES Studio, a Singapore gaming and EdTech company, from 2023 to 2025, with a month on site in Singapore. I architected their training platform for healthcare, the navy, and World Bank-backed cocoa farming programs, and shipped the LLM features on top of it.

## Open source

I'm a founding engineer at [GIKSN Research](https://www.giksn.com/), an independent lab working on AI and memory. Its first open product is [Rinne](https://github.com/GIKSN-RESEARCH/Rinne), which I build with Siddharth Manjul. Rinne is a terminal-first orchestrator written in Rust. It plans a goal as a DAG and drives Claude Code, Codex, Grok, and OpenCode as workers until the checks pass. Everything runs on your machine, API keys stay in the OS keychain, and there is a [macOS app](https://github.com/GIKSN-RESEARCH/rinne_macOS) as well.

My parts include the TUI's live agents view and command palette, the install script, and `rinne learn`, which indexes a codebase into a code graph and explains it separately for engineers and for product people.

<p>
  <a href="https://crates.io/crates/rinne"><img alt="crates.io" src="https://img.shields.io/crates/v/rinne?style=for-the-badge" /></a>
  <a href="https://crates.io/crates/rinne"><img alt="crates.io downloads" src="https://img.shields.io/crates/d/rinne?style=for-the-badge" /></a>
</p>

```sh
curl -fsSL https://raw.githubusercontent.com/GIKSN-RESEARCH/Rinne/main/install.sh | sh
```

I also keep [hunt-desk](https://github.com/symaticvisuals/hunt-desk), a local job search desk in the terminal. It fetches postings, scores them with Claude, and tailors a one-page resume for the best ones.

## Talks and community

- 2024: spoke at React Delhi #2 on wiring LangChain into React apps.
- 2024: [demoed Git Riddle](https://www.linkedin.com/posts/deepanshuweb_aicommunity-gitriddle-defogai-activity-7174680875035422720-PRim) at Singapore's Pi Day SQL Coder meetup. It's a LangChain and Next.js app that writes riddles from a developer's GitHub profile.
- 2024: [won Best Use of Move ($2,500)](https://www.linkedin.com/posts/deepanshuweb_aptoswinterschool-aptos-blockchain-activity-7246775555050627074-_X6X) at Aptos Winter School in Goa.
- 2024: [spoke at React Delhi #7](https://www.linkedin.com/posts/deepanshuweb_reactdelhi-encorets-backenddev-activity-7266340533382320128-sJIS) on Encore.ts and typed backends.
- Member of the [EddieHub](https://github.com/EddieHubCommunity) community.

## Writing

Since 2025 I've posted Stack Wednesday, a weekly note [on LinkedIn](https://www.linkedin.com/in/deepanshuweb/recent-activity/all/) about tools and stacks worth keeping. Recent posts:

- [Notes from the forward deployed seat](https://www.linkedin.com/posts/deepanshuweb_forwarddeployedengineer-aiagents-softwareengineering-share-7486033760392486912-sQjG), on what happens when agents meet real operators and workflows.
- [The Rinne thesis](https://www.linkedin.com/posts/deepanshuweb_opensource-localai-aiagents-ugcPost-7486443311541403649-2ufa): one local conductor over your coding agents and API keys.
- [Scoping agent-heavy delivery](https://www.linkedin.com/posts/deepanshuweb_aiagents-forwarddeployedengineer-share-7487875837963202560-SVkC): outcomes, rules, and the options we rejected.

## Stack

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <br/>
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" />
  <br/>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <br/>
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <br/>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img alt="shadcn/ui" src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
</p>

<div align="center">
<img align="center" src="https://github-readme-streak-stats.herokuapp.com?user=symaticvisuals&theme=react" alt="GitHub streak" width="48%"/>
<img align="center" src="https://github-readme-stats.vercel.app/api?username=symaticvisuals&show_icons=true&theme=react&count_private=true" alt="GitHub stats" width="48%"/>
</div>

<p align="center">
Off the keyboard I run. My first 5k turned into a 10k a month later.<br/>
Questions or work? <a href="https://u6z4fs1b3g3.typeform.com/to/SSXqwLJC">Ask me anything</a>.
</p>
