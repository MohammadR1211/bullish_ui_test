Initial Setup
====================
Below section gives insights on assumptions and decision I have made for this test project.

- PageObject model was used to structure test suit
- I have used allure reporter for report generation.
- cucumber is used to incorporate BDD
- Generated report will be saved allure-report dir which will automatically be generated.
- I have used node 18.4.0 during developing test suits
- .env file is used to config URL

# Steps to run tests
- To install node modules run `npm i`
- To run tests run `npm run test`
- To generate test report run `npm run report`

# Note
As these are not unit tests, and I don't have access to codebase, I can't generate coverage for code the against which tests are running.
