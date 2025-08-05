
<p align="center">
<img src="./banner.png" alt="FaultLab" />
</p>

## Organization Structure & Conventions

FaultLab is currently maintained by two developers. While we're a small team, we operate with clear and consistent workflows to keep things scalable and easy to maintain.

---

### Repo Structure

- **Default Branch**  
  All repositories **must use `main` as the default branch**.  
  Do not rename it to `master`, `production`, or any other name.

- **Development Branch**  
  Every actively developed repository should include a `dev` branch.  
  - All new work (features, fixes, etc.) is based off of `dev`.
  - Once stable, changes from `dev` are promoted to `main` via a pull request.
  - `main` is the release branch; `dev` is the active development branch.

- **Branch Naming Conventions**  
  - Feature branches: `feature/<short-description>`  
  - Bug fixes: `fix/<short-description>`  
  - Experiments/spikes: `spike/<short-description>`

---

### New Repository Checklist

When creating a new repository:

- [x] Set `main` as the default branch
- [x] Create a `dev` branch from `main`
- [x] Add a `README.md`
- [x] Add a `.gitignore` file (based on tech stack)
- [x] Add a `LICENSE`
- [x] (Optional) Set up branch protection for `main`

---

### Required Files in Every Repo

- `README.md`: Clear project purpose and setup instructions  
- `.gitignore`: Tailored to the language/framework used  
- `LICENSE`: (_Optional for private repos_) Any OSI approved license
- `CONTRIBUTING.md`: (_Optional_) For outlining contribution expectations  
- `.github/`: (_Optional_) GitHub templates (issues, PRs, workflow files) will live here

---

### Commit & PR Workflow

- All code changes are merged into `dev` first
- Use pull requests to merge into both `dev` and `main`
- Write clear, descriptive commit messages
- PRs should explain _why_ a change was made, not just _what_ was done
- Every PR should be reviewed by the other person when possible

---
> [!Note]
> These conventions are here to help us move faster _without_ creating chaos. If a situation doesn’t fit the rules, bring it up and we’ll decide together how to evolve them.
