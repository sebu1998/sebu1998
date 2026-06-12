<!--
  ────────────────────────────────────────────────────────────
  GitHub-Profile-README für sebu1998 — LIVE / kanonisch
  ────────────────────────────────────────────────────────────
  Stand 2026-06-11. Zweck: Snapshot „das bin ich gerade" —
  Projekte, Stack, Erfahrung. Bewusst NICHT auf Bewerbung getrimmt,
  einfach schicker als der alte Stand.
  Sprache: Englisch (rendert auf GitHub, Dev-Standard).

  → Diese Datei ersetzt github-profile-readme-DRAFT.md (V8) und
    github-profile-readme-FINAL.md. Beide sind veraltet/widersprüchlich
    und können archiviert werden.

  Geändert ggü. V8 (Scope: „nur schicker, nicht bewerben"):
  - GitHub-Stats-Cards auskommentiert (zeigen ohne eigenen PAT-Deploy
    nur öffentliche Repos → würden leer wirken). Unten als Block parkiert,
    wieder reinnehmen sobald Showcase-Repos / PAT-Deploy stehen.
  - "Website (under construction)"-Badge raus (toter Link wirkt unfertig).
    Reinnehmen, sobald sebastianbuehrmann.de live ist.
  - Harten Job-CTA ("Open to full-time roles 2027") entfernt — passt erst
    zur Bewerbungs-Welle. Kontakt = nur E-Mail.
  - LinkedIn-Button bleibt geparkt, bis das Profil sauber ist.

  Veröffentlichen:
    1. https://github.com/sebu1998/sebu1998 → README.md → Edit
    2. Alles ab <div align="center"> ersetzen
    3. Commit: "chore: profile readme refresh"
  ────────────────────────────────────────────────────────────
-->

<div align="center">

# Hi, I'm Sebastian 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3500&pause=1000&center=true&vCenter=true&width=560&height=40&color=58A6FF&lines=Software+Developer+%C2%B7+Laravel+%C2%B7+Swift+%C2%B7+.NET;From+construction+sites+to+code;If+it+doesn%27t+hold+up%2C+it+isn%27t+done." alt="Typing animation: Software Developer · From construction sites to code · If it doesn't hold up, it isn't done." />

I build my own apps and run them in production.
Currently completing the German IHK degree in software development — *Fachinformatiker Anwendungsentwicklung, 2027*.

</div>

---

### 🛤 How I got here

Trained as a car mechatronics technician, then four years in underground construction — started as a laborer, ended up leading a crew in cable and pipeline network construction. Since 2025 I'm retraining as a software developer and working as a developer at a construction company in parallel.

The standard I keep from those years: software that people rely on at work has to keep working. No tools for the sake of tools.

---

<div align="center">

### 🛠 Stack

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=php,laravel,swift,cs,dotnet,graphql,vue,ts,tailwind,vite,nextjs,py,postgres,mysql,sqlite,docker,bash,git,github,supabase&perline=10" alt="PHP, Laravel, Swift, C#, .NET, GraphQL, Vue, TypeScript, Tailwind, Vite, Next.js, Python, PostgreSQL, MySQL, SQLite, Docker, Bash, Git, GitHub, Supabase" />
</a>

</div>

```text
Backend        PHP 8.4 · Laravel 12 · C# / .NET 10 · Hot Chocolate (GraphQL) · EF Core
Apple          Swift 5.9 · SwiftUI · SwiftData · CoreData · CloudKit
Frontend       Vue 3 · TypeScript · Tailwind CSS · Vite · Next.js · Blade
Databases      PostgreSQL · MS SQL Server · MySQL · SQLite
Ops            Git / GitHub · GitHub Actions · Docker / Compose · FrankenPHP / Caddy · Bash · VMs · VPN / Tunnel
Platforms      macOS · Windows · Linux · Terminal-first (zsh · cmd · PowerShell)
Security       HTTPS · Firewall (UFW) · Auth & Permissions · Backups · Secrets handling — applied to my own deployed web apps
Automation     Python 3.12 · PyMuPDF · Presidio · pytest
AI             Claude (API + Cowork) · agent patterns · decisions documented as ADRs
```

---

### 🤖 How I work with AI

I use Claude (API + Cowork) for code reviews, architecture sparring and routine refactorings. The decisions stay mine and get documented.

My Second Brain links every project to a markdown issue tracker (ideas / roadmap / bugs / decisions), so each AI session starts with full project context instead of a blank slate.

---

### 🚀 Projects

> All repos are currently private (own products and client work). Code walkthrough on request — every project has documented ADRs.

**🕐 Stundenheld** *(Laravel 12 · PostgreSQL · Docker · FrankenPHP)*
Time tracking I use every day: punch clock, workspaces, projects, statistics, calendar, invoicing. Docker stack with setup wizard, Caddy HTTPS and backup script.

**🔧 Workshop Manager** *(Next.js · Supabase — client project)*
PWA for a logistics company's truck workshop. Drivers report issues, dispatch assigns, mechanics work the queue. Role-based views, inspection deadlines, vehicle history.

**🔒 PII Redactor** *(Python · PyMuPDF · Presidio — in progress)*
CLI that strips personal data (names, companies, IBANs, internal IDs) from documents before they go into cloud AI tools. The reverse mapping stays local.

**💰 klar.** *(Swift · SwiftUI · SwiftData · CloudKit)*
iOS finance app: accounts, line-item receipts, OCR receipt scanning, CSV import from German banks, subscription tracking. Local-first with CloudKit sync.

**📱 Habit Tracker** *(Swift 5.9 · SwiftUI · CoreData)*
iOS app for daily routines: streaks, heatmap, local notifications, weekly review.

**🧠 Second Brain** *(Markdown · PARA)*
Knowledge system that doubles as the issue tracker for all projects above.

---

### 📚 How I work

- Architecture decisions become ADRs — every project keeps a learning journal: what, why, which alternative was rejected.
- I run what I build: production deployments on VMs and small servers, HTTPS via Caddy, firewall setup, VPN/tunnel access, scheduled backups — for my own apps and a client project.
- Self-hosted first: Docker Compose, ENV config, INSTALL.md, backup scripts. No vendor lock-in.
- Pragmatic over dogmatic: tests where their absence would hurt, patterns only where they carry weight.

---

<div align="center">

### 📫 Contact

<a href="mailto:sebastianbuehrmann@icloud.com"><img src="https://img.shields.io/badge/Email-3693F3?style=for-the-badge&logo=icloud&logoColor=white" alt="Email" /></a>

*Currently on my desk: final IHK exam prep (Nov 2026) · GraphQL service in .NET 10 · PII Redactor CLI.*

</div>

<!--
  ════════════════════════════════════════════════════════════
  PARKPLATZ — später wieder aktivieren (jeweils Kommentar entfernen)
  ════════════════════════════════════════════════════════════

  GITHUB-STATS-CARDS — erst wenn öffentliche Repos / PAT-Deploy da sind,
  sonst wirken sie leer. count_private greift nur auf deinem eigenen Deploy.
  Quelle: https://github.com/anuraghazra/github-readme-stats

<div align="center">

### 📊 GitHub stats

<img src="https://github-readme-stats.vercel.app/api?username=sebu1998&show_icons=true&hide_border=true&count_private=true&theme=transparent" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sebu1998&layout=compact&hide_border=true&count_private=true&exclude_repo=CsharpLernmappe&theme=transparent" height="165" alt="Top Languages" />

</div>

  WEBSITE-BADGE — reinnehmen, sobald sebastianbuehrmann.de live ist:
<a href="https://sebastianbuehrmann.de"><img src="https://img.shields.io/badge/Website-2D333B?style=for-the-badge&logo=safari&logoColor=white" alt="Website" /></a>

  LINKEDIN-BUTTON — reinnehmen, sobald das Profil sauber ist:
<a href="https://www.linkedin.com/in/sebastian-b%C3%BChrmann-78076a353/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn" /></a>

  JOB-CTA — reinnehmen für die Bewerbungs-Welle:
🤝 Open to: **full-time software developer roles starting 2027** · smaller freelance projects on the side
  ════════════════════════════════════════════════════════════
-->
