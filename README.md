# Delivery

This is where we track every deliverable at Ighodalo Labs. One place. Everyone can see where things stand. No one has to chase anyone or explain themselves.

It is for everyone: developers, designers, marketers, content and social media people, operations, People and Culture, events, and founders.

## Quick start

1. Make a free GitHub account. Send your username to the Studio Lead. You will be added to the team.
2. Go to **Issues > New issue > Milestone**. Fill the form. It works on a phone.
3. When the work is ready, comment `/submit` and a link to the proof. Example: `/submit https://example.com/my-work`
4. The reviewer checks it and comments `/pass` or `/rework`. The system records the rest.

You never need to edit the board. It updates itself.

If the reviewer asks for rework, fix it and write `/submit` again. The item goes back to Ready for check. Only people on the team can create milestones. If a date in the form is wrong, edit the issue and fix it before the agreement is posted.

## What a milestone is

A milestone is one agreed unit of work. It has an owner, a due date and a clear definition of done. We agree the date together before work starts. If a date looks too tight, say so before we lock it.

The form asks for:

- **Venture** and **Role**, so we can see the work by venture and by function.
- **Deliverable**, **Why it matters**, **Definition of done** and **How it will be checked**.
- **Owner**. The person who does the work.
- **Reviewer** (optional). The person who checks it. Empty means the Studio Lead. It cannot be the owner.
- **Start date** (optional). Empty means today.
- **Due date**. A date like `2026-11-20` or a number of days like `14 days`.

## How pay works

- **Stipend.** Paid when the milestone passes its definition of done. Always.
- **On-Time Bonus.** Paid on top when the milestone is submitted by the agreed date and passes the first check.

The bonus never replaces the stipend. Missing the bonus does not reduce the stipend. Amounts are not kept here.

## The clock

- The clock starts on the agreed start date.
- The clock stops when the owner writes `/submit`. Review time on our side never counts against you.
- If Labs causes a delay (late access, late answers), the reviewer pauses the clock with `/pause N reason`. The agreed date moves by N days.
- If the scope grows, the reviewer moves the date later with `/rescope 2026-12-01 reason`.
- Once the date is agreed it is locked. The first date is always kept on record. Dates only move later, and only for a reason that is written down.

## Commands

Write the command on the first line of a comment on the milestone.

| Command | Who | What it does |
| --- | --- | --- |
| `/submit link or note` (or `/done`) | Owner | Work is ready for check. Stamps the date, saves the proof, marks it on time or late. |
| `/pass` (or `/approve`) | Reviewer | Records a pass. A first-check pass, on time, earns the On-Time Bonus. |
| `/rework` (or `/redo`) | Reviewer | Records that rework is needed. |
| `/pause N reason` | Reviewer | Pauses the clock for N days because of a Labs delay. |
| `/rescope DATE reason` | Reviewer | Moves the date later after a scope change. |

Nobody can check their own work. Only the Studio Lead (admin) can check a milestone they own.

The result is shown as labels: `submitted:on-time` or `submitted:late`, `check:first-pass` or `check:rework`, `bonus:earned` or `bonus:missed`, and `scope:changed`.

## Statuses

The system sets them. You do not need to move anything.

| Status | Meaning |
| --- | --- |
| Agreed | Scope and date agreed by both sides. |
| In progress | The owner is working on it. Also used after a rework request. |
| Ready for check | Submitted. Waiting for review. |
| Done | Passed the definition of done. |
| Blocked | Cannot move. The reason is in a comment. The Studio Lead sets this one by hand. |

## Examples by role

A good definition of done is a list of yes or no lines. Always add proof when you submit.

| Role | Example line in the definition of done | Proof to submit |
| --- | --- | --- |
| Engineering | Login works on a phone and a laptop. | Link to the pull request or the live page. |
| Design | Logo files (SVG and PNG) are in the shared folder. | Link to the folder. |
| Marketing | The campaign is live and the first report is shared. | Link to the campaign and the report. |
| Content | Five posts are published. | Links to the five posts. |
| Social media | Seven posts are scheduled and the replies are answered. | Link to the schedule and the account. |
| Operations | Every vendor on the list has a signed form. | Link to the tracker. |
| People and Culture | Interviews are done and notes are shared. | Link to the notes. |
| Events | Venue booked and the run sheet is shared. | Link to the booking and the run sheet. |
| Founder work | The pitch deck is final and sent to the reviewer. | Link to the deck. |

## Repeating work

Some work repeats every week, like content or social posts. Add it once to `.github/recurring.json`. A new milestone is created for it every Monday. Set `"enabled": true` when it is ready.

## This page is public

Anyone can read this repository. Do not write passwords, keys, client names or private strategy in a milestone. Describe the work in plain words. Put the private details in the proof link, in a place only the team can open.

## Good milestones

- Small. Two weeks at most.
- Every line in the definition of done can be answered with yes or no.
- One owner.
- A reviewer who is not the owner.
