# .github

The organization's special repository: `README.md` introduces the org, and any community health file placed here
(`PULL_REQUEST_TEMPLATE.md`, `ISSUE_TEMPLATE/`, `SECURITY.md`, …) becomes the default for every repository in
`arikkfir-org` that lacks its own.

## Rules

- Keep `README.md` a short intro. Details belong in `arikkfir-org/docs`.
- Anything added here applies org-wide; say so in the pull request.
- Conventions (commits, pull requests, Linear keys) are defined in `arikkfir-org/docs/CONTRIBUTING.md`; link to them
  rather than restating them.
- CI is Switchboard + Tekton (`.switchboard.yaml`, `.tekton/ci.yaml`): markdownlint with `.markdownlint-cli2.yaml`.
  Run `npx markdownlint-cli2` before pushing.
