# BEND Integrated Shoe Store Management System

**Course:** System Analysis and Design  
**Project:** Integrated management system for BEND, a multi-branch shoe retailer (3 branches + online store).

This repository contains the project tasks as separate folders. Task documents record scope, steps, responsibilities, outputs and completion checklists. Quantitative values are planning estimates unless validated with real stakeholders.

## Project team (fictional academic role allocation)

| Role | Name |
|---|---|
| Project Manager | Karim Hassan |
| System Analyst | Sara Mostafa |
| Business Analyst | Omar Khaled |
| Financial Analyst | Mariam Adel |
| Technical Lead | Youssef Tarek |
| Documentation & QA | Hana Ibrahim |

These names are fictional project-role allocations and are not Jira user accounts. Jira issues therefore retain an empty Assignee field; the proposed owner and contributors are documented in each issue description.

## Jira tracking — first four course tasks

Jira project: **BEND System Analysis & Design** (Jira-generated key: `SCRUM`).

| Course task | Jira issue | Topic | Review state | Folder |
|---|---|---|---|---|
| Task 1 | [SCRUM-5](https://mahmoudelbendary025.atlassian.net/browse/SCRUM-5) | Current Problem + Project Description + System Request | Reviewed; sponsor approval evidence pending | [Task-1](Task-1) |
| Task 2 | [SCRUM-6](https://mahmoudelbendary025.atlassian.net/browse/SCRUM-6) | Feasibility Study | Reviewed; assumptions require validation | [Task-2](Task-2) |
| Task 3 | [SCRUM-7](https://mahmoudelbendary025.atlassian.net/browse/SCRUM-7) | Cash Flow Analysis | Reviewed; forecast assumptions require validation | [Task-3](Task-3) |
| Task 4 | [SCRUM-8](https://mahmoudelbendary025.atlassian.net/browse/SCRUM-8) | Methodology Selection & Justification | Reviewed; sponsor approval pending | [Task-4](Task-4) |

**Current Jira workflow state:** SCRUM-5, SCRUM-6, SCRUM-7 and SCRUM-8 are currently **To Do**. Their descriptions and acceptance criteria have been reviewed and aligned with the documents; they have not been moved to Done because sponsor approval and real-world validation are still pending. [Open the filtered Jira view for all four tasks](https://mahmoudelbendary025.atlassian.net/issues/?jql=project%20%3D%20SCRUM%20AND%20key%20in%20(SCRUM-5%2C%20SCRUM-6%2C%20SCRUM-7%2C%20SCRUM-8)%20ORDER%20BY%20key%20ASC).

## Remaining project tasks

| Task | Topic | Status | Folder |
|---|---|---|---|
| Task 5 | Time Estimation + Task Identification | Draft prepared – review required | [Task-5](Task-5) |
| Task 6 | PERT + Gantt Chart | Draft prepared – review required | [Task-6](Task-6) |
| Task 7 | Minimum 3 Interviews + Interview Report for Each | Templates prepared – conduct real interviews and complete reports | [Task-7](Task-7) |
| Task 8 | Minimum 2 Questionnaires + Screening Questions + Answers | Draft forms prepared – pilot, publish and collect real answers | [Task-8](Task-8) |

## Repository structure

- `Task-1/` – Current Problem, Project Description and System Request.
- `Task-2/` – Technical, economic and organizational feasibility.
- `Task-3/` – Three-year cash flow, ROI and break-even analysis.
- `Task-4/` – Methodology comparison and selection rationale.
- `Task-5/` – Project time estimate and planning task identification.
- `Task-6/` – Activity network, PERT interpretation, critical path and Gantt schedule.
- `Task-7/` – Three interview plans, question sets and report templates.
- `Task-8/` – Staff and customer questionnaires, screening questions and blank answer records.
- `Jira-First-Four-Tasks.md` – Current Jira issue mapping and acceptance criteria for SCRUM-5 to SCRUM-8.

## Consistency baseline for Tasks 1–4

- Current-state estimates: about 30 staff-hours/week for stock counting and reconciliation; 8% online order cancellations due to unavailable stock; EGP 75,000/year inventory shrinkage; EGP 15,000/year manual invoicing effort plus EGP 10,000/year tax penalties; management reports delayed 7–10 days.
- Initial targets: reduce stock counting/reconciliation to 18 hours/week, online cancellations to 1%, and electronically invoice 100% of sales. These are targets, not achieved results.
- Financial baseline: one-time investment EGP 295,000; annual operating cost EGP 44,000; Year-1 total cost EGP 339,000; three-year cost EGP 427,000; three-year benefits EGP 828,000; net benefit EGP 401,000; ROI approximately 94%; estimated break-even approximately 19.3 months after go-live.
- Project duration constraint: operational within 8 months / 160 working days.
- Methodology: Iterative (RAD) supported by Agile practices; three versions are planned for Days 56–95, 95–128 and 128–160.

## Important completion notes

1. All costs, benefits, operational baselines and forecasts are planning estimates, not audited actual results. Validate them with the sponsor and stakeholders.
2. Task 1's problem statement records the invoicing impact as EGP 15,000/year in manual effort plus EGP 10,000/year in tax penalties (EGP 25,000 combined impact).
3. Task 7 report templates are intentionally blank. Replace illustrative examples with notes from real interviews before marking the task Done.
4. Task 8 contains draft questionnaires. No real survey answers were provided; collect actual responses before reporting results or marking the task Done.
5. The three-version plan and the 160-working-day duration are planning baselines; update them only through an approved schedule change.
6. A Jira issue being created or its description being reviewed does not mean the academic deliverable has sponsor approval or has been completed in the real business.

## GitHub update

Upload the revised `Task-1` through `Task-4` documents, `README.md`, and `Jira-First-Four-Tasks.md` to the repository. Preserve `Task-5` through `Task-8` as they are until separately reviewed. Suggested commit message: `Align Tasks 1-4 documents with Jira and financial baseline`.
