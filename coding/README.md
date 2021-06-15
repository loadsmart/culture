# Coding

- Keep it simple. Simple solutions are faster to implement, maintain and scales better. Avoid duplication of code at all costs. Too hard to maintain.
- Mandatory code review, but keep PRs small.
- Try to automate repetitive tasks.
- Use meaningful names on your code.
- Comment your code if needed, but keep in mind that good code doesn't need much doc.
- Write good commit messages and comment as much as you want during code review.

- Respect code standards (PEP8 and AirBnb, ESlint and React Recommended)
- The team that builds a code needs to maintain it later.
- Every piece of code should have clear owners that decides the rules to work with that piece of code.
- Bus factor >= 2
- Every engineer needs to have access to any code so that he or she can collaborate in some manner, but they need the approval of code owners during code review.
- Don't build code blocks (classes, methods or functions) too big. Too hard to maintain.

- Testing:
- TDD > DTT > no test at all (writing your test before the code is better than doing it after, that is better than not writing tests at all).
- Test code coverage > 90%.
- Unit tests, integration tests, acceptance tests, ...
- Continuous integration:
- Do small commits and integrate your work with other people work as soon as possible to avoid integration nightmare.
- Continuous Delivery:
- Generate value and validate hypothesis as soon as possible.
<!-- prettier-ignore-start -->
<!-- start_toc -->
| Doc | Overview |
|--|--|

<!-- end_toc -->
<!-- prettier-ignore-end -->undefined