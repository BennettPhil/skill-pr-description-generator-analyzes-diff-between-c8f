---
name: pr-description-generator-analyzes-diff-between-c8f
description: A PR description generator that analyzes the diff between two branches and produces a structured pull reque...
version: 0.1.0
license: Apache-2.0
---

# pr-description-generator-analyzes-diff-between-c8f

## Purpose

Test-driven skill scaffold for: A PR description generator that analyzes the diff between two branches and produces a structured pull request description with summary, changes list, testing notes, and review c....

## Contract

- Prints a clear `Goal` and ordered `Steps`.
- Fails with exit code `1` when required arguments are missing.
- Supports `--help` with exit code `0`.

## Inputs

- `target`: required positional argument.

## Outputs

- Human-readable plan on stdout.

## Error Handling

- Missing target returns non-zero and prints an error message.

## Testing

Run `./scripts/test.sh`. The tests are the source of truth for expected behavior.
