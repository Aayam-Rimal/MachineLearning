# Contributing to MachineLearning

Thanks for your interest in contributing to MachineLearning — the repo for my ML learning algorithms and notebooks. Contributions of all kinds are welcome: bug reports, improvements, new notebooks, documentation, or tips to make the repo more useful.

## Table of contents
- How to contribute
- Issues
- Pull requests
- Notebook guidelines
- Code style & formatting
- Testing
- License & attribution
- Thank you

## How to contribute
1. Fork the repository and clone your fork:
   ```bash
   git clone https://github.com/<your-username>/MachineLearning.git
   cd MachineLearning
   ```
2. Create a branch for your work:
   ```bash
   git checkout -b feature/short-description
   ```
3. Make small, focused commits with clear messages. Rebase or merge main before opening a pull request to keep history tidy.
4. Push your branch and open a pull request against `Aayam-Rimal/MachineLearning`'s `main` branch.

## Issues
- Search existing issues before opening a new one.
- When reporting a bug, include:
  - A short title
  - Steps to reproduce
  - The notebook (or cell) and dataset used
  - Environment details (Python version, packages)
  - Any error output or stack traces
- For enhancement requests, explain the motivation and suggested approach.

## Pull requests
- Open a PR describing:
  - What you changed
  - Why the change is needed
  - Any relevant screenshots or notebook outputs
- Keep PRs small and focused.
- Link any related issue in the PR description using `#issue-number`.
- If adding a notebook, include a short explanation of the notebook’s purpose in the PR.

## Notebook guidelines
- Use clear, descriptive notebook names (e.g., `01-linear-regression.ipynb`).
- Keep notebooks reproducible: include dataset download/prep steps or provide a minimal sample dataset.
- Avoid committing large raw datasets. Use `.gitignore` for data that should not be stored in the repo.
- Clear output cells before committing to keep diffs small. Tools:
  - nbstripout: `pip install nbstripout && nbstripout install`
  - nbdime for diffs: `pip install nbdime`
- If a notebook depends on a particular environment, include environment info at the top:
  ```yaml
  # Requirements:
  # Python 3.10
  # pip install -r requirements.txt
  ```
- Prefer keeping long-running experiments or large model weights out of the repo; link to external storage if needed.

## Code style & formatting
- Python code in notebooks should follow PEP 8 where practical.
- Use meaningful variable names and add brief comments explaining non-obvious steps.
- For utilities or reusable functions, consider moving them to a `.py` module in a `src/` or `notebook_utils/` folder so they can be unit tested.

## Testing
- If you add functions or modules, include tests where possible.
- For notebook testing, consider `nbval` to validate notebooks: `pip install nbval` and run with `pytest --nbval`.
- Describe manual verification steps in the PR if tests are not feasible.

## License & attribution
- Respect dataset and code licenses when contributing materials from external sources.
- Add attribution and links for datasets, tutorials, or code snippets used.

## Communication & Code of Conduct
- Be respectful and constructive in all interactions.
- If you have concerns about a contribution, raise them politely in the PR or issue.

## Thank you
Thank you for taking the time to contribute — your help makes this project better and helps others learn. Contributions large or small are appreciated!

