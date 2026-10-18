# Security policy

This policy applies to every KluparLabs repository that has no `SECURITY.md`
of its own.

## Reporting a vulnerability

Use GitHub's private vulnerability reporting on the affected repository
(the **Security** tab, then **Report a vulnerability**). Do not open a public
issue. Say what you found, where, and how to reproduce it. Expect an
acknowledgement within seven days.

## What we promise

- A committed or leaked secret is rotated, not just deleted.
- A bug found after merge is tracked with the cause named, and the fix ships
  with a test that fails without it.
- Dependencies and pinned tool versions are reviewed when a fix is published.

## Scope

KluparLabs repositories and what they deploy. Devices and services KluparLabs
runs but does not build (routers, appliances, vendor clouds) are out of scope;
report those to the vendor.
