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

### Pull Request Reviews

Consider the feedback of teammates.
Any feedback provided in pull requests should be evaluated. 
Even if action is not taken right away,
but never disregarded.

## Code Writing

### Formatting

Keep the code formatted.
It makes it easier to read and diff.

### Small Functions

Write small functions.
It makes them easier to read, to change and to test.

### Function Breakdown

Break down large functions into smaller ones.

### Terminology

Use meaningful names and concepts.
Domain-related terms help in understanding.

### Abstraction

Raise the level of abstraction.
If code is bloated and hard-to-change,
it is probably missing a level of abstraction.

### Test-Drive

Test-drive code.
Write test code before writing or changing the implementation code.
So that it is clear when the code change has achieved the goal,
or broken an existing requirement.

### Refactoring

Redesign, refactor as needed.
When we cannot figure out how to implement a test,
we are probably missing a new abstraction.

## Code Testing

### Testing Automation

Automate tests.
The more automated, the faster they are to execute;
and more reusable, reproducible.

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
