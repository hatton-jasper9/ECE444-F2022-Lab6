# ECE444-F2022-Lab6

Code taken from https://github.com/mjhea0/flaskr-tdd

## Education Pathways Tests

[test_update_rating](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-6-lambda/blob/3820037722a7b9d93863431f61a8351f9a970148/Education_Pathways/tests/test_app.py#L82-L99)

[test_update_comment](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-6-lambda/blob/3820037722a7b9d93863431f61a8351f9a970148/Education_Pathways/tests/test_app.py#L103-L110)

## Test Driven Development

### Benefits

Test driven development encourages thinking about the requirements first when writing code, which can help improve code quality. Since the test is written before writing the code, the developer must be very clear about what the code must accomplish before writing it. This also means that everyone must be on the same page about the code acceptance criteria early on.

Test driven development can improve testing quality. When writing a test after the code, it is easier to miss some cases that should have been tested. TDD prevents treating testing as an afterthought which doesn't get enough time allocated.

### Drawbacks

Takes extra time for executing tests that are known to fail, since tests are executed before finishing the relevant code section.

Can lead to taking extra time writing tests that are not independent. For example, testing the existance of the database file may be redundant if you have other tests that rely on the database file. The error messages from those tests may already indicate what the problem is.
