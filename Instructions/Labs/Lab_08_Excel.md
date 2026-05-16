---
layout: page
lab:
  title: Analyse feedback with Excel
  module: Analyse with Copilot in Excel
  description: In this lab, you will use Copilot in Excel to summarise employee feedback, identify themes, create charts, and produce a management action list, then apply the same skills to a branch performance dataset.
  duration: 45 minutes
  level: 100
  islab: true
  primarytopics:
    - Copilot in Excel
    - Data analysis
    - Theme identification
    - Chart generation
    - Action planning
---

# Lab 07: Analyse feedback with Excel

## Scenario

You are still the **HR Officer at Mayfield Bank Berhad**. The employee feedback survey from Lab 06 has been completed by 47 staff members across three departments. The responses have been exported from Forms into an Excel workbook. You need to summarise the results, identify key themes and risks, create charts for the management presentation, and produce a recommended action list.

In this lab, you learn how to:

- Use Copilot in Excel to analyse a feedback dataset.
- Group open-text responses into themes.
- Create charts from data using prompts.
- Add a formula column using Copilot.
- Translate data into a recommended action list.

**This lab should take approximately 45 minutes.**

---

## Part A: Guided Exercise

### Task 1: Open the dataset and enable Copilot

1. Open the file **Lab_07_Feedback_Results.xlsx** from your OneDrive > Documents folder.

1. Review the data. The workbook contains one sheet with columns: Staff ID, Department, Clarity Score (1-5), Confidence Score (1-5), Top Concern, Additional Support Needed (open text), and Ready to Apply (Yes/No).

1. Click anywhere inside the data, then select the **Copilot** button on the **Home** ribbon.

    > ***Note:** Copilot in Excel requires the data to be formatted as a table. If the Copilot button is greyed out, select your data range and press Ctrl + T to format it as a table first.*

---

### Task 2: Summarise the results

1. In the Copilot panel, type:

    ```
    Analyse this feedback table. Summarise the average clarity score, average confidence score, percentage of staff who said they are ready to apply the guideline, and the top 3 concern themes. Return a management summary and a detailed table.
    ```

1. Review the output. Then ask:

    ```
    Which department has the lowest average confidence score? What does this suggest for follow-up training?
    ```

---

### Task 3: Group open-text responses into themes

1. Type:

    ```
    Group the open-text responses in the Additional Support Needed column into themes. Suggested themes: Training gap, Privacy concern, Unclear workflow, Unclear examples, Positive feedback, and Other. Add a new column called Theme with the grouped label for each row.
    ```

1. Review the groupings. If any responses seem miscategorised, ask Copilot to review specific rows.

    > ***Note:** Always verify Copilot's categorisation before using it in a report. Open-text grouping is interpretive and may not always match your intent.*

---

### Task 4: Create charts

1. Type:

    ```
    Recommend three charts for this feedback data. For each chart, explain the insight it would show and the fields required. Then create the best chart to show confidence score by department.
    ```

1. Review the chart. Then add a second one:

    ```
    Create a bar chart showing the count of responses by Theme from the Theme column. Sort from most to least frequent.
    ```

---

### Task 5: Produce an action list

1. Type:

    ```
    Identify the main adoption risks from this feedback. Group risks into: Training gap, Policy confusion, Privacy concern, and Resistance to change. For each risk, suggest one specific action the HR team at Mayfield Bank should take. Return as a table.
    ```

1. Copy the action list to a new sheet labelled **Action Plan**.

---

### Prompt practice

| Weak prompt | Better prompt | Why the better prompt works |
| --- | --- | --- |
| Analyze this data. | Analyse this feedback table. Summarise average clarity score, confidence score, top 5 concern themes, and departments that need follow-up support. Return a management summary and a detailed table. | Identifies exact metrics and output format. |
| Clean data. | Clean this response table by standardising department names, grouping similar concern themes, and flagging blank or incomplete responses. Show the changes before applying them. | Asks for safe data transformation with review before changes. |
| Make chart. | Recommend three charts for this feedback data. For each chart, explain the insight it would show. Then create the best chart to show confidence level by department. | Asks for chart reasoning before chart creation. |
| Find risk. | Identify adoption risks from the feedback. Group risks into training gap, policy confusion, privacy concern, and resistance to change. Suggest one specific action for each risk. | Translates data into decisions with clear categories. |

---

### Extended practice

- Ask Copilot for a management summary, a detailed theme table, and a recommended action list from the same data in one prompt.
- Ask Copilot to standardise messy category values, then show a before-and-after view so you can inspect the changes.
- Ask Copilot to identify the biggest adoption risk overall and describe what an escalation plan would look like.

---

## Part B: Independent Exercise

**Scenario:** You are a **Business Performance Analyst at Mayfield Bank Berhad's Retail Banking division**. Your regional head has asked you to review Q4 2024 performance data across 12 branches in the Klang Valley.

Using what you practised in Part A, complete the following with minimal guidance using the file **Lab_07_Branch_Performance_Q4.xlsx**:

1. Ask Copilot to identify the top 3 and bottom 2 performing branches overall.

1. Ask whether there is any relationship between customer complaints and loan disbursement volume.

1. Add a calculated column, Complaints per 100 Staff, using Copilot.

1. Create a bar chart comparing loan disbursements across all branches, sorted from highest to lowest.

1. Summarise the key findings in 5 bullet points suitable for a leadership meeting.

---

## Lab complete

You have used Copilot in Excel to analyse feedback data, identify themes, create charts, and produce an action plan. In Lab 08 you will use Work grounding and Scheduled Prompts in Copilot Chat to monitor ongoing feedback.
