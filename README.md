# ECE444-F2023-Lab5

## Test Cases in Group Project
Test cases for the posting page: 
- def test_posting_page_rendering(client)
- def test_posting_complete_submission(client)
- def test_posting_required_submission(client)

https://github.com/ECE444-2023Fall/project-1-web-application-design-group19-webcrafters/blob/a131645231ac149b4b9831c459cc06758f7d1ae3/tests/betula_test.py#L100-L144

## Pros and Cons of TDD

### Pros
TDD is good because it ensures that you are constantly thinking of ways that your code will be used, testing your code, and modifying your code to make it pass the test. This makes it much more likely that your code is correct, since you have to write the code with your test case in mind instead of writing the code first without thinking about how it will be used. At the time of deployment, you will be more confident that thorough testing has taken place, since the code has been implemented with testing in mind throughout the whole development process. TDD also fits well with Agile development because of its cyclical nature. TDD is an iterative development cycle, which matches the iterative methodology of Agile development.

### Cons
The downfall of TDD is that it may cause the coder to think too narrowly. In the TDD process, the coder is focusing on individual test cases, which won’t always translate to the overall picture. This can harm the overall experience for someone using the product of code like this, since high-level interactions may be overlooked and untested. TDD can also take more time. Since it is an iterative cycle of adding a test to fail, writing code, ensuring it passes the test, and adding more, this is more or a trial-and-error approach that will add time to the development process.
