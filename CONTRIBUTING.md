# Contributing

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways
to help and details about how this project handles them. Please make sure to read the relevant section before making
your contribution. It will make it a lot easier for us maintainers and smooth out of the experience for all involved.
The community looks forward to contributions. 🎉

> If you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support
> the project and show your appreciation:
> - Star the project
> - Tweet about it
> - Refer this project in your own README
> - Mention it at local meetups, or share it with friends and colleagues 🎉

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)
- [Improving The Documentation](#improving-the-documentation)
- [Styleguide](#styleguide)
- [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)

## Code of Conduct

This project and everyone participating in its governed by the [Code of Conduct](CODE_OF_CONDUCT.md). By participating,
you are expected to uphold this code. Please report unacceptable behaviour to
[report@sombeyyy.de](mailto:report@sombeyyy.de).

## I Have a Question

> If you want to ask a question, we assume that you've already read the available Documentation.

Before asking a question, it's best to search for existing issues or discussions that might help you. If you find a
relevant issue or discussion and still need clarification, you can post your question there. It's also advisable to
search the web for answers first (e.g. Stack Overflow).

If you still have questions, please follow these steps:

1. Open a **Discussion** on the relevant project.
2. Provide as much context as possible about what you're encountering.
3. Include the version of the project and platform you're using (e.g. Node.js, npm, etc.).

We'll do our best to assist you as soon as possible!

## I Want To Contribute

> ### Legal Notice
> When contributing to the project, you must confirm that you have authored 100% of the content, that you have the
> necessary rights to it, and that the content can be provided under the project license.

### Reporting Bugs

#### Before Submitting a Bug Report

A good bug report should provide all the information needed to diagnose and fix the issue. Follow these steps to help us
resolve it as quickly as possible:

1. Ensure you are using the latest version of the project.
2. Verify that the bug isn't an error on your side (e.g. due to incompatible environments components or versions). Read
   the Documentation and check [the "I have a Question" section](#I-Have-a-Question).
3. Search for similar issues in the **GitHub Issues** to see if it's already been reported.
4. Search the web (e.g. Stack Overflow) to see if anyone else has encountered the issue.
5. Collect relevant information
    - Stack trace (if available)
    - OS, Platform, and Version (Windows, Linux, macOS, etc.)
    - Version of the interpreter, compiler, SDK, runtime environment, package manager, etc.
    - Input and output data (if applicable)
    - Steps to reliably reproduce the issue (and if possible, with older versions)

#### How Do I Submit a Good Bug Report?

> Never report security-related issues or vulnerabilities publicly. Instead, send bugs via email to
> [security@sombeyyy.de](mailto:security@sombeyyy.de).

To report a bug:

1. Open a new **Issue** (don't label it as a bug yet-at this point, we just want to gather more information).
2. Describe the expected and actual behaviour clearly.
3. Provide detailed reproduction steps, ideally isolating the issue and creating a reduced test case.
4. Include all the information you collected in the previous section.

Once your issue is submitted:

- The project team will label it appropriately.
- A maintainer will attempt to reproduce the issue based on your steps. If not reproduction steps are provided, the
  issue will be marked as `needs_repro` and won't be addressed until reproducibility is confirmed.
- Once reproduced, it will be marked `needs-fix` and may be assigned to someone for implementation.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion, including completely new features or minor
improvements.

#### Before Submitting an Enhancement

1. Ensure you're using the latest version.
2. Check the Documentation to see if the functionality is already covered.
3. Search if the enhancement has already been suggested. If so, add a comment to the existing discussion.
4. Ensure your idea aligns with the project's scope and objectives. If your feature targets only a small subset of
   users,
   consider creating an add-on or plugin instead.

#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked through **GitHub Discussions**.

1. Use a **clear and descriptive title** to identify the suggestion.
2. Provide a **step-by-step description** of the enhancement in as much detail as possible.
3. Explain **current behaviour** and **expected behaviour**, and why the change would be beneficial.
4. Provide **screenshots or GIFs** to help demonstrate your suggestion.
5. Explain **why this feature would be useful** for most users. You may also refer to other projects that solved this
   issue, if relevant.

### Your First Code Contribution

We welcome contributions! Please take a look at the `Good First Issue` tag for tasks that are suitable for first-time
contributors. We've made sure these are simple and well-defined to help you get started.

- Fork the repository.
- Create a new branch for your changes.
- Write clear, well-commented code.

### Improving The Documentation

Improving documentation is valuable contribution! You can help by:

- Updating or adding explanations to the README or other sources.
- Fixing grammar or spelling mistakes.
- Clarifying ambiguous sections.

## Styleguide

- **Code Style**: We follow consistent conventions across the project.
- **Formatting**: Ensure proper indentation and spacing (typically 2 spaces per indentation level).
- **Linting**: Ensure that the code passes all linting checks (if applicable).

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification. This ensures a
consistent commit history that is to read and understand.

Each commit message must have the following format:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Types

- **feat**: A new feature.
- **fix**: A bug fix.
- **docs**: Documentation-only changes.
- **style**: Changes that do not affect the meaning of the code (e.g. formatting, missing semicolons).
- **refactor**: A code change that neither fixes a bug nor adds a feature.
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests.
- **chore**: Changes to the build process or auxiliary tools and libraries.

#### Examples

1. **Adding a new feature:**
   feat(auth): add user login functionality
2. **Fixing a bug:**
   fix(ui): resolve dropdown menu alignment issue
3. **Updating documentation:**
   docs: update README with setup instructions
4. **Code refactoring:**
   refactor(api): simplify data fetching logic

#### Rules

- The **type** must always lowercase.
- The **scope** is optional but recommended for better context (e.g. a specific module or feature).
- The **description** should be concise and written in the imperative mood (e.g. "add feature" instead of "added
  feature").
- Use hte **body** to explain "why" the change was made, if necessary.
- Use the *+footer** for referencing issues or breaking changes (e.g. `BREAKING CHANGE: ...` or `Closes #123`).

## Join The Project Team

If you're interested in taking a more aktive role in the project, consider the project team! You can do so by:

- Demonstrating your contributions over time.
- Being proactive in reviewing issues and pull requests.
- Helping to guide discussions and enhancements.

---

## Attribution

This guide is based on the **contributing.md**. [Make your own](https://contributing.md/)!