# Task Checklist

This is a general-purpose example. At the start of a task, define the goal and completion criteria and replace action items with concrete steps for the actual work.

## Maintenance Rules
- Check an item only after the work and necessary verification are complete.
- Do not mark failed, blocked, or unexecuted items as complete.
- Remove unnecessary items or leave them unchecked and label them `Not applicable — reason`.
- Update the checklist after major steps or when the task status changes.
- Record verification commands or methods and actual results.
- When working on multiple tasks, keep records in task-specific sections or separate files.
- Record lasting project rules in AGENTS.md.

## Goal and Scope
- Goal:
- Work targets:
- Completion criteria:

## Current Status
- Phase: choose Preparation / Implementation / Verification / Complete / Blocked
- Next action:
- Blocker: record if applicable

## 1. Preliminary Review
- [ ] Reviewed applicable AGENTS.md files and relevant documentation.
- [ ] Inspected relevant code, configuration, and existing changes.
- [ ] Understood the requested outcome and scope of changes.
- [ ] Identified the required execution and verification methods.

## 2. Actions
<!-- Replace the items below with concrete steps for the actual task. Add or remove items as needed. -->
- [ ] Action item 1:
- [ ] Action item 2:
- [ ] Action item 3:

## 2-1. Orchestration
<!-- Use only for work involving the artwork role. Otherwise label `Not applicable — reason`. -->
- Job ID: (e.g., 20261109-001)
- [ ] Wrote the order in `orders/<job ID>.order.md` (items, sheet layout, style reference, output format).
- [ ] Sent ChatGPT the "Check the mailbox" notice. Time sent:
- [ ] Confirmed `deliveries/<job ID>/done.json`. Time confirmed:
- [ ] Cut and resized the artwork (original sheets kept).
- [ ] Added needed effects in code.
- [ ] Recorded the review in `reviews/<job ID>.review.md`. New job ID if rework is needed:
- [ ] Moved the finished job to `archive/`.
- [ ] Deployed changes to the test address and checked them.
- [ ] Asked the human about required decisions (release, drawing style, etc.). Answer:
- [ ] Release: deployed to the production app only after the human directly said "release it" in the conversation.

## 3. Verification
- [ ] Confirmed that the changed behavior meets the completion criteria.
- [ ] Checked affected existing behavior within the necessary scope.
- [ ] Resolved discovered issues and repeated necessary verification. If no issues were found, record this item as not applicable.

### Verification Record
| Check | Command or method | Result | Reason for not running or failure |
|---|---|---|---|
| | | | |

Distinguish Pass / Fail / Not run / Not applicable and include supporting evidence where needed.

## 4. Completion
- [ ] Updated necessary documentation.
- [ ] Performed a final review of the changes.
- [ ] Recorded unfinished items and remaining limitations.
- [ ] Explained the changes and verification results to the user.

## Key Decisions
- Decision:
- Reason:

## Remaining Work
<!-- Record 'None' if there is no follow-up work. -->
- [ ] Follow-up action:
