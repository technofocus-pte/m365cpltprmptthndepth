**Lab 4- Prompt Engineering for Agent Building: Build a Mini Agent with
Microsoft Copilot Agent Builder**

**Lab Duration- 45--60 minutes**

## Lab Overview

In this lab you will build a small, working AI agent using Microsoft
Copilot Agent Builder --- without writing any code. More importantly,
you will learn how the words you give an agent shape everything it does.
You will build the same agent, called Study Buddy, three times, changing
only its prompting each time, so you can see cause and effect between
your prompts and the agent\'s behavior.

The lab covers:

- The difference between a system prompt (instructions), a user prompt,
  and examples --- and where each one lives in Agent Builder

- How to write clear instructions that control an agent\'s role, tone,
  scope, and output format

- How to use zero-shot and few-shot prompting inside your agent\'s
  instructions

- How to test, observe, and refine an agent by changing only its prompts

- How small wording changes cause large behavior changes --- the core
  lesson of prompt engineering

## Lab Prerequisites

- A Microsoft 365 account with Copilot / Agent Builder access, work or
  web

- Any modern desktop browser --- Agent Builder is not available on
  mobile

- About 45--60 minutes of undisturbed time

- No prior experience building an agent is required

> Note: Screens and menu labels in Microsoft products change often. If a
> button name is slightly different from this guide, look for the
> closest match --- the overall flow (Describe → Configure → Try it)
> stays the same.

## Learning Objectives

By the end of this lab, you will be able to build and refine a
declarative agent in Microsoft Copilot Agent Builder using layered
prompting.

Specifically, you will be able to:

- Explain the difference between a system prompt, a user prompt, and
  few-shot examples

- Write clear instructions that control an agent\'s role, tone, scope,
  and output format

- Apply zero-shot and few-shot prompting inside an agent\'s instructions

- Test an agent on the Try it tab and observe how prompt changes affect
  its answers

- Identify which instruction block to adjust when an agent\'s behavior
  needs to change

## Key Concepts Before You Start

Prompt engineering is the practice of designing and refining the text
you give an AI model so it responds the way you want. It is a two-step
loop: you write an initial prompt, then you keep adjusting it to improve
the results. When you build an agent, you are doing prompt engineering
in a structured, reusable way.

**[The three kinds of prompts in an agent]{.underline}**

A common beginner mistake is to think an agent has just "a prompt." In
reality, an agent\'s behavior comes from several layers of prompting
working together. Understanding which is which is the whole game.

- System Prompt (Instructions) --- The standing rules the agent always
  follows: its role, tone, what it should and should not do, and how to
  format answers. Set once by the builder, in the Instructions field on
  the Configure tab.

- User Prompt --- What the end user types in each turn when they chat
  with the agent. Changes every message. Typed in the chat box on the
  Try it tab, and later by real users.

- Examples (Few-shot) --- Sample inputs and ideal outputs placed inside
  the instructions to show the agent exactly what "good" looks like.
  Written into the Instructions field, usually near the end.

- Key idea: The system prompt (instructions) is fixed and shapes every
  conversation. The user prompt changes each turn. Most of your effort
  as a builder goes into the instructions, because they are the part you
  control and reuse.

**Elements of a good instruction set**

Strong agent instructions usually contain these building blocks. You
will use all of them in this lab:

- Context --- Background that sets the stage --- who the agent is, and
  who it serves.

- Instructions --- Clear directives on what to do and what to avoid.

- Examples --- Sample input and ideal output that illustrate the task.

- Output indicator --- The shape of the answer you want --- length,
  format, structure.

**Zero-shot vs. few-shot prompting**

Zero-shot --- You describe the task with no examples and let the model
figure it out from your words alone. Best for simple, common tasks where
the instruction is enough.

Few-shot --- You include a few worked examples inside the instructions
so the agent copies the pattern. Best for when you need a specific
style, format, or edge-case handling.

Why this matters: AI responses are variable --- the same prompt can give
different answers at different times. Clear instructions and examples
reduce that variability and make your agent predictable. That
reliability is the point of building an agent instead of just chatting.

## Exercise 1 --- Open Agent Builder

Goal: Get Agent Builder open and understand its three tabs before you
start building.

1.  Log in to +++https://copilot.microsoft.com/+++ with your lab
    credentials.\
    ![](media/media/image.png){width="5.322916666666667in"
    height="4.145833333333333in"}

2.  Enter your password.\
    ![](media/media/image2.png){width="5.125in"
    height="3.9791666666666665in"}

3.  In the left navigation pane, find Agents, then select New agent.\
    ![](media/media/image3.png){width="6.25in"
    height="2.5104166666666665in"}

4.  You can view that there is configure and Describe sections that
    would help you generate an agent through two different ways.\
    ![](media/media/image4.png){width="6.25in"
    height="3.6041666666666665in"}

## Exercise 2 --- Round 1: The Weak Prompt (Baseline)

Goal: Build the agent the way most beginners do --- with a vague,
one-line request --- to give yourself a baseline to compare against.

1.  On the Describe tab, paste this into the chat box exactly:

+++Make an agent that helps with studying.+++\
![](media/media/image5.png){width="6.5in" height="3.6770833333333335in"}

2.  Press Send and wait for Agent Builder to generate the agent.\
    ![](media/media/image6.png){width="6.25in"
    height="3.6354166666666665in"}

3.  Open the Configure tab. Read the auto-generated Name, Description,
    and Instructions. Notice how generic they are.\
    ![](media/media/image7.png){width="6.25in"
    height="3.6354166666666665in"}

4.  Select Create.\
    ![](media/media/image8.png){width="6.25in"
    height="1.0312510936132984in"}

5.  Select Start Chat.\
    ![](media/media/image9.png){width="6.25in"
    height="2.4479166666666665in"}

6.  Enter this user prompt in the description box:

+++Explain how the internet works.+++\
![](media/media/imagea.png){width="6.5in" height="2.8020833333333335in"}

7.  Read the answer.\
    ![](media/media/imageb.png){width="6.25in"
    height="4.208333333333333in"}

8.  Then send the same prompt again and compare. Note whether the tone,
    length, and difficulty level are consistent.\
    ![](media/media/imagec.png){width="6.25in"
    height="4.197916666666667in"}

**What to observe:** The instructions are broad and say little about
tone, audience, or format. Answers may be long, technical, or
inconsistent between tries. The agent has no clear "personality" or
rules, because you never gave it any.

**Note:** Write down one or two problems with the Round 1 answers ---
for example, "too technical" or "different length each time." You will
check whether Round 2 fixes them.

## **Exercise 3 --- Round 2: Engineering the System Prompt**

**Goal:** Replace the vague description with a structured system prompt
in the Instructions field, and take control of the agent\'s behavior.

1.  Go to the Agent you recently created. Select the hamburger icon.
    Select Edit.\
    ![](media/media/imaged.png){width="4.552083333333333in"
    height="6.25in"}

2.  On the Configure tab, paste the Name to:

+++Study Buddy+++\
![](media/media/imagee.png){width="6.5in" height="3.7395833333333335in"}

3.  Paste the Description to a short, precise summary --- this helps the
    model know when to use the agent:\
    +++A friendly tutor that explains difficult topics to beginners
    using simple, everyday language and short examples.+++\
    ![](media/media/imagef.png){width="5.354166666666667in"
    height="3.6895702099737533in"}

4.  Clear the Instructions field and replace it with the structured
    system prompt below. Read each labeled part as you type it --- every
    line changes the agent\'s behavior.

***System prompt to paste:***

> ROLE:
>
> You are Study Buddy, a patient tutor for complete beginners.
>
> AUDIENCE:
>
> Assume the user has no background in the topic and may feel
>
> nervous about it. Never make them feel behind.
>
> TONE:
>
> Warm, encouraging, and plain-spoken. Avoid jargon. If a
>
> technical term is unavoidable, define it in one short sentence.
>
> HOW TO ANSWER:
>
> 1\. Start with a one-sentence plain-language summary.
>
> 2\. Give a short everyday analogy.
>
> 3\. Explain in 3 to 5 simple steps or points.
>
> 4\. End with one check-your-understanding question.
>
> SCOPE:
>
> Only help with learning and study topics. If asked for
>
> something else, gently say that is outside what you do.
>
> LENGTH:
>
> Keep answers under 200 words unless the user asks for more.\
> ![](media/media/image10.png){width="6.5in" height="5.875in"}

5.  Select Update.\
    ![](media/media/image11.png){width="6.25in" height="1.25in"}

6.  Go to the Try it tab and enter the same user prompt as before:

+++Explain how the internet works.+++\
![](media/media/image12.png){width="6.5in"
height="2.0104166666666665in"}

7.  Review the output:\
    ![](media/media/image13.png){width="6.25in" height="4.1875in"}

8.  Test the scope rule. Ask something off-topic, such as:

+++Write me a business email to my landlord.+++\
![](media/media/image14.png){width="6.5in"
height="1.3333333333333333in"}

9.  Review the output:\
    ![](media/media/image15.png){width="6.25in"
    height="4.166666666666667in"}

Tip: Change ONE block and re-test. For example, change TONE to "formal
and academic" and send the same question. Seeing a single edit change
the whole feel of the agent is the clearest way to feel prompt
engineering at work.

## Exercise 4 --- Round 3: Adding Few-Shot Examples

**Goal:** Lock in an exact style by showing the agent a worked example
instead of only describing rules in words.

1.  On the Configure tab, scroll to the bottom of your existing
    Instructions and add the example block below. Do not delete Round
    2\'s instructions --- add to them.

***Few-shot example to append:***

> EXAMPLE OF A GOOD ANSWER:
>
> User: What is a variable in programming?
>
> Study Buddy:
>
> In short: a variable is a labeled box that stores a value
>
> you can use later.
>
> Think of it like a lunchbox with a name tag. The tag is the
>
> name; whatever you put inside is the value.
>
> \- You create it by giving it a name.
>
> \- You put a value inside it (a number, word, etc.).
>
> \- You can open it later to use or change the value.
>
> Quick check: if you made a variable called score and put 10
>
> in it, what would score hold right now?
>
> Follow this same shape for every answer.

![](media/media/image16.png){width="6.5in" height="4.354166666666667in"}

2.  Go to Chat and ask a brand-new question the agent has never seen.
    Paste the following prompt:

+++What is a database?+++

![](media/media/image17.png){width="6.5in"
height="1.6770833333333333in"}

3.  Confirm the new answer copies the example\'s shape: short summary, a
    name-tag-style analogy, bullet points, and a quick-check question.\
    ![](media/media/image18.png){width="6.854166666666667in"
    height="4.625in"}

## Exercise 5 --- Refine, Save, and Reflect

**Goal:** Polish the agent, save it, and reflect on what changed its
behavior across the three rounds.

1.  Go to the **Configure** tab.\
    ![](media/media/image19.png){width="6.25in"
    height="4.135416666666667in"}

2.  Find the **Suggested prompts** section (usually below Instructions).
    Add the following prompts:\
    Note: These don\'t change how the agent *answers* --- they just
    guide the user on what kinds of questions it\'s good for.+\
    \
    +++Title: Explain a concept

Message: Explain photosynthesis simply.

Title: Break down a topic

Message: Help me understand how compound interest works.

Title: Give me an example

Message: Give me a simple, everyday example of Newton\'s second law.+++\
![](media/media/image1a.png){width="6.291666666666667in" height="6.5in"}

**Response mode (Quick response vs. Think deeper)**\
This is a setting for how much the underlying model \"thinks\" before
answering.

- **Quick response** --- replies fast, good for simple factual questions
  (which is most of what Study Buddy does).

- **Think deeper** --- takes longer but reasons more carefully, better
  for harder or multi-step questions.

- Try asking the same question in each mode and compare: is \"Think
  deeper\" actually giving a better explanation, or just a slower one
  for something this simple? That comparison *is* the exercise ---
  there\'s no right answer, you\'re just noticing the trade-off.

1.  Select the AI model as Quick Summary.\
    ![](media/media/image1b.png){width="6.25in"
    height="2.7604166666666665in"}

2.  Navigate to the agent. In the description box, paste the following
    prompt:\
    \
    +++Explain how vaccines work to someone with no science background,
    using a simple analogy.+++\
    ![](media/media/image1c.png){width="6.25in"
    height="2.8541666666666665in"}

3.  Review the output:\
    ![](media/media/image1d.png){width="6.25in" height="3.71875in"}

4.  Click +New Chat. Select the AI model as Think Deeper.\
    ![](media/media/image1e.png){width="6.25in"
    height="2.4895833333333335in"}

5.  Paste the same prompt as above:\
    +++Explain how vaccines work to someone with no science background,
    using a simple analogy.+++\
    ![](media/media/image1f.png){width="6.25in"
    height="3.0104166666666665in"}

6.  Review the output:\
    ![](media/media/image20.png){width="6.25in"
    height="4.166666666666667in"}

## Lab Summary

This lab built one agent three times, changing only its prompts. A vague
description in Round 1 gave a generic, unreliable agent with no clear
personality or rules. A structured system prompt in Round 2 --- covering
role, audience, tone, how to answer, scope, and length --- gave the
agent a consistent structure and a clear rule for what it would refuse
to do. Adding a few-shot example in Round 3 locked that structure into
an exact, repeatable style across brand-new questions, without changing
the model or adding any data.

The takeaway for every agent you build from here on: the quality of an
agent is the quality of its prompts. Master the three layers --- system
prompt, user prompt, and examples --- and you can shape an agent to do
almost anything within its tools and knowledge. From here, try
rebuilding Study Buddy for a different audience, such as expert users,
or add a knowledge source on the Configure tab and see how instructions
and grounded data work together.
