<!-- ============================================================ -->
<!--  Header                                                       -->
<!-- ============================================================ -->
<p align="center">
  <img width="100%" alt="Yan Ribeiro Nunes — Software Developer"
       src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1E3A8A,100:0EA5E9&text=Yan%20Ribeiro%20Nunes&fontColor=FFFFFF&fontSize=50&fontAlignY=36&desc=Software%20Developer%20%E2%80%A2%20Computer%20Science%20%40%20CESAR%20School&descSize=18&descAlignY=56&animation=fadeIn" />
</p>

<p align="center">
  <img alt="Systems programming · Back-end · Concurrency"
       src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3500&pause=900&color=38BDF8&center=true&vCenter=true&width=640&lines=Systems+programming+in+C+%E2%80%94+processes%2C+threads%2C+scheduling;Back-end+development+with+Java%2C+Python+%26+MySQL;Clean%2C+tested%2C+well-documented+software" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yan-ribeiro-nunes" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/yan791" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.instagram.com/_yan.nunes" target="_blank"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>

<br />

## About

Computer Science student at **CESAR School** (Recife, Brazil), focused on **systems programming** and **back-end development**. I like working close to the operating system — processes, threads, scheduling and concurrency — and turning well-defined requirements into software that is reliable, readable and properly documented. Most of what I build is delivered in teams, against strict specifications and real deadlines.

```c
typedef struct {
    const char *name, *role, *education, *based_in;
    const char *focus[3], *currently_learning[3];
} Developer;

static const Developer yan = {
    .name               = "Yan Ribeiro Nunes",
    .role               = "Software Developer",
    .education          = "B.Sc. Computer Science @ CESAR School (in progress)",
    .based_in           = "Recife, Brazil",
    .focus              = { "Systems Programming", "Back-end", "Concurrency" },
    .currently_learning = { "Computer Networks", "Operating Systems", "Databases" },
};
```

## Featured Projects

| Project | Overview |
| :-- | :-- |
| **[Frevo Runner](https://github.com/yan791/Frevo_Runner)**<br /><sub>C · Raylib · Make</sub> | Endless-runner game inspired by Olinda's Carnival. Obstacles are managed through a dynamic linked list, scores persist in a sorted ranking, and sound effects are generated in pure C at build time. Built by a team of three. |
| **[Flight-Critical Task Scheduler](https://github.com/yan791/Escalonamento_de_tarefas_criticas_de_voo)**<br /><sub>C11 · Real-time scheduling</sub> | Preemptive scheduling simulator for periodic avionics tasks, comparing **Rate-Monotonic** and **Earliest-Deadline-First**. Strict input validation, controlled failure paths, and a warning-free build under `-Wall -Wextra -Wpedantic`. |
| **[ProcessFlow](https://github.com/yan791/ProcessFlow)**<br /><sub>C · POSIX · Linux</sub> | Process orchestrator with interactive and workflow modes: sequential, parallel and piped execution, I/O redirection, background jobs and `SIGCHLD` handling — built on `fork`, `execvp`, `dup2` and `pipe`, with no `system()` or `popen()`. |

<details>
<summary><b>More work</b> — team products and systems coursework</summary>
<br />

- **KeyFlow** — collaborative password-vault SaaS for Brazilian small and medium businesses, built as a team product with sprint-based delivery.
- **Parallel Mandelbrot Renderer** — serial, Pthreads and OpenMP implementations with timing logs for performance comparison.
- **PintOS Alarm Clock** — reimplementation of `timer_sleep()` in the PintOS kernel, eliminating busy waiting.
- **Property & Car-Rental Management Systems** — Java back-ends following MVC + DAO over JDBC, backed by MySQL.

</details>

## Tech Stack

| Area | Technologies |
| :-- | :-- |
| **Languages** | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) |
| **Systems & Concurrency** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![POSIX](https://img.shields.io/badge/POSIX-334155?style=flat-square) ![Pthreads](https://img.shields.io/badge/Pthreads-334155?style=flat-square) ![OpenMP](https://img.shields.io/badge/OpenMP-334155?style=flat-square) |
| **Back-end & Frameworks** | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![JDBC](https://img.shields.io/badge/JDBC-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Raylib](https://img.shields.io/badge/Raylib-1E1E1E?style=flat-square&logo=raylib&logoColor=white) |
| **Databases** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Testing** | ![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white) |
| **Tooling** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![GNU Make](https://img.shields.io/badge/GNU%20Make-A42E2B?style=flat-square&logo=gnu&logoColor=white) ![GCC](https://img.shields.io/badge/GCC-A42E2B?style=flat-square&logo=gnu&logoColor=white) |

## GitHub Analytics

<p align="center">
  <img height="165" alt="GitHub stats"
       src="https://github-readme-stats.vercel.app/api?username=yan791&show_icons=true&hide_rank=true&hide=stars&include_all_commits=true&hide_border=true&border_radius=8&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9" />
  <img height="165" alt="Most used languages"
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=yan791&layout=compact&langs_count=8&hide=perl,makefile&hide_border=true&border_radius=8&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9" />
</p>

<p align="center">
  <img alt="Contribution streak"
       src="https://streak-stats.demolab.com?user=yan791&hide_border=true&border_radius=8&background=0D1117&stroke=30363D&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&currStreakNum=FFFFFF&sideNums=FFFFFF&sideLabels=C9D1D9&dates=8B949E" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yan791/yan791/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yan791/yan791/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/yan791/yan791/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</p>

<!-- ============================================================ -->
<!--  Footer                                                       -->
<!-- ============================================================ -->
<p align="center">
  <img width="100%" alt=""
       src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0EA5E9,50:1E3A8A,100:0F172A" />
</p>
