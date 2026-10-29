<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,55:1e40af,100:0891b2&height=170&section=header&text=Seno&fontSize=46&fontColor=ffffff&fontAlignY=35&desc=Software%20Engineering%20%7C%20Business%20Systems%20%7C%20AI-assisted%20Development&descSize=15&descAlignY=55" width="100%" alt="Seno profile banner" />

### Hi, I'm Seno 👋

**Software Engineering student at HCMUS · Full-stack Developer**

I build and operate software for real businesses, with a focus on dependable integrations, complex business processes, and systems that remain correct when things go wrong.

[![Portfolio](https://img.shields.io/badge/Portfolio-ldn86.dev-2563EB?style=flat-square&logo=googlechrome&logoColor=white)](https://ldn86.dev)
[![GitHub](https://img.shields.io/badge/GitHub-LDNVN86-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/LDNVN86)
[![Discord](https://img.shields.io/badge/Discord-Connect-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/1511339489526812672)

</div>

## A little about me

I'm a software engineering student and developer working on production systems for businesses. Two of my larger projects, **TongKhoEsim** and **Tavigo**, have been delivered and are serving customers daily. I'm now developing **hub-aitelecom**, a broader enterprise platform with interconnected business functions.

My priorities have changed as the projects have grown. Choosing a framework matters, but understanding how a business operates matters more: how orders move through a system, how partners exchange data, how payments are reconciled, and what should happen when a request fails halfway through.

I use AI extensively in engineering workflows, while keeping responsibility for **business rules, system boundaries, data integrity, and operational safety** firmly in the development process.

---

## Products & current work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://tongkhoesim.com">TongKhoEsim</a></h3>
      <img src="https://img.shields.io/badge/Production-B2B%20eSIM-15803D?style=flat-square" alt="Production B2B eSIM" />
      <p>A wholesale eSIM platform connecting suppliers, distributors, and API partners. It brings together inventory management, reseller operations, partner APIs, and prepaid-wallet workflows.</p>
      <p><b>Engineering focus:</b> transaction integrity, idempotent operations, asynchronous processing, access control, and reliable provider integrations.</p>
      <p><code>Rust</code> <code>Axum</code> <code>Next.js</code> <code>PostgreSQL</code> <code>Redis</code> <code>Apache Kafka</code> <code>Centrifugo</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://tavigo.vn">Tavigo</a></h3>
      <img src="https://img.shields.io/badge/Production-Travel%20eSIM-15803D?style=flat-square" alt="Production travel eSIM" />
      <p>A customer-facing eSIM platform covering product discovery, purchasing, provisioning, and order management. It integrates with external suppliers, payment providers, and supporting business services.</p>
      <p><b>Engineering focus:</b> provider orchestration, payment and webhook handling, background jobs, authentication, and operational visibility.</p>
      <p><code>Go</code> <code>Gin</code> <code>Next.js</code> <code>PostgreSQL</code> <code>Redis</code> <code>Centrifugo</code></p>
    </td>
  </tr>
</table>

### hub-aitelecom · In development

An enterprise platform bringing multiple business functions into a connected operating environment. The scope includes **CRM, ERP, automation workflows (Nexo)**, and a longer-term direction toward mobile applications.

The architecture is evolving toward **domain-oriented services and data-driven operations**, with attention to service boundaries, consistent business processes, and controlled access to shared data. Because the platform is still under development, its internal design and implementation details remain private.

---

## How I work with AI

I see AI as part of the engineering workflow—not a substitute for understanding the problem.

| Area | Current focus |
| :--- | :--- |
| **AI-assisted development** | Research, implementation, code review, debugging, and integration work with human verification. |
| **Agent workflows** | Sub-agents, MCP connectors, task decomposition, and automation across development tools. |
| **Model selection** | Matching models to tasks based on capability, latency, cost, and the need for verification. |
| **AI development** | Learning more about model training, adaptation, evaluation, and practical AI tooling. |
| **Engineering ownership** | Validating business rules, transaction safety, security boundaries, and failure recovery before release. |

I also build utilities for debugging and integration analysis, using **browser DevTools, network traces, and HAR files** to understand how web applications behave. Some of that work has grown into private tools and services.

My day-to-day workflow also includes **tmux**, **HCOM**, and **HERDR** for organizing development work.

---

## Technology I work with

<details open>
<summary><b>Languages & frameworks</b></summary>
<br />

<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,go,ts,js,react,nextjs,nestjs,express&perline=8" alt="Rust, Go, TypeScript, JavaScript, React, Next.js, NestJS and Express logos" />
  <p>
    <img src="https://img.shields.io/badge/Axum-Rust-171717?style=flat-square&logo=rust&logoColor=white" alt="Axum" />
    <img src="https://img.shields.io/badge/Gin-Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Gin" />
  </p>
</div>
</details>

<details open>
<summary><b>Data, messaging & infrastructure</b></summary>
<br />

<div align="center">
  <img src="https://skillicons.dev/icons?i=postgres,redis,docker,cloudflare,linux,ubuntu,git&perline=7" alt="PostgreSQL, Redis, Docker, Cloudflare, Linux, Ubuntu and Git logos" />
  <p>
    <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
    <img src="https://img.shields.io/badge/Centrifugo-Realtime-334155?style=flat-square" alt="Centrifugo" />
    <img src="https://img.shields.io/badge/Cloudflare%20R2-Object%20Storage-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare R2" />
    <img src="https://img.shields.io/badge/Lima-Linux%20VMs-475569?style=flat-square&logo=linux&logoColor=white" alt="Lima" />
    <img src="https://img.shields.io/badge/tmux-Terminal-1BB91F?style=flat-square&logo=tmux&logoColor=white" alt="tmux" />
  </p>
</div>
</details>

### External systems & integrations

I have worked across payment, telecommunications, and business-service integrations, including:

**VNPay · KimNganPay · SePay · MISA · Skyfi · SimplifyTrip · eSIM Access**

The integration itself is only one part of the job. The rest is making sure requests can be retried safely, failures can be investigated, and operational records remain consistent.

---

## Other projects

These are smaller projects alongside my production work. I keep their descriptions short here; the public repositories contain the implementation details.

| Project | Description | Technologies / source |
| :--- | :--- | :--- |
| **[napplus](https://napplus.vn)** | A prepaid-services platform for top-ups, data packages, cards, and bill payments, with an ongoing migration from NestJS to Rust. | NestJS → Rust / Axum |
| **[Shop Acc Game](https://clonegiare.io.vn/)** | An online game-account store with payments, administration, and real-time features. | NestJS · Next.js · PostgreSQL · Redis · BFF |
| **[Muciii Bio](https://muciii-bio.vercel.app/)** | A simple, customizable personal bio and links page. | Personal web project |
| **[SenoDownload](https://github.com/LDNVN86/SenoDownload-BE)** | A video downloader built around format selection, media processing, and download APIs. | [Backend](https://github.com/LDNVN86/SenoDownload-BE) · [Frontend](https://github.com/LDNVN86/SenoDownload-FE) · NestJS · yt-dlp · FFmpeg |
| **[NekozaneDex](https://github.com/LDNVN86/NekozaneDex-BE)** | An unfinished manga-reading and publishing project that I used to explore full-stack development. | [Backend](https://github.com/LDNVN86/NekozaneDex-BE) · [Frontend](https://github.com/LDNVN86/NekozaneDex-FE) · Go / Gin · Next.js · TypeScript |

### Private tools & services

Besides my public projects, I develop and offer a small selection of **private tools for manga- and anime-related workflows**. Some came out of reverse engineering and analyzing how existing websites and web services work. They are separate from my open-source repositories and aren't distributed publicly.

**Interested in a demo or access?** Feel free to [contact me on Discord](https://discord.com/users/1511339489526812672) to discuss availability and terms of use.

---

<div align="center">

**Building useful systems, one business problem at a time.**

[Website](https://ldn86.dev) · [GitHub](https://github.com/LDNVN86) · [Discord](https://discord.com/users/1511339489526812672)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,55:1e40af,100:0891b2&height=80&section=footer" width="100%" alt="Footer wave" />

</div>
