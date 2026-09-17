# Exercise 1 -Weak vs. Briefed Prompts: The Prompting Framework in Microsoft 365 Copilot Chat

*Duration -- 60 minutes*

## Exercise Overview

This exercise teaches one idea that improves almost every result you get
from Microsoft 365 Copilot Chat: the difference between a weak prompt
and a briefed prompt. You work through three real-world scenarios in
Copilot Chat (microsoft365.com/chat), running a weak prompt first, then
a briefed version of the same request, and comparing the two.

This exercise covers:

- The five elements of a well-briefed prompt --- Task, Source, Scope,
  Audience & purpose, and Format & length

- Why weak prompts (\"Summarise my week\") produce vague, unsourced,
  hard-to-verify answers

- How to use the \"/\" picker to point Copilot precisely at a project,
  meeting series, or person

- Three hands-on scenarios: catching up after time away, finding themes
  across a meeting series, and locating a specific concern someone
  raised

- How to refine results with follow-up prompts instead of accepting the
  first answer

- A bonus technique for chaining multiple deliverables (doc → slide
  outline → email) from a single briefed prompt

## Prerequisites

- A browser open to microsoft365.com/chat, or the Microsoft 365 Copilot
  app open to Chat

- A work or school account (not a personal account) signed in, with
  access to work mode / grounded chat --- the mode that can see your
  files, emails, meetings, and Teams chats

- At least one real project, meeting series, or colleague in mind ---
  the exercise works far better with your own content than with made-up
  examples

- No prior experience with Copilot or prompting is required

## Learning Objectives

By the end of this exercise, you will be able to explain the difference
between a weak prompt and a briefed prompt, and confidently apply the
five-part briefing framework to get faster, more trustworthy results out
of Microsoft 365 Copilot Chat.

Specifically, you will be able to:

- Explain the five elements of a briefed prompt --- Task, Source, Scope,
  Audience & purpose, Format & length

- Use the \"/\" picker to reference a project, meeting series, or person
  precisely instead of typing names freehand

- Turn scattered emails, meetings, and Teams chats into a short, dated,
  sourced summary

- Prompt Copilot to surface themes, decisions, and open questions across
  a recurring meeting series, while flagging uncertainty instead of
  guessing

- Retrieve a specific quoted concern, with date and link, so it can be
  verified and acted on

- Refine an initial answer with targeted follow-up prompts rather than
  accepting the first response as final

## Step 0 --- Uploading documents in OneDrive

1.  Log in to https://onedrive.live.com/login with your lab credentials.

![](./Lab_1_media/media/image1.png){width="6.302083333333333in"
height="4.916666666666667in"}

2.  Enter your password.

![](./Lab_1_media/media/image2.png){width="6.302083333333333in"
height="4.895833333333333in"}

3.  Upload the following documents in the OneDrive:

![](./Lab_1_media/media/image3.png){width="6.302083333333333in"
height="2.3333333333333335in"}

## Step 1 --- Catch Up on a Project After Time Away

  -----------------------------------------------------------------------
  Goal: Turn two weeks of scattered emails, meetings, and chats into a
  clear, 200-word briefing you can read in under a minute.

  -----------------------------------------------------------------------

4.  Navigate to https://copilot.microsoft.com/. In the left navigation
    pane, select Chat.

![](./Lab_1_media/media/image4.png){width="6.302083333333333in"
height="3.1979166666666665in"}

5.  Paste the prompt exactly as written and review the output:

  -----------------------------------------------------------------------
  What is happening with my Zava Retail project?

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image5.png){width="6.302083333333333in"
height="2.75in"}

  -----------------------------------------------------------------------
  Notice: Copilot may ask which project you mean or guess wrong; the
  result is usually broad and undated; it likely pulls from only one
  source (often just email) and misses meetings and chats.

  -----------------------------------------------------------------------

6.  Review the output:

![](./Lab_1_media/media/image6.png){width="6.302083333333333in"
height="4.229166666666667in"}

7.  Now run the briefed version, replacing the bracketed part with your
    own project name:

+-----------------------------------------------------------------------+
| Catch me up on ZavaRetail across the last two weeks --- pull from     |
| emails, meetings, and Teams chats.                                    |
|                                                                       |
| Tell me:                                                              |
|                                                                       |
| 1\. What changed                                                      |
|                                                                       |
| 2\. Who decided what                                                  |
|                                                                       |
| 3\. What is currently blocked                                         |
|                                                                       |
| Keep it to about 200 words, plain English, bullet points. List your   |
| sources at the end so I can click through.                            |
+-----------------------------------------------------------------------+

![](./Lab_1_media/media/image7.png){width="6.302083333333333in"
height="2.21875in"}

8.  When you type \"/\", Copilot opens a picker. Start typing the
    project, file, person, or meeting name and select it from the list
    --- this is more reliable than typing the name freehand.

![](./Lab_1_media/media/image8.png){width="6.302083333333333in"
height="2.9375in"}

![](./Lab_1_media/media/image9.png){width="6.302083333333333in"
height="2.6041666666666665in"}

9.  Review the output:

![](./Lab_1_media/media/image10.png){width="6.302083333333333in"
height="4.208333333333333in"}

10. Compare the two results by using the prompt. Paste the following:

  -----------------------------------------------------------------------
  Is it clearly about the right project? Can you tell what\'s new vs.
  old? Are decisions and owners named? Is it short enough to actually
  read? Can you verify it (are sources listed)?

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image11.png){width="6.302083333333333in"
height="4.229166666666667in"}

11. Review the output:

![](./Lab_1_media/media/image12.png){width="6.302083333333333in"
height="4.239583333333333in"}

  -----------------------------------------------------------------------
  Checkpoint: You should now have a tight, dated, sourced summary of your
  project. If the briefed result is still weak, the usual cause is a
  vague \"/\" reference --- re-pick the project from the slash menu and
  run it again.

  -----------------------------------------------------------------------

## Step 2 --- Find the Themes Across a Meeting Series

  -----------------------------------------------------------------------
  Goal: Rise above individual meetings to spot recurring themes,
  decisions made, and questions still hanging.

  -----------------------------------------------------------------------

12. Navigate to the Copilot chat box and paste the following weak
    prompt:

  -----------------------------------------------------------------------
  Summarise my meetings.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image13.png){width="6.302083333333333in"
height="2.90625in"}

13. Review the output:

![](./Lab_1_media/media/image14.png){width="6.302083333333333in"
height="4.177083333333333in"}

14. Now run the briefed version, replacing the meeting series name.
    Paste the following prompt:

+-----------------------------------------------------------------------+
| Summarise the three biggest themes from my meetings over the last     |
| month.                                                                |
|                                                                       |
| For each theme, tell me:                                              |
|                                                                       |
| • What the theme is (one line)                                        |
|                                                                       |
| • Any decisions made, and who owns the follow-up                      |
|                                                                       |
| • Any questions still unresolved                                      |
|                                                                       |
| Plain English. Do not invent anything --- if a decision is unclear,   |
| say so rather than guessing.                                          |
+-----------------------------------------------------------------------+

![](./Lab_1_media/media/image15.png){width="6.302083333333333in"
height="1.6041666666666667in"}

15. Review the output and compare with the output in the above step:

![](./Lab_1_media/media/image16.png){width="6.302083333333333in"
height="4.28125in"}

16. Refine with a follow-up. Paste the following prompt:

  -----------------------------------------------------------------------
  Draft a 4-line email to the group summarising the decisions we made
  this month.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image17.png){width="6.302083333333333in"
height="0.8958333333333334in"}

17. Review the output:

![](./Lab_1_media/media/image18.png){width="6.302083333333333in"
height="3.6458333333333335in"}

## Step 3 --- Find a Specific Concern Someone Raised

  -----------------------------------------------------------------------
  Goal: Locate a precise piece of information buried in your history, get
  it quoted accurately, and get a link so you can act on it.

  -----------------------------------------------------------------------

18. Navigate to the Copilot chat box and paste the following weak
    prompt:

  -----------------------------------------------------------------------
  Did anyone have concerns?

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image19.png){width="6.302083333333333in"
height="1.3333333333333333in"}

19. Review the output:

![](./Lab_1_media/media/image20.png){width="6.302083333333333in"
height="3.4270833333333335in"}

20. Now run the briefed version, replacing the person and topic. Paste
    the following prompt:

+-----------------------------------------------------------------------+
| Find any email or Teams chat from Jordan Lee where they raised a      |
| concern about brand icons in the meeting notes                        |
|                                                                       |
| For each one:                                                         |
|                                                                       |
| • Quote the exact sentence where they raised the concern              |
|                                                                       |
| • Give me the date                                                    |
|                                                                       |
| • Give me the link so I can open it                                   |
|                                                                       |
| If you find nothing, tell me plainly rather than stretching to find   |
| something.                                                            |
+-----------------------------------------------------------------------+

![](./Lab_1_media/media/image21.png){width="6.302083333333333in"
height="2.1354166666666665in"}

21. Review the output:

![](./Lab_1_media/media/image22.png){width="6.302083333333333in"
height="4.0in"}

22. Compare the two results and answer the questions: Did it search the
    right person? On the right topic? Both email and chat covered? Exact
    words, not a paraphrase? Can you act on it (date and link present)?
    Honest about misses?

23. Refine with a follow-up. Paste the following:

  -----------------------------------------------------------------------
  Draft a short, friendly reply to Jordan Lee acknowledging the concern
  and proposing a call.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image23.png){width="6.302083333333333in"
height="1.25in"}

24. Review the output:

![](./Lab_1_media/media/image24.png){width="6.302083333333333in"
height="2.7604166666666665in"}

## Step 4 --- Bonus: Cross-App Drafting in One Prompt

  -----------------------------------------------------------------------
  Goal: Chain several deliverables together from a single briefed prompt.

  -----------------------------------------------------------------------

Once you\'re comfortable with the three scenarios above, try this
advanced briefed prompt:

25. Navigate to the Copilot chat box and paste the following prompt:

+-----------------------------------------------------------------------+
| Draft a one-pager based on Zava Retail project, then:                 |
|                                                                       |
| \- Turn it into a 5-slide outline (title + 3 bullets per slide)       |
|                                                                       |
| \- Write a short executive email summary (under 120 words)            |
|                                                                       |
| Audience is senior leadership. Keep the tone confident and plain.     |
| Flag anything in the brief that seems unclear or incomplete.          |
+-----------------------------------------------------------------------+

![](./Lab_1_media/media/image25.png){width="6.302083333333333in"
height="1.6041666666666667in"}

26. Review the output:

![](./Lab_1_media/media/image26.png){width="6.302083333333333in"
height="4.239583333333333in"}

## Exercise Summary

This exercise walks you through the difference between weak and briefed
prompts in Microsoft 365 Copilot Chat using three real-world scenarios.
You start by running a weak prompt (\"What\'s happening with my
project?\") and observing its vague, unsourced output, then re-run the
same request as a briefed prompt that names the project, sets a two-week
scope, lists sources, and asks for a structured 200-word answer ---
producing a result you can use immediately.

From there, you apply the same weak-vs-briefed comparison to spotting
themes across a recurring meeting series, discovering that a well-formed
brief doesn\'t just improve the summary, it changes the kind of output
you get (themes and decisions instead of a flat recap). The third
scenario pushes into retrieval: finding a specific concern a colleague
raised, quoted exactly, dated, and linked --- a task the weak prompt
fails at almost completely because precision (who, what, and answer
format) is essential.

Throughout, the exercise reinforces a five-part framework --- Task,
Source, Scope, Audience & purpose, Format & length --- remembered as the
sentence \"\[Task\] using \[Source\], covering \[Scope\], for
\[Audience/purpose\], as \[Format & length\],\" along with the \"/\"
picker for precise references and the habit of refining answers with
follow-up prompts rather than accepting the first response. A bonus step
shows how a single briefed prompt can chain multiple deliverables (a
doc, a slide outline, and an email) together. The core habit: before you
send, spend five seconds turning a weak prompt into a briefed one.

# Exercise 2 --- Master the Prompting Techniques: Persona, Audience, Structured Output, Multi-Step

*Duration -- 60 minutes*

## Exercise Overview

This exercise teaches four prompting techniques that combine to produce
dramatically better results in Microsoft 365 Copilot Chat: assigning a
Persona, naming an Audience, requesting Structured output, and working
Multi-step across a single conversation. Each part has you run a plain
prompt first, then a technique-driven version of the same request, so
the improvement is visible side by side in one chat thread. The exercise
closes with a capstone step that combines all four techniques.

This exercise covers:

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

## Prerequisites

- Access to Copilot Chat via m365.cloud.microsoft/chat, the Microsoft
  365 Copilot app, the Teams Copilot sidebar, or Edge

- Some sample text or a file to work with --- either pasted directly
  into the chat, or referenced with \"/\" if you have work-data access
  (a Microsoft 365 Copilot licence)

- No prior experience with Copilot or prompting is required

## Learning Objectives

By the end of this exercise, you will be able to combine four prompting
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

## Step 1 --- Persona: Change Who Copilot Is

  -----------------------------------------------------------------------
  Goal: See how assigning an expert role changes the quality and
  specificity of an answer, using the same base request twice in one
  thread.

  -----------------------------------------------------------------------

1.  Log in to https://copilot.microsoft.com/ with your lab credentials.

![](./Lab_1_media/media/image27.png){width="6.302083333333333in"
height="4.90625in"}

2.  Enter your password.

![](./Lab_1_media/media/image28.png){width="6.302083333333333in"
height="4.895833333333333in"}

3.  You will be redirected to the Copilot chat home page.

4.  Paste the following prompt:

  -----------------------------------------------------------------------
  Write three risks for a data migration project.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image29.png){width="6.302083333333333in"
height="3.1875in"}

5.  Review the output:

![](./Lab_1_media/media/image30.png){width="6.302083333333333in"
height="4.322916666666667in"}

6.  Now paste the following prompt and click Send:

  -----------------------------------------------------------------------
  Now answer again, but act as an experienced IT project manager who has
  delivered many data migrations. Give the three most common risks based
  on what actually goes wrong in practice.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image31.png){width="6.302083333333333in"
height="4.270833333333333in"}

7.  Compare the two answers in your thread:

![](./Lab_1_media/media/image32.png){width="6.302083333333333in"
height="4.3125in"}

  -----------------------------------------------------------------------
  What to notice: The persona version is more specific, practical, and
  professional. The persona raised the quality by telling Copilot what
  expertise to draw on --- and because both answers sit in the same chat,
  the difference is easy to see.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Tip: Good personas combine a role + experience level. \"Act as a senior
  financial analyst\" beats \"Act as an analyst.\"

  -----------------------------------------------------------------------

## Step 2 --- Audience: Change Who It\'s For

  -----------------------------------------------------------------------
  Goal: Rewrite the same facts for two different readers and see how
  naming the audience changes tone and complexity, with no extra
  explaining from you.

  -----------------------------------------------------------------------

8.  Paste the following prompt in the Copilot chat box:

+-----------------------------------------------------------------------+
| Technical Info: The migration will move all records from the legacy   |
| on-premise SQL database to the new cloud data warehouse, with         |
| validation checks at each phase and a rollback plan if data integrity |
| thresholds are not met.                                               |
|                                                                       |
| Rewrite the paragraph above for a non-technical steering committee.   |
| Keep the facts unchanged, avoid jargon, and keep it under 60 words.   |
+-----------------------------------------------------------------------+

![](./Lab_1_media/media/image33.png){width="6.302083333333333in"
height="4.28125in"}

9.  Review the output:

![](./Lab_1_media/media/image34.png){width="6.302083333333333in"
height="4.302083333333333in"}

10. Then, in the same chat, ask for a different audience:

  -----------------------------------------------------------------------
  Now rewrite the same paragraph for the technical engineering team who
  will do the work. Keep the technical detail.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image35.png){width="6.302083333333333in"
height="4.3125in"}

11. Review the output and compare both the outputs:

![](./Lab_1_media/media/image36.png){width="6.302083333333333in"
height="2.3854166666666665in"}

  -----------------------------------------------------------------------
  What to notice: Same facts, two very different results. Naming the
  audience changed the vocabulary, tone, and level of detail.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Tip: Combine Persona + Audience for the strongest results: \"Act as a
  change manager. Write an announcement for frontline staff who are
  nervous about the new system.\"

  -----------------------------------------------------------------------

## Step 3 --- Structured Output: Control the Shape

  -----------------------------------------------------------------------
  Goal: Tell Copilot the exact format you want instead of accepting
  whatever paragraph comes back, so results are immediately usable.

  -----------------------------------------------------------------------

### Task 1: Summarise a thread into a fixed structure

12. Paste the following prompt in the Copilot chat box:

+-----------------------------------------------------------------------+
| Summarise this using exactly this structure:                          |
|                                                                       |
| • Decision made:                                                      |
|                                                                       |
| • Still open:                                                         |
|                                                                       |
| • Action items (with owner):                                          |
|                                                                       |
| • Deadline                                                            |
+-----------------------------------------------------------------------+

  -----------------------------------------------------------------------
  Note: Paste a long email thread (or any long discussion) into the chat.
  The reference email thread file is given in the lab files.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image37.png){width="6.302083333333333in"
height="4.197916666666667in"}

13. Check that the output follows your headings precisely.

![](./Lab_1_media/media/image38.png){width="6.302083333333333in"
height="4.239583333333333in"}

### Task 2: Force a table

14. Paste the following prompt in the Copilot chat box:

  -----------------------------------------------------------------------
  Find the three biggest variances between forecast and actuals in the
  data above. Present as a table with three columns: Item, Variance, and
  Likely Cause. One sentence per cause.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Note: Upload the Zava Retail forecast vs actual doc after pasting the
  prompt.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image39.png){width="6.302083333333333in"
height="4.21875in"}

15. Review the output and note how you get a ready-to-use table.

  -----------------------------------------------------------------------
  What to notice: When you specify the format, you get consistent, usable
  output every time. Common structures to request: bullet points, tables,
  numbered steps, headings, and word/count limits.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image40.png){width="6.302083333333333in"
height="4.25in"}

## Step 4 --- Multi-Step: Build It Up in One Conversation

  -----------------------------------------------------------------------
  Goal: Refine a result across several turns instead of trying to get it
  perfect in one prompt --- the most valuable habit in this exercise.

  -----------------------------------------------------------------------

### Task 1 --- Generate an outline

16. Paste the following prompt in the Copilot chat box:

  -----------------------------------------------------------------------
  Draft the outline for a 6-slide steering-committee presentation on our
  data migration project. Include a title slide, four content slides
  (Goal, Approach, Risks, Asks), and a closing slide with next steps.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Note: Upload the Zava Retail -- Data migration overview document from
  the lab files provided.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image41.png){width="6.302083333333333in"
height="3.7916666666666665in"}

17. The first draft will be about 80% right --- that\'s expected:

![](./Lab_1_media/media/image42.png){width="6.302083333333333in"
height="4.197916666666667in"}

### Task 2 --- Refine one part

18. Paste the following prompt to refine the output:

  -----------------------------------------------------------------------
  Rework the Risks slide. Cut it to 3 bullets, plain English, no jargon.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image43.png){width="6.302083333333333in"
height="4.1875in"}

19. Review the output:

![](./Lab_1_media/media/image44.png){width="6.302083333333333in"
height="4.21875in"}

### Task 3 --- Adjust tone

20. Paste the following prompt to refine the output:

  -----------------------------------------------------------------------
  Rewrite the closing slide in a more confident, action-oriented tone.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image45.png){width="6.302083333333333in"
height="4.177083333333333in"}

21. Review the output:

![](./Lab_1_media/media/image46.png){width="6.302083333333333in"
height="4.21875in"}

### Task 4 --- Polish

22. Paste the following prompt to refine the output:

  -----------------------------------------------------------------------
  Now suggest a stronger, punchier title for slide 1, and give me three
  options.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image47.png){width="6.302083333333333in"
height="4.239583333333333in"}

  -----------------------------------------------------------------------
  What to notice: Each step built on the last because the whole
  conversation stays in context. You never tried to get it perfect in one
  prompt --- you steered it there.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image48.png){width="6.302083333333333in"
height="4.1875in"}

  -----------------------------------------------------------------------
  Tip: The fastest improvements are one-word follow-ups: \"Warmer.\"
  \"Shorter.\" \"Simpler.\" \"More formal.\" Just type them as their own
  message.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Handy for apps: Once your slide outline is right, copy it into
  PowerPoint (or ask PowerPoint\'s own Copilot to build from it). Copilot
  Chat is where you think and draft; the apps are where you produce the
  file.

  -----------------------------------------------------------------------

## Step 5 --- Capstone: Put It All Together

  -----------------------------------------------------------------------
  Goal: Combine all four techniques in a single flowing conversation.

  -----------------------------------------------------------------------

Persona + Audience (one prompt):

23. Paste the following prompt in the Copilot Chat box:

  -----------------------------------------------------------------------
  Act as an experienced project manager. Draft a one-page project brief
  for a non-technical steering committee.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image49.png){width="6.302083333333333in"
height="1.2291666666666667in"}

24. Review the output:

![](./Lab_1_media/media/image50.png){width="6.302083333333333in"
height="4.291666666666667in"}

Structured output (next prompt):

25. Paste the following prompt in the Copilot Chat box:

  -----------------------------------------------------------------------
  Use these sections: Goal, Approach, Risks, Milestones, Asks. Plain
  English, no marketing tone.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image51.png){width="6.302083333333333in"
height="0.9583333333333334in"}

26. Review the output:

![](./Lab_1_media/media/image52.png){width="6.302083333333333in"
height="4.208333333333333in"}

Multi-step (separate prompts, one at a time):

27. Paste the following prompt in the Copilot Chat box:

  -----------------------------------------------------------------------
  Make the Risks section a 3-bullet list.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image53.png){width="6.302083333333333in"
height="0.84375in"}

28. Review the output:

![](./Lab_1_media/media/image54.png){width="6.302083333333333in"
height="3.5833333333333335in"}

29. Paste the following prompt in the Copilot Chat box:

  -----------------------------------------------------------------------
  Rewrite the Goal as one confident sentence.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image55.png){width="6.302083333333333in"
height="4.197916666666667in"}

30. Review the output:

![](./Lab_1_media/media/image56.png){width="6.302083333333333in"
height="2.9375in"}

31. Paste the following prompt in the Copilot Chat box:

  -----------------------------------------------------------------------
  Now turn the whole thing into a 200-word executive summary, then list
  any open questions at the end.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image57.png){width="6.302083333333333in"
height="4.166666666666667in"}

32. Review the output:

![](./Lab_1_media/media/image58.png){width="6.302083333333333in"
height="4.21875in"}

  -----------------------------------------------------------------------
  Scroll back through your chat --- you can see all four techniques
  working together in one thread.

  -----------------------------------------------------------------------

## Exercise Summary

This exercise walks through four prompting techniques in Microsoft 365
Copilot Chat, each demonstrated by running a plain prompt first and a
technique-driven version second, in the same thread, so the improvement
is easy to see. Step 1 shows that assigning a Persona (\"act as an
experienced IT project manager\") produces more specific, practical
answers than a generic request. Step 2 shows that naming an Audience
changes vocabulary and tone without changing the underlying facts. Step
3 shows that requesting Structured output --- fixed headings for a
thread summary, or a named-column table for a variance analysis ---
makes results immediately usable instead of a loose paragraph. Step 4
shows that Multi-step iteration (generate, refine one part, adjust tone,
polish) beats trying to get a perfect result in a single prompt, because
the whole conversation stays in context.

The capstone in Step 5 layers all four techniques into one flowing
conversation --- Persona and Audience in the opening prompt, Structured
output in the next, and Multi-step refinements after that. The core
takeaway: a persona raises expertise, an audience sets tone and
complexity, structured output makes results usable, and multi-step
iteration is what Copilot Chat is built for, since the whole
conversation stays in view. Copilot Chat is where you draft and think;
move the polished result into Word, Excel, or PowerPoint to finish the
file.

# Exercise 3 --- Prompt Engineering across the Microsoft Copilot Apps: Grounding & the Surface Rule

*Duration -- 60 minutes*

## Exercise Overview

This exercise teaches two habits that turn vague Copilot results into
useful ones: writing prompts with the GCSE framework, and grounding
those prompts in a real source. Each step moves to a different Copilot
app --- Word, Excel, PowerPoint, Outlook, and Teams --- so you also
learn the Surface Rule: do the task on the app where the finished thing
lives. The exercise closes with a bonus step on cleaning messy data
before analysis.

This exercise covers:

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

## Prerequisites

- A work or school Microsoft 365 account with a Copilot licence

- Access to Word, Excel, PowerPoint, Outlook, and Teams, desktop or web

- One sample document saved in your OneDrive or SharePoint --- any real
  project note works, or create a short file called Discovery notes with
  a few paragraphs of project background

- About 15 minutes of undisturbed time for each step

- No prior experience with Copilot or prompting is required

## Learning Objectives

By the end of this exercise, you will be able to write focused, grounded
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

## Step 1 --- Word: A Grounded GCSE Brief

  -----------------------------------------------------------------------
  Goal: Turn rough notes into a clean one-page brief using a full GCSE
  prompt, then refine it with iteration.

  -----------------------------------------------------------------------

1.  Log in to https://copilot.microsoft.com/ with your lab credentials.

![](./Lab_1_media/media/image59.png){width="6.302083333333333in"
height="4.90625in"}

2.  Enter your password.

![](./Lab_1_media/media/image28.png){width="6.302083333333333in"
height="4.895833333333333in"}

3.  From the Copilot home page, select Apps. Select Word.

![](./Lab_1_media/media/image60.png){width="6.302083333333333in"
height="2.46875in"}

4.  Select Create Blank Document.

![](./Lab_1_media/media/image61.png){width="6.302083333333333in"
height="1.1979166666666667in"}

5.  Open Copilot --- the icon in the left margin of a blank line.

![](./Lab_1_media/media/image62.png){width="6.302083333333333in"
height="3.71875in"}

6.  Select the + icon to upload the file: Discovery notes, provided in
    the lab files. Paste the following prompt and press Enter:

  -----------------------------------------------------------------------
  Draft a one-page project brief based on /Discovery notes. Sections:
  Goal, Approach, Risks, Milestones, Asks. Plain English, no marketing
  tone.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image63.png){width="6.302083333333333in"
height="9.708333333333334in"}

7.  Review the draft:

![](./Lab_1_media/media/image64.png){width="6.302083333333333in"
height="3.2291666666666665in"}

8.  Practise the iteration habit. Select one paragraph and select Edit
    with Copilot.

![](./Lab_1_media/media/image65.png){width="6.302083333333333in"
height="4.635416666666667in"}

9.  Paste the following prompt in the description box:

  -----------------------------------------------------------------------
  Rewrite this paragraph in a warmer, more confident tone. Keep the facts
  unchanged.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image66.png){width="6.302083333333333in"
height="4.958333333333333in"}

10. Review the output and select Done.

![](./Lab_1_media/media/image67.png){width="6.302083333333333in"
height="5.0625in"}

11. Download the brief document.

![](./Lab_1_media/media/image68.png){width="6.302083333333333in"
height="2.1458333333333335in"}

  -----------------------------------------------------------------------
  What to notice: Grounding the Source in your own notes gave you a brief
  about your project, not generic filler --- and the short follow-up
  prompts adjusted tone in seconds, without you retyping the whole
  request.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Tip: The brief is a finished document, so it belongs on the Word
  surface. Word Copilot also shows exactly what changed and lets you
  revert, which makes it the easiest place to build the iteration habit.
  Save this brief --- you will ground Step 3 in it.

  -----------------------------------------------------------------------

## Step 2 --- Excel: Ask Your Data a Question

  -----------------------------------------------------------------------
  Goal: Use GCSE prompts to pull insight from a clean table instead of
  hunting through cells.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Note: Excel Copilot works best on a tidy table --- clear headers, no
  blank rows, one topic per column. If your data is messy, clean it first
  (see the bonus step at the end of this exercise).

  -----------------------------------------------------------------------

### Task 1: Find the biggest variances

12. From the Copilot chat home page, open Excel.

![](./Lab_1_media/media/image69.png){width="6.302083333333333in"
height="2.6145833333333335in"}

13. Select Create a blank workbook.

![](./Lab_1_media/media/image70.png){width="6.302083333333333in"
height="1.125in"}

14. Open Copilot from the right corner.

![](./Lab_1_media/media/image71.png){width="6.302083333333333in"
height="2.7395833333333335in"}

15. Upload the Forecast vs Actual sheet and paste the following prompt:

  -----------------------------------------------------------------------
  Find the three biggest variances between forecast and actuals in this
  sheet. Explain each in one sentence and propose a likely driver.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image72.png){width="6.302083333333333in"
height="6.739583333333333in"}

16. Review the output and select Done.

![](./Lab_1_media/media/image73.png){width="6.302083333333333in"
height="2.6354166666666665in"}

### Task 2: Generate a formula

17. Paste the following prompt:

  -----------------------------------------------------------------------
  Generate the formula to count unique customers who appear in column B
  but not column F.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image74.png){width="6.302083333333333in"
height="7.864583333333333in"}

18. Review the output:

![](./Lab_1_media/media/image75.png){width="6.302083333333333in"
height="8.09375in"}

### Task 3: Reason through a calculation

19. Paste the following prompt:

  -----------------------------------------------------------------------
  Work out which region missed target and by how much, using this sheet.
  Let\'s think step by step, then give the final figure.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image76.png){width="6.302083333333333in"
height="8.541666666666666in"}

20. Review the output and select Done.

![](./Lab_1_media/media/image77.png){width="6.302083333333333in"
height="2.5in"}

### Task 4: Get an expert read

21. Paste the following prompt:

  -----------------------------------------------------------------------
  Act as a financial analyst. Summarise what this data means for next
  quarter from this sheet, in three bullet points for a non-financial
  manager.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image78.png){width="6.302083333333333in"
height="8.822916666666666in"}

22. Review the output and select Done.

![](./Lab_1_media/media/image79.png){width="6.302083333333333in"
height="2.5208333333333335in"}

### Task 5: Build the right chart

23. Paste the following prompt:

  -----------------------------------------------------------------------
  Build a chart showing monthly trend by region for column G. Pick the
  chart type that best fits this data.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image80.png){width="6.302083333333333in"
height="8.822916666666666in"}

24. Review the output and select Done.

![](./Lab_1_media/media/image81.png){width="6.302083333333333in"
height="2.59375in"}

  -----------------------------------------------------------------------
  What to notice: The same open table served every prompt in this step.
  What changed the result each time was the technique --- a direct ask, a
  step-by-step instruction for the calculation, and a named role for the
  expert summary.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Tip: For a tricky calculation, add \"let\'s think step by step\" before
  asking for the final answer --- it noticeably improves accuracy on
  multi-stage maths.

  -----------------------------------------------------------------------

## Step 3 --- PowerPoint: From Document to Deck

  -----------------------------------------------------------------------
  Goal: Turn the Word brief from Step 1 into a draft deck by grounding
  the Source in that file.

  -----------------------------------------------------------------------

25. From the Copilot chat home page, open PowerPoint presentation.

![](./Lab_1_media/media/image82.png){width="6.302083333333333in"
height="2.6041666666666665in"}

26. Select +Create with Copilot.

![](./Lab_1_media/media/image83.png){width="6.302083333333333in"
height="1.0in"}

27. Paste the following prompt. Upload the brief you saved in Step 1 to
    fill the Source slot.

  -----------------------------------------------------------------------
  Create a 6-slide presentation from /Project brief. Audience is the
  steering committee. Title slide, 4 content slides covering Goal ·
  Approach · Risks · Asks, and a closing slide with next steps.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image84.png){width="6.302083333333333in"
height="9.958333333333334in"}

28. Review the output:

![](./Lab_1_media/media/image85.png){width="6.302083333333333in"
height="3.0104166666666665in"}

29. Sharpen the framing with a role. Paste the following prompt:

  -----------------------------------------------------------------------
  Act as a communications advisor to the board. Rewrite the Risks slide
  so a busy executive grasps each risk in one line.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image86.png){width="6.302083333333333in"
height="10.15625in"}

30. Review the output:

![](./Lab_1_media/media/image87.png){width="6.302083333333333in"
height="2.9583333333333335in"}

31. Simplify a busy slide. Paste the following prompt:

  -----------------------------------------------------------------------
  Redesign this slide to be cleaner and more readable. Reduce the text
  and use a clearer structure.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image88.png){width="6.302083333333333in"
height="10.0625in"}

32. Review the output:

![](./Lab_1_media/media/image89.png){width="6.302083333333333in"
height="3.0416666666666665in"}

33. Tighten it further if needed. Paste the following prompt:

  -----------------------------------------------------------------------
  Make this slide simpler --- cut the bullets to 3, larger font, plain
  English.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image90.png){width="6.302083333333333in"
height="9.947916666666666in"}

34. Review the output:

![](./Lab_1_media/media/image91.png){width="6.302083333333333in"
height="3.5104166666666665in"}

  -----------------------------------------------------------------------
  What to notice: An empty PowerPoint prompt gives you a generic deck. A
  prompt grounded in your own brief gives you your deck --- with your
  goal, your risks, and your asks.

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Tip: Keep nudging with short iteration prompts rather than rewriting
  the whole request each time --- \"simpler,\" \"cut to 3 bullets,\" and
  \"larger font\" all landed as one-line follow-ups above.

  -----------------------------------------------------------------------

## Step 4 --- Outlook & Teams: The Daily Wins

  -----------------------------------------------------------------------
  Goal: Handle everyday email and meeting work with grounded, zero-shot
  prompts, then match your own voice with a few examples.

  -----------------------------------------------------------------------

Outlook --- summarize and reply

35. From Copilot Chat open Outlook.

![](./Lab_1_media/media/image92.png){width="6.302083333333333in"
height="2.5104166666666665in"}

36. Open Copilot chat.

![](./Lab_1_media/media/image93.png){width="6.302083333333333in"
height="1.3958333333333333in"}

37. Upload the email thread document --- this is your Source --- and
    paste the following prompt:

  -----------------------------------------------------------------------
  Summarise this long thread in 4 bullets. What was decided, what\'s
  open, who owns what next?

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image94.png){width="6.302083333333333in"
height="6.864583333333333in"}

38. Review the output:

![](./Lab_1_media/media/image95.png){width="6.302083333333333in"
height="6.90625in"}

39. Draft a reply. Paste the following prompt:

  -----------------------------------------------------------------------
  Reply saying I\'ll attend, propose Thursday afternoon as an
  alternative, and keep the tone warm.

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image96.png){width="6.302083333333333in"
height="7.1875in"}

40. Review the output:

![](./Lab_1_media/media/image97.png){width="6.302083333333333in"
height="6.958333333333333in"}

## Step 5 --- Bonus: Cleaning Messy Data First

  -----------------------------------------------------------------------
  Goal: Prepare disorganised data so Excel Copilot can analyse it
  properly.

  -----------------------------------------------------------------------

Excel Copilot is not yet ideal for very large or messy datasets. When
data is disorganised, do a cleaning pass in Copilot Chat before
analysing.

41. From Copilot chat, open Excel.

![](./Lab_1_media/media/image69.png){width="6.302083333333333in"
height="2.6145833333333335in"}

42. Open Copilot from the right corner.

![](./Lab_1_media/media/image71.png){width="6.302083333333333in"
height="2.7395833333333335in"}

43. Upload the file: Messy Data Sample --- this is your Source. Paste it
    into Copilot Chat along with the following prompt:

  -----------------------------------------------------------------------
  What formatting inconsistencies should I fix before analysing this?

  -----------------------------------------------------------------------

![](./Lab_1_media/media/image98.png){width="6.302083333333333in"
height="8.46875in"}

44. Review the output:

![](./Lab_1_media/media/image99.png){width="6.302083333333333in"
height="2.3333333333333335in"}

## Exercise Summary

This exercise walks through the GCSE framework and the Surface Rule
across five Microsoft Copilot surfaces, each step grounding a prompt in
a real file, email, or meeting rather than letting Copilot invent. Step
1 shows that a full GCSE prompt --- Goal, Context, Source, and
Expectations --- grounded in a Discovery notes file produces a usable
first draft that iteration then refines line by line. Step 2 shows that
the same open table can answer very different requests depending on the
technique layered on top: a direct question, step-by-step reasoning for
a calculation, or a named role for an expert summary. Step 3 shows that
grounding the Source in the Word brief from Step 1 --- rather than
starting from a blank PowerPoint --- is what turns a generic deck into
your deck, and that role prompts and iteration then sharpen it slide by
slide. Step 4 shows that the same fast, one-word nudges that refine a
slide also refine an email reply, and that grounding works just as well
against a person\'s name or a meeting as it does against a file. The
bonus step shows that a short cleaning pass in Copilot Chat is worth
running before asking Excel Copilot to analyse messy data.

The core takeaway: Goal is essential, but Context, Source, and
Expectations are what sharpen an answer --- and grounding the Source
with / is the single biggest lever for making that answer about your
work instead of generic filler. Once a prompt is grounded, the Surface
Rule decides where you run it: do the task on the app where the finished
thing lives, and expect about 80% on the first pass, then iterate the
rest of the way in seconds.
