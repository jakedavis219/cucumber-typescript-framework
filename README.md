# Cucumber/Typescript Framework

A template framework containing templates and ideas that encompass the following:

-   Front end testing using Cypress (with reporting)
-   API tests using Axios
-   Feature File Linting
-   GitHub Actions

Please get in touch if you see any issues or feel free to raise a PR/issue

## Setup

-   Install node 16+
-   Will need the following .env files:
    -   src/testsApi/.env for api tests
    -   cypress.env.json for UI Tests

Then run..

```  
npm install  
```  

## API Test

### Folder Structure

Example feature files and steps live in `Cucumber-Framework/src/testsApi/project-one`

`Feature Files`: BDD Scenarios

`Steps`: Connecting Steps to Scenarios, call on functions written at util level

`Util`: Home for abstracted/reusable functions




### How to run tests:
Run specific tests by tagging with `@test` and run..

```  
npm run project-one-test
```
Run the same test parallelized with 5 threads..
```  
npm run project-one-test-parallel
```
