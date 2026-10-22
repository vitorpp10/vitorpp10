# vitor

I'm a 19-year-old computer science student. I build developer tools and systems
software, and I write about what I'm learning.

**Reach me:** [LinkedIn](https://www.linkedin.com/in/vitor-de-padua) · vitorprofissionalpp10@gmail.com

---

## Working on

**[Markdownify](https://github.com/vitorpp10/markdownify)** — a VS Code extension
that turns messy text into clean Markdown.

Messy text is everywhere: AI output, PDFs, web clips, chat logs. Markdownify
fixes it without asking you to trust a black box. ~800 lines of deterministic
TypeScript rules run first — headings, lists, PDF indentation, inline code —
so the common case is instant, offline and free. AI sits on top as a
refinement, never as the core.

The part I care about: code blocks, tables and front matter are replaced by
sentinels **before** the model sees them, and restored after. The AI cannot
corrupt what it never receives. Before anything is written back, the result
passes four independent checks — and if any of them fails, the file is left
untouched.

`190 tests` · `TypeScript` · published on the VS Code Marketplace

---

## Building

| Project | What it is |
| --- | --- |
| **[markdownify](https://github.com/vitorpp10/markdownify)** | VS Code extension: messy text → clean Markdown. Offline rules first, AI as refinement. |
| **[mini-shell-cpp](https://github.com/vitorpp10/mini-shell-cpp)** | Linux shell from scratch: REPL, `fork`/`exec`, background jobs, and built-ins that must run in the parent (`cd` via `chdir`). |
| **[mini-db-kv](https://github.com/vitorpp10/mini-db-kv)** | Key-value store with a manual on-disk layout: binary records with a magic byte, `lseek` offsets, and an in-memory index. |
| **[live-file-scanner](https://github.com/vitorpp10/live-file-scanner)** | Real-time file scanner using `inotify` and forked workers. |
| **[cpp-system-lab](https://github.com/vitorpp10/cpp-system-lab)** | C++ systems lab: months of code and theory on memory, processes and file systems. |

---

## Stack

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="30" title="typescript"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="30" title="node.js"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="30" title="c"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="30" title="c++"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="30" title="python"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="30" title="linux"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" width="30" title="bash"/>

**Tools:** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neovim/neovim-original.svg" width="30" title="neovim"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="30" title="git"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="30" title="vs code"/>

---

## What I'm learning

**Systems** — memory and processes (multi-threading, `fork`/`exec`, `malloc`,
pipes, signal handling) and file systems (`/proc`, binary formats, low-level
I/O, syscalls). This is where I sharpen the fundamentals; it is the base
everything else sits on.

**AI applied** — not calling an API, but knowing when a model actually helped.
Evaluating output, measuring cost, and designing systems where the model
cannot break things.

---

*Currently: 4th semester of Computer Science. Intern at the Brazilian Superior
Military Court, on the technology team.*
