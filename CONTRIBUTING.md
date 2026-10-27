# Contributing

Thank you for considering a contribution. This project is maintained entirely by volunteers, and contributions from actuaries of all technical backgrounds are welcome — you do not need prior open-source experience.

## Before you start

**For anything beyond a small fix (a new tool, a new feature, a significant change): open an issue first.** Describe what you want to add or change and why. A maintainer will respond, usually within a few days, to confirm it's a good fit before you invest time building it. This step exists to protect *your* time — nobody wants you to write a weekend's worth of code only to be told it doesn't fit the project's scope.

Small fixes (typos, broken links, minor bugs) can go straight to a pull request without an issue first.

## Two ways to contribute

### 1. Listing a tool in the registry

If you maintain a tool elsewhere (your own GitHub repo, a personal project) and want it discoverable here:

1. Fork this repository.
2. Add an entry to the relevant file under `/registry` following the existing format (name, one-line description, link, license, primary language/tool).
3. Open a pull request.

You keep full ownership and control of your own tool — listing it here does not transfer any rights or maintenance responsibility.

### 2. Contributing to a shared package

If you're contributing code directly into a package hosted in this org (under `/packages`):

1. Open an issue describing the change (see above), unless it's a small fix.
2. Fork the repository and create a branch for your change.
3. Make your changes. If the package has tests, add or update tests covering your change. If it doesn't have tests yet and you're able to add some, even better.
4. Open a pull request against `main`, describing what changed and why.
5. A maintainer will review your PR. They may approve it, ask for changes, or explain why it doesn't fit — none of these outcomes reflect poorly on you; review is a normal part of collaborative code.
6. Once approved and passing automated checks, a maintainer merges it.

If you've never opened a pull request before: GitHub's own [guide to pull requests](https://docs.github.com/en/pull-requests) walks through the mechanics step by step. Feel free to also just ask in your issue — a maintainer is happy to help with the process itself, not just the actuarial content.

## Licensing of your contribution

**By submitting a pull request to a package hosted in this repository, you agree that your contribution is licensed under the MIT License**, the same license covering the rest of that package (see its `LICENSE` file). This keeps the licensing of the project consistent and unambiguous for everyone who uses it downstream. If this is a problem for a specific contribution (e.g., you're bound by an employer's IP policy), please raise it in your issue before submitting code, and a maintainer will work through it with you.

## Code style and quality expectations

- Prioritize readability over cleverness — most readers of actuarial code are actuaries, not professional software engineers.
- Include a brief docstring or comment explaining the *purpose* of any nontrivial function, not just what it does mechanically.
- If your change affects calculation logic, include a worked example or test case demonstrating correct output, ideally against a known/published result.
- Don't worry about being a polished programmer. Maintainers will help clean up style issues during review — the priority is correct, well-explained actuarial logic.

## Getting review help

If your PR doesn't receive a response within about two weeks, feel free to comment on it with a friendly nudge, or raise it in the committee's usual communication channel. Maintainers are volunteers with day jobs, so occasional delays happen, but nothing should sit unreviewed indefinitely.
