# ModernLibs/.github

Organization-wide defaults and brand assets for [Modern Libs](https://github.com/ModernLibs).

GitHub uses the files in this repository for every Modern Libs repository that does not have its own
copy. A repository's own file always takes precedence.

## Contents

| Path | Purpose |
|---|---|
| [`profile/README.md`](profile/README.md) | The organization profile shown on [github.com/ModernLibs](https://github.com/ModernLibs) |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Contributor Covenant 2.1 |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Default contribution guide |
| [`SECURITY.md`](SECURITY.md) | How to report a vulnerability privately |
| [`SUPPORT.md`](SUPPORT.md) | Where to ask questions and report problems |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Bug report, feature request and question forms |
| [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | Default pull request description |
| [`brand/`](brand) | Logos, colours and usage rules |
| [`LICENSE`](LICENSE) | MIT License for the text and templates; excludes the logos |

## Notes for maintainers

- This repository must stay public, or GitHub stops applying the defaults and the profile.
- A repository that adds its own `.github/ISSUE_TEMPLATE/` folder loses all the default issue templates, not
  just the one it replaces.
- `SECURITY.md` relies on private vulnerability reporting. Enable it in each repository under
  **Settings → Code security**.
- `profile/README.md` loads the logos from `brand/` through `raw.githubusercontent.com`. Renaming or
  moving a file in `brand/` breaks the profile.

## License and trademarks

The text and templates in this repository are licensed under the [MIT License](LICENSE).
`CODE_OF_CONDUCT.md` is adapted from the Contributor Covenant and licensed under CC BY 4.0.

The Modern Libs name and logos in `brand/` are not covered by any repository license. You may use them
to refer to Modern Libs or its libraries; do not use them to imply endorsement or for other projects.
See [`brand/README.md`](brand/README.md#usage).

## Contact

- Security: [security@modernlibs.dev](mailto:security@modernlibs.dev)
- Code of conduct: [conduct@modernlibs.dev](mailto:conduct@modernlibs.dev)
