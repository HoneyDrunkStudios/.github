# Organization defaults agent instructions

Read [README.md](README.md). This repository owns the public organization profile and fallback GitHub PR template. Repository-local templates take precedence. An AGENTS.md in this repository is not automatically inherited by other organization repositories. Keep organization defaults public-safe; never copy private planning context into the profile or template.

Read the [shared engineering conventions](https://github.com/HoneyDrunkStudios/HoneyDrunk.Standards/blob/main/HoneyDrunk.Standards/docs/CONVENTIONS.md) and this repository's owning documentation before editing. Apply the parts relevant to this stack; preserve existing public contracts, dependency direction and repository-specific behavior. Verify shared capabilities in current code before reusing them; a catalog entry or scaffold is not an implemented integration.

Work within the selected request. Preserve unrelated changes and use a separate worktree when needed. Review the final diff, use Conventional Commits and ready-for-review PRs with exactly one accurate `Authorship:` line and a `Request:` line; include the authorship in commit trailers. Run meaningful checks for the affected behavior and report the reviewed/tested revision, failures and unrun checks. For documentation-only changes, check links, paths and instruction consistency. Preserve required checks and inspect actual latest-head Sonar new-code findings where analysis applies; do not suppress findings or weaken gates to obtain a pass. Legacy Grid Review is retired; do not restore its workers, queues or bypass labels. A configured replacement reviewer is not evidence of a completed review or enforcing merge check.

No executable build/test suite is present. Check Markdown links, template metadata compatibility, repository-local precedence and `git diff --check` for documentation changes.

## Code Review Rules

Apply the [shared review criteria](https://github.com/HoneyDrunkStudios/HoneyDrunk.Standards/blob/main/HoneyDrunk.Standards/docs/CONVENTIONS.md#code-review) to changed behavior, using the repository boundaries above. Report actionable findings with the failing path, concrete impact and a small corrective action; disclose unavailable evidence. These rules grant no cross-repository access or merge authority.

- Keep the public organization profile and fallback PR template within this repository's ownership. Do not claim these instructions automatically govern other repositories; repository-local templates and instructions retain their own scope.
- Check template or profile changes for private information, misleading capability claims and loss of required submission context. Links or historical automation references must not silently authorize tools, payments or retired review execution.
- Require content/path evidence appropriate to the changed artifact; do not invent runtime tests for metadata. Preserve existing CI/approval responsibilities and leave deterministic formatting or required-field validation to their actual consumers.
