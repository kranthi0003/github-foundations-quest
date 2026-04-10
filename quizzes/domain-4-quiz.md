# 🏆 Domain 4 Boss Fight — Modern Development

> Score 10/12 or higher to defeat this boss! Honor system 🎖️
> Write your answers, then check against the key at the bottom.

---

### Q1. What is a GitHub Actions workflow?
- A) A manual code review checklist
- B) An automated process defined in a YAML file that runs one or more jobs in response to events
- C) A project board automation rule
- D) A Dependabot configuration file

### Q2. Where must workflow YAML files be stored in a repository?
- A) In the root directory
- B) In the `.github/workflows/` directory
- C) In the `actions/` directory
- D) In any directory with a `.yml` extension

### Q3. Which of the following is a valid event trigger for a GitHub Actions workflow?
- A) `on: push`
- B) `on: email`
- C) `on: slack_message`
- D) `on: merge_conflict`

### Q4. What is the difference between GitHub-hosted and self-hosted runners?
- A) There is no difference
- B) GitHub-hosted runners are managed by GitHub with a clean environment each time; self-hosted runners are machines you manage yourself
- C) Self-hosted runners are free; GitHub-hosted runners always require payment
- D) GitHub-hosted runners can only run Linux

### Q5. What is GitHub Codespaces?
- A) A code formatting tool
- B) A cloud-hosted development environment that runs in a container and is accessible via browser or VS Code
- C) A GitHub Pages hosting service
- D) A repository template gallery

### Q6. What is the github.dev editor?
- A) A desktop application for GitHub
- B) A lightweight, browser-based VS Code editor that opens when you press `.` on a repository — it edits files but cannot run terminal commands
- C) A paid IDE subscription service
- D) A GitHub Actions workflow editor

### Q7. What is GitHub Copilot?
- A) A project management tool
- B) An AI-powered code completion tool that suggests code based on context and natural language prompts
- C) A code review bot that automatically approves PRs
- D) A repository backup service

### Q8. What is the purpose of reusable workflows in GitHub Actions?
- A) To share workflow steps between repositories by calling one workflow from another, reducing duplication
- B) To automatically retry failed workflows
- C) To create workflow templates that cannot be modified
- D) To run workflows on a schedule only

### Q9. What is the GitHub Marketplace?
- A) A place to buy and sell repositories
- B) A platform to discover and share GitHub Actions and apps that extend GitHub functionality
- C) A hosting service for npm packages
- D) A job board for developers

### Q10. In a GitHub Actions workflow, what does a "job" consist of?
- A) A single YAML file
- B) A set of steps that execute on the same runner, where steps run sequentially
- C) A collection of repositories
- D) A group of pull requests

### Q11. Which keyword in a Codespaces configuration sets up the development container?
- A) `Dockerfile` only
- B) The `devcontainer.json` file in the `.devcontainer/` directory
- C) `codespace.yml` in the root directory
- D) `environment.json` in `.github/`

### Q12. What happens when you press `.` (period key) while viewing a repository on GitHub?
- A) It opens the repository in GitHub Desktop
- B) It opens the repository in the github.dev web-based editor
- C) It creates a new Codespace
- D) It opens the Actions tab

---

<details>
<summary>🔑 Answer Key (click to reveal)</summary>

| Q | Answer | Explanation |
|---|--------|-------------|
| 1 | B | Workflows are YAML-defined automated processes triggered by repository events |
| 2 | B | GitHub Actions only recognizes workflow files in `.github/workflows/` |
| 3 | A | `push` is a built-in event trigger; the others are not valid GitHub Actions events |
| 4 | B | GitHub-hosted runners provide fresh VMs; self-hosted runners are your own infrastructure |
| 5 | B | Codespaces provides full cloud dev environments with terminal, extensions, and compute |
| 6 | B | Pressing `.` opens github.dev — a lightweight browser editor for quick file edits |
| 7 | B | GitHub Copilot is an AI pair programmer that suggests code completions and entire functions |
| 8 | A | Reusable workflows use `workflow_call` to let one workflow invoke another, reducing duplication |
| 9 | B | The Marketplace is a directory of community and verified Actions and GitHub Apps |
| 10 | B | A job is a set of sequential steps that run on a single runner instance |
| 11 | B | `devcontainer.json` configures the development container — specifying tools, settings, and extensions |
| 12 | B | The `.` shortcut opens the current repo in the github.dev browser-based VS Code editor |

**Pass mark: 10/12 (83%)**

</details>
