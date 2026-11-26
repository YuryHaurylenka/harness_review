# AI Agent Harness Review

A focused engineering review of an AI-assisted development harness. The assessment prioritizes the gap between documented controls and the behavior that can be verified in the supplied source snapshot.

## Deliverables

- **[REVIEW.md](./REVIEW.md)** — prioritized findings, removal candidates, missing safeguards, practices worth retaining, and decisions on conflicting rules in `harness/CODE.md`.
- **[CLAUDE.new.md](./CLAUDE.new.md)** — proposed replacement for the project-level agent brief.
- **[PROMPTS.md](./PROMPTS.md)** — review-role prompts and workflow, with an explicit distinction between designed roles and agents actually executed.

## Review standard

1. **Evidence first:** a control described in documentation is not considered implemented until its configuration or executable implementation is present and inspected.
2. **Risk-based prioritization:** findings are ranked by their likely impact on correctness, security, and production safety.
3. **Actionable recommendations:** each major finding explains where it occurs, how it can fail, and how to verify the proposed correction.
4. **Honest execution record:** no claim of independent agent execution, automated validation, or runtime testing without evidence.

## Scope and limitations

This repository contains assessment artifacts, not the original application. Conclusions are limited to the files included in the supplied harness snapshot. Referenced but absent files are identified as unverified; their behavior is not inferred.

## Status

Initial repository setup. The assessment artifacts are being rechecked against the task brief and the complete supplied source snapshot before submission.
