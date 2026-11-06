# FocusFlow — UX Case Study

**Project type:** Self-directed concept project  
**Role:** UX thinking, interface design and front-end development  
**Tools:** HTML, CSS, JavaScript  
**Status:** Functional browser prototype

## 1. Overview

FocusFlow is a lightweight task planner concept. It helps a person capture a task, assign a priority, optionally add a due date, and see what is still open or complete.

The goal was to demonstrate a complete beginner-friendly design-to-build process: define a focused problem, make deliberate interface decisions, build a working prototype, and check the core interactions.

> This is a concept project. The problem framing is a design hypothesis, not a finding from interviews or formal user research. No usability study or measured productivity improvement is claimed.

## 2. Problem statement

When small responsibilities are kept in memory, scattered notes, or chat messages, it can be harder to see what needs attention next. A simple task list should make capture and progress visible without adding unnecessary complexity.

**How might we help someone quickly capture a task and understand its status at a glance?**

## 3. Intended user and needs

**Intended user:** A student or early-career professional managing everyday personal and study tasks.

Needs considered:
- Add a task without navigating through several screens.
- Identify high-priority work quickly.
- See completed and unfinished tasks separately.
- Understand progress without manually counting items.

These are assumptions to validate with real users in a future iteration.

## 4. Design decisions

| Decision | Reason |
|---|---|
| One-screen task entry | Keeps the main action easy to find |
| Priority labels | Adds a quick visual cue without a complex scoring system |
| Optional due date | Supports deadlines without making them mandatory |
| All / To do / Completed filters | Makes task status easy to scan |
| Three summary numbers | Gives a simple view of overall progress |
| Local browser storage | Keeps the prototype usable after refresh without a backend |

## 5. Main user flow

1. Open FocusFlow.
2. Enter a short task name.
3. Choose a priority and optional due date.
4. Add the task to the list.
5. Mark it complete when finished, or filter the list to review progress.
6. Delete a task that is no longer needed.

## 6. Prototype features

- Create tasks with a title, priority and optional due date.
- Mark tasks complete or reopen them.
- Filter all, unfinished and completed tasks.
- Delete tasks.
- View total, remaining and completed counts.
- Save tasks in the current browser using localStorage.
- Responsive layout, keyboard-accessible form controls and visible focus states.

**Try the prototype:** [Open FocusFlow](../projects/focusflow/index.html).

## 7. Validation checklist

These are manual checks to perform, not results from a formal user study:

- [ ] Add a task with only a title.
- [ ] Add a task with a priority and due date.
- [ ] Refresh the page and confirm tasks remain in the same browser.
- [ ] Mark a task complete and reopen it.
- [ ] Switch between all three filters.
- [ ] Delete a task.
- [ ] Check the layout at mobile and desktop widths.
- [ ] Use the form and filters with a keyboard.

## 8. Limitations and next steps

- Tasks are stored only in the current browser; there is no account, cloud sync or cross-device access.
- There are no reminders, collaboration features or recurring tasks.
- The design assumptions should be tested with a small set of target users.
- A next iteration could include task editing, sorting by due date, and usability testing focused on how quickly a first-time user can add and complete a task.

## 9. What I learned

This project helped me connect basic UX decisions to working interface behavior. I focused on reducing friction around the main task, making status visible, and keeping the feature set small enough to build and test.