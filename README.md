# University of Central Florida
## COP3330: Object Oriented Programming, Summer 2021

# Overview
Using IntelliJ and Gradle, you will create a GUI-based desktop application to allow a user to track their personal inventory.

The program should allow you to enter an item, a serial number, and estimated value. The program should then be able to display a tabular report of the data that looks like this:

| Value          | Serial Number  |   Name       |
|----------------|----------------|--------------|
| $399.00        | AXB124AXY3     | Xbox One     |
| $599.99        | S40AZBDE47     | Samsung TV   |


The program should also allow the user to export the data as either a tab-separated value (TSV) file, or as a HTML file. When exported as an HTML file, the data should be stored inside of a table structure to mimic the displayed appearance.

You will be responsible for both the design (UML diagrams) and implementation (production and test code) of this application


# How to use the Application

1. Add new item to the list
* Enter task name in the Text Field and select due date from the Date Picker.
* Click on the Add Task button to add the new task to the table
* Note when a new task is created, the status is set to Incomplete by default
* Both fields, Task Description and Due Date must be filled in to add a task

2. Remove an item from the list
* Select item from the table
* Click the Remove Task Button

3. Clear the list of all items
* Click the Clear List Button
* Clear List Button is disabled if there is no item in the table

4. Edit Item Description and Due Date
* Select item from the table (the description and due date will be populated in the Text Field and Date Picker)
* Edit task description and/or due date
* Click Update Task Button

5. Mark Item as Complete or Incomplete
* Double-click on the Status cell of the item
* Select Complete or Incomplete from the drop down menu (ComboBox)

6. Display All Items
* This option is selected by default in the View Tasks ComboBox
* To view All Task select "All" from the View Tasks ComboBox

7. Display Completed Items
* Select Completed option from the View Tasks ComboBox

8. Display Incomplete Items
* Select Incompleted option from the View Tasks ComboBox

9. Save List
* Go to Menu File and click Save ToDo List
* When FileChooser opens, select a location from the left pane to save the file and type a name for the file
* The file will be saved as .txt

10. Load a List
* Go to Menu File and click Open ToDo List
* When FileChooser prompts, browse to the file location and select .txt file.
* Note the program will give an error if file cannot be opened or if file has incorrect format.

11. Bonus Credit
* To sort the list by due date, click on the Due Date Column of the table
* All 3 columns of the table can be sorted.

12. Additional notes
* The Clear Fields Button clears Description Text Field and Due Date Picker.
* To Exit the Application go to File/Quit
