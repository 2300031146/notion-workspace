# Business Analyst Internship — Elevence Data Analysis Project

**Name:** Sai Reddy
**Role:** Business Analyst Intern
**Company:** Elevence
**GitHub:** https://github.com/2300031146/elevence-tasks
**Notion Workspace:** https://app.notion.com/p/37ba876cf5bb818998daf9122cd116f6
**Internship Duration:** May 7, 2026 – July 7, 2026 (2 Months)

---

# 1. Project Dashboard

This page gives a quick summary of where the project stands right now.

**Project Name:** Elevence Data Analysis Portfolio
**Analyst:** Sai Reddy
**Start Date:** May 7, 2026
**End Date:** July 7, 2026
**Duration:** 2 Months
**Current Status:** In Progress

## How Many Tasks Are Done?

| Task | Status |
|------|--------|
| Task 1 — Financial Risk Inventory | Done |
| Task 2 — Discount vs Rating Analysis | Done |
| Task 3 — Promotion Effectiveness Trend | Done |
| Task 4 | In Progress |
| Task 5 | Not Started |
| Task 6 | Not Started |

**Progress: 3 out of 6 tasks completed**

## Important Note
Elevence will review all my work only after I finish all 6 tasks. There are no mid-way reviews. I need to complete everything before July 7 and then submit for review.

---

# 2. Project Overview

## What is this project about?

I was given this internship by Elevence to do data analysis on their e-commerce business data. My job is to look at the data, find useful business insights, and present them through Power BI dashboards. Each task focuses on a different business question.

I have to complete 6 tasks in 2 months (May 7 to July 7, 2026). Once all 6 are done, Elevence will review everything together.

## What is included in my work?

- 6 Power BI dashboards (one for each task)
- A README file for each task explaining what I found
- All files uploaded to GitHub after each task is done

## What is NOT included?

- I am not building any websites or apps
- I am not collecting new data — I use the dataset given by Elevence
- I am not deploying dashboards to any live system

## Who is involved?

| Person | Role |
|--------|------|
| Sai Reddy | Business Analyst Intern — doing all the analysis and dashboards |
| Elevence Team | They gave me the tasks and will review my work at the end |

## Tools I am using

| Tool | What I use it for |
|------|-------------------|
| Power BI | Building dashboards and charts |
| Power Query | Cleaning and preparing the data |
| DAX | Writing formulas to calculate KPIs |
| GitHub | Saving and submitting my work |
| Notion | Keeping track of the project and writing documentation |

---

# 3. Business Problem

## What problem is Elevence facing?

Elevence sells products online and they offer discounts to attract customers. But they do not have a clear picture of whether these discounts are actually helping the business or hurting it. They also run promotions but are not sure if those promotions are working the way they expect.

The main concerns are:

1. Some products are being sold at heavy discounts but are still getting low ratings from customers. This means the company might be losing money on those products without gaining customer satisfaction in return.

2. The team is not sure if giving higher discounts makes customers happier or if it just increases the number of sales without improving product quality perception.

3. There is no clear data on whether promotional campaigns are creating long-term customer loyalty or just short-term spikes in activity.

## Why does this matter?

If Elevence does not understand these patterns, they could keep spending on discounts and promotions that do not actually help the business. This leads to revenue loss and wasted marketing budget.

## The questions I am trying to answer

1. Which products are financially risky because of high discounts and low ratings?
2. Does giving a bigger discount lead to a better customer rating?
3. Are the promotional campaigns actually working or just creating temporary noise?
4. How do customer ratings change across different discount levels?

---

# 4. Objectives

## What am I trying to achieve?

I have three main goals for this internship project. Each one is tied to a specific task.

---

**Goal 1 — Find financially risky products (Task 1)**

I want to identify which products in Elevence's inventory are a financial risk. These are products that have a high discount percentage but still have a low customer rating. These products cost the company money but do not generate customer satisfaction in return.

How I will measure success: I will calculate what percentage of the total inventory value falls into the risky category.

Result so far: Around 14.4% of inventory value is at financial risk.

---

**Goal 2 — Understand the link between discounts and ratings (Task 2)**

I want to find out whether customers give better ratings to products that have higher discounts. This will help Elevence understand if discounts are actually improving customer satisfaction.

How I will measure success: I will compare average ratings across different discount ranges and plot them visually.

Result so far: Higher discounts do not lead to better ratings. Ratings stay between 3.5 and 4.5 no matter how high the discount is.

---

**Goal 3 — Measure promotion effectiveness (Task 3)**

I want to analyze whether Elevence's promotions are having a positive impact on customer engagement and ratings over time.

How I will measure success: I will look at how review counts and ratings change during promotion periods.

Result so far: Promotions increase the number of reviews but ratings do not improve. This means promotions drive activity but not actual product satisfaction.

---

**Overall target:** Complete all 6 tasks with Power BI dashboards and documentation before July 7, 2026, and submit everything to Elevence for final review.

---

# 5. Requirements

## What does the work need to deliver?

### Things that must be done (Functional Requirements)

| ID | What needs to be done | Priority | Status |
|----|-----------------------|----------|--------|
| FR-01 | Show a table of financially risky products with discount %, rating, and stock value | High | Done |
| FR-02 | Show a KPI card that displays the total percentage of inventory at financial risk | High | Done |
| FR-03 | Show the relationship between discount percentage and customer rating | High | Done |
| FR-04 | Allow the user to filter charts by product category and discount range | Medium | Done |
| FR-05 | Show how promotion effectiveness changes over time using a line or bar chart | High | Done |
| FR-06 | Highlight the top 10 most financially risky products | Medium | Done |
| FR-07 | All charts must have slicers so users can interact with the data | Medium | Done |
| FR-08 | Complete Tasks 4, 5, and 6 with the same quality standard | High | Pending |

### Things that affect quality (Non-Functional Requirements)

| ID | Requirement | Priority |
|----|-------------|----------|
| NFR-01 | Dashboards should open and load quickly (within 5 seconds) | Medium |
| NFR-02 | All dashboards should have a consistent look and color style | Low |
| NFR-03 | The data in the reports should be easy to refresh | High |
| NFR-04 | All report files must be saved in .pbix format and shared on GitHub | High |
| NFR-05 | All documentation must be saved and version controlled on GitHub | Medium |

### Limitations I am working within

- I can only use the dataset given by Elevence
- I can only use Power BI, Power Query, and DAX
- All 6 tasks must be finished before July 7, 2026
- Elevence will only review the work after all tasks are submitted — not before

---

# 6. User Stories

User stories describe who needs what from the dashboards and why. I wrote these to make sure my dashboards answer real business questions.

---

**Story 1**
As a Category Manager, I want to see which products have high discounts and low ratings so that I can decide which ones to remove or reprice.

What "done" looks like:
- The dashboard shows product name, discount percentage, customer rating, and stock value
- I can sort and filter the table
- High-risk products are highlighted so they are easy to spot

---

**Story 2**
As a Finance Analyst, I want to know what percentage of our inventory value is at financial risk so that I can report it to senior management.

What "done" looks like:
- There is a clear KPI number showing the percentage at risk
- I can adjust the risk threshold using a filter
- The data is broken down by product category

---

**Story 3**
As a Marketing Manager, I want to see whether giving bigger discounts leads to better customer ratings so that I can decide if our discount strategy is working.

What "done" looks like:
- There is a scatter chart showing discount percentage on one axis and average rating on the other
- There is a trendline to show the direction
- There is a written insight on the page summarizing the finding

---

**Story 4**
As a Product Manager, I want to compare customer ratings across different discount levels (0–20%, 21–40%, 41–60%, 60%+) so that I can understand which discount range performs best.

What "done" looks like:
- A bar chart grouped by discount band
- Average rating shown for each band
- Review count also shown as a reference

---

**Story 5**
As a CMO, I want to see how promotional campaigns impact review volume and ratings over time so that I can evaluate whether our promotions are worth the investment.

What "done" looks like:
- A time-series chart showing monthly review volume
- Promotion periods are marked on the chart
- The rating trend is shown alongside the review volume

---

**Story 6**
As a Business Analyst, I want to document my findings clearly so that I can present them confidently during the Elevence final review.

What "done" looks like:
- Each task has a .pbix file committed to GitHub
- Each task has a README file with 3 to 5 key insights written in plain language
- The findings are easy to understand without needing to open the Power BI file

---

# 7. Task Tracker

This is a record of every task in the project with its current status.

## Database Fields (for Notion setup)

| Field | Type | Values |
|-------|------|--------|
| Task Name | Title | — |
| Status | Select | Not Started / In Progress / Complete |
| Priority | Select | High / Medium / Low |
| Owner | Text | Person responsible |
| Sprint | Select | Sprint 1 to Sprint 6 |
| Due Date | Date | — |
| Category | Select | Analysis / Documentation / Review / Setup |
| Notes | Text | Any extra information |
| Task ID | Auto ID | Starts with ELV |

## All Tasks

| ID | Task | Status | Priority | Sprint | Category |
|----|------|--------|----------|--------|----------|
| ELV-1 | Set up GitHub repository with folder structure | Complete | High | Sprint 1 | Setup |
| ELV-2 | Download and explore the e-commerce dataset | Complete | High | Sprint 1 | Analysis |
| ELV-3 | Task 1 — Build Financial Risk Inventory Dashboard | Complete | High | Sprint 1 | Analysis |
| ELV-4 | Task 1 — Write README with key insights | Complete | Medium | Sprint 1 | Documentation |
| ELV-5 | Task 2 — Build Discount vs Rating Dashboard | Complete | High | Sprint 2 | Analysis |
| ELV-6 | Task 2 — Write README with key insights | Complete | Medium | Sprint 2 | Documentation |
| ELV-7 | Task 3 — Build Promotion Effectiveness Dashboard | Complete | High | Sprint 3 | Analysis |
| ELV-8 | Task 3 — Write README with key insights | Complete | Medium | Sprint 3 | Documentation |
| ELV-9 | Task 4 — Dashboard (in progress) | In Progress | High | Sprint 4 | Analysis |
| ELV-10 | Task 5 — Dashboard | Not Started | High | Sprint 5 | Analysis |
| ELV-11 | Task 6 — Dashboard | Not Started | High | Sprint 6 | Analysis |
| ELV-12 | Submit all 6 tasks to Elevence for final review | Not Started | High | Sprint 6 | Review |
| ELV-13 | Write Final Project Summary | Not Started | Medium | Sprint 6 | Documentation |

---

# 8. Kanban Board

The Kanban board shows the same tasks from the Task Tracker but in a visual column layout. In Notion, this is created as a Board View of the Task Tracker database.

**How to create it in Notion:**
1. Open the Task Tracker database
2. Click Add a View
3. Choose Board
4. Set Group By to Status
5. Add Priority, Sprint, and Due Date as visible properties

## Current Board State

**Not Started**
- Task 5 — Dashboard
- Task 6 — Dashboard
- Submit all 6 tasks to Elevence for review
- Write Final Project Summary

**In Progress**
- Task 4 — Dashboard

**Complete**
- Set up GitHub repository
- Download and explore dataset
- Task 1 — Financial Risk Dashboard
- Task 1 — README
- Task 2 — Discount vs Rating Dashboard
- Task 2 — README
- Task 3 — Promotion Effectiveness Dashboard
- Task 3 — README

---

# 9. Risks and Assumptions

## Risks — Things that could go wrong

| ID | What could go wrong | How likely | How serious | What I will do about it |
|----|---------------------|------------|-------------|--------------------------|
| R-01 | The dataset has missing or incorrect values | Medium | High | Use Power Query to clean the data and note any issues in the README |
| R-02 | I fall behind schedule and cannot finish all 6 tasks before July 7 | Medium | High | Track progress weekly and focus on one task at a time |
| R-03 | A Power BI file gets corrupted or lost | Low | High | Commit to GitHub after finishing every single task |
| R-04 | A DAX formula gives wrong results | Medium | High | Double-check each formula by comparing it with a manual calculation |
| R-05 | The recruiter or reviewer misunderstands the findings | Low | Medium | Write clear, simple insight summaries in every README file |

## Assumptions — Things I am assuming to be true

| ID | Assumption |
|----|-----------|
| A-01 | The dataset Elevence gave me is accurate and usable |
| A-02 | All 6 tasks use the same dataset format |
| A-03 | Power BI Desktop is the only tool I need to complete the work |
| A-04 | Elevence will only review my work after all 6 tasks are submitted |
| A-05 | GitHub is the agreed platform for submitting my work |
| A-06 | The 2-month timeline runs from May 7 to July 7, 2026 |
| A-07 | No new datasets or major changes will be added mid-internship |

---

# 10. Meeting Notes

## Meeting 1 — Kickoff Meeting
**Date:** May 7, 2026
**Who was there:** Sai Reddy, Elevence Team
**Type:** Project Kickoff
**Duration:** About 1 hour

### What we talked about

- Elevence introduced the internship and explained what they expect from me
- I was given 6 data analysis tasks to complete over 2 months
- The deadline is July 7, 2026
- I need to use Power BI for all dashboards
- Each task should be committed to GitHub with a README explaining the findings
- Elevence made it clear that they will only review my work after all 6 tasks are done — there will be no check-ins or feedback in between
- It is my responsibility to manage my own time and make sure all tasks are finished on time

### What was decided

- Internship runs from May 7 to July 7, 2026
- I will complete roughly one task per week
- All work goes to GitHub — one folder per task
- Final review happens only after all 6 tasks are submitted

### What I need to do next

| Task | Who | By When |
|------|-----|---------|
| Create the GitHub repository and folder structure | Sai Reddy | May 8, 2026 |
| Download and explore the dataset | Sai Reddy | May 9, 2026 |
| Start Task 1 — Financial Risk Inventory analysis | Sai Reddy | May 10, 2026 |
| Complete and submit all 6 tasks | Sai Reddy | July 7, 2026 |

---

# 11. Project Timeline

## Overview of Phases

| Phase | What happens | Start | End | Status |
|-------|-------------|-------|-----|--------|
| Phase 1 | Getting set up — repo, dataset, tools | May 7, 2026 | May 10, 2026 | Done |
| Phase 2 | Completing all 6 analysis tasks | May 11, 2026 | June 28, 2026 | In Progress |
| Phase 3 | Submitting everything and Elevence review | June 29, 2026 | July 7, 2026 | Not Started |
| Phase 4 | Final documentation and project wrap-up | July 7, 2026 | July 7, 2026 | Not Started |

## Milestones

| Milestone | Target Date | Actual Date | Status |
|-----------|-------------|-------------|--------|
| GitHub repo created | May 8, 2026 | May 8, 2026 | Done |
| Task 1 done and committed | May 17, 2026 | May 17, 2026 | Done |
| Task 2 done and committed | May 24, 2026 | May 24, 2026 | Done |
| Task 3 done and committed | May 31, 2026 | May 31, 2026 | Done |
| Task 4 done and committed | June 7, 2026 | — | Pending |
| Task 5 done and committed | June 14, 2026 | — | Pending |
| Task 6 done and committed | June 21, 2026 | — | Pending |
| All 6 tasks submitted to Elevence | June 28, 2026 | — | Pending |
| Elevence review completed | July 7, 2026 | — | Pending |

## Weekly Plan

| Week | Dates | What I am doing | Status |
|------|-------|----------------|--------|
| Week 1 | May 7–10 | Setup — GitHub, dataset exploration | Done |
| Week 2 | May 11–17 | Task 1 — Financial Risk Inventory | Done |
| Week 3 | May 18–24 | Task 2 — Discount vs Rating | Done |
| Week 4 | May 25–31 | Task 3 — Promotion Effectiveness | Done |
| Week 5 | June 1–7 | Task 4 | In Progress |
| Week 6 | June 8–14 | Task 5 | Upcoming |
| Week 7 | June 15–21 | Task 6 | Upcoming |
| Week 8 | June 22–28 | Final review prep and submission | Upcoming |
| Week 9 | June 29 – July 7 | Elevence review and project closure | Upcoming |

---

# 12. Final Project Summary

*This section will be filled in fully once all 6 tasks are complete and Elevence has reviewed the work. The content below is based on what has been done so far.*

## Quick Summary

| Field | Detail |
|-------|--------|
| Project | Elevence Data Analysis Portfolio |
| Analyst | Sai Reddy |
| Duration | May 7, 2026 – July 7, 2026 |
| Total Tasks | 6 |
| Tasks Done | 3 |
| Review | After all 6 tasks are submitted |

## What I Have Delivered So Far

**Task 1 — Financial Risk Inventory**
I analyzed Elevence's product data and found that around 14.4% of their inventory value is financially at risk. These are products with heavy discounts and low customer ratings. The dashboard makes it easy to filter and identify these products so the business team can take action.

**Task 2 — Discount vs Rating Causation Analysis**
I looked at whether giving customers bigger discounts leads to better ratings. My finding was that it does not. Ratings stay between 3.5 and 4.5 no matter how high the discount is. This tells Elevence that discounts bring more buyers but do not improve how people feel about the product.

**Task 3 — Promotion Effectiveness Trend**
I analyzed how promotions affect customer engagement over time. I found that during promotion periods, the number of reviews goes up significantly. However, the average rating does not improve. This means promotions create activity but not loyalty.

## What I Learned

1. Cleaning the data took more time than I expected — I had to handle missing values and fix data types before I could build anything useful
2. Writing clear, simple insights in the README was just as important as building a good dashboard
3. Pushing work to GitHub regularly helped me stay organized and never lose progress
4. Managing my own timeline without a supervisor checking in taught me a lot about self-discipline
5. Breaking a big problem into smaller business questions made each task much easier to approach

## Sign-Off

| Role | Name | Date |
|------|------|------|
| Business Analyst Intern | Sai Reddy | To be filled after review |
| Elevence Reviewer | — | To be filled after review |

---

*Last updated: June 2026*
*This workspace was built as part of a 2-month Business Analyst internship at Elevence.*
*All dashboards and code are available at: https://github.com/2300031146/elevence-tasks*
