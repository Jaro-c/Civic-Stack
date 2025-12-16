# Contributing to Civic Stack

Thank you for your interest in contributing to Civic Stack.

This project is community-driven and collaborative. To maintain clarity,
consistency, and long-term sustainability, contributions are accepted
under the rules described below.


## Types of Contributions

The following types of contributions are welcome:

- Bug reports (issues)
- Feature proposals
- Documentation
- Code contributions
- Reviews and suggestions

All contributions must align with the project's community-oriented and
non-commercial nature.


## General Guidelines

- Be respectful and clear in all communications
- Clearly describe problems or proposed improvements
- Keep contributions focused and well-scoped
- Contributions with commercial intent are not accepted


## License of Contributions

By contributing to this project, you agree that:

- Your contribution is published under the same license as the project
- You do not gain any right to relicense the project
- You do not obtain commercial rights to the software
- Contributions may be modified or rejected by the maintainers

No exclusive or commercial rights are transferred to contributors.


## Contribution Process

1. Open an issue to discuss the change when appropriate
2. Fork the repository
3. Create a dedicated branch for your change
4. Submit a Pull Request with a clear and concise description

Maintainers may request changes before accepting a contribution.


## Branching Model

This project uses a two-branch workflow:

- `main`: contains only stable, production-ready code
- `develop`: integration branch for ongoing development

Direct commits to `main` and `develop` are not allowed.
All changes must be introduced through Pull Requests.


## Forks and Pull Requests

### External contributors

External contributors must:

1. Fork the repository
2. Create a branch in their fork
3. Open a Pull Request targeting the `develop` branch

Pull Requests from forks targeting `main` will not be accepted.


### Maintainers and collaborators

Maintainers and approved collaborators may:

- Create branches directly in the main repository
- Open Pull Requests targeting `develop`

Only maintainers are responsible for merging changes from `develop` into `main`.


## Commit Message Convention

This project follows the Conventional Commits specification.

Contributors are expected to use commit messages in the following format:

type: short description

Examples:
- docs: add contributing guidelines
- feat: add initial configuration loader
- fix: handle null configuration values

For full details, see:
https://www.conventionalcommits.org/en/v1.0.0/


## Branch Naming Convention

Contributors are encouraged to use the following branch naming format:

- `feat/<short-slug>` for new features
- `fix/<short-slug>` for bug fixes
- `docs/<short-slug>` for documentation
- `chore/<short-slug>` for maintenance tasks
- `refactor/<short-slug>` for refactoring
- `test/<short-slug>` for test-related changes

Examples:
- feat/config-loader
- fix/null-config-values
- docs/update-contributing


## Conventions Scope

The conventions described in this document are intended to provide clarity
and consistency without introducing unnecessary rigidity.

- The Conventional Commits specification applies to **commit messages**
- The Branch Naming Convention applies to **branch names**

Both conventions are complementary and aim to improve collaboration,
readability, and project maintainability.

Examples are intentionally limited to keep this document concise.
For commit messages, contributors are encouraged to consult the official
Conventional Commits specification for full details.


## Project Authority

Final decisions regarding the project, including design, scope, and
licensing, are made by the original author and designated maintainers.

Contributions do not grant control or authority over the project.
