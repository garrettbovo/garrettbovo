<a href="https://www.linkedin.com/in/garrett--ellis/">
  <img src="https://github.com/user-attachments/assets/f7586f68-5076-46dd-95bb-135380e5e896"
       title="Go to my LinkedIn" alt="Garrett Ellis — C/C++ Software Developer">
</a>

# Garrett Ellis

**C/C++ Software Developer** · Web Developer @ Pinellas County Clerk of Court · Computer Science @ University of South Florida

[![Clearance](https://img.shields.io/badge/U.S._Citizen-Clearance_Eligible-2ea043?style=for-the-badge)](#what-im-looking-for)
[![Portfolio](https://img.shields.io/badge/Portfolio-garrettbovo.github.io-1f6feb?style=for-the-badge)](https://garrettbovo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/garrett--ellis/)
[![Email](https://img.shields.io/badge/Email-Contact-6e7681?style=for-the-badge&logo=gmail&logoColor=white)](mailto:egarrett021@gmail.com)

I write **C++17 simulation and pathfinding engines** on my own time and ship **AES-256 encrypted court software** at work. CS junior at USF (3.95 GPA, graduating December 2027), **seeking a software engineering internship** — in defense, aerospace, or anywhere correctness and performance actually matter.

---

## By the numbers

| | |
|---|---|
| **~500,000** | public users served by web applications I build and maintain |
| **$15,000/yr** | county costs eliminated — accessibility remediation plus throughput gains |
| **3.1× / 97%** | A\* speedup over Dijkstra, and fewer nodes explored, across 1,000 benchmarked runs |
| **1,000,000+** | multithreaded simulation runs executed in a single batch |

---

## Featured Projects

### [Graph Loot Engine](https://github.com/garrettbovo/GraphLoot-Engine) — C++17 Simulation & Pathfinding Engine

![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

> **A\* explores 97% fewer nodes and runs 3.1× faster than Dijkstra** on large graphs — measured with `std::chrono` across 1,000 runs, not assumed.

- **Dijkstra and A\*** over an adjacency-list graph backed by `std::unordered_map`, using `std::priority_queue` with custom comparators.
- **Polymorphic world abstraction** (`World` base, `FortniteWorld` derived) spanning 11+ classes, with a data-driven item system of 5 types across 5 rarity tiers loaded from CSV — content changes require no recompilation.
- **1,000,000+ batch simulation runs** parallelized with `std::thread` and mutex-protected result aggregation.
- CMake build, interactive and headless CLI modes, and a **GitHub Actions pipeline** running build and regression checks on every push.

### [Collection System Simulation](https://github.com/garrettbovo/Pokemon-Go-System-Simulation) — C/C++ Engine with Trie Indexing

![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)

> **O(k) lookup across a 493-record dataset**, with a custom character index handling apostrophes, hyphens, and periods.

- **Function-pointer dispatch tables** (`ListManager`, `MenuManager`, `TrieManager`) emulating OOP-style polymorphism in C, backed by a doubly linked list supporting insertion, deletion, sort, and reverse.
- **Trie-based search** with custom character indexing for keys standard implementations mishandle.
- Refactored into a **hybrid C/C++ architecture** using `extern "C"` linkage to expose the C engine to a C++ wrapper, managing construction and teardown through **RAII**.

### [Student Registration System](https://github.com/garrettbovo/Student-Registration-System-Simulation) — C Data Management Engine

![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)

Enrollment workflow modeling with validated input pipelines, a trie-based index guaranteeing NetID uniqueness, and doubly linked list record management with sorting, filtering, and file-backed persistence.

---

## Technical Skills

**Languages** — C++17 · C · Python · JavaScript · HTML/CSS

**C++** — STL containers and algorithms · templates · RAII · inheritance and polymorphism · structured bindings · `std::thread` / `std::mutex` · file I/O

**Algorithms & Data Structures** — Dijkstra and A\* · tries · adjacency-list graphs · priority queues · doubly linked lists · hash maps · benchmarking

**Tools & Systems** — CMake · Make · Git · GitHub Actions (CI/CD) · VS Code · Ollama / Continue

**Security & Compliance** — AES-256 encryption · ADA/WCAG remediation · offline-first design · data integrity and auditability

**Platforms** — DNN (DotNetNuke) CMS · SharePoint · Power Apps · Power Automate

---

## Experience

**Web Developer** — Pinellas County Clerk of the Circuit Court and Comptroller · *Oct 2025 – Present*

- Designed a fully offline, **AES-256 encrypted web application** automating Florida probate guardianship court filings — replacing manual Excel workflows with guided data entry, automatic calculations, and filing-ready PDF/Excel export.
- Maintain public-facing applications in the **DNN CMS serving ~500,000 residents** and 500+ internal staff; cut website request turnaround from **weeks to under 24 hours**.
- Led **ADA/WCAG remediation** across county pages, improving WAVE AIM scores ~40% and saving **~$10,000 annually** by ending third-party remediation outsourcing.

**Management Intern, Web Development** — Pinellas County Clerk of the Circuit Court · *Aug 2024 – Oct 2025*

- Built **Clerk's Closet**, a Power Apps inventory system integrated with SharePoint Lists and Power Automate.
- Consolidated a dozen SharePoint pages into a unified intranet used by **500+ employees**.
- Department's **highest-output docketer** — 25% of all Intellidact filings at 70 filings/hour, eliminating ~$5,000 in annual overtime.

---

## What I'm Looking For

Seeking a **software engineering internship**, with particular interest in:

- Systems programming in C and C++
- Simulation, modeling, and mission software
- Embedded and real-time systems

**U.S. citizen, eligible for security clearance.** Based in the Tampa Bay area — home to a significant defense presence — and available for on-site roles in the region or remote work.

---

## Contact

**Email** — [egarrett021@gmail.com](mailto:egarrett021@gmail.com)

**Portfolio** — [garrettbovo.github.io](https://garrettbovo.github.io/)

**LinkedIn** — [garrett--ellis](https://www.linkedin.com/in/garrett--ellis/)
