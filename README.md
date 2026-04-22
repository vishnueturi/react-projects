# React Projects Repository

This repository is intentionally split into one documentation branch and multiple isolated project branches.

## Branch Model

- `main`: repository overview, branch index, shared documentation, and common Git config files.
- Project branches: orphan branches where each branch contains exactly one React project at the repository root.

## Project Index

| Branch | Source Folder | Notes |
| --- | --- | --- |
| `01basicreact` | `01basicreact/` | Independent project branch |
| `01vitereact` | `01vitereact/` | Independent project branch |
| `02counter` | `02counter/` | Independent project branch |
| `03tailwindprops` | `03tailwindprops/` | Independent project branch |
| `04bgChanger` | `04bgChanger/` | Independent project branch |
| `05passwordGenerator` | `05passwordGenerator/` | Independent project branch |
| `06currencyConvertor` | `06currencyConvertor/` | Independent project branch |
| `07reactRouter` | `07reactRouter/` | Independent project branch |
| `08miniContext` | `08miniContext/` | Independent project branch |
| `09themeswitcher` | `09themeswitcher/` | Independent project branch |
| `10todocontextLocal` | `10todocontextLocal/` | Independent project branch |

## Usage Guide

Clone the repo and switch to the branch for the project you want to run:

```powershell
git clone https://github.com/vishnueturi/react-projects.git
cd react-projects
git switch 04bgChanger
npm install
npm run dev
```

Switch back to `main` when you want the repository documentation and branch index.

## Source Of Truth

Repository structure rules are defined in [docs/REPO_STRUCTURE.md](docs/REPO_STRUCTURE.md).
