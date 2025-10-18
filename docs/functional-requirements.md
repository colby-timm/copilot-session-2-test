# Functional Requirements: Add Due Date to Task

## Overview
These requirements specify the functionality needed to allow users to add a due date to a task and ensure tasks are sorted by date created.

## Requirements

1. **Add Due Date to Task**
   - The user must be able to specify a due date when creating a new task.
   - The user must be able to edit the due date of an existing task.
   - The due date must be stored in the task data model.
   - The due date must accept valid date formats and reject invalid entries.
   - The UI must display the due date for each task.

2. **Sort Tasks by Date Created**
   - Tasks must be displayed in order of their creation date (oldest first or newest first, as specified by the user or default behavior).
   - The creation date must be stored for each task.
   - Sorting must be consistent across all task views (e.g., list, board).

3. **Validation and Error Handling**
   - If a user enters an invalid due date, an error message must be shown.
   - The system must prevent saving a task with an invalid due date.

4. **Persistence**
   - Due dates and creation dates must be persisted in the backend/database.
   - Changes to due dates must be saved and reflected in all relevant views.

5. **API Support**
   - The backend API must support creating, updating, and retrieving tasks with due dates and creation dates.
   - API responses must include both due date and creation date fields for each task.

6. **Testing**
   - Automated tests must verify that due dates can be added, edited, and displayed correctly.
   - Automated tests must verify that tasks are sorted by creation date as required.
