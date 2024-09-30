# Overview

You're working on a quest platform where users complete quests to earn points. The system uses a microservices architecture with Node.js backend servers and MongoDB as the database. Each quest has a completion limit (1 to n times per user). Your task is to implement a robust quest completion system that prevents users from exceeding the completion limit, even under high concurrency.

## Objectives

Create a robust solution for the quest completion system that handles race conditions and prevents users from exceeding the quest completion limit. Your solution should include:

1. A Node.js Express API endpoint for quest completion that correctly handles concurrent requests.
2. MongoDB schema designs for users, quests, and completions.
3. A mechanism to ensure atomicity and prevent race conditions.
4. Proper error handling and logging.
5. Unit tests for your implementation, including a test for race conditions.

## Requirements

1. Use Node.js (latest LTS version) and Express.js for the API.
2. Use TypeScript (latest stable version) with ES6 features.
3. Use mongodb-memory-server for in-memory MongoDB data storage.
4. Implement proper concurrency control.
5. Include appropriate error handling and logging.
6. Write unit tests using Jest, including a test for race conditions.

## Evaluation Criteria

- **Functionality**: The application should meet all outlined objectives.
- **System Design**: Practicality and simplicity in the overall system architecture, with particular attention to code modularization for different routes.
- **Code Quality**: Cleanliness, readability, and inline documentation.
- **Modularity and Scalability**: Effective use of modular design patterns to enhance code scalability and maintainability.
- **Testing**: Comprehensive coverage and quality of unit tests, especially for race conditions.

## Submission Guide

Please submit your solution using one of the following methods:

1. CodeSandbox.io (Recommended):

   - Fork the provided repository in CodeSandbox.
   - Complete your implementation in the CodeSandbox environment.
   - Provide the link to your CodeSandbox project.

2. GitHub:

   - Fork the provided repository on GitHub.
   - Complete your implementation and push your changes to your forked repository.
   - Provide the link to your GitHub repository.
