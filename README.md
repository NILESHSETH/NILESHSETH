<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   > SYSTEM BOOT...                                          │
│   > LOADING PROFILE: NILESHSETH                             │
│   > STATUS: ONLINE ██████████ 100%                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=500&size=20&duration=3000&pause=500&color=00FF41&center=true&width=650&lines=hey+!+I'm+Nilesh+%2C+Welcome+to+my+corner+%3E_;3rd+Year+%7C+BIT+Mesra+%7C+CSE+(2024%E2%80%932028);Backend+Dev+%40+Allswift+Solutions+(NestJS%2C+MongoDB);GSSoC+2026+Contributor+%7C+SDS+BIT+Mesra;building+cool+stuff+%2C+one+commit+at+a+time" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=NILESHSETH&color=00ff41&label=Profile+Visits&style=flat-square" alt="Profile Visits" width="160"/>

</div>

---

<div align="center">

## 🐍 contribution_snake.exe

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NILESHSETH/NILESHSETH/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NILESHSETH/NILESHSETH/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/NILESHSETH/NILESHSETH/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>



</div>

---

<div align="center">

## 📊 github_stats.exe

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NILESHSETH&theme=chartreuse-dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact&cache_seconds=1800" height="165" alt="Top Languages" />
&nbsp;&nbsp;
<img src="https://streak-stats.demolab.com/?user=NILESHSETH&theme=chartreuse-dark&hide_border=true&cache_seconds=1800" height="165" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=NILESHSETH&theme=chartreuse-dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&cache_seconds=1800" height="165" alt="GitHub Stats" />

<br/>

## 🏆 trophy_case.exe

<img src="https://github-profile-trophy.vercel.app/?username=NILESHSETH&theme=algolia&no-frame=true&no-bg=true&row=1&column=6" alt="Trophies" />

<br/>

![LeetCode Stats](https://leetcard.jacoblin.cool/NILESHSETH1?theme=dark&font=Share%20Tech%20Mono&ext=heatmap)

</div>

> **Real talk on Top Languages / GitHub Stats / Trophies:** those 3 are dead right now because `github-readme-stats.vercel.app` and `github-profile-trophy.vercel.app` are shared free instances that literally millions of profiles hit — they rate-limit constantly. Streak and LeetCode render fine because they're hosted elsewhere. No query param fixes this reliably; the only permanent fix is forking + self-hosting your own instance ([github-readme-stats deploy guide](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance)). The snake above is the actually-dependable dynamic piece — it runs off your own repo, not a shared server, so it won't randomly die on visitors.

<details>
<summary><b>🔧 One-time setup: get the snake working (~5 min, do this once)</b></summary>

<br/>

**1.** Confirm you have a public repo named exactly `NILESHSETH` (same as your username) — GitHub's special "profile README" repo. Create it if it doesn't exist.

**2.** Inside it, create `.github/workflows/snake.yml`:

```yaml
name: generate animated snake

on:
  schedule:
    - cron: "0 0 * * *"   # regenerates daily at midnight UTC
  workflow_dispatch:      # lets you trigger it manually from the Actions tab
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - name: generate snake svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**3.** Commit to `main`. Open the **Actions** tab — "generate animated snake" should be running. Takes 30-60 sec.

**4.** It auto-creates an `output` branch holding the SVGs. The `<picture>` block above already points there, so once the run finishes, refresh your profile page and the snake is live — dark or light version depending on the viewer's GitHub theme.

**5.** The cron line reruns it daily on its own — you don't touch it again.

If the run fails with a permissions error: **Settings → Actions → General → Workflow permissions** → set to "Read and write permissions."

</details>

---

<details>
<summary align="center"><b>> ✨ CLICK ME — WHO AM I? ✨</b></summary>

<br/>

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║  nilesh@bitmesra:~$ cat about_me.txt                     ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Name       :  Nilesh Kumar Seth                         ║
║  From       :  Ranchi, Jharkhand, India                   ║
║  Education  :  B.Tech CSE @ BIT Mesra (2024-2028)        ║
║                3rd Year  |  CGPA: 8.02                   ║
║                                                          ║
║  Currently  :  Placement Grind Mode 🔥                    ║
║                Ex Backend Dev Intern @ Allswift Solutions ║
║                GSSoC 2026 Contributor                    ║
║                Core Member @ Society for Data Science    ║
║                Photography Club (PSOC)                   ║
║                                                          ║
║  Interests  :  Backend Dev  ·  DSA  ·  System Design      ║
║                Stock Markets  ·  Anime  ·  Reading        ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

</div>

---

<div align="center">

## > ls skills/

*// languages*

<img src="https://skillicons.dev/icons?i=cpp,c,javascript,typescript,python,html,css&theme=dark" />

<br/><br/>

*// frontend & backend*

<img src="https://skillicons.dev/icons?i=react,redux,tailwind,nextjs,nodejs,express,nestjs&theme=dark" />

<br/><br/>

*// databases & tools*

<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,docker,git,github,postman,vercel,aws,linux&theme=dark" />

<br/><br/>

*// ai / ml*

```
[ XGBoost ]  [ Random Forest ]  [ NLP ]  [ Gemini API ]  [ OpenAI API ]
[ AWS SageMaker ]  [ AWS Bedrock ]  [ scikit-learn ]
```

</div>

---

<div align="center">

## > cat projects.log

</div>

<br/>

| Project | Stack | What it does |
|:--------|:------|:-------------|
| 📈 **Nelix AI** | Next.js · MongoDB Atlas · Inngest · shadcn/ui | Real-time stock market app with background job pipelines |
| 🤖 **Nexora** | React · Vite · NestJS · MongoDB · Gemini AI | AI-powered interview management system with native schema-based evaluation |
| ⚙️ **BullMQ Job System** | Next.js · Redis · BullMQ | Production-grade background job queue architecture |
| ☕ **NestJS Mail Module** | NestJS · BullMQ · Handlebars | Queued transactional email system with templating |
| 💼 **Portfolio 3D** | React Three Fiber · GSAP · Tailwind v4 | Interactive 3D developer portfolio deployed on Vercel |
| 📝 **Megablog** | React · Appwrite · Redux Toolkit | Full-stack blogging platform with auth and CRUD |

---

<div align="center">

## > cat experience.log

```
[JUN 2026 → AUG 2026]  Backend Developer Intern   @ Allswift Solutions (ASPL India)
                        NestJS · MongoDB · RESTful APIs

[MAY 2026 → NOW]       Open Source Contributor     @ GSSoC 2026
                        AI Agents & Open Source tracks · PRs & issues

[FEB 2026 → NOW]       Core Member                  @ Society for Data Science, BIT Mesra
                        Co-organized 150+ participant hackathon · workshops

[NOW]                  Member                       @ Photography Club (PSOC), BIT Mesra
[NOW]                  Management Role              @ Aveon Associate
```

</div>

---

<div align="center">

## > cat cp_stats.log

```
╔══════════════════════════════════════════════════════════╗
║  COMPETITIVE PROGRAMMING                                 ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  LeetCode   →  Max Rating 1689  |  Top 15% globally      ║
║                Handle: NILESHSETH1                       ║
║                                                          ║
║  Codeforces →  Rating 1144                               ║
║                Handle: NILESHSETH                        ║
║                                                          ║
║  CodeChef   →  Rating 1451  (2★)                         ║
║                Handle: binary_sage                       ║
║                                                          ║
║  Total: 800+ problems solved across all platforms        ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

</div>

---

<div align="center">

## > ./currently_grinding.sh

```javascript
const nilesh = {
  status      : "Full placement grind mode",
  applied_to  : ["Google (referral)", "Microsoft", "GE HealthCare", "Cisco"],
  dsa_sheet   : "285 curated questions · C++ · subsequence DP patterns",
  building    : ["Minor Project (w/ Dr. Debjani Mustafi)", "Nelix AI"],
  routine     : ["Gym", "College", "DSA", "OA Prep"],
  reading     : ["Carnegie", "Cialdini", "Greene", "Voss"],
  investing   : ["Stock Markets", "Mutual Funds"],
  goal        : "Crack SWE placements @ top product company"
};
```

</div>

---

<div align="center">

## > ./connect.sh

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%2300FF41.svg?style=flat-square&logo=linkedin&logoColor=black)](https://linkedin.com/in/nileshkumarseth)
[![GitHub](https://img.shields.io/badge/GitHub-%2300FF41.svg?style=flat-square&logo=github&logoColor=black)](https://github.com/NILESHSETH)
[![LeetCode](https://img.shields.io/badge/LeetCode-%2300FF41.svg?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/NILESHSETH1)
[![Codeforces](https://img.shields.io/badge/Codeforces-%2300FF41.svg?style=flat-square&logo=codeforces&logoColor=black)](https://codeforces.com/profile/NILESHSETH)
[![Portfolio](https://img.shields.io/badge/Portfolio-%2300FF41.svg?style=flat-square&logo=vercel&logoColor=black)](https://nilesh-seth-portfolio-1-three-topaz.vercel.app)

<br/>

📬 &nbsp; sethji.nileshkumar@gmail.com

</div>

---

<div align="center">

```
> session terminated
> thanks for visiting _
```

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=500&duration=3000&pause=500&color=00FF41&center=true&width=435&lines=Thanks+for+visiting+!+%3E_" alt="Thank you!" />

</div>
