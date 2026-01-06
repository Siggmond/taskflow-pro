# Contributing to TaskFlow Pro

Thanks for your interest in contributing to **TaskFlow Pro** 🙌  
I’m happy to review thoughtful, well-scoped improvements that align with the goals of the project.

This repository is intentionally structured to resemble a real production codebase, so clarity and maintainability matter more than quick fixes.

---

## How to Contribute

Before opening a pull request, please keep the following in mind:

- 🧩 **Keep changes focused**  
  Small, well-defined improvements are preferred over large, sweeping refactors.

- 🏗 **Respect the existing architecture**  
  - Feature-first modules  
  - Clear store / service separation  
  - No cross-module coupling without a strong reason

- 🧠 **Be consistent with the stack**  
  - Vue 3 Composition API  
  - TypeScript everywhere (no `any` shortcuts)

- 🧪 **Run checks locally**  
  Make sure the project is in a healthy state before submitting a PR:
  ```bash
  npm run typecheck
  npm run lint
  ```

---

## Pull Request Guidelines

When opening a pull request, please:

- Clearly explain **what problem** the change solves
- Describe **why the change is worth merging**
- Include screenshots or short clips for any UI-related updates
- Avoid “drive-by” refactors, especially across unrelated modules

If you’re unsure whether a change fits the scope, feel free to open an issue first to discuss it.

---

## Final Notes

This project is designed to be **readable, predictable, and easy to reason about**.  
Contributions that improve clarity, UX, or maintainability are always welcome.

Thanks again for taking the time to contribute 🚀
