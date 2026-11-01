# Contributing

This guide applies to every repository in the `neverinstall-labs` organisation that does not have its own
`CONTRIBUTING.md`. A repository's own guide adds build and test steps for that tool.

## Ways to contribute

- **Report a bug.** Open an issue with the bug report form.
- **Correct a rule or figure.** Vendor rules, formulas and hardware figures live in versioned data files. If one is
  wrong or out of date, open an issue with the correction form or send a pull request. Include the source URL.
- **Request a tool or a feature.** Open an issue with the request form and describe the problem you are solving.
- **Send a pull request.** For a change larger than a small fix, open an issue first so we can agree on the
  approach.

## Rules for every tool

Changes must keep these properties:

- The tool works for any target platform. Do not add behaviour that favours one vendor.
- The tool runs locally and sends no data anywhere.
- A tool that runs on a user's systems stays read-only.
- Every vendor rule, price rule or figure in a data file cites a source and a checked date.

## Pull requests

1. Fork the repository and create a branch from `main`.
2. Keep each pull request to one change.
3. Add or update tests where the repository has them.
4. Update the README if behaviour or usage changes.
5. Sign off every commit (see below).

A maintainer reviews pull requests weekly.

## Sign-off (Developer Certificate of Origin)

We use the [Developer Certificate of Origin](https://developercertificate.org/) instead of a contributor licence
agreement. Signing off states that you wrote the change or have the right to submit it under the repository's
licence.

Add a sign-off line to each commit with `git commit -s`:

```
Signed-off-by: Your Name <you@example.com>
```

## Licences

Contributions are licensed under the repository's licence: Apache License 2.0 for code, Creative Commons
Attribution 4.0 for guides and templates.

## Conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).

## Security problems

Do not report security problems in issues. Follow [SECURITY.md](SECURITY.md).
