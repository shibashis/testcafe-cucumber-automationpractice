# testcafe-cucumber-automationpractice

[![Build Status](https://travis-ci.com/shibashis/testcafe-cucumber-automationpractice.svg?branch=master)](https://travis-ci.com/shibashis/testcafe-cucumber-automationpractice)

Sample automation tests for automationpractice web app using testcafe and cucumberjs.

### How to run

1. Install typescript globally `npm i -g typescript`
1. Clone the repo
1. Install dependencies: `npm i`
1. Run tests: `npm run test`

### Note

- This repo uses gherkin-testcafe, as testcafe does not support cucumber yet.
- Some tests use random data (e.g. email id) to populate form. (should use test fixtures to initialize app)
- Some Tests use input forms to bring application to desired state. (should use test fixtures to initialize app)
