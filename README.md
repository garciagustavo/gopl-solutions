# My personal solutions to the exercises in The Go Programming Language book

With this TODO-List API you are able to connect your front-end app, CLI tool or any other integration method in order to manage your day-by-day tasks to do, and keep track of your completed appointments.


# Running:

You will need only a few support to run TODO-List app

1. [go1.16](https://golang.org "Golang oficial site")
2. [PostgreSQL 12](https://postgresql.org "PostgreSQL oficial site")

It's possible to conteinerize the application build file present on this repository, aside another container that keeps PostgreSQL database running, but it doesn't stop you from expose the build file and database on your local host in order to have the benefits of the App without the work overload that container systems bring up.

# API Endpoints:

`/list-tasks`
List all the current tasks you have appointed.

`/list-completed`
List all the tasks you have already finished up.

`/create-task`
Create a new task according to your description.

`/update-task`
Update the description or status of your tasks, completed or not.

`/delete-task`
Delete a task only by passing its ID

`/decline-task`
End up the appointment changing its status

`/restore-task`
Bring some task back to your TODO list
