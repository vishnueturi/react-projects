# Repository Structure Source Of Truth

This document is the contract for the `react-projects` repository setup.

## Objective

Create a clean repository where:

- `main` contains documentation and shared repository configuration only.
- every project folder becomes its own orphan branch
- orphan branches do not share commit history with `main` or with each other
- each orphan branch contains only one project at the repository root

## Main Branch Contents

The `main` branch is allowed to contain:

- `README.md`
- `.gitignore`
- repository-level config files such as `.editorconfig`
- documentation under `docs/`

The `main` branch must not contain project source folders such as `01basicreact/` or `07reactRouter/`.

## Orphan Branch Rules

Each project branch must be created with orphan history and must contain:

- source code for one project only
- project config such as `package.json`, lockfiles, Vite config, and source files
- no `node_modules`
- no build output folders

Each project branch should flatten the source folder so the project files live at the repository root of that branch.

## Branch Mapping

| Branch Name | Current Local Source Folder |
| --- | --- |
| `01basicreact` | `01basicreact/` |
| `01vitereact` | `01vitereact/` |
| `02counter` | `02counter/` |
| `03tailwindprops` | `03tailwindprops/` |
| `04bgChanger` | `04bgChanger/` |
| `05passwordGenerator` | `05passwordGenerator/` |
| `06currencyConvertor` | `06currencyConvertor/` |
| `07reactRouter` | `07reactRouter/` |
| `08miniContext` | `08miniContext/` |
| `09themeswitcher` | `09themeswitcher/` |
| `10todocontextLocal` | `10todocontextLocal/` |

## Operational Rules

1. Build the repository locally first.
2. Validate branch content before any push.
3. Push `main` and each orphan branch only after local verification succeeds.
4. Do not merge orphan branches into each other.
5. Future projects should follow the same pattern: folder name becomes orphan branch name unless there is a strong reason to rename it.
