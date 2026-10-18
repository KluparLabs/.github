Ticket: owner/repo#N

<!-- Name the ticket as above, never with a closing keyword (Closes, Fixes,
Resolves). The branch links the PR to the ticket; close-ticket.mjs closes it
after the merge. CI fails a PR with a closing keyword. -->

## What

One paragraph: what changes and why. The ticket has the detail.

## Checks

- [ ] `pwsh ./test.ps1` green locally.
- [ ] Every behavior change has a test that fails without it.
- [ ] No secrets, personal data, or machine-specific paths.
- [ ] Docs that name the changed thing are updated.

## Review

<!-- Code and config: request one Copilot review at creation. Chore, log,
and docs PRs: none. -->
