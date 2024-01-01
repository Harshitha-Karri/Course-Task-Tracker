# Course-Task-Tracker


**HTML Structure:**

- **Lists and Text Field:** The HTML code features lists for tasks and a text field for user input.
- **Classes:** Elements are assigned classes for styling and DOM manipulation.
- **Container Div:** The content is enclosed within a div with the class container for overall styling.

**JavaScript Functionality:**

**1. Creating Task Elements:**
   - Takes input string (task text) as input.
   - Creates task elements (label, button, input) using DOM methods.
   - Appends classes for styling and functionality.
   - Inserts elements as list items within a list.

**2. Adding Tasks:**
   - Triggered by clicking the addButton.
   - Creates a list item with the entered task text.
   - Checks for empty input.
   - Appends the list item to the inputTaskHolder.
   - Clears the input field.
   - Calls the bindFunction for event handling.

**3. Editing Tasks:**
   - Tracks the parent node of the task being edited.
   - Toggles editMode based on button clicks.
   - Updates task text by switching between label and input fields.

**4. Deleting Tasks:**
   - Accesses the parent and grandparent nodes of the task.
   - Removes the task element from its parent.

**5. Marking Tasks as Complete:**
   - Moves the task element to the completeTaskHolder.
   - Calls the bindFunction for updates.

**6. Marking Tasks as Incomplete:**
   - Moves the task element to the inCompleteTaskHolder.
   - Calls the bindFunction for updates.

**7. Binding Events:**
   - The bindFunction handles user interactions with buttons and elements.

**8. Iterating and Binding Children:**
   - Loops through tasks within completeTaskHolder and inCompleteTaskHolder.
   - Binds events for individual task elements.
