<!-- Header Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Seno%20Impotent&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Full-Stack%20Developer%20%7C%20Software%20Engineering%20Student&descSize=16&descAlignY=52" width="100%"/>
</div>

<!-- Typing Animation -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&multiline=true&repeat=false&width=700&height=130&lines=Software+Engineering+Student+%40+HCMUS;Building+production+eSIM+%26+fintech+platforms;Go+%E2%80%A2+Rust+%E2%80%A2+TypeScript+%E2%80%A2+Next.js;Money-safe+systems%3A+ledgers%2C+idempotency%2C+outbox" alt="Typing SVG" />
  </a>
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://ldn86.dev"><img src="https://img.shields.io/badge/Portfolio-ldn86.dev-6366F1?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="https://github.com/LDNVN86"><img src="https://img.shields.io/github/followers/LDNVN86?label=Followers&style=for-the-badge&logo=github&color=181717"/></a>
  <img src="https://komarev.com/ghpvc/?username=LDNVN86&style=for-the-badge&color=6366F1"/>
</p>

---

## 🚀 Summary

- 🎓 **HCMUS** - Faculty of Information Technology (Software Engineering)
- 🏗️ Shipping **production, money-critical platforms**: [Tavigo](https://tavigo.vn) (eSIM e-commerce), [TongKhoEsim](https://tongkhoesim.com) (B2B eSIM wholesale), [napplus](https://napplus.vn) (prepaid top-up)
- 💻 Backends in **Go** (Gin, pgx) & **Rust** (Axum, SQLx) — transactional outbox, Redis Streams workers, double-entry ledgers
- 🌐 Frontends with **Next.js / React / TypeScript** behind **BFF** auth layers
- 🗄️ **PostgreSQL**, **Redis**, **Docker**, Centrifugo realtime, VPS ops with Traefik/Caddy + Cloudflare
- 🎨 Hobbies: anime, stories, algorithms, and exploring new tech

---

## 🏆 Flagship Products — Live in Production

<table>
  <tr>
    <td>
      <h3 align="center">📡 Tavigo — eSIM E-commerce Platform</h3>
      <p align="center">
        <a href="https://tavigo.vn" target="_blank">
          <img src="https://img.shields.io/badge/LIVE-tavigo.vn-22c55e?style=for-the-badge&logo=google-chrome&logoColor=white"/>
        </a>
        <img src="https://img.shields.io/badge/Source-Private-6b7280?style=for-the-badge&logo=github"/>
      </p>
      <p align="center">Travel eSIM e-commerce for the Vietnamese market — real-time provisioning from 3 upstream suppliers (eSIM Access, eSIM Go, SimplifyTrip). Go modular monolith + 3 Next.js apps (storefront / admin / affiliate) behind BFF auth, VNPay · SePay · KimNganPay payments, Centrifugo realtime order tracking, MISA e-invoicing.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/PostgreSQL_16-336791?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis_Streams-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/Centrifugo-2C3E50?style=flat-square&logo=websocket&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
      <details>
        <summary align="center"><b>⚙️ Architecture highlights</b></summary>
        <br/>
        <ul>
          <li>Multi-provider eSIM provisioning with per-provider token-bucket rate limits and fail-closed webhook signature/IP verification</li>
          <li>Transactional outbox over Redis Streams → separately scalable worker binary (payment expirers, reconciliation crons, DLQ) with Prometheus metrics</li>
          <li>Shared Argon2 session cookie across 3 Next.js apps, encrypted TOTP 2FA, Google OAuth, admin RBAC with immutable audit logs</li>
          <li>AEAD-encrypted bank data at rest with dual-key rotation; 108 SQL migrations; GitHub Actions push-to-deploy behind Traefik + Cloudflare</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td>
      <h3 align="center">📦 TongKhoEsim — B2B Wholesale eSIM Distribution</h3>
      <p align="center">
        <a href="https://tongkhoesim.com" target="_blank">
          <img src="https://img.shields.io/badge/LIVE-tongkhoesim.com-22c55e?style=for-the-badge&logo=google-chrome&logoColor=white"/>
        </a>
        <img src="https://img.shields.io/badge/Source-Private-6b7280?style=for-the-badge&logo=github"/>
      </p>
      <p align="center">Wholesale eSIM inventory & distribution — stock synced from telecom suppliers into a central warehouse, sold through two-tier reseller dashboards and a partner-facing <b>Open API</b> on a prepaid-wallet model. Rust workspace (~97k LOC) with separate API & worker binaries, 3 Next.js apps, SePay top-ups + MISA VAT invoicing.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
        <img src="https://img.shields.io/badge/Axum-6E56CF?style=flat-square&logo=rust&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/PostgreSQL_16-336791?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis_Streams-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/Centrifugo-2C3E50?style=flat-square&logo=websocket&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_4-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white"/>
      </p>
      <details>
        <summary align="center"><b>⚙️ Architecture highlights</b></summary>
        <br/>
        <ul>
          <li>Money-safe core: multi-tenant prepaid wallets on an append-only double-entry ledger — integer VND only, mandatory <code>Idempotency-Key</code> on all money POSTs</li>
          <li>Partner Open API: per-key rate limits, endpoint scopes, IP whitelists, sandbox mode, webhook fanout with retry backoff + delivery log & replay</li>
          <li>Field-level AES-256-GCM encryption (versioned key rotation) for eSIM activation codes & TOTP secrets; Argon2id + TOTP 2FA; dynamic RBAC down to UI components</li>
          <li>4-crate Rust workspace (<code>unsafe_code</code> forbidden), 89 SQL migrations, 3-environment Docker deploys behind Caddy + Cloudflare, backups to R2</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td>
      <h3 align="center">💳 napplus — Prepaid-Wallet Top-up Platform</h3>
      <p align="center">
        <a href="https://napplus.vn" target="_blank">
          <img src="https://img.shields.io/badge/LIVE-napplus.vn-22c55e?style=for-the-badge&logo=google-chrome&logoColor=white"/>
        </a>
        <img src="https://img.shields.io/badge/Rewrite-NestJS_%E2%86%92_Rust-F74C00?style=for-the-badge&logo=rust&logoColor=white"/>
      </p>
      <p align="center">Dual-brand fintech platform for phone credit, cards, data packages & bill payments backed by a prepaid wallet — VNPAY/SePay payments, VinNet & Viettel IRIS fulfillment. Currently being rewritten <b>strangler-fig</b> from legacy NestJS/MySQL to a 15-crate hexagonal Rust/Axum workspace: a Rust gateway proxies un-migrated routes to the legacy API while 7 bounded contexts move to PostgreSQL + Redis.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
        <img src="https://img.shields.io/badge/Axum-6E56CF?style=flat-square&logo=rust&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS_(legacy)-E0234E?style=flat-square&logo=nestjs"/>
        <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/>
      </p>
      <details>
        <summary align="center"><b>⚙️ Architecture highlights</b></summary>
        <br/>
        <ul>
          <li>Strangler-fig gateway: per-bounded-context production cutover with parallel-run reconciliation instead of a big-bang rewrite</li>
          <li>Append-only double-entry ledger as the source of money truth; <code>clippy float_arithmetic = deny</code> workspace-wide; idempotency keys on every money mutation</li>
          <li>Legacy system reverse-engineered into a 522-test-case spec across 12 flows — each suspected bug gets an explicit keep-or-fix ADR before porting (incl. a P0 IDOR account-takeover fix)</li>
          <li>CI "layer purity" gate enforcing hexagonal architecture (domain must not know infrastructure), cargo-deny, k6 smoke/load suites</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">🛒 Shop Acc Game</h3>
      <p align="center">
        <a href="https://clonegiare.io.vn/" target="_blank">
          <img src="https://img.shields.io/badge/LIVE-View%20Site-22c55e?style=for-the-badge&logo=vercel"/>
        </a>
      </p>
      <p align="center">E-commerce platform for game accounts with PayOS payment, WebSocket realtime, admin dashboard.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs"/>
        <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql"/>
        <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io"/>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🎨 Muciii Bio</h3>
      <p align="center">
        <a href="https://muciii-bio.vercel.app/" target="_blank">
          <img src="https://img.shields.io/badge/LIVE-View%20Site-22c55e?style=for-the-badge&logo=vercel"/>
        </a>
      </p>
      <p align="center">Linktree-style bio page with theme customization, dark mode, smooth animations.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/TailwindCSS-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white"/>
        <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">📥 Video Downloader</h3>
      <p align="center">
        <a href="https://github.com/LDNVN86/SenoDownload-BE" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-View%20Code-181717?style=for-the-badge&logo=github"/>
        </a>
      </p>
      <p align="center">Download videos from YouTube, TikTok, Facebook, Instagram with queue management.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs"/>
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/yt--dlp-FF0000?style=flat-square&logo=youtube"/>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">📚 NekozaneDex</h3>
      <p align="center">
        <a href="https://github.com/LDNVN86/NekozaneDex-BE" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-View%20Code-181717?style=for-the-badge&logo=github"/>
        </a>
      </p>
      <p align="center">Manga/comic reading platform with upload system and chapter management.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=gin&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js"/>
        <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql"/>
      </p>
    </td>
  </tr>
</table>

---

## 🧰 Tech Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### Frameworks & Libraries

![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=go&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-6E56CF?style=for-the-badge&logo=rust&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Databases, Infra & Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-omega-two-17.vercel.app/api?username=LDNVN86&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="165"/>
  <img src="https://github-readme-stats-omega-two-17.vercel.app/api/top-langs/?username=LDNVN86&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=css,scss,html" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats-nine-phi.vercel.app/?user=LDNVN86&theme=tokyonight&hide_border=true" />
</div>

<br/>

<!-- Animated commit activity graph -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=LDNVN86&theme=tokyo-night&hide_border=true&area=true&radius=8" width="96%"/>
</div>

<br/>

<!-- Trophies (self-hosted) -->
<div align="center">
  <img src="https://github-profile-trophy-chi-seven.vercel.app/?username=LDNVN86&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8&margin-h=8" width="96%"/>
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LDNVN86/LDNVN86/output/github-snake.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LDNVN86/LDNVN86/output/github-snake-light.svg">
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/LDNVN86/LDNVN86/output/github-snake.svg" width="100%">
  </picture>
</div>

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://ldn86dev.io.vn">
    <img src="https://img.shields.io/badge/Portfolio-ldn86.dev-6366F1?style=for-the-badge&logo=google-chrome&logoColor=white"/>
  </a>
  <a href="https://discord.com/users/1102459554454847558">
    <img src="https://img.shields.io/badge/Discord-Seno●Impotent-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
  </a>
  <a href="https://github.com/LDNVN86">
    <img src="https://img.shields.io/badge/GitHub-LDNVN86-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<!-- Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>

<p align="center">
  <i>⭐ Thanks for visiting! 👋</i>
</p>
