# Lab 3- Prompt Engineering across the Microsoft Copilot Apps: Grounding & the Surface Rule

Lab Duration- 60 minutes

## Lab Overview

This lab teaches two habits that turn vague Copilot results into useful
ones: writing prompts with the GCSE framework, and grounding those
prompts in a real source. Each exercise moves to a different Copilot app
--- Word, Excel, PowerPoint, Outlook, and Teams --- so you also learn
the Surface Rule: do the task on the app where the finished thing lives.
The lab closes with a bonus exercise on cleaning messy data before
analysis.

The lab covers:

- GCSE --- a four-part recipe for a strong prompt: Goal, Context,
  Source, and Expectations

- Four core techniques --- zero-shot, few-shot, role, and
  chain-of-thought --- and when to reach for each

- Grounding --- using the / command to point Copilot at a real file,
  email, or meeting instead of letting it invent

- The Surface Rule --- matching each task to the app that owns the
  finished thing: documents in Word, numbers in Excel, slides in
  PowerPoint, email in Outlook, meetings in Teams

- A full grounded workflow that carries one project\'s content from
  notes, into a Word brief, into a PowerPoint deck

## Lab Prerequisites

The document doesn\'t list an explicit "Prerequisites" section
separately from setup, but based on the content, you should have:

- A work or school Microsoft 365 account with a Copilot licence

- Access to Word, Excel, PowerPoint, Outlook, and Teams, desktop or web

- One sample document saved in your OneDrive or SharePoint --- any real
  project note works, or create a short file called Discovery notes with
  a few paragraphs of project background

- About 15 minutes of undisturbed time for each exercise

- No prior experience with Copilot or prompting is required

## Learning Objectives

By the end of this lab, you will be able to write focused, grounded
prompts across the Microsoft Copilot apps and choose the right app for
each task.

Specifically, you will be able to:

- Name the four parts of the GCSE framework and explain what each one
  adds

- Rewrite a vague prompt into a clear GCSE prompt

- Choose zero-shot, few-shot, role, or chain-of-thought prompting for
  the task in front of you

- Use the / command to ground the Source part of a prompt in a real
  file, email, or meeting

- Apply the Surface Rule to pick the correct Copilot app for a given
  goal

- Chain a grounded prompt across apps, carrying one project\'s content
  from notes to a finished deck

## Exercise 1 --- Word: A Grounded GCSE Brief

Goal: Turn rough notes into a clean one-page brief using a full GCSE
prompt, then refine it with iteration.

1.  Log in to +++https://copilot.microsoft.com/+++ with your lab
    credentials.\
    ![](media/media/image.png){width="5.322916666666667in"
    height="4.145833333333333in"}

2.  Enter your password.\
    ![](media/media/image2.png){width="5.125in"
    height="3.9791666666666665in"}

3.  From the Copilot home page, select Apps. Select Word.\
    ![](media/media/image3.png){width="6.25in"
    height="2.4479166666666665in"}

4.  Select Create Blank Document.\
    ![](media/media/image4.png){width="6.25in" height="1.1875in"}

5.  Open Copilot- the icon in the left margin of a blank line.\
    ![](media/media/image5.png){width="6.25in" height="3.6875in"}

6.  Select the + icon to upload the file: Discovery notes, provided in
    the lab files. Paste the following prompt and press Enter:

+++Draft a one-page project brief based on /Discovery notes. Sections:
Goal, Approach, Risks, Milestones, Asks. Plain English, no marketing
tone.+++\
![](media/media/image6.png){width="3.02208552055993in"
height="4.65625in"}

7.  Review the draft:

![](media/media/image7.png){width="6.5in" height="3.3333333333333335in"}

8.  Practise the iteration habit. Select one paragraph and select Edit
    with Copilot.\
    ![](media/media/image8.png){width="6.25in" height="4.59375in"}

9.  Paste the following prompt in description box:\
    \
    +++Rewrite this paragraph in a warmer, more confident tone. Keep the
    facts unchanged.+++\
    ![](media/media/image9.png){width="6.25in"
    height="4.916666666666667in"}

10. Review the output and Select Done.\
    ![](media/media/imagea.png){width="6.25in"
    height="5.020833333333333in"}

11. Download the brief document.\
    ![](media/media/imageb.png){width="6.25in" height="2.125in"}

What to notice: Grounding the Source in your own notes gave you a brief
about your project, not generic filler --- and the short follow-up
prompts adjusted tone in seconds, without you retyping the whole
request.

Tip: The brief is a finished document, so it belongs on the Word
surface. Word Copilot also shows exactly what changed and lets you
revert, which makes it the easiest place to build the iteration habit.
Save this brief --- you will ground Exercise 3 in it.

## Exercise 2 --- Excel: Ask Your Data a Question

Goal: Use GCSE prompts to pull insight from a clean table instead of
hunting through cells.

Note: Excel Copilot works best on a tidy table --- clear headers, no
blank rows, one topic per column. If your data is messy, clean it first
(see the bonus exercise at the end of this lab).

### Task 1: Find the biggest variances

1.  From the Copilot chat home page, open Excel.\
    ![](media/media/imagec.png){width="6.25in" height="2.59375in"}

2.  Select Create a blank workbook.\
    ![](media/media/imaged.png){width="6.25in"
    height="1.1145833333333333in"}

3.  Open Copilot from right corner.\
    ![](media/media/imagee.png){width="6.25in"
    height="2.7083333333333335in"}

4.  Upload the Forecast vs Actual sheet and Paste the following prompt:

+++Find the three biggest variances between forecast and actuals in this
sheet. Explain each in one sentence and propose a likely driver.+++\
![](media/media/imagef.png){width="4.489583333333333in"
height="4.805317147856518in"}

5.  Review the output and Select Done.\
    ![](media/media/image10.png){width="6.25in"
    height="2.6145833333333335in"}

### Task 2: Generate a formula

1.  Paste the following prompt:

+++Generate the formula to count unique customers who appear in column B
but not column F.+++\
![](media/media/image11.png){width="5.208333333333333in" height="6.5in"}

2.  Review the output:\
    ![](media/media/image12.png){width="4.864583333333333in"
    height="6.25in"}

### Task 3: Reason through a calculation

1.  Paste the following prompt:

+++Work out which region missed target and by how much, using this
sheet. Let\'s think step by step, then give the final figure.+++\
![](media/media/image13.png){width="3.5323184601924758in"
height="4.791666666666667in"}

2.  Review the output and select Done.\
    ![](media/media/image14.png){width="6.25in"
    height="2.4791666666666665in"}

### Task 4: Get an expert read

1.  Paste the following prompt:

+++Act as a financial analyst. Summarise what this data means for next
quarter from this sheet, in three bullet points for a non-financial
manager.+++\
![](media/media/image15.png){width="3.179420384951881in"
height="4.458333333333333in"}

2.  Review the output and select Done.\
    ![](media/media/image16.png){width="6.25in" height="2.5in"}

### Task 5: Build the right chart

1.  Paste the following prompt:

+++Build a chart showing monthly trend by region for column G. Pick the
chart type that best fits this data.+++\
![](media/media/image17.png){width="3.8229166666666665in"
height="5.360673665791776in"}

2.  Review the output and select Done.\
    ![](media/media/image18.png){width="6.25in"
    height="2.5729166666666665in"}

What to notice: The same open table served every prompt in this
exercise. What changed the result each time was the technique --- a
direct ask, a step-by-step instruction for the calculation, and a named
role for the expert summary.

Tip: For a tricky calculation, add "let\'s think step by step" before
asking for the final answer --- it noticeably improves accuracy on
multi-stage maths.

## 

## Exercise 3 --- PowerPoint: From Document to Deck

Goal: Turn the Word brief from Exercise 1 into a draft deck by grounding
the Source in that file.

1.  From the Copilot chat home page, open PowerPoint presentation.\
    ![](media/media/image19.png){width="6.25in"
    height="2.5833333333333335in"}

2.  Select +Create with Copilot.\
    ![](media/media/image1a.png){width="6.25in"
    height="0.9895833333333334in"}

3.  Paste the following prompt. Upload the brief you saved in Exercise 1
    to fill the Source slot.

+++Create a 6-slide presentation from /Project brief. Audience is the
steering committee. Title slide, 4 content slides covering Goal ·
Approach · Risks · Asks, and a closing slide with next steps.+++\
![](media/media/image1b.png){width="4.114583333333333in" height="6.5in"}

4.  Review the output:\
    ![](media/media/image1c.png){width="6.25in"
    height="2.9895833333333335in"}

5.  Sharpen the framing with a role. Paste the following prompt:

+++Act as a communications advisor to the board. Rewrite the Risks slide
so a busy executive grasps each risk in one line.+++\
![](media/media/image1d.png){width="2.855469160104987in"
height="4.604166666666667in"}

6.  Review the output:\
    ![](media/media/image1e.png){width="6.25in"
    height="2.9270833333333335in"}

7.  Simplify a busy slide. Paste the following prompt:

+++Redesign this slide to be cleaner and more readable. Reduce the text
and use a clearer structure.+++\
![](media/media/image1f.png){width="4.0625in" height="6.5in"}

8.  Review the output:\
    ![](media/media/image20.png){width="6.25in"
    height="3.0208333333333335in"}

9.  Tighten it further if needed. Paste the following prompt:

+++Make this slide simpler --- cut the bullets to 3, larger font, plain
English.+++\
![](media/media/image21.png){width="4.114583333333333in" height="6.5in"}

10. Review the output:\
    ![](media/media/image22.png){width="6.25in"
    height="3.4791666666666665in"}

What to notice: An empty PowerPoint prompt gives you a generic deck. A
prompt grounded in your own brief gives you your deck --- with your
goal, your risks, and your asks.

Tip: Keep nudging with short iteration prompts rather than rewriting the
whole request each time --- "simpler," "cut to 3 bullets," and "larger
font" all landed as one-line follow-ups above.

## Exercise 4 --- Outlook & Teams: The Daily Wins

Goal: Handle everyday email and meeting work with grounded, zero-shot
prompts, then match your own voice with a few examples.

Outlook --- summarize and reply

1.  From Copilot Chat open Outlook.\
    ![](media/media/image23.png){width="6.25in"
    height="2.4791666666666665in"}

2.  Open Copilot chat.\
    ![](media/media/image24.png){width="6.25in"
    height="1.3854166666666667in"}

3.  Upload the email thread document --- this is your Source --- and
    paste the following prompt:

+++Summarise this long thread in 4 bullets. What was decided, what\'s
open, who owns what next?+++\
![](media/media/image25.png){width="4.3125in"
height="4.69633530183727in"}

4.  Review the output:\
    ![](media/media/image26.png){width="5.697916666666667in"
    height="6.25in"}

5.  Draft a reply. Paste the following prompt:

+++Reply saying I\'ll attend, propose Thursday afternoon as an
alternative, and keep the tone warm.+++\
![](media/media/image27.png){width="4.40625in"
height="5.026508092738408in"}

6.  Review the output:\
    ![](media/media/image28.png){width="3.9479166666666665in"
    height="4.362339238845144in"}

## Bonus Exercise --- Cleaning Messy Data First

Goal: Prepare disorganised data so Excel Copilot can analyse it
properly.

Excel Copilot is not yet ideal for very large or messy datasets. When
data is disorganised, do a cleaning pass in Copilot Chat before
analysing.

1.  From Copilot chat, open Excel.\
    ![](media/media/imagec.png){width="6.25in" height="2.59375in"}

2.  Open Copilot from right corner.\
    ![](media/media/imagee.png){width="6.25in"
    height="2.7083333333333335in"}

3.  Upload the file: Messy Data Sample--- this is your Source.

Paste it into Copilot Chat along with the following prompt:

+++What formatting inconsistencies should I fix before analysing
this?+++\
![](media/media/image29.png){width="4.833333333333333in" height="6.5in"}

4.  Review the output:\
    ![](media/media/image2a.png){width="6.25in" height="2.3125in"}

## Lab Summary

This lab walks through the GCSE framework and the Surface Rule across
five Microsoft Copilot surfaces, each exercise grounding a prompt in a
real file, email, or meeting rather than letting Copilot invent.
Exercise 1 shows that a full GCSE prompt --- Goal, Context, Source, and
Expectations --- grounded in a Discovery notes file produces a usable
first draft that iteration then refines line by line. Exercise 2 shows
that the same open table can answer very different requests depending on
the technique layered on top: a direct question, step-by-step reasoning
for a calculation, or a named role for an expert summary. Exercise 3
shows that grounding the Source in the Word brief from Exercise 1 ---
rather than starting from a blank PowerPoint --- is what turns a generic
deck into your deck, and that role prompts and iteration then sharpen it
slide by slide. Exercise 4 shows that the same fast, one-word nudges
that refine a slide also refine an email reply, and that grounding works
just as well against a person\'s name or a meeting as it does against a
file. The bonus exercise shows that a short cleaning pass in Copilot
Chat is worth running before asking Excel Copilot to analyse messy data.

The core takeaway: Goal is essential, but Context, Source, and
Expectations are what sharpen an answer --- and grounding the Source
with / is the single biggest lever for making that answer about your
work instead of generic filler. Once a prompt is grounded, the Surface
Rule decides where you run it: do the task on the app where the finished
thing lives, and expect about 80% on the first pass, then iterate the
rest of the way in seconds.
