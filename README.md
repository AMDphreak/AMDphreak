# AMDphreak

Architecture notes for dense web UIs—**Bonsai** vs **Leptos** vs **vibe.d**, client/server split for auth and databases, creative-stack interop, and why some integrated suites *feel* faster than others—are in **Dev-Centr** docs: [UI-heavy web applications](https://docs.devcentr.org/home/latest/architecture/ui-heavy-web-apps.html) ([source](https://github.com/dev-centr/docs/blob/HEAD/docs/modules/ROOT/pages/architecture/ui-heavy-web-apps.adoc)).

---

## Organizations

GitHub orgs I own:

- [antora-supplemental](https://github.com/antora-supplemental)
- [Cook-Systems-Team-Blue-Feb-2021-Ryan](https://github.com/Cook-Systems-Team-Blue-Feb-2021-Ryan)
- [dev-centr](https://github.com/dev-centr)
- [dlang-supplemental](https://github.com/dlang-supplemental)
- [FoodTruckNerdz](https://github.com/FoodTruckNerdz)
- [formatte](https://github.com/formatte)
- [Linx-Photos](https://github.com/Linx-Photos)
- [openshellorg](https://github.com/openshellorg)

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

I fork on the first date and commit to `main`.
