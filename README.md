Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
[![Build Status](https://akrosproject.visualstudio.com/Parts%20Unlimited-Curso/_apis/build/status/pablomontero03.calculator?branchName=master)](https://akrosproject.visualstudio.com/Parts%20Unlimited-Curso/_build/latest?definitionId=1376&branchName=master)
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

