# Practices

Practices are specific actions,
derived from the [Principles](principles),
that one should aim at performing daily
in order to achieve the engineering values.

> "The easiest concepts to understand 
>  are sometimes the hardest ones to excel on." -- [Crafter](http://wordnetweb.princeton.edu/perl/webwn?s=crafter)

## Implementation Tasks

### Task Breakdown 

Break down tasks into sub-tasks.
It helps us get started,
and know when we are really done.

### Task Description

Write a description for each task / sub-task.
Explain the problem and define the scope of solution.
It helps teammates understand what is to be worked on.

### Task Appetite

Determine the appetite for each task.
Make sure it is clear how long the task will take,
and reduce the scope if time-boxing is necessary.

### Acceptance Criteria

Define acceptance criteria for each task.
They are single statements that must be testable
once the task is complete.

### Task Update

Update often the status of tasks / sub-tasks
in order to be accountable to teammates and other stakeholders.

## Pull Requests

### Small Pull Requests

Small pull requests are easier to understand,
and quicker to review.

### Multiple Pull Requests

One may open many PRs for each task / subtask
as long as each PR results in working, tested, releasable software.

### Pull Request Accretions

Each pull request should be an accretion.
It is a new layer on top of an existing foundation (previous PRs).

### Code Coverage

Increase or at least maintain code coverage.
Each new pull request should have additional tests,
which will check new code,
but should *not* reduce coverage of existing code.

Code coverage ideally greater than 90%.
Do not blindly target the 100%.
Sometimes, reaching it is not worth it.

### Pull Request Reviews

Code reviews are mandatory.
Consider the feedback of teammates.
Any feedback provided in pull requests should be evaluated. 
Even if action is not taken right away,
but never disregarded.

### Pull Request Comments

Comment as much as you want during code review,
having our [teamwork](../values/teamwork.md) value always in mind.

## Code Writing

### Code Formatting

Keep the code well-formatted.
It makes it easier to read and diff.
Respect code standards (PEP8 and AirBnb, ESlint and React Recommended),
although tools will play the main role here.

### Code Readability

Write code that documents itself.
Code comments should only be added to answer a question that the code itself cannot.

### Small Functions / Methods / Classes

Write small functions, methods or classes.
It makes them easier to read, to change and to test.

### Function Breakdown

Break down large functions into smaller ones.

### Terminology

Use meaningful names and concepts in variables, functions and classes.
Domain-related terms help in understanding the code.

### Abstraction

Raise the level of abstraction.
If code is bloated and hard-to-change,
it is probably missing a level of abstraction.

### Test-Drive

Consider writing the test code before writing or changing the implementation code.
Or, as at least, try thinking about the testing scenarios before implementing the code.
So that it is clear when the code changes have achieved the implementation goal.

### Simplicity

Keep the code as simple as possible; avoid over-engineering solutions.

### Code Duplication

Avoid [duplicating code](https://en.wikipedia.org/wiki/Duplicate_code) as much as possible.

### Refactoring

Redesign, refactor as needed.
When we cannot figure out how to implement a test,
we are probably missing a new abstraction.

### Pair Programming

Do Pair Programming often and have feedback on your code sooner.

### Commit / Pull Request Messages

Write descriptive commit messages.
Title and body if needed. [Commitizen](https://github.com/commitizen/cz-cli) is a good tool to help (but not required)

## Code Testing

### Always Testing

Your code should always be tested.
Whether it's a unit, functional or e2e test,
make sure your code is covered.

### Testing Automation

Automate tests [when it is worth it](https://xkcd.com/1205/).
The more automated the tests, 
the faster they are to execute;
and more reusable, reproducible.
Consider the [testing pyramid](https://martinfowler.com/bliki/TestPyramid.html)
when making decisions on your testing effort.

### Testing Scenarios

Define clearly the scenarios.
Specify the set of testable statements,
which will tell you this implementation is complete.

### Testing on Reality

Test with real, production-like data.
If the tests do not exercise the code with real data,
they will not catch real production issues.

### Beyond Happiness

Consider more than the happy-path scenarios.
The success scenario is just one of the real scenarios occurring in production.
Think about all types of input data: out-of-bounds, out-of-format, none / null, etc.

### Validate Input

Validate input data in APIs, interfaces.
Make sure APIs validate input data before using them.
APIs should return helpful validation errors; not stack traces.

### Log Away

Log special, error conditions in code as warnings, errors.
Log the start and completion of tasks.
It will help in unearthing, diagnosing problems early,
even before getting to production.

## Code Ownership

### Code Maintenance

The team that builds the code needs to maintain it later.

### Code Owners

Every piece of code should have clear owners,
which decide the rules to work with that code.
We use GitHub's [CODEOWNERS](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-code-owners)

### Code Access

Every engineer should have read access to all repositories.
Write access is given to them through the teams that own them.

### Bus Factor

[Bus factor](https://en.wikipedia.org/wiki/Bus_factor) should be >= 2, preferably greater.

## Continuous Deployment

### Leverage Automation

Try to automate repetitive tasks [when it is worth it](https://xkcd.com/1205/).

## References

Some inspiring references for the practices above:
- [Extreme Programming Explained](https://books.google.com.br/books/about/Extreme_Programming_Explained.html)
- [The Pragmatic Programmer](https://www.google.com/books/edition/The_Pragmatic_Programmer/5wBQEp6ruIAC)
- [Software Craftsmanship](https://www.amazon.com.br/Software-Craftsmanship-Imperative-Pete-McBreen/dp/0201733862)
