# Introduction
Hello, thank you for showing your interest in Bits of Good! This semester, we are changing how we recruit devs. Instead of asking what flexbox and difference btwn let and var, we would like you to showcase your skills by actually coding out an app! We hope you enjoy the task and feel free to reach out to our email (hello@bitsofgood.org) if you have any questions! 

# Task
### Feature 1: Todo Form
1. Form takes inputs for title (a short description of todo item), tags (array of words describing todo item), and a due date.
2. Form should have a "create" button that creates a new todo item and display it on todo list
3. The user should be able to type a tag and create it by clicking on "create tag" button. 
4. By clicking the "create tag" button, the user should be able to see list of tags they want to attach to todo item.
5. Toggling the tags should remove them from tag list. Only the visible tags at the time of pressing "create todo" button should be included in the todo item.

### Feature 2: Sort Section
1. Sort section should have two buttons: sort by date and sort by completed.
2. "Sort by date" button should rearrange todo items by dates in increasing order. Thus, if todo item A has due date 8/28/2021 and todo item B has due date 9/1/2021, todo item A should appear before todo item B.
3. "Sort by completed" button should bring incompleted todo items to front and completed items to the back.
4. Note that if both buttons are toggled, items should be sorted by completedness first and each section (completed and incompleted) should be sorted by dates.
5. (Bonus) Implement a filter feature that filters the list of todo items based on tags. Tags should be displayed as dropdown and users should be able to select multiple tags from the dropdown. Note that this is a filter feature, so any todo items that does not contain the feature should not be displayed. Resetting filters should revert the array to previous state (display all items)

### Feature 3: Todo List section
1. Todo list section should display todo items contained in a card
2. Each todo item card should have a title, a due date, and tags. 
3. When toggled, todo item should be marked completed. It should be visually explicit that the item is completed, either via including a checkbox or by graying out todo item card.

# Assessment Rubric
