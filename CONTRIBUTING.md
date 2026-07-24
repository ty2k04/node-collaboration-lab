#  Contributing to node-collaboration-lab

Thank you for your interest in contributing to **node-collaboration-lab**. This project is a small collaborative Node.js lab, so the best contributions are clear, focused, and easy for other contributors to review.

This guide explains how external developers can fork the repository, make changes, and submit pull requests.

## Ways to Contribute

You can help by:

- Fixing bugs or improving existing code
- Adding small, well-scoped Node.js examples
- Improving documentation
- Cleaning up formatting or readability
- Reporting issues with clear reproduction steps
- Suggesting improvements through GitHub Issues

For larger changes, please open an issue first so maintainers can discuss the idea before you spend time implementing it.

## Getting Started

### Prerequisites

Install the following before working on the project:

- Git
- Node.js 18 or newer

This repository currently uses a simple Node.js entry point and does not require installing dependencies.

### Fork and Clone

1. Fork this repository on GitHub.
2. Clone your fork:

   ```bash
   git clone https://github.com/<your-username>/node-collaboration-lab.git
   cd node-collaboration-lab
   ```

3. Add the original repository as `upstream`:

   ```bash
   git remote add upstream https://github.com/<owner>/node-collaboration-lab.git
   ```

4. Confirm the project runs:

   ```bash
   node app.js
   ```

You should see the welcome message and sample output in your terminal.

## Keeping Your Fork Updated

Before starting new work, sync your fork with the latest upstream changes:

```bash
git checkout main
git pull upstream main
git push origin main
```

If the default branch is named something other than `main`, use the branch name shown on GitHub.

## Making Changes

Create a new branch for each contribution:

```bash
git checkout -b fix/clear-output-spacing
```

Use a short branch name that describes the work. Common prefixes include:

- `fix/` for bug fixes
- `docs/` for documentation changes
- `feature/` for new functionality
- `chore/` for maintenance work

Keep pull requests focused. A small PR that solves one problem is easier to review than a large PR that changes several unrelated things.

## Code Guidelines

Please follow these guidelines when changing code:

- Keep the project simple and beginner-friendly.
- Use clear variable names and readable formatting.
- Avoid adding dependencies unless they are necessary.
- Do not commit generated files, local environment files, or editor-specific settings.
- Match the existing JavaScript style unless the project adopts a formatter later.
- Add comments only when they explain something that is not obvious from the code.

If you add a new feature, include a short explanation in the README when helpful.

## Testing Your Changes

Before submitting a pull request, run the project locally:

```bash
node app.js
```

Check that:

- The program runs without errors.
- Existing output still makes sense.
- Your change behaves as described.
- Documentation examples are accurate.

If tests are added in the future, run the documented test command before opening your PR.

## Commit Guidelines

Write clear commit messages that explain what changed. A good format is:

```bash
docs: update contribution instructions
fix: correct console output spacing
feature: add greeting helper
```

Use the present tense and keep the subject line concise.

## Submitting a Pull Request

When your change is ready:

1. Push your branch to your fork:

   ```bash
   git push origin fix/clear-output-spacing
   ```

2. Open a pull request against the upstream repository's default branch.
3. In the pull request description, include:

   - What you changed
   - Why the change is needed
   - How you tested it
   - Any related issue number, such as `Fixes #12`

4. Respond to review comments respectfully and update your branch when requested.

Maintainers may ask for changes before merging. This is normal and helps keep the project consistent.

## Reporting Bugs

Before opening a new issue, search existing issues to see whether the bug has already been reported.

When reporting a bug, include:

- A clear title
- Steps to reproduce the problem
- What you expected to happen
- What actually happened
- Your Node.js version
- Your operating system
- Screenshots or terminal output, if useful

## Requesting Features

Feature requests are welcome. Please explain:

- The problem the feature solves
- The behavior you expect
- Any alternatives you considered
- Whether you are willing to submit a pull request

For major changes, wait for maintainer feedback before beginning implementation.

## Review and Merge Process

Project maintainers review pull requests for:

- Correctness
- Simplicity
- Readability
- Fit with the project scope
- Documentation quality

A pull request may be merged after maintainer approval and any requested changes are complete.

## Community Standards

Please keep all participation respectful, constructive, and welcoming. Be patient with new contributors, assume good intent, and focus feedback on the work rather than the person.

Harassment, personal attacks, or exclusionary behavior are not acceptable. If a problem occurs, contact a project maintainer through GitHub.

## Maintainers

The current project team listed in the README is:

- Maintainer: Tyron James Beza
- QA Lead: Kristine Camille Bowman
- Developer: Rhea Mae Mendoza
- Contributor: Aliyah Amor Dulce
- DevOps: Samantha Maxene Garcia

## Thank You

Every useful issue, pull request, review, and documentation improvement helps make this lab better for everyone learning and collaborating with Node.js.
oyed on **Vercel**, so major changes may affect build times.