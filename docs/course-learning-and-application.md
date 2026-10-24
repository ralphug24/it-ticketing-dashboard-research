# What I learned, and how I applied it

This guide connects my learning in IE 8020, Design of Human–Computer Systems (Spring 2025), to the team's IT ticketing dashboard project. My course journal records the methods covered in class; the submitted report and presentation document the team's application. I participated across interviews, needs analysis, specifications, concept sketches, Axure prototyping, usability testing, writing and coordination.

## 1. Frame a problem before choosing a feature

**What I learned:** Begin with a mission statement: the system's purpose, benefit proposition, measurable goals, primary and secondary markets, assumptions, constraints and stakeholders. A customer who adopts or manages a system may need different things from the staff who use it each day.

**Application:** The team scoped a centralized IT ticketing dashboard for CECAS CORE. Stakeholders included help desk staff, managers and directors. The existing workflow involved manual assignments, rerouting and difficulty keeping track of unresolved work. This framed the design around ticket retrieval, prioritization and workflow visibility.

**Why it matters:** A shared problem definition helps a team resolve scope questions and evaluate whether a proposed feature serves a real need. A quantifiable goal is a target until evaluation establishes an outcome.

## 2. Investigate underlying needs

**What I learned:** Interviews, focus groups and observation serve different purposes. Ask about actual tasks, current frustrations and workarounds. When someone suggests a solution, ask why it would help and identify the underlying need. Write a need in terms of what the system enables, keeping implementation choices open.

**Application:** The final presentation reports interviews with 10 participants across support staff, managers and directors. The report describes semi-structured interviews and surveys. Findings concerned manual work, misassigned tickets, navigation and visibility of unresolved tickets.

**Example:** A request for a reminder points to a need to notice work awaiting attention. A reminder is one possible implementation; ticket ordering, an aging indicator or a dedicated queue could address related needs. This example explains the reasoning process, rather than quoting a participant.

**Why it matters:** Research can reveal workflow requirements that a visually attractive dashboard alone would miss.

## 3. Organize and prioritize the evidence

**What I learned:** Translate research into need statements, remove redundancy, group related statements with affinity mapping, and organize primary and secondary needs. Use importance ratings to support prioritization after exploratory work. Keep a path back to the research that motivated each need.

**Application:** The final report records 8 primary and 18 secondary needs. These include intuitive navigation, search, role support, ticket management, prioritization, communication and customization. The team used importance ratings to identify priorities.

**Why it matters:** A hierarchy makes overlapping requests easier to discuss and prevents a long feature list from obscuring the most important user goals. The report's need lists contain some overlapping wording; maintaining consistent identifiers would make future traceability clearer.

## 4. Turn a need into a measurable specification

**What I learned:** A metric identifies what is measured; a target sets its intended value. Define units, task conditions and the desired direction of change. Set an ideal value and a marginally acceptable value, and connect each metric to a need. Consider practical constraints and competitive references.

**Application:** The team defined measures for navigation time, intuitiveness, finding urgent tickets, role-specific task performance and filtering. The report includes a needs-to-metrics table and references Zendesk, ServiceNow and Jira in its benchmarking discussion.

**Example:** For easier navigation, specify a standard find-a-feature task, record completion time in seconds and define a target before testing. A rating of intuitiveness captures perceived ease, while time measures task performance. They answer different questions.

**Why it matters:** Measurable criteria connect research to a design review. A numerical value in a comparison table needs a documented measurement basis before it can be treated as an independently verified benchmark. The class materials' competitor values are not independent benchmark results established by this repository.

## 5. Explore alternatives and make a documented selection

**What I learned:** Generate alternatives individually and as a group, decompose a problem into smaller functions, and compare concepts against user needs. Screening matrices make the criteria and trade-offs visible. A selected concept can combine useful elements from several alternatives.

**Application:** The report describes 8 concepts and multiple screening iterations. Criteria included ease of use, workflow coverage, search and filtering, prioritization, communication, role support, customization and error prevention. A combined concept progressed to detailed design.

**Why it matters:** A decision record lets collaborators understand why an option was selected and revisit it when new research changes the priorities.

## 6. Design for different roles and understandable interactions

**What I learned:** Personas help represent different goals and contexts. Interface principles such as visibility, affordances, mapping, constraints and feedback help explain how people discover available actions and understand their effects.

**Application:** The report includes student-worker and management personas. Prototype views show ticket priorities, campus metrics, agent performance, messages and management modules. Critical tickets use a color cue and a text label. Navigation groups the available destinations, and status/confirmation feedback communicates system responses.

**Why it matters:** Staff need to act on tickets, while managers need an overview of workload and performance. Role-sensitive information hierarchy helps avoid presenting every user with every metric. The prototype's accessibility controls and labels are design features, not evidence of completed accessibility conformance testing.

## 7. Test the workflow and refine the design

**What I learned:** A prototype makes an idea concrete enough for users to perform tasks and critique it. Observe task behavior, collect feedback, compare results with the specifications, then decide what to change. Explain the task and participant context when reporting a number.

**Application:** The final report describes feedback that ticket work should lead the home page, with unresolved and in-progress tickets receiving attention ahead of secondary information. The team used this feedback to guide refinement. The materials report navigation time, an intuitiveness rating, role-specific timings and a SUS calculation.

**Why it matters:** A design can look polished while putting the wrong information first. Testing helps a team discover whether the information hierarchy reflects the user's actual work.

## 8. Interpret results and prepare a handoff

**What I learned:** Keep usability perception, observed task performance and organizational impact separate. Record changes to metrics, keep units consistent and make the next implementation steps visible.

**Application:** The coursework ended with a prototype, report, presentation and implementation plan. Integration, training, monitoring and phased rollout remained implementation activities. The report lists a goal of increasing satisfaction by 40%, but does not provide a controlled before-and-after result establishing that improvement.

**What I would strengthen next:** Keep a task-level results sheet with participant count, completion status, errors and times; document every revision to a target; use a consistent questionnaire procedure; resolve mismatched units; and test the next prototype against the same tasks. See the [evaluation guide](evaluation.md) for the saved results and their interpretation.

## Course process at a glance

| Deliverable | Main question | Evidence produced | Skill developed |
| --- | --- | --- | --- |
| PD1: Customer and user needs | Whose problem are we solving? | Mission statement, research and need hierarchy | Problem framing and research synthesis |
| PD2: Target specifications | How will we judge the design? | Metrics, units and target values | Evaluation planning and traceability |
| PD3: Concept generation and selection | Which approach best fits the needs? | Personas, concepts and screening matrices | Design exploration and decision documentation |
| PD4: Detail design and evaluation | How does the prototype support real tasks? | Axure prototype, feedback, reported results and handoff plan | Prototyping, usability evaluation and iteration |

## Learning beyond the project

My journal also covers opportunity identification, cross-functional product development, active versus passive observation and practical trade-offs in setting specifications. The most useful connection across these topics is a repeatable reasoning process: clarify the problem, gather evidence, define success, explore alternatives, test an interaction and document the next decision.
