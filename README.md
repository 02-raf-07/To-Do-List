# To-Do-List
A To-Do List is a simple application that allows users to create, manage, and organize tasks. Users can add new tasks, mark them as complete, edit details, and delete tasks, often with options to categorize or prioritize them, helping to enhance productivity and time management.

# Features of the To-Do List

1. **Add Tasks with Title and Optional Deadline**

   * Enter a task title.
   * Optionally add a deadline using a date and time picker (`datetime-local` input).

2. **Task Display**

   * Shows task title.
   * Displays creation date and time.
   * Shows deadline date and time if set.
   * Shows a short preview of the task description (if any).

3. **Task Completion Toggle**

   * Click on the task's left side to toggle between **done** and **not done**.
   * Visual feedback with a circular progress indicator (0% or 100%).

4. **Task Description**

   * Edit or add detailed description in a modal popup.
   * Description preview appears in the task item.

5. **Delete Tasks**

   * Remove tasks permanently with a delete button.
   * Confirmation prompt before deleting.

6. **Filtering**

   * Filter tasks by:

     * **All** tasks.
     * **Active** tasks (not done, and not overdue).
     * **Completed** tasks.
     * **Overdue** tasks (past deadline and not done).

7. **Overdue Task Highlight**

   * Overdue tasks are visually highlighted with a red border and background.

8. **Persistent Storage**

   * Tasks are saved in `localStorage` and persist across page reloads.

9. **Responsive UI**

   * Flexible layout with form inputs and task list.
   * Accessible buttons and clear visual cues.

10. **Modal Interaction**

    * Popup modal for editing descriptions.
    * Close modal by clicking the close button or outside the modal.
