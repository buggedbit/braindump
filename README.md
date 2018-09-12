## What?
EscapeErrands is a sophisticated yet intuitive task management system

## The philosophy behind
* __See the things you can, clearly! For if you do so, you can see those beyond__
* EscapeErrands enables the user to be stateless in his/her daily life. 
* It pushes the user to organize his/her tasks properly and removes the need to remember them
* The intention however is not to impose user to forget everything, but to provide a means to swap out all the irrelevant information (for the time being) so that the user can focus on the present
* EscapeErrands can organize arbitrarily complex tasks, store and visualize them in an orderly and relevant fashion
* It comes handy when user has quite a number of interdependent tasks

## How?
1. Make migrations in all apps
    python manage.py makemigrations <app>
2. Migrate them to db
    python manage.py migrate
3. Run the server
    python manage.py runserver

### todo
- [x] improve goal search app
	- [x] group by families
	- [x] fix sort order
	- [x] set bg of overdue goals to red
- [x] title
- [x] password
- [x] goal color Create & Update
- [ ] keyboard shortcuts
- [ ] Job model
