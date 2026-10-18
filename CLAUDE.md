# .github

Organization defaults for KluparLabs. GitHub reads this repo for the org
profile (`profile/README.md`), the default security policy (`SECURITY.md`),
the default issue and pull request templates (`.github/ISSUE_TEMPLATE/`,
`.github/PULL_REQUEST_TEMPLATE.md`), and reusable workflows
(`.github/workflows/`). A repo with its own copy of a file overrides the
default.

Read `KluparLabs/platform` first: the inventory of systems, the conventions,
and the roadmap. This repo owns the org defaults; the roadmap item that
created it is in `platform/roadmap.md` § Conventions and tooling.

## Not from the template

Every other KluparLabs repo starts from `KluparLabs/repo-template`. This one
does not: the template brings board scripts, skills, and `test.ps1` for a
project with code, and GitHub gives the `.github` repo a fixed layout. The
process still applies: branch, PR, the owner merges.

## Rules

- **Nothing private.** This repo may be made public so GitHub applies its
  defaults (GitHub requires that). No addresses, hostnames, account names,
  personal names, or anything from `platform/inventory/`. Role language only.
- **No secrets**, as everywhere in KluparLabs. See
  `platform/conventions/secrets.md`.
- **Templates mirror the process**, not the other way round. The ticket
  skeleton is `docs/ticket-template.md` in the template; change it there
  first, then here.
- **Reusable workflows pin versions** and run with `contents: read`.
