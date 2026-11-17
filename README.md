# Software Project Management – ProjectLibre Practicals (1–9)

![Subject](https://img.shields.io/badge/Subject-Software_Project_Management_%28SPM%29-0A66C2?style=flat-square)
![Software](https://img.shields.io/badge/Software-ProjectLibre-2EA44F?style=flat-square)
![Practicals](https://img.shields.io/badge/Total_Practicals-9-F59E0B?style=flat-square)
![Format](https://img.shields.io/badge/Format-MS_Project_XML_%28.xml%29-6366F1?style=flat-square)

A structured collection of **Software Project Management (SPM)** laboratory practicals created for **ProjectLibre**. This repository provides ready-to-import Microsoft Project XML interchange files (`.xml`) covering end-to-end project management workflows across **9 practical exercises**, along with a generalized 20-phase master project template.

- **Subject:** Software Project Management (SPM)
- **Software Used:** ProjectLibre
- **Total Practicals:** 9 (`SPM_Practical_1.xml` – `SPM_Practical_9.xml`)
- **Master Templates Included:** `SPM_General_Master_Template.xml` and `SPM_Detailed.xml`

---

## Table of Contents

- [About the Repository](#about-the-repository)
- [Practical-Wise Documentation](#practical-wise-documentation)
- [Detailed Practical Overview](#detailed-practical-overview)
- [Repository Structure](#repository-structure)
- [How to Open the Practicals](#how-to-open-the-practicals)
- [Concepts Covered](#concepts-covered)
- [Author](#author)
- [Footer](#footer)

---

## About the Repository

This repository contains practical exercises demonstrating core Software Project Management methodologies using **ProjectLibre**, including:

- **Project Planning & Working Calendars:** Defining standard working days, daily shifts, and non-working intervals.
- **Task Management & Scheduling:** Structuring project task lists, estimating task durations, and computing start/finish dates.
- **Work Breakdown Structure (WBS):** Organizing project activities into a 20-phase hierarchical structure (20 summary tasks and 60 indented child tasks; 80 tasks in total).
- **Gantt Charts & Network (PERT) Diagrams:** Visualizing task timelines, summary roll-ups, critical paths, and sequential activity networks.
- **Checkpoints & Milestones:** Tracking zero-duration milestones (`PT0H0M0S`) and 1-day review checkpoints (`PT8H0M0S`).
- **Dependencies & Scheduling Constraints:** Linking tasks via Finish-to-Start (`FS`) predecessor relationships and evaluating scheduling constraints such as *Start No Earlier Than (SNET)*.
- **Resource Allocation & Documentation:** Defining a pool of 8 project roles, documenting role responsibilities in Resource Notes, and mapping 60 resource assignments across project tasks.

> **Note on File Format:** All project files in this repository are provided as Microsoft Project XML interchange files (`.xml`) supported for direct import into ProjectLibre. Native serialized `.pod` files and static screenshots are not pre-bundled in the repository; once imported into ProjectLibre, any practical can be inspected interactively and saved as a native `.pod` file (`File > Save As > ProjectLibre (*.pod)`).

---

## Practical-Wise Documentation

| No. | Practical Title | Description | Files |
| :---: | :--- | :--- | :--- |
| **1** | **Practical 1:** Setup of Working Calendar | Configures the base `Standard` working calendar (Monday–Friday, `08:00–12:00` and `13:00–17:00`, 8 hours/day, 40 hours/week, with weekends non-working). The main learning objective is to establish working time rules and calendar definitions that govern how ProjectLibre schedules all project activities. | [`SPM_Practical_1.xml`](./SPM_Practical_1.xml) |
| **2** | **Practical 2:** Project Task List and Schedule | Defines a complete 80-row project task list (20 summary phases and 60 subtasks) with task durations and sequential Finish-to-Start (`FS`) predecessor links. The main learning objective is to build an automated project schedule and understand how task durations and links determine start and finish dates. | [`SPM_Practical_2.xml`](./SPM_Practical_2.xml) |
| **3** | **Practical 3:** Network (PERT) Diagram | Models the logical sequence of project tasks and inter-task dependencies as a connected project network. The main learning objective is to inspect and analyze activity flow, predecessor/successor chains, and critical sequence relationships using ProjectLibre's Network Diagram (PERT) view. | [`SPM_Practical_3.xml`](./SPM_Practical_3.xml) |
| **4** | **Practical 4:** Gantt Chart | Represents the project schedule visually across a horizontal calendar timeline using task bars, summary roll-up bars, milestone diamonds, and dependency arrows. The main learning objective is to interpret timeline progress, phase roll-ups, and linked task schedules in the Gantt Chart view. | [`SPM_Practical_4.xml`](./SPM_Practical_4.xml) |
| **5** | **Practical 5:** Manage, Plan and Organize Project Activities | Organizes project activities into logical summary phases (`OutlineLevel 1`) and child subtasks (`OutlineLevel 2`), including a dedicated `Split Activity` exercise placeholder. The main learning objective is to structure project work packages and practice interactive activity operations (`Indent`, `Outdent`, and `Split Task`) in ProjectLibre. | [`SPM_Practical_5.xml`](./SPM_Practical_5.xml) |
| **6** | **Practical 6:** Hierarchical Task Structure Using Indent, Outdent and Split Task | Demonstrates a two-level Work Breakdown Structure (WBS `1` to `20`, with child tasks `x.1`–`x.3`) linked by Finish-to-Start predecessors. The main learning objective is to manage hierarchical task relationships and observe how modifying upstream task durations propagates schedule shifts across downstream phases. | [`SPM_Practical_6.xml`](./SPM_Practical_6.xml) |
| **7** | **Practical 7:** Identify Project Tasks, Checkpoints and Milestones | Distinguishes between regular work activities (2 working days), 1-day quality/status review checkpoints (`PT8H0M0S`), and zero-duration milestones (`PT0H0M0S`). The main learning objective is to establish governance gates, progress checkpoints, and formal sign-off milestones across the project lifecycle. | [`SPM_Practical_7.xml`](./SPM_Practical_7.xml) |
| **8** | **Practical 8:** Task Duration, Dependencies and Scheduling Constraints | Combines task duration estimates and Finish-to-Start predecessor links with a dedicated `Date Constraint` task (`WBS 16.1`) for constraint testing. The main learning objective is to evaluate how applying scheduling constraints (such as *Start No Earlier Than*) impacts downstream dates and the overall project finish date. | [`SPM_Practical_8.xml`](./SPM_Practical_8.xml) |
| **9** | **Practical 9:** Assign the Resources and Set the Notes for Resources | Configures 8 work resources (`Project Manager`, `Business Analyst`, `Designer`, `Developer`, `Software Tester`, `DevOps Engineer`, `Reviewer`, and `Project Coordinator`) with detailed role notes and 60 task assignments. The main learning objective is to manage the Resource Sheet, document resource responsibilities in notes, and allocate resources to project tasks. | [`SPM_Practical_9.xml`](./SPM_Practical_9.xml) |

**Additional Reference Files in Root:**
- [`SPM_General_Master_Template.xml`](./SPM_General_Master_Template.xml) — Generalized master project plan with 20 main phases and 3 child subtasks under each phase.
- [`SPM_Detailed.xml`](./SPM_Detailed.xml) — Detailed copy of the generalized 20-phase SPM project plan.
- [`README_Practicals_1_to_9.txt`](./README_Practicals_1_to_9.txt) — Original plain-text overview and practical mapping notes.

---

## Detailed Practical Overview

Click on any practical below to expand its objective, key concepts, workflow, file links, and expected learning outcomes.

<details>
<summary><strong>Practical 1: Setup of Working Calendar</strong></summary>

<br>

- **Practical Number & Title:** Practical 1: Setup of Working Calendar
- **Objective:** Configure and verify a standard project working calendar in ProjectLibre to define working days, daily working hours, and non-working weekend periods.
- **Key Concepts Demonstrated:**
  - Base calendar configuration (`Standard` calendar)
  - Working vs. non-working days (Monday–Friday working; Saturday–Sunday non-working)
  - Split daily working shifts (`08:00–12:00` and `13:00–17:00`, totaling 8 hours/day and 40 hours/week)
  - Calendar impact on task duration and date calculation
- **Workflow & Implementation Details:**
  1. Import [`SPM_Practical_1.xml`](./SPM_Practical_1.xml) into ProjectLibre.
  2. Inspect **WBS Phase 4 (`Calendar Setup`)**, which highlights three focus tasks annotated with Practical 1 instructions:
     - `WBS 4.1` — **Working Week**
     - `WBS 4.2` — **Daily Hours**
     - `WBS 4.3` — **Holiday Calendar**
  3. Open the **Calendar** settings in ProjectLibre (`File > Calendar` or `Task > Calendar`) to inspect the `Standard` calendar definition and optionally add custom holiday/non-working exceptions.
- **Project File Link:** [`SPM_Practical_1.xml`](./SPM_Practical_1.xml)
- **Expected Learning Outcome:** Ability to establish organizational working time rules and calendars so that task durations automatically respect working hours, weekends, and holidays.

</details>

<details>
<summary><strong>Practical 2: Project Task List and Schedule</strong></summary>

<br>

- **Practical Number & Title:** Practical 2: Project Task List and Schedule
- **Objective:** Construct a structured project task list with defined task durations and predecessor links to generate a complete forward-scheduled project plan.
- **Key Concepts Demonstrated:**
  - Comprehensive task enumeration across 20 software project phases (from *Project Initiation* to *Project Closure*)
  - Duration estimation (`480 minutes/day` = 8 working hours/day; standard tasks set to 2 days / `PT16H0M0S`)
  - Finish-to-Start (`FS`) sequential task linking
  - Automated calculation of task Start and Finish dates
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_2.xml`](./SPM_Practical_2.xml) in ProjectLibre.
  2. Review the tabular task sheet containing 80 rows (20 summary phases and 60 child tasks) spanning `2026-04-06` to `2026-08-27`.
  3. Examine the highlighted focus tasks for Practical 2:
     - `WBS 5.2` — **Task Duration** (`Effort Estimation` phase)
     - `WBS 7.1` — **Task Sequence** (`Schedule Planning` phase)
     - `WBS 7.3` — **Schedule Baseline** (`Schedule Planning` milestone)
  4. Verify how each subtask links to its predecessor and automatically computes start and finish timestamps.
- **Project File Link:** [`SPM_Practical_2.xml`](./SPM_Practical_2.xml)
- **Expected Learning Outcome:** Proficiency in entering project tasks, assigning durations, linking predecessors, and interpreting the resulting project schedule.

</details>

<details>
<summary><strong>Practical 3: Network (PERT) Diagram</strong></summary>

<br>

- **Practical Number & Title:** Practical 3: Network (PERT) Diagram
- **Objective:** Generate and analyze a Network (PERT) Diagram to visualize logical task dependencies, activity flow, and sequence chains.
- **Key Concepts Demonstrated:**
  - Program Evaluation and Review Technique (PERT) / Activity-on-Node (AoN) network representation
  - Predecessor and successor task relationships
  - Sequential dependency chains across phases
  - Visual identification of critical path flow
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_3.xml`](./SPM_Practical_3.xml) in ProjectLibre.
  2. Inspect **WBS Phase 8 (`Task Linking`)**, which contains the focus tasks for this practical:
     - `WBS 8.1` — **Predecessor Links**
     - `WBS 8.2` — **Successor Links**
     - `WBS 8.3` — **Network Diagram**
  3. *Interactive Step Required in ProjectLibre:* Navigate to **View > Network** (PERT Diagram view) in ProjectLibre to render the connected activity nodes and inspect how task dependencies form an end-to-end network.
- **Project File Link:** [`SPM_Practical_3.xml`](./SPM_Practical_3.xml)
- **Expected Learning Outcome:** Ability to switch between tabular schedules and network diagrams to validate dependency logic and trace predecessor-successor paths.

</details>

<details>
<summary><strong>Practical 4: Gantt Chart</strong></summary>

<br>

- **Practical Number & Title:** Practical 4: Gantt Chart
- **Objective:** Visualize and inspect the project schedule using ProjectLibre's Gantt Chart view, examining task bars, summary roll-ups, milestones, and dependency connectors.
- **Key Concepts Demonstrated:**
  - Horizontal bar chart timeline representation
  - Summary phase roll-up bars (`Summary = 1`) vs. individual work task bars
  - Milestone diamond markers (`Milestone = 1`)
  - Finish-to-Start dependency arrows connecting consecutive tasks
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_4.xml`](./SPM_Practical_4.xml) in ProjectLibre.
  2. Review the annotated focus tasks for Practical 4:
     - `WBS 7.1` — **Task Sequence**
     - `WBS 12.2` — **Progress Updates**
     - `WBS 19.3` — **Schedule Forecast**
  3. *Interactive Step Required in ProjectLibre:* Open the **Gantt Chart** view, zoom/scroll across the timeline to inspect task bars, summary bars, and dependency arrows, and capture a Gantt view screenshot if required for lab submission.
- **Project File Link:** [`SPM_Practical_4.xml`](./SPM_Practical_4.xml)
- **Expected Learning Outcome:** Competence in reading and presenting Gantt charts to communicate project timelines, phase durations, and task interdependencies.

</details>

<details>
<summary><strong>Practical 5: Manage, Plan and Organize Project Activities</strong></summary>

<br>

- **Practical Number & Title:** Practical 5: Manage, Plan and Organize Project Activities
- **Objective:** Organize project tasks into structured summary groups and perform task manipulation operations including `Indent`, `Outdent`, and `Split Task`.
- **Key Concepts Demonstrated:**
  - Grouping related activities under summary phases (`OutlineLevel 1` and `OutlineLevel 2`)
  - Indenting and outdenting tasks to modify outline levels
  - Splitting an interrupted task (`Split Task`) to introduce a non-working gap between work segments
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_5.xml`](./SPM_Practical_5.xml) in ProjectLibre.
  2. Locate the annotated focus tasks in **Phase 6 (`Work Structuring`)** and **Phase 7 (`Schedule Planning`)**:
     - `WBS 6.1` — **Task Breakdown**
     - `WBS 6.2` — **Indent Tasks**
     - `WBS 6.3` — **Outdent Tasks**
     - `WBS 7.2` — **Split Activity** (2-day / 16-hour task placeholder)
  3. *Interactive Step Required in ProjectLibre:* Select `WBS 6.2` / `WBS 6.3` to test the **Indent** and **Outdent** commands on the Task ribbon, and execute **Task > Split** on `WBS 7.2 (Split Activity)` in the Gantt chart to create a visible work gap between its segments.
- **Project File Link:** [`SPM_Practical_5.xml`](./SPM_Practical_5.xml)
- **Expected Learning Outcome:** Practical mastery over organizing work packages, adjusting task hierarchy levels, and modeling work interruptions using task splits.

</details>

<details>
<summary><strong>Practical 6: Hierarchical Task Structure Using Indent, Outdent and Split Task</strong></summary>

<br>

- **Practical Number & Title:** Practical 6: Hierarchical Task Structure Using Indent, Outdent and Split Task
- **Objective:** Build and analyze a multi-level Work Breakdown Structure (WBS) and observe how duration changes in upstream tasks propagate through linked hierarchical phases.
- **Key Concepts Demonstrated:**
  - Work Breakdown Structure (WBS) numbering (`1` through `20`, with subtasks `x.1`, `x.2`, `x.3`)
  - Summary duration roll-up calculation from indented child tasks
  - Dynamic schedule recalculation across linked WBS phases
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_6.xml`](./SPM_Practical_6.xml) in ProjectLibre.
  2. Examine the 20 summary tasks (`OutlineLevel 1`) and 60 indented child tasks (`OutlineLevel 2`), focusing on:
     - `WBS 6.1` — **Task Breakdown**
     - `WBS 6.2` — **Indent Tasks**
     - `WBS 6.3` — **Outdent Tasks**
     - `WBS 7.1` — **Task Sequence**
     - `WBS 8.1` — **Predecessor Links**
  3. *Interactive Step Required in ProjectLibre:* Modify the duration of an upstream subtask (e.g., increasing a 2-day task to 4 days) and observe how the parent summary bar expands and all downstream dependent dates shift automatically.
- **Project File Link:** [`SPM_Practical_6.xml`](./SPM_Practical_6.xml)
- **Expected Learning Outcome:** Deep understanding of WBS hierarchy, summary task roll-ups, and dynamic schedule propagation in ProjectLibre.

</details>

<details>
<summary><strong>Practical 7: Identify Project Tasks, Checkpoints and Milestones</strong></summary>

<br>

- **Practical Number & Title:** Practical 7: Identify Project Tasks, Checkpoints and Milestones
- **Objective:** Differentiate between standard execution tasks, short-duration review checkpoints, and zero-duration milestones within a project schedule.
- **Key Concepts Demonstrated:**
  - **Standard Project Tasks:** 2-day (`PT16H0M0S`) work activities representing deliverables and execution steps
  - **Checkpoints:** 1-day (`PT8H0M0S`) review and inspection activities used to verify quality before sign-off
  - **Milestones:** Zero-duration (`PT0H0M0S`, `Milestone = 1`) markers representing major phase completions and approval gates
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_7.xml`](./SPM_Practical_7.xml) in ProjectLibre.
  2. Inspect **WBS Phase 9 (`Milestone Planning`)** and **WBS Phase 10 (`Progress Checkpoints`)**, which highlight the focus items for this practical:
     - Zero-duration Milestones (`PT0H0M0S`): `WBS 9.1 (Start Milestone)`, `WBS 9.2 (Review Milestone)`, `WBS 9.3 (Final Milestone)`, and `WBS 10.3 (Approval Gate)` (plus `WBS 1.3 Project Kickoff`, `WBS 3.3 Acceptance Criteria`, `WBS 7.3 Schedule Baseline`, and `WBS 20.3 Final Signoff` across the plan).
     - 1-Day Checkpoints (`PT8H0M0S`): `WBS 10.1 (Status Review)` and `WBS 10.2 (Quality Check)` (along with `WBS 15.1 Work Inspection` and `WBS 15.2 Formal Approval`).
  3. Compare how regular task bars, 1-day checkpoint bars, and diamond milestone symbols appear in the Gantt Chart view.
- **Project File Link:** [`SPM_Practical_7.xml`](./SPM_Practical_7.xml)
- **Expected Learning Outcome:** Ability to model project governance using checkpoints for quality assurance and zero-duration milestones for key decision gates.

</details>

<details>
<summary><strong>Practical 8: Task Duration, Dependencies and Scheduling Constraints</strong></summary>

<br>

- **Practical Number & Title:** Practical 8: Task Duration, Dependencies and Scheduling Constraints
- **Objective:** Analyze how task durations, Finish-to-Start dependencies, and calendar date constraints interact to control project start and finish dates.
- **Key Concepts Demonstrated:**
  - Task duration configuration (`PT16H0M0S` / 2 days and `PT8H0M0S` / 1 day)
  - Finish-to-Start (`FS`) dependency chains
  - Scheduling constraints (specifically *Start No Earlier Than – SNET*) vs. default *As Soon As Possible (ASAP)* scheduling
  - Schedule variance and finish-date comparison
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_8.xml`](./SPM_Practical_8.xml) in ProjectLibre.
  2. Review the annotated focus tasks:
     - `WBS 5.2` — **Task Duration**
     - `WBS 8.1` — **Predecessor Links**
     - `WBS 16.1` — **Date Constraint** (`Schedule Control` phase)
     - `WBS 16.2` — **Schedule Variance** (`Schedule Control` phase)
  3. *Interactive Step Required in ProjectLibre:* Double-click `WBS 16.1 (Date Constraint)` (or another downstream task), go to the **Advanced** tab in Task Information, apply a **Start No Earlier Than (SNET)** constraint with a future date, and compare the overall project finish date before and after applying the constraint.
- **Project File Link:** [`SPM_Practical_8.xml`](./SPM_Practical_8.xml)
- **Expected Learning Outcome:** Ability to configure scheduling constraints in ProjectLibre and evaluate their impact on schedule flexibility, float, and project completion dates.

</details>

<details>
<summary><strong>Practical 9: Assign the Resources and Set the Notes for Resources</strong></summary>

<br>

- **Practical Number & Title:** Practical 9: Assign the Resources and Set the Notes for Resources
- **Objective:** Define project work resources, document their roles and responsibilities using Resource Notes, and assign resources to project tasks.
- **Key Concepts Demonstrated:**
  - Resource Sheet configuration (8 work resources with standard rates and 100% max units)
  - Resource Notes documentation for role clarity and governance
  - Mapping resource assignments (`60 assignments`) across the 60 non-summary project subtasks
- **Workflow & Implementation Details:**
  1. Open [`SPM_Practical_9.xml`](./SPM_Practical_9.xml) in ProjectLibre.
  2. Switch to **View > Resources** (Resource Sheet) to inspect the 8 pre-configured work resources and their embedded **Notes**:
     - `Project Manager` — *Coordination, approvals, reporting and schedule control.*
     - `Business Analyst` — *Requirements, scope, acceptance criteria and reviews.*
     - `Designer` — *Design, models, interfaces and documentation.*
     - `Developer` — *Implementation, integration and technical updates.*
     - `Software Tester` — *Test planning, validation and defect verification.*
     - `DevOps Engineer` — *Packaging, deployment, release and transition.*
     - `Reviewer` — *Independent reviews, checkpoints and approvals.*
     - `Project Coordinator` — *Resource coordination, notes, tracking and records.*
  3. Switch back to the **Gantt** or **Task Usage** view and inspect **WBS Phase 17 (`Resource Planning`)**:
     - `WBS 17.1` — **Team Selection**
     - `WBS 17.2` — **Task Assignment**
     - `WBS 17.3` — **Resource Notes**
- **Project File Link:** [`SPM_Practical_9.xml`](./SPM_Practical_9.xml)
- **Expected Learning Outcome:** Competence in setting up a project resource pool, documenting role metadata in resource notes, and assigning resources to work packages.

</details>

---

## Repository Structure

```text
SPM19/
├── README.md                         # Comprehensive documentation for Practicals 1–9
├── README_Practicals_1_to_9.txt      # Plain-text practical mapping and interaction notes
├── SPM_Detailed.xml                  # Detailed 20-phase generalized SPM project plan (XML)
├── SPM_General_Master_Template.xml   # Master template with 20 phases & 60 child tasks (XML)
├── SPM_Practical_1.xml               # Practical 1: Setup of Working Calendar
├── SPM_Practical_2.xml               # Practical 2: Project Task List and Schedule
├── SPM_Practical_3.xml               # Practical 3: Network (PERT) Diagram
├── SPM_Practical_4.xml               # Practical 4: Gantt Chart
├── SPM_Practical_5.xml               # Practical 5: Manage, Plan and Organize Project Activities
├── SPM_Practical_6.xml               # Practical 6: Hierarchical Task Structure Using Indent, Outdent and Split Task
├── SPM_Practical_7.xml               # Practical 7: Identify Project Tasks, Checkpoints and Milestones
├── SPM_Practical_8.xml               # Practical 8: Task Duration, Dependencies and Scheduling Constraints
└── SPM_Practical_9.xml               # Practical 9: Assign the Resources and Set the Notes for Resources
```

---

## How to Open the Practicals

> **Understanding `.pod` vs `.xml` Formats:**
> - **`.pod` (ProjectLibre Open Document):** ProjectLibre's native binary serialization format used when saving projects directly inside ProjectLibre.
> - **`.xml` (Microsoft Project XML Interchange):** A standardized, human-readable XML format supported by both ProjectLibre and Microsoft Project for cross-platform project interchange. All practicals in this repository are stored in `.xml` format for portability and version control transparency.

Follow these steps to open, explore, and save the practicals on your machine:

1. **Install ProjectLibre:**
   Download and install **ProjectLibre** (free and open-source) from [projectlibre.com](https://www.projectlibre.com/) or SourceForge for Windows, macOS, or Linux.
2. **Clone or Download this Repository:**
   ```bash
   git clone https://github.com/Sonu1011/SPM19.git
   cd SPM19
   ```
   *(Alternatively, click **Code > Download ZIP** on GitHub and extract the folder.)*
3. **Open ProjectLibre:**
   Launch the ProjectLibre application and close the welcome dialog or click **Open Project**.
4. **Open the Relevant `.xml` (or `.pod`) File:**
   Navigate to the cloned `SPM19` directory, select the desired file (e.g., `SPM_Practical_1.xml` through `SPM_Practical_9.xml`), and click **Open**. ProjectLibre automatically imports Microsoft Project `.xml` files.
5. **Save as Native `.pod` (If Required):**
   If your coursework submission requires a native `.pod` file, go to **File > Save As**, choose **ProjectLibre (`*.pod`)** as the file type, and save a copy.
6. **Explore Project Views and Features:**
   - **Gantt Chart (`View > Gantt`):** Inspect task bars, summary roll-ups, milestone diamonds, and dependency links.
   - **Network Diagram (`View > Network`):** View the PERT activity network and trace task sequences.
   - **WBS / Task Hierarchy:** Expand or collapse the 20 summary phases, and double-click tasks to read the embedded **Notes** tab for practical-specific guidance.
   - **Resource Sheet (`View > Resources`):** Inspect the 8 assigned project roles, standard rates, and detailed role notes.

---

## Concepts Covered

- **Working Calendars:** Configuring standard working weeks (Monday–Friday), daily shift hours (`08:00–12:00`, `13:00–17:00`), and non-working weekends/holidays.
- **Project Scheduling:** Automated forward scheduling from a defined project start date (`2026-04-06`) based on task durations and logical links.
- **Task Lists:** Organizing 80 project rows across 20 end-to-end software engineering phases.
- **PERT / Network Diagrams:** Activity-on-Node (AoN) visualization of task sequences, predecessors, and successors.
- **Gantt Charts:** Visual timeline tracking of task bars, phase summary bars, milestones, and dependency connectors.
- **Work Breakdown Structure (WBS):** Hierarchical decomposition of project scope into 20 Level-1 summary phases (`WBS 1`–`20`) and 60 Level-2 work packages (`WBS x.1`–`x.3`).
- **Task Indentation and Splitting:** Modifying outline hierarchy using `Indent` and `Outdent`, and modeling interrupted execution using `Split Task`.
- **Milestones and Checkpoints:** Differentiating zero-duration approval/phase milestones (`PT0H0M0S`) from 1-day quality/status review checkpoints (`PT8H0M0S`).
- **Task Dependencies:** Sequencing project execution through Finish-to-Start (`FS`) predecessor relationships.
- **Scheduling Constraints:** Applying date constraints such as *Start No Earlier Than (SNET)* and analyzing schedule variance.
- **Resource Assignment and Resource Notes:** Establishing a multi-role resource pool, documenting role responsibilities in Resource Notes, and mapping resources to project tasks.

---

## Author

**Saumyya Manish Dalal**

- **GitHub:** [@Sonu1011](https://github.com/Sonu1011)

---

## Footer

This repository was created for academic and educational purposes as part of the **Software Project Management (SPM)** coursework to demonstrate project planning, scheduling, and resource management using **ProjectLibre**.

🔗 **Repository Link:** [https://github.com/Sonu1011/SPM19](https://github.com/Sonu1011/SPM19)
