# Delivery

This is where we track every deliverable at Ighodalo Labs. One place. Everyone can see where things stand. No one has to chase anyone or explain themselves.

## What a milestone is

A milestone is one agreed unit of work. It has an owner, a due date and a clear definition of done. We agree the date together before work starts. If a date looks too tight, say so before we lock it.

Create one with **Issues > New issue > Milestone**. The owner is assigned, the dates are recorded and the item appears on the project board on its own.

## How pay works

- **Stipend.** Paid when the milestone passes its definition of done. Always.
- **On-Time Bonus.** Paid on top when the milestone is submitted by the agreed date and passes the first check.

The bonus never replaces the stipend. Missing the bonus does not reduce the stipend.

## The clock

- The clock starts on the agreed start date.
- The clock stops when the owner writes `/submit`. Review time on our side never counts against you.
- If Labs causes a delay (late access, late answers, a scope change), the Studio Lead pauses the clock with `/pause N reason`. The agreed date moves by N days.
- Once the date is agreed it is locked. The first date is always kept on record.

## Commands

Write the command on the first line of a comment on the milestone.

| Command | Who | What it does |
| --- | --- | --- |
| `/submit` | Owner | Work is ready for check. Stamps the date. Marks it on time or late. |
| `/pause N reason` | Studio Lead | Pauses the clock for N days because of a Labs delay. |
| `/pass` | Studio Lead | Records a pass. A first-check pass, on time, earns the On-Time Bonus. |
| `/rework` | Studio Lead | Records that rework is needed. |

The result is shown as labels on the milestone: `submitted:on-time` or `submitted:late`, `check:first-pass` or `check:rework`, and `bonus:earned` or `bonus:missed`.

## Statuses

| Status | Meaning | Who moves it |
| --- | --- | --- |
| Backlog | Not agreed yet. | Anyone |
| Agreed | Scope and date agreed by both sides. | Studio Lead |
| In progress | The owner is working on it. | Owner |
| Ready for check | Submitted. Waiting for review. | Owner |
| Done | Passed the definition of done. | Studio Lead, after the check |
| Blocked | Cannot move. The reason is in a comment. | Anyone |

## First check

The reviewer follows the steps in **How it will be checked**. A pass on the first check, submitted by the agreed date, earns the On-Time Bonus. If rework is needed, the stipend is still paid once it passes.

## Good milestones

- Small. Two weeks at most.
- Every line in the definition of done can be tested with yes or no.
- One owner.
