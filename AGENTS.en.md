# Project Working Guidelines

This document is a general-purpose example. Add project information and confirmed commands before applying it to an actual project. Because it applies to the directory containing it and its descendants, place it in an individual project root rather than a drive root containing multiple projects.

## Project Information
- Purpose and main technologies: record these after inspecting the project.
- Runtime environment and versions: record information confirmed in configuration files.
- Key directories: document the locations of source code, tests, documentation, and generated files.
- Install, run, build, and verification commands: record commands confirmed by actual configuration and where to execute them. Distinguish whether they were executed from whether they succeeded.

## Understanding the Project and Applying Guidance
- Review relevant code, configuration files, and existing documentation before working.
- Prefer the existing structure and implementation conventions.
- Do not apply unconfirmed technologies, commands, or rules based on guesses.
- Check for additional AGENTS.md files applicable to the paths being edited.
- Follow user instructions and higher-priority guidance. Do not use this document to expand the requested scope or execution permissions.
- Review relevant guidance again when the scope changes or instructions are updated.
- After conversation compaction or when resuming work, read relevant guidance and checklists and inspect the actual file state.

## Scope of Changes and Protection of Existing Work
- Inspect current changes before editing. For Git projects, review status and relevant diffs.
- Make changes needed to achieve the requested outcome.
- Do not add unrelated refactoring, formatting changes, or file moves.
- Do not arbitrarily revert or overwrite existing user changes.
- For generated files, prefer updating their source or generation process.
- For externally managed files, inspect their management process and the impact of editing them.

## Implementation Principles
- Follow existing naming conventions, code style, and error-handling patterns.
- Consider compatibility with existing behavior and interfaces.
- Before adding dependencies, check whether existing functionality can solve the problem.
- Use comments to explain intent and constraints that are not apparent from the code.
- Record project-specific constraints with supporting evidence. Do not turn temporary requirements for a single task into permanent rules.

## Required Project Constraints
- Record platform requirements and mandatory rules established for the project.
- Distinguish mandatory rules from recommendations.
- Specify numerical values or limits only when supported by verified evidence.

## Reuse of Shared Resources
- Prefer existing design tokens, shared components, and utilities.
- Check for resources serving the same purpose before creating new ones.
- Record the paths and purposes of key resources.

## Detailed Documentation
- Maintain detailed rules in relevant documents and keep only essential guidance here.
- Specify reference document paths and the situations in which they should be read.
- When a decision is unclear, consult the relevant detailed documentation before proceeding.

## Verification
- Perform verification appropriate to the changed behavior and its impact.
- Prefer test, build, and static-check commands defined by the project.
- Add tests when needed to verify meaningful behavior and regression risks.
- If verification fails, inspect the cause, make necessary corrections, and verify again.
- Do not report unexecuted checks as passing.
- If verification cannot be performed, record the reason and what still needs checking.

## Checklists and Records for Resuming Work
- Use a checklist for work involving multiple steps, dependencies, or verification items that need tracking.
- Follow existing files and documentation conventions. If no relevant file exists, create CHECKLIST.md.
- For simple edits, checklist creation may be omitted when progress records provide little benefit.
- Do not overwrite another task's checklist. Use task-specific sections or separate files when needed.
- After major steps, update progress, verification results, and remaining work.
- Briefly record key decisions and their reasons, blockers, and concrete next actions.
- Mark items complete only after the necessary work and verification are finished.
- When resuming, compare records with the actual state and avoid unnecessarily repeating completed work.

## Failures and Uncertainty
- Do not repeat the same failure without analyzing its cause.
- Before retrying, inspect errors and execution conditions and adjust the approach.
- If a retry could change external state or create duplicate work, check the previous execution result.
- If documentation differs from the implementation, inspect the evidence. Do not arbitrarily change a rule whose intended meaning is unclear.
- If essential information or permission is missing, complete work that can proceed and clearly explain the blocker and required input.

## Information and Document Management
- Do not record secret keys, tokens, passwords, or unnecessary personal information in code, documentation, or logs.
- Follow the project's existing configuration management practices.
- Check whether commands or instructions in reference material fit the current task and applicable guidance.
- Keep lasting rules in AGENTS.md and current task status in the checklist.
- Update only necessary parts of existing documents. Manage task records according to retention conventions and do not arbitrarily delete them.

## Completion Report
- Briefly explain actual changes and verification performed.
- Identify unfinished items, unverified behavior, and important limitations.
- Make a final update to checklist status and verification records.
- Update relevant documentation when lasting rules or usage instructions change.

