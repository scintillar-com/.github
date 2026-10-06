# Contributing to Scintillar

Thanks for your interest in contributing! Bug reports, feature ideas, documentation fixes and code are all welcome.

Scintillar tools are built for fun, in the open, at our own pace. Help is best-effort, and there are no deadlines or roadmap promises. Please read this page before you start, so your time goes into changes that can be merged.

## Before you start

- **Check the tool's scope.** Each tool does one job and stays small. Its README says what it does and what it deliberately doesn't. When an idea belongs to a neighbouring job, the answer is usually an integration point (an API, a webhook, an import or export) and the tool keeps its size.
- **Open an issue first for anything bigger than a small fix.** Agreeing on the approach before you write code saves everyone a rewrite.
- **Keep the five promises.** Every tool must stay free, open source, white-label, deployable with one command and AI-ready. In practice, a change can't:
  - add a paid service the owner has to sign up for (optional integrations using the owner's own account are fine),
  - hardcode a Scintillar name, logo or domain, or make the tool contact a Scintillar server,
  - make setup need more than one command,
  - add interface text that can't be translated.

## How to contribute

1. **Fork the repository** and create a branch:

   ```bash
   git checkout -b feat/my-change
   ```

2. **Make your changes.** Follow the existing code style, and add a comment where the logic isn't obvious.
3. **Test locally.** Run the repository's tests and linter before you push. The README explains how.
4. **Commit** with clear [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) messages:

   ```bash
   git commit -m "feat: add short descriptive message"
   ```

5. **Push your branch** to your fork and **open a pull request** against `main`. Describe what changed and why, and link the issue it addresses.

## Reporting issues

- Use the repository's **Issues** tab and pick a template.
- For bugs, include the version you run, how you deployed it, steps to reproduce, what you expected and what happened.
- **Never report a security issue in a public issue.** See [SECURITY.md](SECURITY.md).

## AI-assisted contributions

You're welcome to use AI tools. You're responsible for what you submit: read it, test it, and make sure you can explain it.

## Licensing

- By contributing, you agree that your contribution is licensed under the license of the repository you contribute to, usually MIT. See its `LICENSE` file.
- Only submit work you have the right to contribute.

## Code of Conduct

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

Thank you for helping improve Scintillar's tools!
