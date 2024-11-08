# RESTful Todo List API

This is a RESTful Todo List API built with FastAPI.

--- 

# Project Link
project: [roadmap.sh/todo-list-api](https://roadmap.sh/projects/todo-list-api)

--- 

# How to Setup and Run
[Not yet available]
--- 

# API Documentation
[Not yet available]
---

# Roadmap

## Phase 1: Basic Setup
- [ ] Create the project structure
- [ ] Set up virtual environment and dependencies
- [ ] Configure `.env` and database connection
- [ ] Test database connection

## Phase 2: User Authentication
- [ ] Implement user registration:
  - [ ] Validate input data (e.g., email, password strength)
  - [ ] Hash passwords before saving
  - [ ] Return a success or error response
- [ ] Implement user login:
  - [ ] Verify credentials and generate JWT token
  - [ ] Set token expiration
  - [ ] Include token in responses
- [ ] Protect sensitive endpoints using JWT-based authentication

## Phase 3: To-Do List Functionality
- [ ] Define `Todo` model and schemas
- [ ] Implement CRUD operations for tasks:
  - [ ] Create a task
  - [ ] Read all tasks for the user
  - [ ] Update a task
  - [ ] Delete a task
- [ ] Add pagination for task lists
- [ ] Implement filtering:
  - [ ] Filter by completion status
  - [ ] Filter by priority or deadline
  - [ ] Filter by date created or updated

## Phase 4: Error Handling
- [ ] Add validation for user inputs:
  - [ ] Invalid data (e.g., malformed emails, empty fields)
  - [ ] Unauthenticated or unauthorized access
- [ ] Implement global exception handlers

## Phase 5: Testing
- [ ] Write unit tests for:
  - [ ] User registration
  - [ ] User login
  - [ ] Task CRUD operations
- [ ] Write integration tests for:
  - [ ] Full authentication flow
  - [ ] Task management with filtering and pagination

## Phase 6: Security Measures
- [ ] Hash and securely store passwords
- [ ] Use HTTPS in production
- [ ] Add rate-limiting for endpoints

## Phase 7: Documentation
- [ ] Add OpenAPI documentation (via FastAPI)
- [ ] Provide usage instructions in `README.md`:
  - [ ] How to set up and run the project
  - [ ] API endpoint details with examples
  - [ ] Testing instructions
