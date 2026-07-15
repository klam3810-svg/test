# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **documentation / text-only repository**. There is no application source code, build system, dependency manifest, test suite, or CI configuration. Do not look for or invent build/lint/test commands — none exist. The only meaningful content lives in Markdown files at the repo root:

- `README.md` — a free-form collection of greetings and motivational quotes (e.g. "xin chao", "hello world"). It is the primary target of most changes.
- `AI_READINESS_AUDIT.md` — a large, self-contained audit report. It describes the repo as "empty" from an earlier snapshot; treat it as a historical artifact, not a live spec.
- `CLAUDE.md` — this file.
- `.keep` — empty placeholder.

## How work happens here

The repository is driven almost entirely by small, automated tasks that append or tweak lines of text in `README.md`. Git history reflects this: commits like `[Task <id>] Add 'xin chao N' to README.md`, and many `ssmp/*` and `ssmp/task-*` branches, each carrying one such change that merges to `main` via PR.

When given a task, expect it to be a minor text edit (add a phrase, append a quote). Make the smallest change that satisfies it, in the file named — usually `README.md`.

## Git & commit guidelines

- Write concise, imperative commit messages (e.g. "Add greeting to README", "Update CLAUDE.md").
- **Do NOT** include `Co-Authored-By:` or any other automated co-author / attribution trailer in commit messages, under any circumstances.
- Follow the existing branch/PR flow: work on a branch (the `ssmp/*` convention is used throughout) and merge to `main` via pull request rather than committing directly.
