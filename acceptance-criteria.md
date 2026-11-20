# Acceptance Criteria

<!--
Acceptance criteria tell you when a user story is DONE. Each one must be testable: pass or fail.
Write 2–3 criteria for every user story using this format:

Given [a situation], when [the user does something], then [this should happen].

Tips:
- Number them under their story: AC1.1 and AC1.2 belong to US1.
- Describe what the user SEES, not how the code works.
- Include at least one "what if it goes wrong" case per story (empty input, no results).
- Avoid vague words like "fast," "nice," or "easy." Could a classmate test it and agree it passed?

Example:
## US1: View today's menu
- AC1.1: Given I open the App page, when it loads, then I see each dish with its name, photo and price.
- AC1.2: Given no dishes are added yet, when I open the menu, then I see "No dishes today yet."

AC - Acceptance Criteria
-->

### Feature: Task Management (Add, Edit, Delete, and Complete Tasks)

US1: As a student, I want to add, edit, delete, and mark my schoolwork as done with a specific class and due date so that I can keep track of my assignments and not miss deadlines.

- AC1.1: The app checks that the task name, class subject, and due date are all filled in before saving a new task.
- AC1.2: The user can edit or remove existing task.
- AC1.3: The user can mark a task as done, which updates the screen's numbers for total tasks, due tasks, and late tasks.

### Feature: Search and Subject Filtering

US2: As a student taking many classes, I want to search for specific tasks and filter my list by class subject so that I can quickly find homework and quizzes without scrolling through everything.

- AC2.1: Typing words in the search bar shows only tasks with matching names.
- AC2.2: Picking a class subject from the filter menu shows only tasks for that class.
- AC2.3: Clearing the search box and resetting the class filter brings back the full list of tasks.

### Feature: Auto-Saving and Screen Design

US3: As a student who checks my schedule on different devices, I want my tasks to save automatically in my web browser and look good in light and dark colors on any screen size so that I can easily manage my tasks anytime.

- AC3.1: All added, edit, or finished tasks save automatically in the web browser and stay there even after refreshing or closing and reopening the page.
- AC3.2: Users can switch between light mode and dark mode, and the screen colors change right away.
- AC3.3: The page layout fits cleanly on computer, tablet, and phone screens without items overlapping or needing to scroll sideways.
