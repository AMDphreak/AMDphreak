<!--
**AMDphreak/AMDphreak** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

> Hey, babe, I fork on the first date and commit to `main`.

## Developer Learning material

Developer Roadmap: <https://github.com/kamranahmedse/developer-roadmap>

## Rules for programmers

**Systems programming**
- *Do not use C for systems programming.* C has no namespaces to contain variable names or module system to provide a namespace.
  C requires header files, which are annoying. C's common libraries are full of horribly-named constants and functions.
- **Use D instead of C.** D improves on C by introducing advanced data types and higher-level abstraction of functions,
  as well as automatic memory management via a garbage collector, which can be disabled if you really need to remove the
  GC for performance or memory size reasons in embedded systems like a firmware.
  C vs D: <https://gemini.google.com/share/bdba47f19258>
- **Or use Rust.** Ideally, we would be rewriting all core operating system userland code in D lang,
  however Rust has captured the public attention. Certain features from Rust's toolchain are excellent ideas that need to be incorporated
  into D lang, however D lang already has `safe D` which is a similar idea for enforcing memory-safe practices in critical system-level tooling.

**Scientific and numerical computing**
- [Julia and D lang vs Java](<https://gemini.google.com/share/b0964e893d07>)
  - _Do not use Java._ Their ecosystem of tools is confusing, even if the language is organized. One of their language features
    (annotations) is heavily abused by frameworks, which makes it feel horrible to use.
  - **Use Julia, not Python, for scientific and numerical computing, data science, and artificial intelligence.** Python is slow and has
    stupid design choices in the language that make it difficult to rectify one library's design assumptions against another library that
    you may be using. Julia is clean and fast.

**Application programming**
- _Do not use C++._ It is the worst programming language of all time: <https://youtu.be/7fGB-hjc2Gc?si=6qM7eUBS5t8fV-Np>
  C++ vs D: <https://gemini.google.com/share/51f07fad7499>

**Scripting**
- _Do not use Python._ See above. Python was originally made to "bridge the gap between C and shell scripting" (Guido van Rossum, creator of Python).
  It accomplished this but introduced several poor design choices: everything is an object, including each number. The number 1 is an object.
  Python cannot be compiled normally. It has to bundle the Python runtime with the code using `pyinstaller`. Python's runtime is massive, so
  this results in poor loading performance, on top of the slow execution performance.
- **Use D lang** for applications that need a clean syntax like Python that will interact with the system (userland tools).
