# API Automated Testing with Postman CLI

This repository contains automated tests for our API using Postman CLI. The tests are executed automatically with every push to the `main` branch.


## Test Results

The latest test results can be found at the following link:

[![Test Report](https://img.shields.io/badge/test-report-success)](https://your-username.github.io/your-repository-name/report.html)

Click [here](https://your-username.github.io/your-repository-name/report.html) to view the latest test report.

## Configuration

Ensure that the following secrets are set in the repository:

- `POSTMAN_API_KEY`: Your Postman API Key.

## How It Works

- Every push to the `main` branch triggers a GitHub Action that runs the API tests using Postman CLI.
- Results are published as an HTML report and deployed to GitHub Pages.
