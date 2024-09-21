# API Automated Testing with Postman CLI

This repository contains automated tests for our API using Postman CLI. The tests are executed automatically with every push to the `main` branch.


# API Testing for JIRA

This project contains automated tests for the JIRA API, focusing on the functionality of comments. The tests cover the following operations:

- **GET**: Retrieve comments associated with a specific issue.
- **POST**: Add new comments to an issue.
- **PUT**: Update existing comments.
- **DELETE**: Remove comments from an issue.

### Test Cases

The tests verify both positive scenarios and error handling, including:

- **Positive Cases**: 
  - Successfully retrieving, adding, updating, and deleting comments.
  - Ensuring the correct response data format and content.

- **Error Handling**: 
  - Testing responses for invalid inputs (e.g., malformed requests).
  - Verifying appropriate error codes (e.g., 400 Bad Request, 404 Not Found) for non-existent resources.

- **Authentication**: 
  - Validating authentication mechanisms and checking responses for unauthorized access (e.g., 401 Unauthorized).

These tests ensure that the API behaves as expected and helps maintain the integrity of comment functionality within JIRA.

### Test Results

Latest test results can be viewed at the following URL: [Test Results](https://bootcamp-qa.github.io/postman-run/report.html).

These tests are executed weekly to ensure ongoing reliability and functionality of the JIRA API.
