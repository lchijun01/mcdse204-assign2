# MCDSE204 Assignment 2

This repository contains the files and configuration for Assignment 2 of the MCDSE204 course.

## Contents

- `postman_collection.json`: The Postman collection containing the API tests.
- `postman_environment.json`: The Postman environment file with necessary variables.
- `.github/workflows/postman-tests.yml`: The GitHub Actions workflow file for running the Postman collection using Newman.

## How to Run the Tests

1. **Set up the Repository:**
   - Clone this repository to your local machine.
   - Ensure you have Node.js and Newman installed.

2. **Run the Tests Locally:**
   ```bash
   newman run postman_collection.json -e postman_environment.json
   
3. GitHub Actions:
   - The tests will automatically run on every push or pull request to the main branch.
   - You can view the test results in the 'Actions' tab of this GitHub repository.
