SDAIA Academy GitHub: https://github.com/SDAIAAcademy

# My Final Project

## Project Name
Daily Manager Briefing Assistant

## Idea Selected
Choose one:
1. Meeting Follow-up Assistant

## Problem Statement
What problem does this assistant solve?
Managers spend a lot of time opening multiple reports and following up with teams to know what happened, what is overdue, and what needs a decision. This assistant turns KPI data and task status into a short daily briefing: key updates, decisions needed, overdue tasks, KPIs that dropped, and team follow-ups. The numbers are calculated by fixed rules, and the AI only writes the summary.

## Target Users
Who will use it?
Department managers and executives (e.g., COO-level) who need a quick daily overview instead of reviewing several dashboards.

## R-C-T-F Prompt
Paste your final prompt here.
Role: You are a daily briefing assistant for a department manager.

Context: You receive pre-calculated KPI results and task statuses as a text summary. All numbers were computed by fixed rules, not by you. KPI values are percentages unless a unit is given. The change value is the change compared with the previous period, not the gap from the target. The reader is a busy executive who wants a quick overview instead of opening several dashboards.

Task: Write a Daily Briefing with these sections:

Key updates today (KPIs that met their target or improved)
Decisions needed (max 3)
Overdue tasks (max 5)
KPIs that dropped, each with a short reason from the data
Team follow-ups required

Format: Short bullet points, professional tone, under 200 words. Use only the numbers in the input. If information is missing, write "Not available" and do not guess. If a section has no items, write "None". Output only the briefing, with no introduction or closing.

## Sample Input
Paste your sample input here.
Date: 29 September 2026

KPIs:

Patient satisfaction: 82% (target 90%). Changed by -8% compared with the previous period. Driver: Clinic B.
Appointment on-time rate: 91% (target 90%). Changed by +1% compared with the previous period. Driver: Not available.

Overdue tasks:

Monthly KPI report, owner: Team A, 3 days late
Update risk register, owner: Team C, 5 days late

Decisions pending:

Approve extra staff for Clinic B

Team follow-ups:

Team A to confirm report date

## Sample Output
Paste your AI-generated output here.
Daily Briefing: 29 Sep 2026

Key updates

Appointment on-time rate is 91%, above the 90% target (+1% vs previous period).

Decisions needed

Approve extra staff for Clinic B.

Overdue tasks

Monthly KPI report (Team A): 3 days late
Update risk register (Team C): 5 days late

KPIs that dropped

Patient satisfaction: 82% vs 90% target, down 8% vs previous period, driven by Clinic B.

Team follow-ups

Team A to confirm report date.

## Safety Checklist
Explain what you checked before using the output.
Checked that every number in the output matches the input data exactly.
Confirmed the AI did not invent any tasks, KPIs, or reasons.
Used sample/dummy data only, with no real patient or employee information.
Did not enter any confidential or sensitive data into the tool.
Reviewed the tone and wording before sharing with anyone.
Final decisions stay with the manager; the briefing is a summary, not advice.

## Reflection
What did you learn?
I learned that AI works best when the calculations are done by fixed rules and the AI only writes the summary. A clear prompt structure (R-C-T-F) with strict limits helped reduce made-up details, and checking the output against the input is an essential step.
