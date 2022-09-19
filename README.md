# JS Unit Testing with Vitest

## JS Statements

[![tested with vitest](https://img.shields.io/badge/tested_with-vitest-99424f.svg)](https://vitest.dev/)




This project is written in [Node](https://nodejs.org/en/), and tested with [Vitest - Blazing Fast Unit Test Framework](https://vitestjs.io/).

---

## The assignment

When npm runs vitest, all the tests are failing as seen at the end of its output to the console.


<img width="600" alt="all tests fail"  src="https://user-images.githubusercontent.com/13385801/189547187-9a6e14e8-0d1f-45e0-bde7-db0ffee09bff.png">


# Instructions

## Install your dependencies

`npm install`

---

## Run tests on a single file

Start with the first file.

`npm run test:1`

The above npm command is equivalent to the following but is easier to type:

`npx vitest tests/stmnts-01.test.js --globals --run --reporter verbose`

as inside the package.json you see it is listed in the scripts:

`"test:1": "vitest tests/stmnts-01.test.js --globals --run --reporter verbose"`

Repeat tha process for all of your test files.

**NOTE:** As you are editing, don't forget to save the file before you try running the test or it won't be able to see the changes.

---

So the above example tests the first file `tests/stmnts-01.test.js` and outputs the results to the console.

If a test fails, vitest will identify it as failing and print one or more error messages, depending on the test expectations.

---

## Edit and test each file sequentially

One-by-one and in order, edit each JavaScript file and follow the instructions for each coding skill. You should run the test after each completed skill and see the pass count increase. When one file passes completely, you are ready for the next file.

Start with stmnts-01.test.js and finish with stmnts-04.test

---

## Continue writing and fixing code until all tests pass

When you feel the coding skills are completed, the following command will test all files in the repo that end in test.js

`npm test`

---

## Completing the Assignment

Commit and push after all tests pass. GitHub will run the same tests and report pass/fail.

---

## Resources

> "Unit testing ensures that all code meets quality standards before it's deployed."
> [The importance of unit testing](https://fortegrp.com/the-importance-of-unit-testing/)
