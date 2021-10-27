# Task Manager

* This program is for a small business that can help it to manage tasks assigned to each team member of the team.

* This program works with two text files, the files have the following:
    
    * One text file (tasks.txt) stores a list of all the tasks that the team is working on. The data for each task is stored on a seperate line in         the text file. Each line includes the following data about a task in this order:
      
      * The username of the person to whom the task is assigned.
      * The title of the task.
      * A description of the task.
      * The date that the task was assigned to the user. 
      * The due date for the task.
      * Either a 'Yes' or 'No' value that specifies if the task has been completed yet.
   
   * Then the other text file (user.txt) stores the username and password for each user that has permission to use the program. The username and          password for each user is written to the file in the following format:
      
      * First, the username followed by a comma, a space and then the password.
      * One username and corresponding password per line.

* The program allows the user to do the following:
  
  * Login. The user is prompted to enter a username and password. A list of valid usernames and passwords are stored in a text file (user.txt). The       program displays an appropriate error message if the user enters a username that is not listed in ther text file with usernames (user.txt) or         enters a valid username but not valid password. The user is repeatedly asked to enter a valid username and password until they provide               appropriate credentials.
  * Register. A user is able to register, and the credentials stored in a text file.
  * Users are able to add tasks.
  * Users are able to view all tasks assigned to them.
    * If the user have more than one they can select a specific task and edit it if they want to.
    * A task can only be edited if it is not yet being completed.

* The program is formated so that:
  
  * Only the user with the username 'admin' is allowed to register users.
  * The admin user is provided with new menu option that allows them to display statistics. When this menu option is selected, the total number of      tasks and the total number of users is displayed in a user-friendly manner.

* The program can generate a reports, when the user chooses to generate reports, two text files (task_overview.txt and user_overview.txt) are         generated.

  * One text file (task_overview.txt) contain:
    * The total number of tasks that have been generated and tracked using the program.
    * The total number of completed tasks.
    * The total number of uncompleted tasks.
    * The total number of tasks that haven't been completed and that are overdue.
    * The percentage of tasks that are incomplete.
    * The percentage of tasks that are overdue.
    
  * The other text file (user_overview.txt) contain:
    * The total number of tasks assigned to that user.
    * What percentage of the total number of tasks have been assigned to the user?
    * What percentage of the tasks assigned to the user have been completed?
    * What percentage of the tasks assigned to the user must still be completed?
    * What percentage of the tasks assigned to the user have not yet been completed and are overdue?
    
 * The program allows the admin to display statistics.
