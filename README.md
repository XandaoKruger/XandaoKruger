<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1000&color=FFFFFF&center=true&vCenter=true&width=650&lines=Hey%2C+I'm+Xand%C3%A3o+%F0%9F%91%8B;42+Student+%7C+Developer+in+progress;Building+from+scratch+%E2%80%94+no+shortcuts.)](https://git.io/typing-svg)

<br/>

![42](https://img.shields.io/badge/42-School-000000?style=for-the-badge&logo=42&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 🇧🇷 Sobre mim &nbsp;&nbsp;|&nbsp;&nbsp; 🇺🇸 About me

<table>
<tr>
<td width="50%" valign="top">

Desenvolvedor em formação pela **42** — escola baseada em aprendizado entre pares, sem professores, sem aulas. Cada projeto é entregue funcional ou não passa.

Construo desde sistemas de baixo nível em C até aplicações web completas. Foco atual: solidificar domínio em C, Unix e programação de sistemas.

Tenho experiência paralela construindo ferramentas reais para comunidades — o que me força a pensar além do código: arquitetura, persistência e experiência de uso.

</td>
<td width="50%" valign="top">

Developer in training at **42** — a peer-to-peer school with no teachers and no lectures. Projects either work or they don't.

I build from low-level C systems to full-stack web applications. Current focus: deepening my foundation in C, Unix, and systems programming.

I have parallel experience building real tools for online communities — which pushes me to think beyond code: architecture, persistence, and usability.

</td>
</tr>
</table>

---

## 🏫 42 — Common Core Curriculum

> Completed projects, peer-evaluated. Click each one to expand technical details.

<details>
<summary><b>📦 Libft</b> &nbsp;—&nbsp; C standard library reimplemented from scratch</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Evaluation:** Peer review + strict norminette compliance

Reimplementation of 40+ functions from `libc` without using any external library. Includes custom memory functions, string utilities, and a full linked list API (bonus).

**Key functions:** `ft_memset`, `ft_memmove`, `ft_split`, `ft_itoa`, `ft_lstmap`, `ft_strtrim`, among others.

**What it builds:** Deep understanding of how the C standard library actually works under the hood, and the discipline of writing clean, norm-compliant code.

<br/>
</details>

<details>
<summary><b>🖨️ ft_printf</b> &nbsp;—&nbsp; Variadic printf implementation</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** Variadic functions (`va_list`), format string parsing, type dispatch

Custom `printf` handling all major conversion specifiers: `%c %s %d %i %u %x %X %p %%`. Parses the format string character by character and routes each specifier to the correct handler.

**What it builds:** Understanding of variadic functions, type promotion in C, and building reusable libraries.

<br/>
</details>

<details>
<summary><b>📄 get_next_line</b> &nbsp;—&nbsp; Line-by-line file descriptor reading</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** File descriptors, static variables, dynamic buffer management

Function that reads from any file descriptor one line at a time across successive calls, handling arbitrary `BUFFER_SIZE` values and no memory leaks. Bonus: handles multiple file descriptors simultaneously without mixing buffers.

**What it builds:** Mastery of memory lifecycle in C, file I/O at the syscall level.

<br/>
</details>

<details>
<summary><b>🖥️ Born2beroot</b> &nbsp;—&nbsp; System administration & virtualization</summary>
<br/>

**Environment:** Debian on VirtualBox &nbsp;|&nbsp; **Concepts:** LVM, disk encryption, SSH, UFW, sudo hardening, cron

Full VM setup from scratch with strict security policy: encrypted partitions (LVM), SSH on non-default port, UFW firewall rules, password strength enforcement, sudo logging, and automated monitoring script via cron.

**Bonus:** WordPress stack deployed manually — Lighttpd + MariaDB + PHP-FPM, all configured by hand.

**What it builds:** Real sysadmin fundamentals — the kind that make Docker and cloud deployments make sense later.

<br/>
</details>

<details>
<summary><b>🗺️ FdF</b> &nbsp;—&nbsp; 3D wireframe map renderer</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** Isometric projection, MiniLibX, matrix math, event loop, keyboard/mouse handling

Reads a height map file and renders it as an interactive 3D isometric wireframe using MiniLibX. Supports zoom, translation, and rotation. Each altitude value maps to a Z coordinate and an interpolated color.

**What it builds:** First contact with graphics programming, coordinate transformations, and real-time event handling.

<br/>
</details>

<details>
<summary><b>📡 Minitalk</b> &nbsp;—&nbsp; IPC via UNIX signals</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** `SIGUSR1`/`SIGUSR2`, bit manipulation, signal handlers, PID-based communication

Client-server architecture using only UNIX signals for inter-process communication. The client encodes each character bit by bit and transmits it to the server's PID. The server reconstructs and prints the message in real time.

**Bonus:** Acknowledgement system — server confirms each character received; Unicode support.

**What it builds:** Understanding of UNIX signal mechanics, asynchronous communication, and bit-level operations.

<br/>
</details>

<details>
<summary><b>🔀 push_swap</b> &nbsp;—&nbsp; Sorting with constrained operations</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** Algorithm design, stack operations, complexity optimization

Sorts a stack of integers using only two stacks (`a` and `b`) and 11 allowed operations. Graded by total operation count — fewer is better. Requires a custom algorithm; naive approaches fail the evaluation thresholds.

**Operations:** `sa sb ss pa pb ra rb rr rra rrb rrr`

**What it builds:** Algorithm thinking under hard constraints, performance analysis, and the real cost of implementation choices.

<br/>
</details>

<details>
<summary><b>🐚 minishell</b> &nbsp;—&nbsp; POSIX-compliant Unix shell</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** Lexing, parsing, AST, `fork`/`execve`, pipes, redirections, signals, environment

Full shell implementation supporting:
- Pipes (`|`) and redirections (`>`, `>>`, `<`, `<<`)
- Environment variable expansion and `$?`
- Quote handling (single and double)
- Signal behavior matching bash (`ctrl-C`, `ctrl-D`, `ctrl-\`)
- Built-ins: `echo`, `cd`, `pwd`, `export`, `unset`, `env`, `exit`

**What it builds:** Comprehensive understanding of how a shell works — and by extension, how the OS manages processes, file descriptors, and execution.

<br/>
</details>

<details>
<summary><b>🧵 Philosophers</b> &nbsp;—&nbsp; Concurrency & the dining philosophers problem</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** `pthread`, mutexes, race conditions, deadlock, precise timing

Simulation of the dining philosophers problem. Each philosopher is a thread; each fork is a mutex. No philosopher may die of starvation — the solution must be precise to the millisecond and free of data races.

**Bonus:** Process-based version using `fork()` and semaphores (`sem_open`).

**What it builds:** Concurrency fundamentals — the hardest class of bugs to debug, and the most valuable to understand.

<br/>
</details>

<details>
<summary><b>🌐 NetPractice</b> &nbsp;—&nbsp; TCP/IP networking & subnetting</summary>
<br/>

**Concepts:** IPv4, CIDR notation, subnet masks, routing tables, network topology

10 progressive exercises requiring correct IP/mask/route configuration on broken network diagrams. No code — pure applied networking logic. Each exercise adds complexity to the topology.

**What it builds:** Practical TCP/IP intuition — subnetting, routing decisions, and why `192.168.1.0/24` means what it means.

<br/>
</details>

<details>
<summary><b>🎮 cub3D</b> &nbsp;—&nbsp; Raycasting 3D engine</summary>
<br/>

**Language:** C &nbsp;|&nbsp; **Concepts:** Raycasting, DDA algorithm, texture mapping, MiniLibX, map parsing

First-person 3D engine inspired by Wolfenstein 3D. Renders a 2D map as a textured 3D perspective using raycasting — one ray per screen column. Handles wall textures per direction (N/S/E/W), floor/ceiling colors, movement, and collision.

**Bonus:** Minimap, animated sprites, mouse-look.

**What it builds:** Deep understanding of how 3D rendering worked before GPUs — and how much you can do with pure math and a pixel buffer.

<br/>
</details>

<details>
<summary><b>☕ CPP Modules 00–09</b> &nbsp;—&nbsp; C++ from fundamentals to advanced</summary>
<br/>

**Language:** C++ (C++98 standard) &nbsp;|&nbsp; **Format:** 10 progressive modules, each with multiple exercises

| Module | Core Topic |
|--------|-----------|
| 00 | Namespaces, classes, member functions, I/O streams |
| 01 | Memory allocation, references, pointers to members, file streams |
| 02 | Orthodox Canonical Form, ad-hoc polymorphism, operator overloading, fixed-point arithmetic |
| 03 | Inheritance, access specifiers, method overriding |
| 04 | Subtype polymorphism, abstract classes, interfaces, deep vs shallow copy |
| 05 | Repetition & exceptions, try/catch, custom exception classes |
| 06 | C++ casts: `static_cast`, `dynamic_cast`, `reinterpret_cast`, `const_cast` |
| 07 | Function templates, class templates, template specialization |
| 08 | Templated containers, iterators, STL algorithms |
| 09 | STL in practice: `map`, `stack`, `deque` applied to real problems |

**What it builds:** A genuine transition from C to modern systems programming — and the conceptual base for any language with OOP.

<br/>
</details>

<details>
<summary><b>🐳 Inception</b> &nbsp;—&nbsp; Docker infrastructure from scratch</summary>
<br/>

**Environment:** Docker, Docker Compose, Debian &nbsp;|&nbsp; **Concepts:** Containerization, custom images, inter-service networking, volumes, TLS

Full web infrastructure deployed in isolated Docker containers, built from scratch — no pre-built images allowed:

- **NGINX** — only entry point, TLS 1.2/1.3 only
- **WordPress + PHP-FPM** — dynamic content, connects to MariaDB
- **MariaDB** — database, no direct external access

All containers communicate via a Docker network. Data persists via volumes. Everything configured through custom Dockerfiles and a single `docker-compose.yml`.

**What it builds:** Real DevOps fundamentals — how containerized services talk to each other, how to isolate responsibility, and how production infrastructure is structured.

<br/>
</details>

<details>
<summary><b>🏆 ft_transcendence</b> &nbsp;—&nbsp; Full-stack web application (final project)</summary>
<br/>

**Stack:** TypeScript, NestJS, React, PostgreSQL, Docker &nbsp;|&nbsp; **Team project**

The capstone of the Common Core. A full-stack web application built as a team, featuring:

- **Real-time multiplayer Pong** via WebSockets
- **Live chat** with channels, DMs, and moderation (ban, mute, kick)
- **Friend system** and user profiles with stats and match history
- **Tournament system** with bracket logic
- **OAuth 2.0** via 42 intranet + **2FA** (TOTP)
- **JWT-based auth**, security hardening, and input sanitization

Fully containerized with Docker Compose.

**What it builds:** End-to-end product thinking — real-time systems, authentication security, team coordination, and shipping something that actually works.

<br/>
</details>

---

## 🛠️ Tech Stack

<div align="center">

| Area | Technologies |
|------|-------------|
| **Systems** | C, C++98, memory management, POSIX |
| **Scripting** | Bash, Shell scripting |
| **Backend** | Node.js, NestJS, TypeScript |
| **Database** | PostgreSQL, SQL |
| **DevOps** | Docker, Docker Compose, Linux (Debian) |
| **Tools** | Git, GitHub, SSH, Make |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=XandaoKruger&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github"/>
&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=XandaoKruger&layout=compact&theme=github_dark&hide_border=true&langs_count=8"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=XandaoKruger&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

</div>

---

## 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/XandaoKruger/XandaoKruger/blob/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/XandaoKruger/XandaoKruger/blob/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake animation" src="https://github.com/XandaoKruger/XandaoKruger/blob/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

---

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=XandaoKruger&color=555555&style=flat-square&label=profile+views)

</div>
