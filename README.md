# Postman-Newman Automation

Automated testing of REST APIs using **Postman**, **Newman**, **Allure**, and **yaml-server** for mocking.

## Setup

1. Install dependencies:

    ```bash
    npm install
    ```

2. Start the mock API server:

    ```bash
    npm run turn-on-api
    ```

3. Run tests:

    ```bash
    npm run test:postman
    ```

4. Generate and view Allure report:

    ```bash
    npm run allure:generate
    npm run allure:open
    ```

5. Run everything in one command:

    ```bash
    npm run test:full
    ```

## GitHub Pages

Allure reports are automatically pushed to GitHub Pages after each push to `main`.