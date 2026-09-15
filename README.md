<div align="center">

# `H4CK3RL0R`

### `INFORMATION SECURITY // RED TEAM // OFFENSIVE SECURITY`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=00FF9C&center=true&vCenter=true&width=700&lines=Breaking+systems+to+understand+them.;Learning+how+machines+actually+work.;PWN+%7C+RE+%7C+WEB+%7C+LINUX;CTF+player+%7C+Security+student+%7C+Builder" alt="Typing SVG" />

<br>

[![GitHub](https://img.shields.io/badge/GitHub-111111?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/)
[![CTF](https://img.shields.io/badge/CTF-000000?style=for-the-badge\&logo=hackthebox\&logoColor=00FF9C)](https://tryhackme.com/)
[![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge\&logo=linux\&logoColor=FCC624)](https://www.linux.org/)
[![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge\&logo=python\&logoColor=3776AB)](https://www.python.org/)

</div>

---

```text
┌──────────────────────────────────────────────────────────────────────┐
│                         SYSTEM // WHOAMI                             │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  USER        : H4ck3rl0r                                             │
│  ROLE        : Information Security Student                          │
│  ENVIRONMENT : Linux / Windows / CTF Labs                            │
│  MODE        : LEARN → BREAK → UNDERSTAND → BUILD                    │
│                                                                      │
│  PRIMARY INTERESTS                                                   │
│  ├── Binary Exploitation                                             │
│  ├── Reverse Engineering                                             │
│  ├── Web Security                                                    │
│  ├── Linux & Systems                                                 │
│  ├── Networking                                                       │
│  └── Security Research                                               │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

## `01 // PHILOSOPHY`

> **I don't want to memorize exploits.
> I want to understand why they work.**

I'm an Information Security student interested in understanding
computer systems from the bottom up.

My current rabbit holes include:

* How source code becomes machine instructions
* How operating systems manage processes and memory
* What really happens across a syscall boundary
* Why memory corruption can become control-flow hijacking
* How vulnerabilities turn into practical exploits
* How attackers think — and how defenders can detect them

For me, **breaking things is a method of learning how they were built.**

---

## `02 // SECURITY LOADOUT`

### ⚔️ Offensive Security

```text
Binary Exploitation     ███████████████░░░
Reverse Engineering    ██████████████░░░░░
Web Security           ████████████░░░░░░░
CTF                    ████████████████░░░
```

### 🧠 Systems

```text
C / C++                ████████████░░░░░░░
x86-64 / Assembly      █████████████░░░░░░
Linux                  ██████████████░░░░░
Networking             ███████████░░░░░░░░
Operating Systems      ██████████░░░░░░░░░
```

### 🛠️ Toolchain

```text
GDB / pwndbg     •     pwntools      •     IDA Pro
Burp Suite       •     Kali Linux    •     Git
Docker           •     Wireshark     •     Python
```

---

## `03 // CTF OPERATIONS`

```text
                         CTF LAB

             ┌───────────────┐
             │   CHALLENGE   │
             └───────┬───────┘
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
        PWN         RE         WEB
          │          │          │
          └──────────┼──────────┘
                     ▼
               UNDERSTAND
                     │
                     ▼
                  EXPLOIT
                     │
                     ▼
                    FLAG
```

### Current focus

| Domain    | Topics                                                 |
| --------- | ------------------------------------------------------ |
| `PWN`     | Stack overflow · ROP · ret2libc · Format String · Heap |
| `RE`      | ELF · x86-64 · Static Analysis · Dynamic Analysis      |
| `WEB`     | SSRF · IDOR · JWT · JS Obfuscation                     |
| `LINUX`   | Processes · Memory · Syscalls · Permissions            |
| `NETWORK` | TCP/IP · Protocols · TLS · Packet Analysis             |

> CTF is not just about getting the flag.
>
> **The real objective is understanding the primitive that made the flag reachable.**

---

## `04 // OPERATIONS`

### `OP-001 // Pictionary Online`

**Multiplayer drawing & guessing platform**

```text
                    ┌──────────────┐
                    │   CLIENT     │
                    │  .NET 8      │
                    └──────┬───────┘
                           │
                          TLS
                           │
                           ▼
                    ┌──────────────┐
                    │   GATEWAY    │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │ GAME SERVER  │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │    SQLite    │
                    └──────────────┘
```

**Stack**

`C#` · `.NET 8` · `WinForms` · `SQLite` · `Azure` · `Sockets`

**Security**

* TLS between client and gateway
* Password hashing with bcrypt
* Session-based authentication
* Server-side game logic
* Separated gateway / game-server architecture

---

### `OP-002 // LifeBoard`

Personal productivity / planning platform.

```text
React / Vite
     │
     ▼
.NET Backend
     │
     ▼
  Database
```

Current focus:

`State Management` · `Persistence` · `API Design` · `Security`

---

## `05 // THINGS I'M TRYING TO UNDERSTAND`

These are the questions currently occupying my brain:

```text
[01] What actually happens when a program executes a syscall?

[02] How does an interpreter eventually reach machine instructions?

[03] What happens between a process and the physical disk?

[04] How does the CPU turn bytes into execution?

[05] Where exactly does memory corruption become control flow?

[06] Why is one bug exploitable while another is not?

[07] How do modern mitigations change exploitation strategy?

[08] Can I explain the entire attack chain from first principles?
```

---

## `06 // CURRENT OBJECTIVE`

```text
┌───────────────────────────────────────────────────────────────┐
│                     CURRENT MISSION                           │
├───────────────────────────────────────────────────────────────┤
│                                                               │
│  [ BUILD ]       ███████████████░░░░░                         │
│  [ BREAK ]       █████████████████░░░                         │
│  [ RESEARCH ]    ████████████░░░░░░░                         │
│  [ UNDERSTAND ]  ████████████████████                        │
│                                                               │
│  NEXT TARGETS                                                  │
│                                                               │
│  → Deepen x86-64 exploitation                                 │
│  → Improve reverse engineering                                │
│  → Understand Linux internals                                 │
│  → Build security-focused projects                            │
│  → Move from solving challenges → researching systems         │
│                                                               │
└───────────────────────────────────────────────────────────────┘
```

---

## `07 // GITHUB ACTIVITY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Thv0n9K1nG&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" height="170">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Thv0n9K1nG&hide_border=true&theme=transparent" height="170">

</div>

<br>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Thv0n9K1nG&layout=compact&hide_border=true&theme=transparent" height="150">

</div>

---

## `08 // CONNECT`

<div align="center">

**Want to talk about systems, security, CTFs or something that probably should not be run as root?**

<br>

`OPEN CONNECTION`

</div>

```text
$ whoami

H4ck3rl0r

$ echo $STATUS

LEARNING

$ echo $NEXT

RESEARCH
```

<div align="center">

### `SYSTEM ONLINE // KEEP BREAKING THINGS`

</div>

<!--
    If you found this comment:

    Congratulations.

    You are now part of the attack surface.

    Nothing interesting here...
    probably.
-->
