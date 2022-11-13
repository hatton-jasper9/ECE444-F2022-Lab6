# ECE444-F2022-Lab6

Code taken from https://github.com/mjhea0/flaskr-tdd

## Test Driven Development

### Benefits

Test driven development encourages thinking about the requirements first when writing code, which can help improve code quality. Since the test is written before writing the code, the developer must be very clear about what the code must accomplish before writing it.

Test driven development makes it easier to add new features, because the developer has already written tests for the old features. This means that you can very quickly check that your changes have not broken previous features.

Test driven development can improve testing quality. When writing a test after the code, it is easier to miss some cases that should have been tested.

### Drawbacks

Takes extra time for executing tests that are known to fail, since tests are executed before finishing the relevant code section.

Can lead to taking extra time writing tests that are not independent. For example, testing the existance of the database file may be redundant if you have other tests that rely on the database file. The error messages from those tests may already indicate what the problem is.

Any time on testing which is not productive could be spent on development instead, making the project better.
