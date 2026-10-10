<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:000000&height=200&section=header&text=Israa%20Chiheb&fontSize=52&fontColor=00ff41&animation=fadeIn&fontAlignY=38&fontName=Fira-Code&desc=Frontend%20Developer%20%7C%20CTF%20Player%20%7C%20AI%20Automation%20Builder&descAlignY=58&descAlign=50&descSize=15&descColor=00E5FF" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1000&color=00FF41&center=true&vCenter=true&width=620&lines=Build+interfaces.+Break+things+ethically.;Automate+the+rest.;Frontend+%2B+Security+%2B+AI+workflows" alt="Tagline" />

<br/>

<a href="https://portfolio-v2-chi-lilac.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Live-00ff41?style=for-the-badge&logo=vercel&logoColor=white&labelColor=black" /></a>
<img src="https://img.shields.io/github/followers/itsmeisraa?label=Followers&style=for-the-badge&color=00E5FF&labelColor=black" />
<img src="https://img.shields.io/github/stars/itsmeisraa?label=Stars&style=for-the-badge&color=FF0033&labelColor=black" />
<img src="https://komarev.com/ghpvc/?username=itsmeisraa&style=for-the-badge&color=00ff41&label=VIEWS&labelColor=black" />

<br/>
<sub>19 · Guelma / Bejaia, Algeria · Higher School of Computer Science (ESI Bejaia)</sub>
<br/>
<img src="https://img.shields.io/badge/focus-frontend-00ff41?style=flat-square&labelColor=black" />
<img src="https://img.shields.io/badge/learning-backend_+%26_n8n-00E5FF?style=flat-square&labelColor=black" />
<img src="https://img.shields.io/badge/practicing-CTF_%26_Kali-FF0033?style=flat-square&labelColor=black" />

</div>

---

## Contents

- [Profile](#profile)
- [Focus areas](#focus-areas)
- [CTF toolkit](#ctf-toolkit)
- [Tech stack](#tech-stack)
- [How I work](#how-i-work)
- [Selected repositories](#selected-repositories)
- [Activity](#activity)
- [Roadmap](#roadmap)
- [Connect](#connect)

---

## Profile

```bash
$ whoami
israa chiheb — @itsmeisraa
frontend developer + CTF player, learning backend and AI automation
```

I build frontend interfaces and I am working toward full-stack. In parallel I practice cybersecurity through CTFs (web, forensics/OSINT, reverse) and I build AI automations with n8n that connect apps, APIs and LLMs into working workflows.

Beyond code: swimming, gaming, sports photography.

| Now | Learning | Interests |
|---|---|---|
| Frontend interfaces (HTML, CSS, JS, Tailwind, React) | Node.js & Express backend | Web exploitation, reverse, forensics |
| CTF practice (TryHackMe, Hack The Box, PicoCTF) | n8n AI automations, LLM agents, webhooks | Kali Linux labs |
| Portfolio v2 — live | Deeper cybersecurity | Sports photography |

Portfolio: <https://portfolio-v2-chi-lilac.vercel.app/>

---

## Focus areas

### 1. Frontend development — implemented
Building responsive interfaces with HTML, CSS, JavaScript, Tailwind and React (Vite). Evidence: live portfolio plus practice repos such as `my-counter-app` and `ColorPicker`.

### 2. CTF & security — practicing
- Web: SQLi, XSS, IDOR and related fundamentals
- Forensics & OSINT: finding what is hidden
- Reverse engineering: understanding behavior under the hood
- Arenas: TryHackMe, Hack The Box, PicoCTF
- Environment: Kali Linux

> Practice only on legal targets: CTF platforms and local labs.

### 3. AI automation with n8n — building
- Connecting apps, APIs and AI models into working flows
- Wiring LLMs into agents that take real action
- Triggers, webhooks and multi-step flows
- Goal: end-to-end automation with minimal manual steps

---

## CTF toolkit

<details>
<summary><b>Open my usual recon checklist (generic commands, no targets)</b></summary>

```bash
# recon — read-only first, only against your assigned CTF target
nmap -sV -sC -oN nmap_initial.txt <target>
gobuster dir -u http://<target> -w /usr/share/wordlists/dirb/common.txt

# web — inspect in browser + proxy, never attack real sites
# 1. check robots.txt, sitemap.xml, JS bundles for hidden routes
# 2. test IDOR / auth gaps with two low-priv accounts in Burp
# 3. XSS: encode, confirm reflection, check CSP

# forensics — keep hashes before you touch anything
sha256sum evidence.* > hashes.txt
strings image.dd | grep -i "flag\|ctf" | head
exiftool photo.jpg
```

</details>

---

## Tech stack

Organized from the stack you list. Only what you provided plus what your public repos confirm (HTML, JavaScript, React/Vite).

| Category | Technologies |
|---|---|
| Frontend | JavaScript, HTML, CSS, Tailwind, React, Vite |
| Backend & data (learning) | Node.js, Express, MongoDB, Supabase |
| Languages & foundations | C, Java |
| Security & systems | Kali Linux, Linux, Ubuntu |
| Tools | Git, GitHub, npm, Postman, PowerShell, Obsidian, Arduino |

<div align="center">

[![Skills](https://skillicons.dev/icons?i=js,html,css,tailwind,react,vite,nodejs,express,mongodb,supabase,npm,postman,c,java,git,github,linux,ubuntu,kali,powershell,obsidian,arduino&perline=7)](https://skillicons.dev)

</div>

---

## How I work

Current learning architecture — not a production claim, just how the pieces fit:

```mermaid
flowchart LR
    U[User] --> F[Frontend: React + Tailwind + Vite]
    F --> B[Backend learning: Node + Express]
    B --> D[(Data: MongoDB / Supabase)]
    B --> N[n8n Workflow]
    N --> L{LLM Agent}
    L -->|API / Webhook| A[Apps + Services]
    A --> R[Automated Result]
    style L fill:#00E5FF,stroke:#00ff41,stroke-width:2px,color:#000
    style N fill:#000,stroke:#00ff41,stroke-width:2px,color:#00ff41
    style R fill:#00ff41,stroke:#000,stroke-width:2px,color:#000
```

Repository map (verified popular repos on your profile):

| Repository | What it is | Link |
|---|---|---|
| `portfolio` | First portfolio (HTML) | <https://github.com/itsmeisraa/portfolio> |
| `pray-time` | Pray time app (JavaScript) | <https://github.com/itsmeisraa/pray-time> |
| `Via_Health` | Economy project app (JavaScript) | <https://github.com/itsmeisraa/Via_Health> |
| `my-counter-app` | React + Vite counter practice | <https://github.com/itsmeisraa/my-counter-app> |
| `ColorPicker` | Simple color picker (JavaScript) | <https://github.com/itsmeisraa/ColorPicker> |

Quick start for visitors:

```bash
# explore the code
git clone https://github.com/itsmeisraa/portfolio.git
cd portfolio
# then follow that repo's own README for install/run steps
```

> Each repo has its own setup. I do not document a single install here because stacks differ per repo.

---

## Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=itsmeisraa&theme=github-dark&bg_color=000000&color=00ff41&line=00E5FF&point=FF0033&area=true&hide_border=true" width="100%" alt="Contribution activity graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=itsmeisraa&theme=darkhub&no-frame=true&row=1&column=6" alt="GitHub trophies" />

<br/>

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=itsmeisraa&show_icons=true&theme=dark&border_radius=10&hide_border=true&title_color=00ff41&icon_color=00E5FF&text_color=ffffff&bg_color=000000" height="180" alt="GitHub stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=itsmeisraa&theme=dark&border_radius=10&hide_border=true&ring=00ff41&fire=FF0033&currStreakLabel=00E5FF&background=000000" height="180" alt="GitHub streak" />

<br/>

<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=itsmeisraa&layout=compact&theme=dark&border_radius=10&hide_border=true&title_color=00ff41&text_color=ffffff&bg_color=000000" height="170" alt="Top languages" />

<br/>
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Dev quote" width="60%" />

</div>

<!-- Snake animation requires a workflow that publishes to the `output` branch.
     If the image 404s, add .github/workflows/snake.yml with Platane/snk, or remove this line. -->
<div align="center">
<img src="https://raw.githubusercontent.com/itsmeisraa/itsmeisraa/output/snake.svg" alt="Contribution snake" />
</div>

---

## Roadmap

Based on current state. Checked boxes have public evidence, the rest are in progress or planned.

- [x] Frontend fundamentals and live portfolio v2
- [x] Public practice repos (21 repos, 60 stars at time of writing)
- [x] CTF fundamentals on TryHackMe / Hack The Box / PicoCTF
- [ ] Node.js & Express backend proficiency
- [ ] n8n + LLM agent flows in production-like demos
- [ ] Deeper cybersecurity (web exploitation and forensics focus)
- [ ] Full-stack projects with documented READMEs, tests and deploys
- [ ] Consistent open-source contributions

---

## Connect

```bash
$ ssh connect@israa
# encrypted channel established — pick one:
```

<div align="center">

<a href="https://portfolio-v2-chi-lilac.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=00ff41" /></a>
<a href="https://github.com/itsmeisraa"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=00ff41" /></a>
<a href="https://www.linkedin.com/in/israa-chiheb-aaa3b837a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:israaisraa202000@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://discordapp.com/users/748619400034385991"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00FF41&center=true&vCenter=true&width=480&lines=First%2C+solve+the+problem.;Then%2C+write+the+code." alt="First, solve the problem. Then, write the code." />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:000000&height=120&section=footer" width="100%" />

<sub>Maintained by <a href="https://github.com/itsmeisraa">@itsmeisraa</a> · Solo maintainer · No license file specified in profile repo</sub>

</div>
