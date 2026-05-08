---
layout: page
lab:
  title: Analyse data and surface insights
  module: Analyse with Copilot in Excel
  description: In this lab, you will use Copilot in Excel to analyse a branch performance dataset for a Malaysian bank, identify trends, and generate charts and summaries using natural language prompts.
  duration: 30 minutes
  level: 100
  islab: true
  primarytopics:
    - Copilot in Excel
    - Data analysis
    - Chart generation
---

# Lab 05 — Analyse data and surface insights

## Scenario

You are a **Business Performance Analyst** at Mayfield Bank Berhad's Retail Banking division. Your regional head has asked you to review Q4 2024 performance data across 12 branches in the Klang Valley. The data is in an Excel workbook. You need to identify the top and bottom performers, flag any anomalies, and prepare a short summary for the leadership meeting on Friday.

In this lab, you learn how to:

- Use Copilot in Excel to explore and understand a dataset.
- Ask questions about the data in natural language.
- Generate charts and highlight insights using prompts.
- Add formula columns using Copilot.

**This lab should take approximately 30 minutes.**

---

## Task 1: Open the dataset and enable Copilot

1. Open the file **Lab_05_Branch_Performance_Q4.xlsx** from your OneDrive > Documents folder.

1. Review the data. The workbook contains one sheet with columns: Branch Name, Region, New Accounts Opened, Loan Disbursements (RM), Deposit Growth (%), Customer Complaints, and Staff Headcount.

1. Click anywhere inside the data table, then select the **Copilot** button on the **Home** ribbon.

    > ***Note:** Copilot in Excel requires the data to be formatted as a table. If the Copilot button is greyed out, select your data range and press **Ctrl + T** to convert it to a table first.*

---

## Task 2: Ask questions about the data

1. In the Copilot panel, type:

    ```
    Which branch had the highest loan disbursements in Q4?
    ```

1. Then ask:

    ```
    Which 3 branches had the most customer complaints? Show the complaint count and their deposit growth side by side.
    ```

1. Then ask:

    ```
    Is there any relationship between staff headcount and new accounts opened?
    ```

1. Review the responses. Copilot will highlight relevant rows or generate summaries directly in the panel.

---

## Task 3: Generate a chart

1. In the Copilot panel, type:

    ```
    Create a bar chart comparing loan disbursements across all 12 branches, sorted from highest to lowest.
    ```

1. Copilot will insert a chart into the worksheet. Move and resize it as needed.

1. Then type:

    ```
    Add a second chart showing deposit growth percentage by branch, and highlight the branches below 5% growth in red.
    ```

---

## Task 4: Add a formula column

1. In the Copilot panel, type:

    ```
    Add a new column called "Complaints per 100 Staff" that divides Customer Complaints by Staff Headcount and multiplies by 100. Round to 1 decimal place.
    ```

1. Review the formula Copilot inserts. Verify it is correct before accepting.

---

## Task 5: Summarise the findings

1. In the Copilot panel, type:

    ```
    Summarise the key findings from this dataset in 5 bullet points. Focus on top performers, underperformers, and any data points worth flagging for the leadership team.
    ```

1. Copy the summary to a new Word document or paste it into the meeting agenda.

---

## Lab complete

You have used Copilot in Excel to explore a branch performance dataset, generate charts, add a calculated column, and produce a leadership-ready summary — all without writing a single formula manually.
