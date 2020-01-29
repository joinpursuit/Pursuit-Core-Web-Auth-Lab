[![Pursuit Logo](https://avatars1.githubusercontent.com/u/5825944?s=200&v=4)](https://pursuit.org)


# Express / Passport / React Authentication Lab 
 
Create a frontend and backend with authentication that allows users to register, log in, and log out.

#### Learning Objectives

- Understand authentication concepts
    - sessions
    - hashing
    - localstorage
- Understand how to create private/protected routes

#### Prerequisites

- React & react router
- Express routes
- db queries with pg-promise

---

## Getting Started

1. Create an express application on your local machine.
1. Using create-react-app, make a new react project. You may make it in a sub-directory of the express app, or in a separate directory.
1. Fulfill the listed technical requirements below.

## Deliverables

1 or 2 repos and applications.

## Technical Requirements

1. Set up an express app that's connected to psql with at least 4 routes:
    * login
    * signup
    * logout
    * list items (users)
1. Set up a react app with react-router and 3 routes:
    * login
        * should display a login form that logs the user in
    * register
        * should display a registration form that creates a new user in 
    * list items (private routes)
        * should display a list of all registered users



* Bonus: add logout functionality
* Bonus 2: add functionality to create, read, update, and delete a tasks for each logged in user
* Bonus 3: logged in users should only be able to see tasks that they've created, not everyone elses.

## Submission Guidelines

- Fellows should submit a pull request with their finished application to this repository. If you have two separate repos, make two pull requests and label each one appropriately (e.g. front-end and back-end).

### Resources

- [Passport documentation](http://www.passportjs.org/)
- [frontend lesson](https://github.com/joinpursuit/Pursuit-Core-Web/blob/master/react_2/user_authentication_frontend/README.md)
- [backend lesson](https://github.com/joinpursuit/Pursuit-Core-Web/blob/master/react_2/user_authentication_backend/README.md)
