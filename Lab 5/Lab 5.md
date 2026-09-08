# Copilot Cowork: Transforming Weak Prompts into GCSE-Aligned Prompts

### **Lab Overview**

This hands-on lab walks through three common Cowork task types — meeting
prep, inbox triage, and performance forecasting. For each task type,
you'll run a deliberately weak, Goal-only prompt first, observe its
shortcomings, then rewrite the same request using the **GCSE framework**
(Goal, Context, Source, Expectation) and compare the two outputs side by
side. Each section ends with a review checklist so you can verify the
strong prompt actually produced a review-ready deliverable rather than
generic output. By the end, you'll have a repeatable framework to apply
to your own Cowork tasks going forward.

### **Learning Objectives**

By the end of this lab, you will be able to:

1.  **Identify** the typical failure modes of a bare, Goal-only prompt
    (ambiguity, missing sources, unpredictable format, no actionable
    output).

2.  **Apply** the GCSE framework (Goal, Context, Source, Expectation) to
    convert a vague request into a structured, delegation-ready prompt.

3.  **Direct Cowork to specific sources** (email threads, CRM records,
    decks, inbox, spreadsheets) rather than relying on generic
    knowledge.

4.  **Specify concrete expectations** — format, structure, length, and
    required actions — to produce outputs that are immediately usable (a
    brief, drafted replies, a report).

5.  **Evaluate** Cowork output against a review checklist to confirm it
    meets scope, structure, and audience requirements before acting on
    it.

6.  **Transfer** the GCSE pattern to your own real-world Cowork tasks
    beyond the three scenarios covered in this lab.

### **Lab Prerequisites**

- Access to **Microsoft 365 Copilot Cowork** with an active license

- A **Contoso-style test tenant or sandbox environment** (or your own
  working tenant, substituting real names/dates for the sample
  placeholders)

- At least one **email thread**, a **Dynamics 365 (or equivalent CRM)
  record**, and a **prior QBR deck** available in your mailbox/CRM for
  Task Type 1

- A mailbox with **unread mail from the current week** for Task Type 2
  (a backlog of at least 10–15 messages is recommended so
  grouping/triage is visible)

- A **Finance workbook** (or any budget-vs-actuals spreadsheet)
  accessible to Cowork for Task Type 3

- Familiarity with basic Cowork task creation (starting a new task,
  reviewing task output)

- No prior prompt-engineering experience required — the lab teaches the
  GCSE framework from scratch

## The GCSE framework 

GCSE is a simple pattern for delegated work. A bare Goal gets a generic
result; Goal + Context + Source + Expectation gets a finished,
review-ready output.

Element, what it means

- Goal: What you actually want to do (the task and its purpose).

- Context: The situation, audience, constraints, and tone.

- Source: Where Cowork should get the material (files, threads, systems,
  data).

- Expectation, the format, structure, length, and any concrete action to
  take.

## Exercise 1- Prep a customer meeting 

Scenario: You need to brief yourself before a client call.

### Task 1 — Run the weak prompt 

1.  Log in to +++https://copilot.microsoft.com/+++ with your lab
    credentials.\
    <img src="./Lab 5_media/media/image.png"
    style="width:5.32292in;height:4.14583in" />

2.  Enter your password.\
    <img src="./Lab 5_media/media/image2.png"
    style="width:5.125in;height:3.97917in" />

3.  Select Cowork tab.\
    <img src="./Lab 5_media/media/image3.png"
    style="width:6.25in;height:2.4375in" />

4.  In the chat box, paste the following prompt:\
    “Help me get ready for my Contoso meeting.”\
    <img src="./Lab 5_media/media/image4.png"
    style="width:6.25in;height:3.28125in" />

5.  Run this in Cowork now, then review the response:\
    <img src="./Lab 5_media/media/image5.png"
    style="width:6.25in;height:3.53125in" />

Note:

- Look for these typical weaknesses:

- It doesn't know which meeting, when, or what the objective is.

- It pulls nothing from your email, CRM, or past decks — so it stays
  generic.

- The output format is unpredictable: maybe a wall of tips, maybe
  questions back to you.

- No deliverable you can actually walk into the meeting with.

## Task 2 — Align the prompt with GCSE 

STRONG PROMPT: Goal + Context + Source + Expectation

1.  In the chat box, paste the following prompt:

“Prepare a 1-page brief for my 10 a.m. Contoso meeting (renew + upsell).
Ground it in our

email thread, the Dynamics 365 record, and last QBR deck. Give summary,
3 talking points,

2 risks, next step; draft a follow-up email.”\
<img src="./Lab 5_media/media/image6.png"
style="width:5.61615in;height:3.17708in" />

2.  Review the output:

<img src="./Lab 5_media/media/image7.png"
style="width:5.55177in;height:3.78125in" />

**<u>Element , In this prompt</u>**

- Goal , Prepare a 1-page brief for my 10 a.m. Contoso meeting.

- Context , The meeting is a renew + upsell conversation.

- Source , Our email thread, the Dynamics 365 record, and the last QBR
  deck.

- Expectation , Summary, 3 talking points, 2 risks, a next step — plus
  draft a follow-up email.

Note: Run the strong prompt in Cowork, then check the response against
this list:

- Is it a single-page brief, not a generic essay?

- Does it reference real details from your thread, CRM, and deck?

- Are there exactly 3 talking points, 2 risks, and a clear next step?

- Did it draft the follow-up email as an action, not just describe one?

## Exercise 2 — Triage your inbox 

Scenario: You want to clear a backlog with judgement, not just sort by
date.

### Task 1 — Run the weak prompt 

WEAK PROMPT (Goal only)

1.  In the chat box, paste the following prompt:

“Sort out my inbox.”\
<img src="./Lab 5_media/media/image8.png"
style="width:4.66238in;height:3.19792in" />

2.  Run this in Cowork now, then review the response:\
    <img src="./Lab 5_media/media/image9.png"
    style="width:5.23931in;height:4.69792in" />

### 

Note: Look for these typical weaknesses:

- “Sort out” is ambiguous — archive? label? reply? It may guess wrong
  and act on the wrong mail.

- No time window, so it may reach far back or touch messages you didn't
  mean.

- No grouping logic, so the result is a flat, hard-to-act-on list.

- No review step — it might send or delete without you seeing it first.

### Task 2 — Align the prompt with GCSE 

GOAL + CONTEXT + SOURCE + EXPECTATION

STRONG PROMPT (Goal + Context + Source + Expectation)

1.  In the chat box, paste the following prompt:

“Triage my unread mail from this week: group by project, flag anything
needing a reply

today, and draft responses to the top 5 for my review. Keep a neutral,
concise tone.”\
<img src="./Lab 5_media/media/imagea.png"
style="width:4.53125in;height:4.11734in" />

2.  Approve the email. Select Approve All to approve all the emails.\
    <img src="./Lab 5_media/media/imageb.png"
    style="width:6.25in;height:5.72917in" />

3.  Review the response:

<img src="./Lab 5_media/media/imagec.png"
style="width:6.5in;height:5.90625in" />

Note: Run the strong prompt in Cowork, then check the response against
this list:

- Did it limit itself to this week's unread mail only?

- Is the mail grouped by project rather than a flat list?

- Are same-day-reply items clearly flagged?

- Did it draft the top 5 replies and hold them for your review instead
  of sending?

## 

## Exercise 3 — Forecast performance 

Scenario: You want to turn raw data into a report leadership can use.

### Task 1 — Run the weak prompt 

WEAK PROMPT (Goal only)

1.  In the chat box, Upload the Contoso Q3 finance workbook and paste
    the following prompt:

“Look at our budget numbers.”

<img src="./Lab 5_media/media/imaged.png"
style="width:6.5in;height:2.21875in" />

2.  Run this in Cowork now, then review the response:\
    <img src="./Lab 5_media/media/imagee.png"
    style="width:6.25in;height:5.625in" />

Look for these typical weaknesses:

- No source file named, so it may describe budgeting in general instead
  of your numbers.

- No period or comparison, so “look at” produces observations, not
  analysis.

- No audience or deadline, so the output isn't shaped for a leadership
  review.

- You get raw analysis, not a report you can forward.

### Task 3 — Align the prompt with GCSE 

GOAL + CONTEXT + SOURCE + EXPECTATION

STRONG PROMPT (Goal + Context + Source + Expectation)

1.  In the Chatbox paste the following prompt:\
    \
    “Analyze Q3 budget vs. actuals in the Finance workbook, explain the
    top 3 variances, and build a short report for the leadership review
    on Friday. Flag anything off-track.”

<img src="./Lab 5_media/media/imagef.png"
style="width:6.5in;height:5.90625in" />

2.  Review the prompt:\
    <img src="./Lab 5_media/media/image10.png"
    style="width:6.25in;height:5.72917in" />

Element , In this prompt

- Goal , Analyze Q3 budget vs. actuals and forecast where things stand.

- Context , For the leadership review on Friday; flag anything
  off-track.

- Source , The Finance workbook (Q3 budget vs. actuals).

- Expectation , A short report explaining the top 3 variances.

<u>Note</u>: Run the strong prompt in Cowork, then check the response
against this list:

Did it use the actual Finance workbook rather than generic commentary?

Does it compare Q3 budget against actuals?

## Lab Summary

Across all three task types, the same pattern held: a bare Goal produced
a generic, unfinished result, while Goal + Context + Source +
Expectation produced a review-ready deliverable.

The GCSE quick-check for any Cowork task

- Goal — Have I said what I want done and why?

- Context — Have I given the situation, audience, tone, and constraints?

- Source — Have I told Cowork exactly where to get the material?

- Expectation — Have I specified the format, structure, length, and the
  action to take?
