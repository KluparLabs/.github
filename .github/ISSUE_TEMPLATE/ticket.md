---
name: Ticket
about: A feature or a bug. Every ticket has a parent (its epic, or the ticket it was split from).
title: ""
labels: []
---

<How found or who asked, date>. Related to epic owner/repo#NNN. **Size: S.**

Personal data and customer identifiers are kept out of this ticket; the unredacted line is in <the log for YYYY-MM-DD at HH:MMZ | the query>.

## Why

What happened, what it cost, and what the fix buys. Two paragraphs at most.

## Root cause

`<path>` line N: what the code does and why that produced the symptom.
(For a feature, use `## Premise` instead: the file and line the claim rests on.)

## Change

1. `<path>`: the edit, in one or two sentences.
2. Tests and docs that move with it.

## Done

- [ ] (Bugs) `<test name>` reproduces the bug: fails before the fix, passes after.
- [ ] A file, a test, a number, or a comment a reader who was not present can check.
- [ ] `./test.ps1` green; PR opened.

## Callers

Who names the thing being changed: modules, scripts, skills, docs, tests. "None" is an answer. Omit the section when no contract changes.

## Telemetry

- **Event or log:** the event name or log line and its fields. No personal data or customer identifiers.
- **Alert:** each new alert condition and where it fires.
- **Audit:** the audit line for every write, naming the principal that made it.
- **Read it with:** the query, dashboard, or command that reads it, and the window.

"None" is an answer for a change with nothing new to observe.

## Estimate

N hrs raw, 1x (1.5x when there is a named tail; name it). History: xR for this size from hours-report.mjs, or "too few to calibrate". **Estimate: E h.**
