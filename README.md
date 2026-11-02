<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2800&pause=900&color=5BCDEC&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Danish;Full-stack+developer+from+Pakistan;Healthcare+products+%C2%B7+trading+systems;I+build+things+people+actually+use" alt="Typing intro" />

**M Danish** · `Rajadanish53`

I design and ship product software: clinical portals and admin tools, trading platforms and MetaTrader automation, and the web apps linked below. Click any section to open it.

<p>
  <a href="mailto:bestbarb43@gmail.com"><img src="https://img.shields.io/badge/Email-bestbarb43%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=161B22" alt="Email" /></a>
  <a href="https://github.com/Rajadanish53"><img src="https://img.shields.io/badge/GitHub-Rajadanish53-0D1117?style=for-the-badge&logo=github&logoColor=white&labelColor=161B22" alt="GitHub" /></a>
  <a href="https://www.youtube.com/channel/UCKezJVkNYff2Dmxy6aUNvFw"><img src="https://img.shields.io/badge/YouTube-Danish-0D1117?style=for-the-badge&logo=youtube&logoColor=FF0000&labelColor=161B22" alt="YouTube" /></a>
</p>

<img src="https://komarev.com/ghpvc/?username=Rajadanish53&style=flat-square&color=5BCDEC&label=PROFILE+VIEWS" alt="Profile views" />
&nbsp;
<img src="https://img.shields.io/github/followers/Rajadanish53?label=Followers&style=flat-square&color=5BCDEC&labelColor=161B22" alt="Followers" />

</div>

---

## About

<details open>
<summary><b>Who I am</b></summary>
<br />

- Based in **Pakistan**. GitHub since 2020. The profile bio still says “Soon PuroGrammer” — the work below is the update.
- Day to day I build **production healthcare software**: patient and client portals, admin and developer consoles, intake, claims, explanation of benefits, insurance payment posting, email templates, and a shared design system.
- Front ends are **component-based React and Next.js**. APIs follow a consistent contract, written in **camelCase**, and reused from a shared components layer instead of one-off screens.
- Alongside that I build **trading systems**: a full trading workspace, charting platforms, journals, Discord and Telegram alerts, and a large set of **MetaTrader 5** expert advisors and indicators.
- Final-year project (**CS619**): **TraceFake**, an image-authenticity pipeline that reads EXIF metadata and preprocesses real vs. synthetic images.
- I still play games, and I still learn the next tool by shipping something with it.

</details>

<details>
<summary><b>How I like to work</b></summary>
<br />

- Reusable components live in a `components` folder. Screens compose them. They do not reinvent them.
- New APIs match the architecture already in the codebase: same naming, same response shape, same client pattern.
- TypeScript, Tailwind, and a design system when the product is large enough to need one. Monorepos (pnpm + Turborepo) when several apps share UI.
- Real-time where it matters: Socket.io for chat, order flow, and live alerts. Background workers for anything that should not block a request.

</details>

---

## Projects

<details open>
<summary><b>Healthcare products</b> — portals, intake, claims, design system</summary>
<br />

Product work across an EHR platform and related clinical apps. These stay private; this is the shape of the work.

| Area | What I build |
| --- | --- |
| Patient & client portals | Scheduling, records, and account flows used by patients and clinic staff |
| Admin consoles | Practice, client, and internal admin panels, plus a developer portal and API docs |
| Intake | Multi-step intake (TruIntake) that feeds the clinical record |
| Revenue cycle | Claims, explanation-of-benefits files, and insurance payment posting |
| Design system | Shared TruCare UI, email templates, and a React component library consumed by several front ends |
| Mobile | Companion EHR and patient apps |
| Platform UI | Large clinical React monorepos (Turborepo, pnpm, shared packages) including product UI for PsychPlus |

Stack on this side: **React, Next.js, TypeScript, Tailwind, Node, component libraries, Docker.**

</details>

<details open>
<summary><b>Trading systems</b> — platforms, journals, MetaTrader, alerts</summary>
<br />

| Project | What it is |
| --- | --- |
| TradingOS | Dark, Discord-style trading workspace: communities, realtime chat, journals, charts, learning, and AI assistants. **Next.js, React, TypeScript, Tailwind, Prisma, PostgreSQL, Socket.io.** |
| Trading platform | Live charting product with accounts, workers, and MetaTrader expert-advisor sync (**PipsGuard**). **Next.js, MongoDB, Socket.io, Tailwind.** |
| Trading journal | A TradeZella-style journal for reviewing trades, tags, and performance. |
| MetaTrader 5 | Expert advisors and indicators in **MQL5** and Pine: scalping, order blocks, fair-value gaps, range breakout, gold opening-range, smart-money concepts, support and resistance, EMA / RSI, and a trade copier. |
| [AlphaBot](https://github.com/Rajadanish53/discord_bot) | Personal **Discord** bot. Watches Solana wallets and posts buy, sell, liquidity, transfer, and bridge alerts. **Python**, slash commands, SQLite. [Live app](https://discord-bot-theta-gilt.vercel.app). |
| Market alerts | Telegram market pulse and memecoin monitoring, plus Binance automation for scalping and unusual-move detection. |

</details>

<details>
<summary><b>TraceFake</b> — final-year project, CS619</summary>
<br />

Image-authenticity project. The pipeline extracts **EXIF** metadata and preprocesses a real-vs-synthetic image set so a model can tell camera photos from generated ones.

- Course: **CS619**, Spring 2026
- Pieces: metadata extraction, dataset preprocessing (real / fake splits), final report and viva
- Language: **Python**

</details>

<details>
<summary><b>Public repos</b> — click a group</summary>
<br />

**Social & product clones**

| Repo | Stack | Note |
| --- | --- | --- |
| [ProfileNest](https://github.com/Rajadanish53/ProfileNest) | MERN | Social profiles. Early hosted build. |
| [React-SQL-Social-Media](https://github.com/Rajadanish53/React-SQL-Social-Media) | React, SQL | Social app for people nearby |
| [Linkedin-clone](https://github.com/Rajadanish53/Linkedin-clone) | React, Redux, Firebase | Feed-style UI clone |
| [mtech-task-2023](https://github.com/Rajadanish53/mtech-task-2023) | JavaScript | Chat with image sharing |
| [Pizza-Delivery-RealTime](https://github.com/Rajadanish53/Pizza-Delivery-RealTime) | Express, Socket.io | Live pizza-order tracking |
| [Hulu-2.0-Nextjs](https://github.com/Rajadanish53/Hulu-2.0-Nextjs) | Next.js, TMDB | Movie browser. [Demo](https://hulu-2-0-nextjs-mu.vercel.app) |

**Files, tools & experiments**

| Repo | Stack | Note |
| --- | --- | --- |
| [ShareNow-filesharing](https://github.com/Rajadanish53/ShareNow-filesharing) + [server](https://github.com/Rajadanish53/ShareNow-server) | JavaScript | File sharing, client and server |
| [Random-Password-Generator](https://github.com/Rajadanish53/Random-Password-Generator) | JavaScript | Password generator |
| [whoisapiparse](https://github.com/Rajadanish53/whoisapiparse) | TypeScript, React | WHOIS response parser |
| [next-js-allconnections](https://github.com/Rajadanish53/next-js-allconnections) | Next.js | Connection patterns in one app |
| [mynpx-card](https://github.com/Rajadanish53/mynpx-card) | Node | NPX calling card |
| [portfolio-mdanish](https://github.com/Rajadanish53/portfolio-mdanish) | HTML | Portfolio with custom themes |
| [rajadanish53.github.io](https://github.com/Rajadanish53/rajadanish53.github.io) | HTML | GitHub Pages site |

**Mobile**

| Repo | Stack | Note |
| --- | --- | --- |
| [Pindi-Tour](https://github.com/Rajadanish53/Pindi-Tour) | Java, XML, Firebase | Android city-tour app |
| [Simple-Catalog-App-Flutter-](https://github.com/Rajadanish53/Simple-Catalog-App-Flutter-) | Dart, Flutter | Catalog practice app |
| [OLX-ui-clone](https://github.com/Rajadanish53/OLX-ui-clone) | Dart, Flutter | Classifieds UI clone |

**First React apps**

| Repo | Note |
| --- | --- |
| [Simple-Todos-App](https://github.com/Rajadanish53/Simple-Todos-App) | First finished React app |
| [Mdfoods](https://github.com/Rajadanish53/Mdfoods) | Food UI, second React app |
| [HikingProject](https://github.com/Rajadanish53/HikingProject) | Static hiking site |
| [FareedPortfolio](https://github.com/Rajadanish53/FareedPortfolio) | Portfolio page for someone else |
| [discord_bot](https://github.com/Rajadanish53/discord_bot) | Python Discord bot, deployed on Vercel |

</details>

---

## Stack

<details open>
<summary><b>Languages and tools</b></summary>
<br />

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/MQL5-1B4F72?style=for-the-badge&logo=metatrader5&logoColor=white" alt="MQL5" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
</p>

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

</details>

---

## GitHub

<details open>
<summary><b>Stats — open for the graphs</b></summary>
<br />

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Rajadanish53&theme=github_dark" alt="Profile details" />

<br />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Rajadanish53&theme=github_dark" alt="GitHub stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Rajadanish53&theme=github_dark" alt="Top languages" />

<br /><br />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Rajadanish53&theme=github_dark" alt="Most used language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Rajadanish53&theme=github_dark&utcOffset=5" alt="Productive time" />

</div>

These cards count public GitHub activity only. They do not include the private healthcare and trading work.

</details>

---

## Connect

<details open>
<summary><b>Say hello</b></summary>
<br />

<p>
  <a href="mailto:bestbarb43@gmail.com"><img src="https://img.icons8.com/color/48/gmail-new.png" width="40" alt="Email" /></a>
  &nbsp;
  <a href="https://www.facebook.com/muhammed.danish.334"><img src="https://img.icons8.com/fluency/48/facebook-new.png" width="40" alt="Facebook" /></a>
  &nbsp;
  <a href="https://www.instagram.com/m_dani_sh_/"><img src="https://img.icons8.com/fluency/48/instagram-new.png" width="40" alt="Instagram" /></a>
  &nbsp;
  <a href="https://www.youtube.com/channel/UCKezJVkNYff2Dmxy6aUNvFw"><img src="https://img.icons8.com/color/48/youtube-play.png" width="40" alt="YouTube" /></a>
  &nbsp;
  <a href="https://github.com/Rajadanish53"><img src="https://img.icons8.com/fluency/48/github.png" width="40" alt="GitHub" /></a>
</p>

Open to collaboration on product work, trading tools, and open source.

</details>

<div align="center">

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0E4D5C,100:5BCDEC&height=120&section=footer" alt="" />

</div>
