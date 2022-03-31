# ToDo List

A custom module in Drupal 7 that allow users to control and add there own tasks with status 


## User Can do:

- Add and manage his tasks.
- Import and export his tasks in CSV format.
- See Drupal block to list the tasks due date is today and latest 5 tasks. and it auto assign to homepage content region.
- Action to close the task if he has the role of "close tasks".
- There is a cron job to remind the user of his today tasks.
- Action to manage all tasks and export and import all task if he has the role od "manage tasks".

## Issues that fixed 

- fix expert status new that not visible in csv file.
- add "uid" column in tasks migration as an update. 
- fix create and edit form with new assign to field to current user.
- set new permission call "manage tasks".
- only user that has role "manage tasks" that can show all tasks and reassign or create with assign the task to other users.
- fix block to be auto assign to homepage content region.
- all user can see there own tasks in block, only who has permission "manage task" can see all tasks that due date is today and latest 5 tasks.
