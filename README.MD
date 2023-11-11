### Test Files:

# login.cy.js

The tests written in this file cover the following scenarios:

* A user can log in and access their profile.
* The user gets denied with invalid information.
* The user gets denied with empty credentials.
* The user gets denied with an empty password field.
* The user gets denied with an empty email field.

logout.cy.js
The tests written in this file include:

A user successfully logs in as an existing user and then logs out.
Unit Testing with Jest
Test Files:
login.test.js
The tests in this file verify that:

The login function fetches and stores a token in browser storage.
logout.test.js
The tests in this file ensure that:

The logout function clears the token from browser storage.
