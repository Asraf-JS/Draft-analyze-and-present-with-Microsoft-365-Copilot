---
layout: page
lab:
  title: Research with Copilot Chat
  module: Get started with Microsoft 365 Copilot Chat
  description: In this lab, you will use Copilot Chat with Web grounding to research workplace AI guideline practices, then apply the same skills to a banking research scenario.
  duration: 45 minutes
  level: 100
  islab: true
  primarytopics:
    - Copilot Chat
    - Web grounding
    - Prompt construction
    - Research and synthesis
---

# Lab 01 — Research with Copilot Chat

## Scenario

You are an **HR Officer at Mayfield Bank Berhad**. Your manager has asked you to research how other organisations and regulators approach workplace AI usage guidelines. You will use Copilot Chat with Web grounding to gather and synthesise findings before drafting the bank's own guideline.

In this lab, you learn how to:

- Open Copilot Chat and identify Web vs Work grounding.
- Write effective research prompts using the Context, Task, Source, Constraints, Output, Review pattern.
- Refine and follow up on responses.
- Distinguish source-based findings from Copilot's interpretive recommendations.

**This lab should take approximately 45 minutes.**

---

## Prompt construction method

These labs use a simple prompt pattern. You do not need to use every element every time — use what the task needs.

| Element | What to include |
| --- | --- |
| **Context** | Who you are and the business situation |
| **Task** | The exact action Copilot should perform |
| **Source** | Web, a file, a thread, or work data |
| **Constraints** | Tone, length, audience, exclusions |
| **Output** | The structure you want: table, bullets, email, summary |
| **Review** | Ask Copilot to flag assumptions, gaps, or items needing human review |

---

## Part A — Guided Exercise

### Task 1: Open Copilot Chat and orient yourself

1. Open a browser and go to [https://m365.cloud.microsoft](https://m365.cloud.microsoft), or open the **Microsoft 365 Copilot** app from Microsoft 365.

1. Sign in with your work or school account.

1. In the left sidebar, select **New chat** to start a clean session.

    ![Copilot Chat interface showing the New chat button in the left sidebar](../../assets/images/lab01_chat_interface_wide.jpg)

1. Near the top centre of the screen you will see two small icons side by side — a briefcase and a globe. The briefcase represents **Work** grounding (your organisation's internal data); the globe represents **Web** grounding (public internet sources). Select the **globe icon** to switch to Web.

    ![Close-up of the grounding toggle with the Web globe icon highlighted](../../assets/images/lab01_web_toggle_close_wide.jpg)

    > ***Note:** If neither icon is visible, your licence or tenant settings may not support this feature. Check with your trainer before continuing. Features may differ depending on whether you have Copilot Chat only or the full Microsoft 365 Copilot add-on licence.*

1. In the top-right corner, you will see a model selector labelled **Auto**. Leave this as is for now — Auto lets Copilot decide how much processing time a question needs based on its complexity. You can explore the other options (Quick Response, Think Deeper) later.

    ![Model picker dropdown showing Auto, Quick Response, Think Deeper, Opus, and GPT](../../assets/images/lab01_model_picker_wide.jpg)

1. Before running the main research prompt, try a quick question to confirm Web grounding is working and to see how citations appear. Click into the **Message Copilot** box and type:

    ```
    What is the weather like in Kuala Lumpur today?
    ```

    Press **Enter** and wait for the response.

1. Look at the response. You will see small source tags — such as `msn` or `weather` — sitting inline with the text. Hover your mouse over one of these tags to see the full source name and the web address it came from.

    ![Copilot response with inline citation tags, showing a hover preview of the source website](../../assets/images/lab01_citations_hover_wide.jpg)

    > ***Note:** This is how every Web-grounded response works — Copilot draws from live web sources and cites them inline. Get into the habit of checking these before acting on the information, especially for research that will inform a policy or document.*

You are now familiar with the interface. In the next task you will use these same controls to run the actual research for Mayfield Bank.

---

### Task 2: Run a research prompt

1. Type the following prompt and press **Enter**:

    ```
    Using web sources, research how large organisations handle AI usage guidelines in the workplace. Focus on HR use cases, confidential data, employee privacy, human decision-making, and training requirements. Return a table with these columns: Practice, Why it matters, Risk addressed, Recommendation for a Malaysian HR team.
    ```

1. Review the response. Check whether Copilot has cited sources below the answer.

1. Ask Copilot to separate what is confirmed from sources versus what is interpretive:

    ```
    Review your previous response. Identify which recommendations are drawn from the sources cited and which are your own interpretive suggestions. Label each row in the table as Source-based or Interpretive.
    ```

    > ***Note:** This step builds critical thinking — participants should understand that Copilot's output is not all equally grounded in evidence.*

---

### Task 3: Narrow the research scope

1. Follow up with a more focused prompt:

    ```
    Research Malaysian policy considerations relevant to workplace AI use. Include PDPA, national AI guidance if available, employee data handling, and human oversight requirements. Separate legal requirements from good-practice recommendations.
    ```

1. Then ask:

    ```
    Based on all the research so far, summarise the 5 most important practices for a Malaysian bank's HR team to include in an internal AI Usage Guideline. Return as a numbered list with a one-sentence explanation for each.
    ```

1. Save this summary — you will use it in Lab 02.

---

### Task 4: Use Prompt Coach to improve a research prompt

Copilot Chat includes a built-in agent called **Prompt Coach** that analyses your prompts and suggests improvements. In this task you will use it to refine a prompt before running it — a habit worth building before any important research.

1. In the left sidebar, select **All agents** to open the Agent Store.

    ![Copilot Agent Store showing available agents including Prompt Coach](../../assets/images/lab01_agent_store_wide.jpg)

1. Select the **Prompt Coach** tile. When the detail card appears, select **Open**.

    ![Prompt Coach detail card in the Agent Store with the Open button highlighted](../../assets/images/lab01_prompt_coach_open_wide.jpg)

1. Prompt Coach opens with three built-in starter actions: **Prompt Generation**, **Analyze Prompt**, and **Prompt Compliance**. You can use these as shortcuts, or simply type your own request directly into the message box.

    ![Prompt Coach interface showing the three starter actions](../../assets/images/lab01_prompt_coach_starters_wide.jpg)

1. Type the following into the message box and press **Enter**:

    ```
    I am doing a research on how organisations are using AI in their workplace. I would like you to search the internet for S&P 500 companies and how they are adopting AI in their workplace and what policies they are applying to their organisation. After that I want you to come up with a first draft for my organisation. Ask me any question for clarification.
    ```

    ![Full multi-part prompt typed into Prompt Coach, ready to send](../../assets/images/lab01_prompt_coach_prompt_wide.jpg)

    > ***Note:** Notice this prompt does three things at once: it asks for research, requests a draft, and invites follow-up questions. Prompt Coach is well suited to handling multi-step requests like this.*

1. Wait for Prompt Coach to respond. It will search the web, pull in examples from real organisations, and generate a structured first draft. Scroll through the response — you will see a research table with company examples and inline citations, followed by numbered policy sections.

    ![Prompt Coach response showing an S&P 500 AI adoption research table with inline citations](../../assets/images/lab01_prompt_coach_output_wide.jpg)

1. Scroll to the end of the response. Prompt Coach finishes with a **bonus prompt** — a ready-to-use template you can copy and paste into Copilot in Word to refine the draft further with your organisation's specific context.

    ![Prompt Coach bonus section showing a copy-paste ready prompt template for refining the policy draft](../../assets/images/lab01_prompt_coach_bonus_wide.jpg)

    > ***Note:** Copy this bonus prompt somewhere safe — you will be able to use it in Lab 03 when you open the draft in Word.*

---

### Prompt practice

| Weak prompt | Better prompt | Why the better prompt works |
| --- | --- | --- |
| Find AI guidelines. | Using web sources, research how large organisations handle AI usage guidelines in the workplace. Focus on HR use cases, confidential data, employee privacy, human decision-making, and training. Return a table with: practice, why it matters, risk addressed, and recommendation for a Malaysian HR team. | Defines scope, audience, and table columns. Connects external research to the HR scenario. |
| Tell me about AI in Malaysia. | Research Malaysian policy considerations relevant to workplace AI use. Include PDPA, national AI guidance if available, employee data handling, and human oversight. Separate legal requirements from good-practice recommendations. | Prevents Copilot from mixing law, policy, and best practice without labelling the difference. |
| Why are answers different? | Explain why two users may get different Copilot responses even when using similar prompts. Cover grounding mode, permissions, personalization, files available, and AI variability. Use bullets. | Requests specific causes and a clear format for training use. |

---

### Extended practice

- Run the same research prompt twice: once with a broad scope and once narrowed to privacy, human oversight, and training only. Compare the usefulness of both outputs.
- Ask Copilot to compare public AI guidance from regulators, large employers, and technology companies, then turn the findings into a shortlist suitable for internal policy drafting.
- Ask Copilot to identify which findings appear source-based and which appear interpretive or advisory.

---

## Part B — Independent Exercise

**Scenario:** You are a **Relationship Manager at Mayfield Bank Berhad**. You have a meeting later today with a new prospect — a mid-sized logistics company based in Shah Alam. You want to walk in prepared.

Using what you practised in Part A, complete the following tasks with minimal guidance:

1. Use Web grounding in Copilot Chat to research the current state of the logistics industry in Malaysia — key trends, challenges, and growth areas.

1. Ask a follow-up question about what financing needs logistics companies in Malaysia typically have.

1. Narrow it further: which financing needs are most relevant for a company with around RM 50 million in annual revenue?

1. Draft a short pre-meeting briefing note (under 300 words) for a Relationship Manager preparing to meet this prospect. Include: industry context, likely financing needs, and 3 suggested talking points. Mention Mayfield Bank's SME financing solutions.

> ***Note:** This exercise uses the same skills as Part A — web grounding, follow-up prompts, and output refinement — applied to a completely different task. If you get stuck, refer back to the prompt construction table at the top of this lab.*

---

## Lab complete

You have used Copilot Chat with Web grounding to research a topic, refine outputs through follow-up prompts, and produce a structured summary. In Lab 02 you will move this research into Copilot Pages to organise and share it.
