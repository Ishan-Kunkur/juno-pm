## Diagnostic Diff · Juno RAG Lab

_Working notes from Module 3 Lab 1. Do not paste over `03-rag-prd/prd.md`. That file comes from the AI PRD Builder._

**Lovable prototype:** https://lovable.dev/projects/d7e7a2bb-0ce8-48c9-92cb-848e0411dfc7?magic_link=mc_11af906a-1998-4cc7-852a-837f20cb835c

### Before - Quality Mode (no strategy)

Inability to export CSV from 'Quarterly Reports' page leads to lost hours and manual workarounds
Users attempting to export data to CSV from the 'Quarterly Reports' tab experience indefinite loading times (5 minutes) followed by a crash without an error message. This forces them to resort to inefficient manual methods like screenshots, leading to significant time loss and frustration.

Negative
Reliability
P1
Quality 90
This request demonstrates high Problem Clarity, clearly describing a critical bug that directly impacts a user's workflow. Evidence Quality is strong, with a detailed first-hand account. Requirement Specificity is excellent, pointing to a specific function ('Export to CSV') and its problematic behavior. No anti-patterns are present. Without strategy document, priority reflects request quality, not strategic alignment.

I try to click ‘Export to CSV’ because I need to pivot this in Excel. It spins for like 5 minutes and then just crashes. No error message. Just blank. I’ve lost hours because of this. I end up just taking screenshots of the table, which is stupid.

Backed by 1 sources

New blue navigation bar is visually uncomfortable for users
The recently implemented blue navigation bar is described as 'really bright' and 'hurts my eyes bright', indicating a negative user experience related to visual comfort.

Negative
User Experience
P2
Quality 70
This request has good Problem Clarity, describing a clear discomfort. Evidence Quality is solid with a direct quote. Requirement Specificity is moderate, asking 'Can we change that?' without a specific solution, but the problem is clear. No anti-patterns detected. Without strategy document, priority reflects request quality, not strategic alignment.

The first thing I notice is that the new blue navigation bar is really bright, like hurts my eyes bright. Can we change that?

Backed by 1 sources

User expresses a desire for a dark mode feature
A user explicitly states they would 'love a dark mode', suggesting a demand for interface customization to improve visual comfort or preference.

Neutral
User Experience
P3
Quality 45
Problem Clarity is low; while a solution is suggested, the underlying problem (e.g., eye strain, personal preference, specific environment) isn't explicitly detailed, making it a solution-first ask. Evidence Quality is minimal, being a single, brief statement. Requirement Specificity is vague, simply stating 'I'd love a dark mode' without further context or details. No anti-patterns are present. Without strategy document, priority reflects request quality, not strategic alignment.

Oh, and I’d love a dark mode.

Backed by 1 sources

### After - Strategy Mode (with RocketShip Strategy One-Pager)

Critical CSV export crashes causing significant workflow disruption
Users are experiencing complete system crashes when attempting to export data to CSV, leading to lost work and frustration. This directly impacts their ability to use the platform as intended for data analysis in tools like Excel.

Negative
Reliability First
P0
Alignment 100
This is a P0 reliability bug, directly cited in the strategy: 'The platform must work. Every export, every report, every load.' and 'If a request fixes a workflow blocker (CSV crash, permission error) -> P0/P1'. It also aligns with the NORTH STAR to be 'the fastest, most reliable analytics platform for mid-market data teams who currently rely on Excel + Salesforce.'

I try to click ‘Export to CSV’ because I need to pivot this in Excel. It spins for like 5 minutes and then just crashes. No error message. Just blank. I’ve lost hours because of this.

Backed by 1 sources

Request for dark mode and aesthetic adjustments to UI colors
A user found the new blue navigation bar 'really bright' and 'hurts my eyes', leading to a request for a dark mode and general aesthetic adjustments.

Neutral
N/A
P3
Alignment 0
The strategy explicitly states 'WHAT WE ARE NOT DOING THIS QUARTER: Aesthetic refreshes (dark mode, color palette tweaks, "make it pop" UI work)'. This request conflicts with current strategic priorities.

Not recommended — This request is explicitly listed under 'WHAT WE ARE NOT DOING THIS QUARTER' in the strategy document.

The first thing I notice is that the new blue navigation bar is really bright, like hurts my eyes bright. Can we change that? ... Oh, and I’d love a dark mode.

Backed by 1 sources

### Takeaway

> Optimization is evident

