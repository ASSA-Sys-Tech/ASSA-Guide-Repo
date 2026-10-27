# ASSA Open Source Actuarial Tools

A community index and collaboration space for open-source actuarial tools, built by and for members of the Actuarial Society of South Africa (ASSA), maintained by volunteers from the ASSA Systems & Technology committee and the wider actuarial community.

## What this is

This repository is a **curated index** of open-source tools relevant to South African actuaries — spreadsheets, VBA macros, Python/R packages, Power Query templates, and similar — contributed and maintained by individual members of the community. It also hosts a small number of **shared packages** that the community maintains collectively (see `/packages` once these exist).

This is not an ASSA-certified or ASSA-warranted product. See **Disclaimer** below.

## Why this exists

South African actuaries frequently rebuild the same tools independently — regulatory calculation helpers, mortality table loaders, reserving utilities — because there has been no shared place to publish, discover, and improve them together. This repo exists to reduce that duplication and let the community build on each other's work.

## How it's organized

- **`/registry`** — an index of external tools/repos maintained by individuals or teams elsewhere on GitHub. Entries here are *linked*, not hosted — each tool has its own license and maintainer(s), listed here for discoverability.
- **`/packages`** — tools that live directly in this org and are maintained collectively under the governance model below. Each has its own subdirectory, README, license, and test suite.

## How to get involved

- **To list an existing tool you maintain elsewhere**: open a PR adding an entry to `/registry` (see `CONTRIBUTING.md`).
- **To propose a new shared package**: open an issue describing what it does and why it belongs here before writing code — this saves you from unreviewed work going to waste.
- **To contribute to an existing shared package**: see that package's own `CONTRIBUTING.md`, or the general guidance in this repo's `CONTRIBUTING.md`.
- **To get involved in maintaining/governing the project itself**: see `GOVERNANCE.md`.

## Disclaimer

Tools listed or hosted here are provided **as-is, with no warranty of any kind**, by volunteer contributors. Inclusion in this repository does not constitute review, endorsement, or certification of correctness by the Actuarial Society of South Africa or its Systems & Technology committee. **Users are responsible for independently verifying the correctness of any tool before relying on it for professional actuarial work.** Tools that have passed the review process described in `GOVERNANCE.md` are marked "Reviewed" — this indicates a documented review occurred, not a guarantee of fitness for any particular purpose.

## License

Code hosted directly in this repository (under `/packages`) is licensed under the [MIT License](LICENSE) unless a subdirectory states otherwise. Tools listed under `/registry` retain whatever license their own maintainers have chosen — check each project individually.

## Code of Conduct

This is a professional community space. See `CODE_OF_CONDUCT.md`.
