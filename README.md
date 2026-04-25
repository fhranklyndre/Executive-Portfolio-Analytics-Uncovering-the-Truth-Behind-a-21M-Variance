# Executive Portfolio Analytics - Uncovering the Truth Behind a £21M Variance

##  Project Overview

**At first glance, the portfolio shows a £21M budget underspend.  
However, deeper analysis reveals this is driven by under-delivery and delayed execution, not true efficiency.**

This project explores how seemingly positive financial metrics can mask underlying operational issues. It delivers an end-to-end **portfolio analytics dashboard** designed to move beyond surface-level reporting and uncover the true drivers of performance across a complex portfolio of 700+ projects.

Rather than simply presenting metrics, the dashboard answers critical questions around **execution, risk, and financial sustainability**, providing a clearer picture of whether projects are delivering real value or quietly accumulating risk.

---

##  Objectives

- Assess overall portfolio performance  
- Identify cost overruns and financial risks  
- Detect delayed and underperforming projects  
- Analyse dependency-driven risks  
- Enable data-driven prioritisation of interventions  

---

##  Business Context

The organisation operates across multiple business domains, including IT Infrastructure, Customer Experience, Corporate Services, Digital Transformation, and Data & Analytics. Each of these areas contributes to a large and interconnected portfolio of strategic initiatives.

Managing such a portfolio introduces significant complexity. Projects are not only evaluated on individual performance, but also on how they interact with one another through shared resources, dependencies, and timelines. As the portfolio grows, it becomes increasingly difficult to maintain visibility over delivery performance, cost efficiency, and emerging risks.

In this environment, leadership requires more than isolated reports, they need a **unified, data-driven view** that connects financial performance with operational execution.

---

##  Key Business Problem

While the portfolio reported a **£21M favourable budget variance**, this metric alone did not provide meaningful insight into overall performance. The central challenge was determining whether this underspend reflected genuine efficiency or masked deeper issues within project execution.

Without a structured analytical approach, it was difficult to identify where delays were occurring, how widespread underperformance was, and which projects posed the greatest risk to the organisation. Additionally, the interconnected nature of the portfolio meant that delays in one area could have cascading effects elsewhere, further complicating decision-making.

The problem, therefore, was not a lack of data, but a lack of **contextualised insight**, the ability to interpret financial and operational data together to understand the true state of the portfolio.

---

##  Tech Stack

- **SQL (SSMS)** — data exploration, data transformation, validation, and analytical views  
- **Power BI** — data modelling and dashboard development  
- **DAX** — business logic and calculations   

---

##  Dataset

The dataset consists of over **700 project records**, capturing enterprise-level portfolio data across project status, completion metrics, financials (budget, actual cost, and forecast), milestone timelines, risk levels, and inter-project dependencies.

It supports analysis across financial performance, delivery progress, and risk exposure, while also enabling dependency mapping to assess how delays in one project can impact others across the portfolio.

---

##  Dashboard Structure

The dashboard is structured into three layers:

- **Executive Summary** — a high-level view of portfolio health, risk distribution, and performance trends  
- **Financial & Delivery Risk** — analysis of cost variance, delays, and underperforming projects  
- **Risk & Dependencies** — identification of bottlenecks, cascading risks, and intervention priorities  

---

##  Analysis

The analysis combined financial, operational, and dependency data to evaluate how effectively the portfolio is being executed.

At a headline level, the portfolio shows a **£21M underspend (Actual < Budget)**. However, this sits alongside **566 projects with forecasted costs exceeding their budgets**, indicating significant future financial pressure.

Delivery performance was assessed by comparing **time elapsed against completion levels**. This revealed **70 projects that have used more than 50% of their timeline but remain less than 50% complete**, as well as **18 critical projects nearing timeline exhaustion (around 80% time used with limited progress)**.

In addition, **~37% of projects are currently At Risk or Delayed**, highlighting widespread delivery challenges across the portfolio. By combining cost and delay metrics, “double jeopardy” projects were identified, those simultaneously behind schedule and trending towards overspend.

Finally, dependency analysis exposed key projects acting as bottlenecks, where delays have the potential to cascade across multiple downstream initiatives.

---

##  Key Insights

The £21M underspend is not a reflection of efficiency, but rather a symptom of execution gaps within the portfolio.

Despite this favourable variance, **~37% of projects are currently At Risk or Delayed**, and **70 projects have already consumed more than 50% of their timeline while remaining less than 50% complete**. In more severe cases, **18 projects are nearing timeline exhaustion (around 80% time used) with limited progress**, highlighting critical delivery failure risks.

At the same time, **566 projects are forecasted to exceed their budgets**, indicating that the current underspend is likely to reverse into future cost pressure.

This suggests that allocated budgets have not been fully utilised not because of efficiency, but because **planned work has not yet been delivered**. In parallel, some projects remain in early stages, where spend has not fully materialised.

As a result, the portfolio presents a misleading financial position: what appears as savings is, in reality, **deferred spend and incomplete execution**, increasing the likelihood of future cost overruns and compounded risk.

Dependency analysis further reinforces this, showing that delays are not isolated but interconnected, with key projects acting as bottlenecks capable of impacting multiple downstream initiatives across the portfolio.
---

##  Recommendations

The analysis highlights the need for a more proactive and execution-focused approach to portfolio management. Priority should be given to projects that show a mismatch between time consumed and progress made, as these represent the highest risk of failure if left unaddressed. 

Greater attention should also be placed on early-stage projects that already exhibit elevated risk levels, as intervening at this stage offers the best opportunity to prevent escalation. In addition, resolving dependency bottlenecks is critical, as delays in key projects can propagate across the portfolio and amplify overall risk exposure.

Ultimately, improving alignment between budget allocation and actual delivery progress will ensure that financial performance reflects real value creation rather than deferred activity.

---

##  Future Improvements

Future enhancements to this project would focus on deepening the analytical capability and improving real-time decision support. Introducing historical tracking of project status would enable true lifecycle analysis, allowing for a clearer understanding of how projects evolve over time.

Incorporating predictive modelling could further strengthen the solution by identifying projects at risk of delay or overspend before issues fully materialise. Automating data pipelines would also allow for more frequent updates, moving the dashboard closer to real-time monitoring.

Finally, expanding the scope of analysis to include resource utilisation and return on investment would provide a more comprehensive view of portfolio effectiveness and strategic value.

---

##  Dashboard Preview

<img width="1377" height="721" alt="Executive summary" src="https://github.com/user-attachments/assets/561752f1-64a2-468d-afe1-4bf2a9ebcc8d" />


---

##  Summary

A £21M underspend may appear positive at first glance, but deeper analysis reveals it is driven by **under-delivery and delayed execution rather than true efficiency**.

This project demonstrates how combining financial, operational, and dependency analysis can uncover hidden risks and provide a more accurate and actionable view of portfolio performance.

---

##  Tags

`Power BI` `SQL` `DAX` `Data Analytics` `Business Intelligence`  
`Portfolio Management` `Dashboard Design` `Data Visualization`

---

## 👤 Author

**Nwafor Franklin**  
Data Analyst | Power BI | SQL | Analytics
