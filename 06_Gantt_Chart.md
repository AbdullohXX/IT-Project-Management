# Gantt Chart — E-Commerce Sales Analysis

## Project Schedule

```mermaid
gantt
    title E-Commerce Sales Analysis Project Schedule
    dateFormat  YYYY-MM-DD
    axisFormat  %d %b

    section Planning
    Project planning and objectives      :done, p1, 2026-09-07, 7d
    Team agreement and role assignment   :done, p2, 2026-09-10, 4d
    Requirements and scope review        :done, p3, 2026-09-12, 5d

    section System Modeling
    Use case model                       :done, m1, 2026-09-15, 4d
    BPMN process model                   :done, m2, 2026-09-17, 4d
    WBS preparation                      :done, m3, 2026-09-19, 3d

    section Data Preparation
    Dataset selection                    :d1, 2026-09-14, 7d
    Data cleaning and transformation     :d2, after d1, 7d
    Data validation                      :d3, after d2, 3d

    section Analysis
    Sales analysis                       :a1, after d3, 6d
    Product and country analysis         :a2, after d3, 6d
    Customer and order-value analysis    :a3, after d3, 6d
    Visualization                        :a4, after a1, 4d

    section Finalization
    Interpret findings                   :f1, after a4, 3d
    Final report preparation             :f2, 2026-09-28, 7d
    Presentation preparation             :f3, 2026-10-05, 8d
    Final consistency review             :crit, f4, 2026-10-12, 2d
    Project presentation                 :milestone, f5, 2026-10-14, 0d
```

## Task Dependencies

| Task | Depends On | Main Owner |
|---|---|---|
| Dataset selection | Project objectives | Abdulloh |
| Data cleaning | Dataset selection | Abdulloh |
| Data validation | Data cleaning | Abdulloh / Najmiddin |
| Sales analysis | Validated dataset | Abdulloh |
| Visualizations | Analysis results | Abdulloh / Najmiddin |
| Findings and recommendations | Analysis + visualizations | Entire team |
| Final report | Planning models + analytical results | Abdulloh |
| Presentation | Finalized findings and report structure | Biloliddin |
| Final review | All deliverables | Entire team |

## Milestone
**14 October 2026 — Project Presentation**

This schedule replaces the earlier order-management Gantt example as the official timeline for the E-Commerce Sales Analysis project.
