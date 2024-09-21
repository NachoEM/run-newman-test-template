# API Automated Testing with Postman CLI

This repository contains automated tests for for the JIRA API using Postman CLI. The tests are executed automatically every week.

### Test Results

The latest test results can be found in the latest GitHub Actions run. Click the badge above to view the most recent execution and download the HTML report from the "Artifacts" section.


[![Latest Run](https://github.com/bootcamp-qa/postman-run/actions/workflows/postman-tests.yml/badge.svg)](https://github.com/bootcamp-qa/postman-run/actions)


### Test Scenarios
The tests cover the following API operations:

- **GET**: Retrieve comments associated with a specific issue.
- **POST**: Add new comments to an issue.
- **PUT**: Update existing comments.
- **DELETE**: Remove comments from an issue.

The tests verify both positive scenarios and error handling, including:

- **Positive Cases**: 
  - Successfully retrieving, adding, updating, and deleting comments.
- **Error Handling**: 
  - Testing responses for invalid inputs and verifying appropriate error codes.
- **Authentication**: 
  - Validating authentication mechanisms and checking responses for unauthorized access.
