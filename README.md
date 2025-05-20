# ✨ Frontend Commit Message Convention (with Emojis)

This project uses an emoji-enhanced [Conventional Commits](https://www.conventionalcommits.org/) format for clear,
consistent, and expressive commit messages.

Each commit should follow the format:

- **`<emoji>`**: Visual indicator of the type of change.
- **`<type>`**: Kind of change (e.g., feat, fix, docs).
- **`<scope>`** _(optional)_: Affected area/module of the app.
- **`<message>`**: Brief, imperative summary of the change.

---

## 🧾 Emoji Commit Types

| Emoji | Type       | Description                                                     | Example                                                               |
| ----- | ---------- | --------------------------------------------------------------- | --------------------------------------------------------------------- |
| 💥    | `feat`     | Add a new user-facing feature (component, page, hook, etc.)     | `💥 feat(form): add dynamic validation to contract fee form`          |
| 🐛    | `fix`      | Fix a bug, logic error, or unexpected behavior                  | `🐛 fix(modal): close button not working in Safari`                   |
| 📝    | `docs`     | Add or update documentation (README, comments, guides)          | `📝 docs(readme): update project setup instructions`                  |
| 🌷    | `UI`       | Improve styles, layout, responsiveness, or spacing              | `🌷 UI(button): increase padding for mobile screens`                  |
| 🏰    | `chore`    | Routine changes that don't affect app logic (cleanups, configs) | `🏰 chore: clean up unused assets and rename components`              |
| 🌐    | `locale`   | Add or update internationalization/localization files           | `🌐 locale: add Yoruba translations for dashboard page`               |
| 🔨    | `refactor` | Restructure code without changing its behavior                  | `🔨 refactor(hooks): extract useFetchFeeStructure into separate file` |
| ⚡    | `perf`     | Optimize performance (lazy loading, memoization, etc.)          | `⚡ perf(image): lazy load hero banner on landing page`               |
| 🔁    | `workflow` | Update dev workflows (pre-commit hooks, scripts, automation)    | `🔁 workflow: add husky pre-commit hook for linting`                  |
| 🧱    | `build`    | Update build configuration (Vite, Webpack, UmiJS, etc.)         | `🧱 build: switch from Webpack to Vite for faster builds`             |
| 🤖    | `CI`       | Update continuous integration setup or pipelines                | `🤖 CI: run e2e tests on push to main`                                |
| ✏️    | `typos`    | Fix spelling, grammar, or label text                            | `✏️ typos(form): fix label spelling from "ammount" to "amount"`       |
| ✅    | `tests`    | Add or update unit, integration, or e2e tests                   | `✅ tests(modal): add test for auto-close timeout behavior`           |
| 🧩    | `types`    | Update or fix TypeScript types, interfaces, or generics         | `🧩 types(api): correct FeeStructureResponse interface`               |
| 🚧    | `wip`      | Work in progress, not ready to be merged                        | `🚧 wip(stepper): progress tracker component in progress`             |
| 🔖    | `release`  | Release version tagging or changelog updates                    | `🔖 release: v1.2.0`                                                  |
| 📦    | `dep`      | Add, remove, or update project dependencies                     | `📦 dep: upgrade antd to v5.15.0`                                     |

---

## ✅ Tips

- Use the **imperative mood** for commit messages:  
  ✔ `Add login modal`  
  ✖️ `Added login modal` or `Adds login modal`

- Keep the **message under 72 characters** if possible.

- Include a **scope** to clarify the context (e.g., `form`, `modal`, `hooks`, `config`, etc.).

---

## 🔧 Suggested Tools

- [commitlint](https://commitlint.js.org/) – Enforce commit format
- [husky](https://typicode.github.io/husky/) – Run hooks on commit
- [cz-customizable](https://github.com/leoforfree/cz-customizable) – Interactive commit UI with emoji support

---
