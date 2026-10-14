# Independent Judgment

A free, open-source Codex skill for evidence-based judgment, realistic planning, and accountable follow-through. It helps an assistant challenge weak assumptions, track actual outputs, and adapt a plan without quietly abandoning the goal.

## Free and Open Source

This project is freely available under the [MIT License](LICENSE). Use, modify, and redistribute it under the license terms. MIT also permits commercial use and requires preserving the copyright and license notice.

This repository has no paid installation, subscription, or payment integration.

## When to Use It

- You want honest pushback instead of automatic agreement.
- A study plan or important commitment is drifting away from actual behavior.
- Unfinished tasks need a realistic next date and clear completion criteria.
- You need to separate facts, assumptions, uncertainty, and personal preferences.

The skill respects the user's final decisions. It does not treat insults, sleep deprivation, or unnecessary interrogation as accountability.

## Installation

The skill is located at `skills/independent-judgment/SKILL.md`.

Ask your skill installer to install `skills/independent-judgment` from this repository, or copy that folder into the skill directory supported by your environment. Confirm that it appears in the available skill list.

Repository: https://github.com/huoyanbo2006-ui/independent-judgment-skill

## Usage

```text
$independent-judgment
Review my study plan against what I actually completed. Identify the gaps,
then propose concrete tasks, estimated durations, and dates for postponed work.
```

Automatic selection depends on the client and its skill discovery behavior. For persistent defaults, add the relevant short rules to your personal or project instructions.

## Examples

**User:** "I barely studied for two days and cannot focus today."

**Expected behavior:** Accept the self-report, check the deadline and workload, identify the obstacle, and adjust the method or task placement. Explain the effect on the weekly goal. Do not automatically replace the entire day's work with a ten-minute exercise.

**User:** "I am going to sleep tonight. Plan tomorrow normally."

**Expected behavior:** Respect the explicit rest decision, plan around actual constraints, and do not invent a catch-up commitment or record rest as completed study.

## Limits

This is a workflow and assessment standard. It does not create an independent personality or guarantee grades, admission, or other outcomes. Structural validation checks the skill format, not the quality of every future judgment.

The repository contains only the reusable skill, usage documentation, and license. It does not contain private study records, account credentials, or personal timetables.
