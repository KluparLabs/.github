---
name: Escaped bug
about: A bug found in code already merged to the default branch. Names the PR that introduced it and why review did not catch it.
title: ""
labels: ["escaped"]
---

<How found, date>. Related to epic owner/repo#NNN. **Size: S.**

Introduced by: <owner/repo#PR>.
Why it escaped: <no test | test missed the case | Done list missed it | review missed it | premise wrong | outside change> — <one sentence>.
Diagnosable from logs: <yes, via <query or command> | no — missing <what>; adding it is part of this fix>.

Personal data and customer identifiers are kept out of this ticket; the unredacted line is in <the log for YYYY-MM-DD at HH:MMZ | the query>.

## Why

What happened, what it cost, and what the fix buys. Two paragraphs at most.

## Root cause

`<path>` line N: what the code does and why that produced the symptom.

## Change

1. `<path>`: the edit, in one or two sentences.
2. The test that reproduces it, committed first so the branch shows red, then green.
3. The log line that was missing, if "Diagnosable from logs" said no.

## Done

- [ ] `<test name>` reproduces the bug: fails before the fix, passes after.
- [ ] A file, a test, a number, or a comment a reader who was not present can check.
- [ ] `./test.ps1` green; PR opened.

## Telemetry

- **Event or log:** the line that would have shown this sooner, and its fields.
- **Read it with:** the query or command, and the window.

## Estimate

N hrs raw, 1x (1.5x when there is a named tail; name it). **Estimate: E h.**
