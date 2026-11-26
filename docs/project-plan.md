# Project Plan

## 1. The tool

- **Name**: Student Assignment Deadline Tracker
- **One sentence**: A Python tool that reads student assignment information from a CSV file and identifies overdue assignments to help students manage their academic deadlines.
- **Category**: management
- **Track**: A only

## 2. Scope - input, one processing step, output

| | Our project |
|---|---|
| **Input** | assignments.csv containing course name, assignment name, deadline, and completion status. |
| **Processing step** | Identify incomplete assignments with deadlines earlier than the current date. |
| **Output** | Display a formatted table of overdue assignments in the terminal. |

**Definition of done**: one run command, one input, one output result.
Anything beyond that is track B, not the baseline.

## 3. Open source we plan to use

| Library | Why we need it | On the whitelist? |
|---|---|---|
| pandas | Reads assignment data from a CSV file and filters overdue assignments. | yes |
| rich | Displays assignment information in a clear, formatted table in the terminal. | yes |
| python-dateutil | Processes assignment deadlines and helps compare dates. | yes |

## 4. Team and roles

| Role | Who |
|---|---|
| PM | @torjoymorshad |
| Developer | @Islam-sajjadul |
| Documentation | @AminAl69 |
| Reviewer | @hasan6319 |

## 5. Schedule

| Chapter | What we finish |
|---|---|
| 11 | Repository set up, plan written, 3 issues opened, first feature branch |
| 12 | Core feature works end to end (the two blanks are filled) |
| 13 | Peer review, error handling, documentation complete, tests pass |
| Final submission | Final tag, "My contribution" written, peer evaluation done |

## 6. Risks

| What could go wrong | What we will do about it |
|---|---|
| <e.g. our input file has empty cells or extra columns> | <e.g. shrink to one column and validate it> |
