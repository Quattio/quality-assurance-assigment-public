# Quatt Quality Assurance Assignment

A developer has quickly built some features that were needed for our backend application, it has gone through the development lifecycle and it is now your turn to make sure that it adheres to our quality standards. Run the application and test it as you normally would, create a github repository with your findings and invite [dboris](https://github.com/diboris) and [GabrielKidane96](https://github.com/GabrielKidane96).

# Documentation
The openapi documentation is hosted on `/docs`

# User Stories

## User Story 1

As a user, I want to be able to create a new user in the system, providing their name, email, and password.

### Acceptance Criteria

- The system should validate that all required fields (name, email, password) are provided.
- Upon successful creation, the system should generate a unique identifier for the user.
- The user's information should be stored securely in the system.

## User Story 2

As a user, I want to be able to retrieve a specific user's information by their unique identifier.

### Acceptance Criteria

- The system should allow me to provide a valid unique identifier to retrieve the user's information.
- If the user exists, the system should return their name, email, and other relevant details.
- If the user does not exist, the system should provide an appropriate error message.

## User Story 3

As a user, I want to be able to update an existing user's information, such as their name or email.

### Acceptance Criteria

- The system should allow me to provide a valid unique identifier for the user I want to update.
- I should be able to update the user's name, email, or any other relevant fields.
- The system should validate the updated information and store it securely.

## User Story 4

As a user, I want to be able to delete a user from the system by their unique identifier.

### Acceptance Criteria

- The system should allow me to provide a valid unique identifier for the user I want to delete.
- Upon successful deletion, the user's information should be permanently removed from the system.
- If the user does not exist, the system should provide an appropriate error message.

## User Story 5

As a user, I want to be able to retrieve a list of all users in the system.

### Acceptance Criteria

- The system should provide a way to retrieve a complete list of all users.
- The list should include each user's name, email, and other relevant details.
- The system should handle large numbers of users efficiently.
