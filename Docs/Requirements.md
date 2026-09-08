Requirements.md

## 1. Project Requirements

The project is a **SkillsTrack Learner Support Portal**. The portal will help learners manage their learning tasks, support bookings and progress.

The application will be developed using:

* HTML5
* CSS3
* JavaScript ES6+
* Firebase Realtime Database
* Git and GitHub
* Visual Studio Code

---

## 2. Main Features

During Month 1, the following features will be planned and started:

### User Account

The system must allow users to:

* Register an account.
* Log in.
* Log out.
* View their own information.

### Task Manager

The learner should be able to:

* Add a task.
* View tasks.
* Edit a task.
* Mark a task as completed.
* Delete a task.
* Confirm before deleting a task.

### Progress

The dashboard should show:

* Total tasks.
* Completed tasks.
* Outstanding tasks.
* Calculated progress.

### Support Booking

The learner should be able to:

* Enter a support topic.
* Select a preferred date.
* Add notes.
* Submit a support request.
* Receive feedback after submitting.

### Search and Filter

The application should allow the learner to search, filter or sort tasks.

JavaScript array methods such as `map()`, `filter()` or `reduce()` should be used for meaningful results.

---

## 3. JavaScript Requirements

The Month 1 project must demonstrate the following JavaScript skills:

* Variables.
* `let` and `const`.
* Data types.
* Operators.
* Functions.
* Parameters.
* Return values.
* Arrow functions.
* Local and global scope.
* Arrays.
* Arrays of objects.
* Loops.
* Conditional statements.
* `map()`.
* `filter()`.
* `reduce()`.
* Event listeners.
* DOM manipulation.

The code should use clear names, proper indentation, comments where needed and good file organisation.

---

## 4. Firebase Requirements

The project will use **Firebase Realtime Database**.

The database will be planned using these main sections:

```text
users/
tasks/
bookings/
scores/
resources/
```

### Users

```text
users/{uid}
```

Fields:

```text
displayName
email
role
createdAt
```

### Tasks

```text
tasks/{taskId}
```

Fields:

```text
userId
title
category
dueDate
priority
completed
createdAt
```

### Bookings

```text
bookings/{bookingId}
```

Fields:

```text
userId
topic
preferredDate
notes
status
```

### Scores

```text
scores/{scoreId}
```

Fields:

```text
userId
score
duration
completedAt
```

### Resources

```text
resources/{resourceId}
```

Fields:

```text
title
type
url
description
```

The database structure follows the suggested structure in the project brief.

---

## 5. Firebase Security

Firebase data must not be left open for unrestricted public writing.

The database should use the authenticated user's ID to identify ownership of their information.

Passwords must be handled by Firebase Authentication and must not be saved in the database, cookies or source code.

User input should also be validated before it is saved.

---

## 6. REST API Planning

The Firebase Realtime Database REST API will be planned for the project.

| Method | Purpose                      |
| ------ | ---------------------------- |
| GET    | Read data                    |
| POST   | Create new data              |
| PUT    | Replace existing data        |
| PATCH  | Update part of existing data |
| DELETE | Remove data                  |

The REST requests must be authenticated or used in an assessor-controlled test environment.

---

## 7. Application Interface

The Month 1 application should have a basic working interface with:

* Navigation.
* Main content.
* Buttons.
* Forms.
* Dynamic content.
* Basic validation.
* User feedback.

JavaScript should be used to create, change and remove DOM elements.

---

## 8. Cookie Preference

The application should have one simple preference, such as a light or dark theme.

The preference can be stored in a browser cookie.

Example:

```text
theme=dark
```

The cookie must not contain passwords or sensitive information.

---

## 9. GitHub Requirements

The team must set up a shared GitHub repository.

The repository should contain:

* `README.md`
* `.gitignore`
* Issues/tasks.
* Feature branches.
* Pull requests.
* Commits from team members.
* Basic CI check.

Team members should make meaningful contributions and be able to explain their work.

---

## 10. Testing and Debugging

Testing will be done while developing the project.

At least three problems must be recorded.

For each problem, the team should record:

* What went wrong.
* How the problem was found.
* What caused it.
* How it was fixed.
* Whether the fix worked after testing.

Browser developer tools, the console and debugging tools can be used.

---

## 11. Month 1 Deliverables

By the end of Month 1, the project should have:

* Problem statement.
* Project scope.
* Client requirements.
* At least six user stories.
* Acceptance criteria for the user stories.
* Programming life-cycle plan.
* Flowcharts or pseudocode.
* Firebase data model.
* REST endpoint plan.
* Two planned classes or structured objects.
* Configured IDE.
* Formatter and linter.
* Debugging tools.
* GitHub repository.
* README.
* `.gitignore`.
* Issues.
* Branches.
* Pull request evidence.
* Basic CI check.
* Working application shell.
* JavaScript fundamentals.
* Cookie preference prototype.
* Confirmation dialog.
* Redirect plan or prototype.
* Print-function plan or prototype.
* Testing and debugging record.
* Assessor review record.
* Month 1 reflection.

These are the Month 1 deliverables listed in the assessment document.

---

## 12. Month 1 Goal

The goal of Month 1 is to create a working foundation for the SkillsTrack Learner Support Portal.

The project should have the basic interface, JavaScript functionality, Firebase database plan and GitHub workflow ready so that the more advanced development can be completed in Month 2.
