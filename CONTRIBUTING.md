# Contributing

Thank you for contributing to Browser Kit.

This project aims to improve developer experience for UiPath web automation with a practical and collaborative approach.

Contributions are welcome from:

- RPA developers
- testers
- documentation writers
- reviewers
- issue triage contributors
- developers with little or no GitHub experience


## Ways to contribute

You do not need to submit production code.

Examples:

- propose activity ideas
- report bugs
- improve documentation
- create examples
- contribute XAML prototypes
- test existing features
- review requirements
- improve naming and usability


## Repository structure

```

/core
Production-ready coded implementations maintained by project maintainers.

/contrib-xaml
Community XAML prototypes and executable specifications.

/examples
Sample projects and usage examples.

/docs
Architecture notes, decisions and onboarding material.

/lab
Experimental ideas and early work.

```

## XAML contributions

XAML contributions are welcome.

Because UiPath XAML files can be difficult to diff and merge, XAML contributions may be treated as:

- executable specifications
- prototypes
- proof-of-concept implementations

Accepted functionality may later be rewritten into coded implementations under `/core`.

The goal is to preserve behavior while keeping maintainability high.

Original contributors will receive attribution.


## Contribution workflow

1. Open an Issue or Discussion when possible
2. Create a feature branch

Example:

```

feature/browser-profile-export

```

3. Implement your change
4. Open a Pull Request
5. Maintain discussion until review is complete


## Pull request guidelines

Keep PRs focused.

Prefer:

- one feature
- one fix
- one idea

Avoid combining unrelated changes.


## Design principles

Prefer:

- stability over visual complexity
- reproducibility over convenience hacks
- explicit behavior over hidden assumptions
- maintainable implementation over workflow size
- developer experience


## Licensing

By contributing, you agree that your contribution will be released under the repository license.

Current repository license:

Apache License 2.0


## Questions

If you are unsure where to start:

Open an Issue and ask.
