# React Projects Repository

A beginner-friendly React practice repository.  
`main` contains the guide. Each project lives in its own orphan branch so you can open and learn one concept at a time.

## How This Repo Is Organized

- `main`: overview, docs, and common repo files
- project branches: one branch = one React mini project

## How To Use

```powershell
git clone https://github.com/vishnueturi/react-projects.git
cd react-projects
git switch 04bgChanger
npm install
npm run dev
```

Pick one branch, study the code, run it, then move to the next.

## Projects

| Branch | Project | What It Does | What You Learn |
| --- | --- | --- | --- |
| `01basicreact` | Basic React | Simple starter app using Create React App | components, JSX, project structure |
| `01vitereact` | React With Vite | Minimal React app with Vite | Vite setup, faster dev workflow, app entry flow |
| `02counter` | Counter | Counter app with increment and decrement | `useState`, events, re-rendering |
| `03tailwindprops` | Tailwind Props Demo | UI built with reusable card props | props, reusable components, Tailwind basics |
| `04bgChanger` | Background Changer | Changes page background from UI actions | state-driven styling, events, dynamic class updates |
| `05passwordGenerator` | Password Generator | Creates passwords from user options | hooks, derived values, inputs, utility logic |
| `06currencyConvertor` | Currency Convertor | Converts one currency into another | custom hooks, API/data handling, controlled inputs |
| `07reactRouter` | React Router Demo | Multi-page style app with routing | routing, layouts, params, navigation |
| `08miniContext` | Mini Context App | Small login/profile flow with context | Context API, shared state, provider pattern |
| `09themeswitcher` | Theme Switcher | Toggles application theme | context, theme state, global UI updates |
| `10todocontextLocal` | Todo App | Todo app with saved local data | CRUD UI, Context API, localStorage, state flow |

## Learning Path

Good order for beginners:
`01basicreact -> 01vitereact -> 02counter -> 03tailwindprops -> 04bgChanger -> 05passwordGenerator -> 06currencyConvertor -> 07reactRouter -> 08miniContext -> 09themeswitcher -> 10todocontextLocal`

## Source Of Truth

Repository structure rules are defined in [docs/REPO_STRUCTURE.md](docs/REPO_STRUCTURE.md).
