# Lab 2- Master the Prompting Techniques: Persona, Audience, Structured Output, Multi-Step

Lab Duration- 60 minutes

## Lab Overview

This lab teaches four prompting techniques that combine to produce
dramatically better results in Microsoft 365 Copilot Chat: assigning a
Persona, naming an Audience, requesting Structured output, and working
Multi-step across a single conversation. Each part has you run a plain
prompt first, then a technique-driven version of the same request, so
the improvement is visible side by side in one chat thread. The lab
closes with a capstone exercise that combines all four techniques, plus
an optional quick-practice challenge.

The lab covers:

- Persona --- telling Copilot what expertise to write from, and why
  \"senior financial analyst\" beats \"analyst\"

- Audience --- rewriting the same facts for different readers by naming
  who the response is for

- Structured output --- forcing a specific shape (fixed headings, a
  table with named columns) instead of accepting a loose paragraph

- Multi-step --- building a result across several turns in one chat
  rather than cramming everything into a single prompt

- A capstone conversation that layers Persona + Audience + Structured
  output + Multi-step together

## Lab Prerequisites

The document doesn\'t list an explicit \"Prerequisites\" section, but
based on the content, you should have:

- Access to Copilot Chat via m365.cloud.microsoft/chat, the Microsoft
  365 Copilot app, the Teams Copilot sidebar, or Edge

- Some sample text or a file to work with --- either pasted directly
  into the chat, or referenced with \"/\" if you have work-data access
  (a Microsoft 365 Copilot licence)

- No prior experience with Copilot or prompting is required

Learning Objectives

By the end of this lab, you will be able to combine four prompting
techniques --- Persona, Audience, Structured output, and Multi-step ---
to steer Microsoft 365 Copilot Chat toward results you can use
immediately.

Specifically, you will be able to:

- Assign a Persona to change the expertise Copilot\'s answers are
  written from

- Define an Audience so responses match who will actually read them

- Request Structured output to get results in a fixed, usable format
  (headings, tables, limits)

- Chain Multi-step prompts in one conversation, refining a result across
  several turns instead of one

- Combine all four techniques in a single flowing conversation

## Exercise 1 --- Persona: Change Who Copilot Is

Goal: See how assigning an expert role changes the quality and
specificity of an answer, using the same base request twice in one
thread.

1.  Log in to +++https://copilot.microsoft.com/+++ with your lab
    credentials.\
    ![](media/media/image.png){width="5.322916666666667in"
    height="4.145833333333333in"}

2.  Enter your password.\
    ![](media/media/image2.png){width="5.125in"
    height="3.9791666666666665in"}

3.  You will be redirected to the Copilot chat home page.

4.  Paste the following prompt:

+++Write three risks for a data migration project.+++\
![](media/media/image3.png){width="6.5in" height="3.2916666666666665in"}

5.  Review the output:\
    ![](media/media/image4.png){width="6.25in" height="4.28125in"}

6.  Now paste the following prompt and click Send:

+++Now answer again, but act as an experienced IT project manager who
has delivered many data migrations. Give the three most common risks
based on what actually goes wrong in practice.+++\
![](media/media/image5.png){width="6.5in" height="4.40625in"}

7.  Compare the two answers in your thread:\
    ![](media/media/image6.png){width="6.25in" height="4.28125in"}

What to notice: The persona version is more specific, practical, and
professional. The persona raised the quality by telling Copilot what
expertise to draw on --- and because both answers sit in the same chat,
the difference is easy to see.

Tip: Good personas combine a role + experience level. \"Act as a senior
financial analyst\" beats \"Act as an analyst.\"

## Exercise 2 --- Audience: Change Who It\'s For

Goal: Rewrite the same facts for two different readers and see how
naming the audience changes tone and complexity, with no extra
explaining from you.

1.  Paste the following prompt in the Copilot chat box:

+++Technical Info: The migration will move all records from the legacy
on-premise SQL database to the new cloud data warehouse, with validation
checks at each phase and a rollback plan if data integrity thresholds
are not met.

Rewrite the paragraph above for a non-technical steering committee. Keep
the facts unchanged, avoid jargon, and keep it under 60 words.+++\
![](media/media/image7.png){width="6.5in" height="4.416666666666667in"}

2.  Review the output:\
    ![](media/media/image8.png){width="6.25in"
    height="4.270833333333333in"}

3.  Then, in the same chat, ask for a different audience:

+++Now rewrite the same paragraph for the technical engineering team who
will do the work. Keep the technical detail.+++\
![](media/media/image9.png){width="6.5in" height="4.447916666666667in"}

4.  Review the output & Compare both the outputs:\
    ![](media/media/imagea.png){width="6.25in" height="2.375in"}

What to notice: Same facts, two very different results. Naming the
audience changed the vocabulary, tone, and level of detail.

Tip: Combine Persona + Audience for the strongest results: \"Act as a
change manager. Write an announcement for frontline staff who are
nervous about the new system.\"

## Exercise 3 --- Structured Output: Control the Shape

Goal: Tell Copilot the exact format you want instead of accepting
whatever paragraph comes back, so results are immediately usable.

### Task 1: Summarise a thread into a fixed structure

1.  Paste the following prompt in the Copilot chat box:\
    +++Summarise this using exactly this structure:\
    • Decision made:\
    • Still open:\
    • Action items (with owner):\
    • Deadline+++

Note: Paste a long email thread (or any long discussion) into the chat.
The reference email thread file is given in lab files\
![](media/media/imageb.png){width="6.5in" height="4.333333333333333in"}

2.  Check that the output follows your headings precisely.\
    \
    ![](media/media/imagec.png){width="6.25in"
    height="4.208333333333333in"}

### Task 2: Force a table

1.  Paste the following prompt in the Copilot chat box:

+++Find the three biggest variances between forecast and actuals in the
data above. Present as a table with three columns: Item, Variance, and
Likely Cause. One sentence per cause.+++

Note: Upload the Zava Retail forecast vs actual doc after pasting the
prompt.\
![](media/media/imaged.png){width="6.5in" height="4.34375in"}

2.  Review the output and note how you get a ready-to-use table.

What to notice: When you specify the format, you get consistent, usable
output every time. Common structures to request: bullet points, tables,
numbered steps, headings, and word/count limits.\
\
![](media/media/imagee.png){width="6.5in" height="4.375in"}

## Exercise 4 --- Multi-Step: Build It Up in One Conversation

Goal: Refine a result across several turns instead of trying to get it
perfect in one prompt --- the most valuable habit in this lab.

### Task 1- Generate an outline

1.  Paste the following prompt in the Copilot chat box:

+++Draft the outline for a 6-slide steering-committee presentation on
our data migration project. Include a title slide, four content slides
(Goal, Approach, Risks, Asks), and a closing slide with next steps.+++\
\
Note: Upload the Zava Retail- Data migration overview document from the
lab files provided.\
![](media/media/imagef.png){width="6.5in" height="3.90625in"}

2\. The first draft will be about 80% right --- that\'s expected:\
![](media/media/image10.png){width="6.5in" height="4.322916666666667in"}

### Step 2 --- Refine one part:

1.  Paste the following prompt to refine the output:\
    +++Rework the Risks slide. Cut it to 3 bullets, plain English, no
    jargon.+++\
    ![](media/media/image11.png){width="6.25in" height="4.15625in"}

2.  Review the output:\
    ![](media/media/image12.png){width="6.25in" height="4.1875in"}

### Step 3 --- Adjust tone:

1.  Paste the following prompt to refine the output:\
    +++Rewrite the closing slide in a more confident, action-oriented
    tone.+++\
    ![](media/media/image13.png){width="6.25in"
    height="4.145833333333333in"}

2.  Review the output:\
    ![](media/media/image14.png){width="6.25in" height="4.1875in"}

### Step 4 --- Polish:

1.  Paste the following prompt to refine the output:\
    +++Now suggest a stronger, punchier title for slide 1, and give me
    three options.+++\
    ![](media/media/image15.png){width="6.25in"
    height="4.208333333333333in"}

2.  What to notice: Each step built on the last because the whole
    conversation stays in context. You never tried to get it perfect in
    one prompt --- you steered it there.

![](media/media/image16.png){width="6.5in" height="4.3125in"}

Tip: The fastest improvements are one-word follow-ups: \"Warmer.\"
\"Shorter.\" \"Simpler.\" \"More formal.\" Just type them as their own
message.

Handy for apps: Once your slide outline is right, copy it into
PowerPoint (or ask PowerPoint\'s own Copilot to build from it). Copilot
Chat is where you think and draft; the apps are where you produce the
file.

## Exercise 5 --- Capstone: Put It All Together

Goal: Combine all four techniques in a single flowing conversation.

**[Persona + Audience (one prompt):]{.underline}**

1.  Paste the following prompt in the Copilot Chat box:\
    +++Act as an experienced project manager. Draft a one-page project
    brief for a non-technical steering committee.+++\
    ![](media/media/image17.png){width="6.25in" height="1.21875in"}

2.  Review the output:\
    ![](media/media/image18.png){width="6.25in"
    height="4.260416666666667in"}

**[Structured output (next prompt):]{.underline}**

1.  Paste the following prompt in the Copilot Chat box:\
    +++Use these sections: Goal, Approach, Risks, Milestones, Asks.
    Plain English, no marketing tone.+++\
    ![](media/media/image19.png){width="6.25in"
    height="0.9479166666666666in"}

2.  Review the output:\
    ![](media/media/image1a.png){width="6.25in"
    height="4.177083333333333in"}

**[Multi-step (separate prompts, one at a time):]{.underline}**

1.  Paste the following prompt in the Copilot Chat box:

+++Make the Risks section a 3-bullet list.+++\
![](media/media/image1b.png){width="6.5in" height="0.875in"}

2.  Review the output:\
    \
    ![](media/media/image1c.png){width="6.25in"
    height="3.5520833333333335in"}

3.  Paste the following prompt in the Copilot Chat box

+++Rewrite the Goal as one confident sentence.+++

![](media/media/image1d.png){width="6.5in" height="4.333333333333333in"}

4.  Review the output:\
    ![](media/media/image1e.png){width="6.25in"
    height="2.9166666666666665in"}

5.  Paste the following prompt in the Copilot Chat box

+++Now turn the whole thing into a 200-word executive summary, then list
any open questions at the end.+++\
![](media/media/image1f.png){width="6.5in" height="4.302083333333333in"}

6.  Review the output:\
    \
    ![](media/media/image20.png){width="6.25in"
    height="4.177083333333333in"}

Scroll back through your chat --- you can see all four techniques
working together in one thread.

## Lab Summary

This lab walks through four prompting techniques in Microsoft 365
Copilot Chat, each demonstrated by running a plain prompt first and a
technique-driven version second, in the same thread, so the improvement
is easy to see. Exercise 1 shows that assigning a Persona (\"act as an
experienced IT project manager\") produces more specific, practical
answers than a generic request. Exercise 2 shows that naming an Audience
changes vocabulary and tone without changing the underlying facts.
Exercise 3 shows that requesting Structured output --- fixed headings
for a thread summary, or a named-column table for a variance analysis
--- makes results immediately usable instead of a loose paragraph.
Exercise 4 shows that Multi-step iteration (generate, refine one part,
adjust tone, polish) beats trying to get a perfect result in a single
prompt, because the whole conversation stays in context.

The capstone in Exercise 5 layers all four techniques into one flowing
conversation --- Persona and Audience in the opening prompt, Structured
output in the next, and Multi-step refinements after that --- and the
optional Exercise 6 challenge checks that the techniques can be
recognized and applied without a script. The core takeaway: a persona
raises expertise, an audience sets tone and complexity, structured
output makes results usable, and multi-step iteration is what Copilot
Chat is built for, since the whole conversation stays in view. Copilot
Chat is where you draft and think; move the polished result into Word,
Excel, or PowerPoint to finish the file.
