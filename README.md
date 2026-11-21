# lab-agile-planning

Agile planning work for the **IBM DevOps & Software Engineering Professional Certificate**.

This repository holds the backlog of a back-end **product catalog for an e-commerce website**.
The stories were written as a product owner, refined into a sprint plan as a scrum master, and
executed across a Kanban board as a developer.

## Kanban board

The board lives in the GitHub Project **Final Project**:
https://github.com/users/LeonardoMarcelo/projects/2

Columns: `Icebox` → `Product Backlog` → `Sprint Backlog` → `In Progress` → `Review/QA` → `Done`

## Stakeholder requirements

| # | Requirement | Issue | Label |
|---|---|---|---|
| 1 | Create a product in the catalog | #7 | enhancement |
| 2 | Retrieve a product from the catalog | #8 | enhancement |
| 3 | Update a product in the catalog | #9 | enhancement |
| 4 | Delete a product from the catalog | #10 | enhancement |
| 5 | Like a product in the catalog | #11 | enhancement |
| 6 | Dislike a product in the catalog | #12 | enhancement |
| 7 | List all products in the catalog | #13 | enhancement |
| 8 | Query a subset of products in the catalog | #14 | enhancement |
| 9 | Must be hosted in the cloud | #15 | technical debt |
| 10 | Must have automation to deploy new changes to the cloud | #16 | technical debt |

Requirements 7 and 8 sit in the Icebox. Requirements 9 and 10 are tracked as technical debt.

## Sprint

The `Sprint` milestone runs for two weeks (Nov 21 – Dec 05, 2026) and covers the top four
stories of the product backlog, estimated in story points:

| Story | Estimate | End of sprint |
|---|---|---|
| #7 Create a product | 5 | Done |
| #8 Retrieve a product | 3 | Done |
| #9 Update a product | 5 | In Progress |
| #10 Delete a product | 3 | Sprint Backlog |

## Issue template

New stories are created from [`.github/ISSUE_TEMPLATE/user-story.md`](.github/ISSUE_TEMPLATE/user-story.md),
which follows the **As a… I need… So that…** format and writes acceptance criteria in
Gherkin (**Given… When… Then…**).
