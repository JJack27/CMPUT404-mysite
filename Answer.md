## Question 1
- https://github.com/JJack27/CMPUT404-mysite

## Question 2
- It shows a page "The install worked successfully! Congradulations!".

## Question 3
- `/` will shows a 404 page.
- `polls/` will shows a pure HTML page contains "Hello, world. You're at polls index". Which is our HTTP response.

## Question 4
- Migrations are used to propagate the changes we make to our models into database schema.

## Question 5
- It shows an administration page. We can add and change POLLS and authentications in this page.

## Question 6
- It shows a HTML page with content "You're looking at question xx" if we are visiting `/polls/xx`. And showing "You're looking at the results of question xx" if we are visiting `/polls/xx/results/`. And showing "You're voting on question xx" if we are visiting `/polls/xx/vote/`. 

## Question 7
- Because templates is for reusing. Put a hardcoding url makes the template inflexible.

# Question 8
- Because it helps us to connect models and views easily. And it also helps us to reduce repeating code for similar code in several views. But when you are writing a page that is very unique, then you do not have to use generic views.
