<div align="center">
  <h1>AMDphreak</h1>
  <p>
    Systems architect and full-stack developer building an ecosystem of composable tools focused on developer experience (DevX) and high-performance, cross-platform computing.
  </p>
  <p>
    <a href="https://ryanjohnson.dev">Website</a>
    &middot;
    <a href="https://docs.devcentr.org/home/index.html">Dev-Centr docs</a>
    &middot;
    <a href="https://ryanjohnson.dev/inspirations">Inspirations</a>
  </p>
  <p>
    <a href="https://dlang.org"><img src="https://img.shields.io/badge/D-0075B8?style=flat-square&logo=d&logoColor=white" alt="D"></a>
    <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust"></a>
    <a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"></a>
    <a href="https://react.dev"><img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"></a>
    <a href="https://www.solidjs.com"><img src="https://img.shields.io/badge/SolidJS-2C4F7C?style=flat-square&logo=solid&logoColor=white" alt="SolidJS"></a>
    <a href="https://tauri.app"><img src="https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black" alt="Tauri"></a>
    <a href="https://julialang.org"><img src="https://img.shields.io/badge/Julia-9558B2?style=flat-square&logo=julia&logoColor=white" alt="Julia"></a>
    <a href="https://antora.org"><img src="https://img.shields.io/badge/Antora-docs-E40046?style=flat-square&logo=asciidoctor&logoColor=white" alt="Antora"></a>
  </p>
</div>

## Focus

- Composable tooling, typed systems, and documentation-first developer experience
- High-performance software from long-lived web UIs to cross-platform native code
- Software reliability as a product concern—not an afterthought

Architectural decisions are catalogued in [Dev-Centr docs](https://docs.devcentr.org/home/index.html).

## AI Coding Desk

[![Cursor](https://img.shields.io/badge/Cursor-Composer%202.5-000?style=flat-square&logo=cursor&logoColor=white)](https://cursor.com)

- **Cursor + Composer 2.5** — primary IDE and agent for day-to-day repo work
- **Cursor cloud agents** — async and background agent runs when work can leave the editor
- **Hermes** — on the radar to try; no active use case yet
- **T3 Code** — on the radar to try; would run through Cursor CLI if it sticks

---

## Organizations

GitHub orgs I own:

- [antora-supplemental](https://github.com/antora-supplemental)
- [connectome-fs](https://github.com/connectome-fs)
- [Cook-Systems-Team-Blue-Feb-2021-Ryan](https://github.com/Cook-Systems-Team-Blue-Feb-2021-Ryan)
- [dev-centr](https://github.com/dev-centr)
- [dlang-supplemental](https://github.com/dlang-supplemental)
- [FoodTruckNerdz](https://github.com/FoodTruckNerdz)
- [formatte](https://github.com/formatte)
- [HCI-Nerdz](https://github.com/HCI-Nerdz)
- [LinxPhotos](https://github.com/LinxPhotos)
- [nonprofit-resources](https://github.com/nonprofit-resources)
- [openshellorg](https://github.com/openshellorg)

Historical (kept so they are not “rediscovered” as missing):

- [memphis-cs-projects](https://github.com/memphis-cs-projects)

---

## Curated learning

- [Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x)

---

## Language preferences (short)

Opinions are defaults, not absolutes—they keep my own projects consistent.

<details>
<summary>Systems programming</summary>

- Prefer **D** (or **Rust**) over **C** for new systems work: modules and safer patterns beat C’s global namespace and header friction.
- [C vs D (Gemini share)](https://gemini.google.com/share/bdba47f19258)

</details>

<details>
<summary>Scientific and numerical computing</summary>

- Prefer **Julia** over **Python** for serious numerical / ML work when you control the stack; [Julia and D vs Java (Gemini share)](https://gemini.google.com/share/b0964e893d07).
- I avoid leaning on **Java** for that space when the bloat and fragmentation in the ecosystem outweighs the gain.

</details>

<details>
<summary>Application and systems scripting</summary>

- Prefer **D** over **C++** for application code; [C++ vs D (Gemini share)](https://gemini.google.com/share/51f07fad7499). [C++ rant (YouTube)](https://youtu.be/7fGB-hjc2Gc?si=6qM7eUBS5t8fV-Np) — same thesis, louder volume.
- For scripting-shaped tools that still talk to the OS, **D** is my default over **Python** when I want readable syntax without dragging a huge runtime (see scientific section for why Python is a weak default for me).

</details>

<details>
<summary>Math-heavy / functional style</summary>

Programming is math. **Lisp** and **Haskell** are the usual on-ramps if you want lambda-calculus-shaped thinking in performant languages.
- [Haskell by Example](https://lotz84.github.io/haskellbyexample/)

</details>

---

Hey, babe—I fork on the first date and commit to `main`.
