# Coding

## Producing Code

- Keep it simple and do not over-engineer solutions
- Avoid code duplication as much as you can
- Use meaningful names in your code - variables, functions and classes should explicitly say what they mean
- Try to automate repetitive tasks [when it is worth it](https://xkcd.com/1205/)
- Don't build code blocks (classes, methods or functions) too big. They're hard to maintain. Prefer to follow the [single-responsibility principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
- Code comments should only be added to answer a question that the code itself can’t
- Respect code standards (PEP8 and AirBnb, ESlint and React Recommended), although tools will play the main role here

## Processes around Coding

- Code reviews are mandatory
- Keep Pull Requests small to get the best of the reviewing process
- Integrate often and avoid long-living feature branches
- Do Pair Programming often and have feedback on your code sooner
- Write good and descriptive commit messages. Title and body if needed. [Commitizen](https://github.com/commitizen/cz-cli) is a good tool to help (but not required)
- Comment as much as you want during code review, having our [teamwork](../values/teamwork.md) value always in mind
- The team that builds the code needs to maintain it later
- Every piece of code should have clear owners that decide the rules to work with that code - we use GitHub's [CODEOWNERS](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-code-owners)
- [Bus factor](https://en.wikipedia.org/wiki/Bus_factor) >= 2
- Every engineer has read access to all repositories. Write access is given to them through the teams they belong to

## Testing

- Your code should always be tested. Whether it's a unit, functional or e2e test, make sure your code is covered
- TDD is good but not mandatory. Do only if you feel comfortable in doing so.
- Code coverage ideally greater than 90%. Do not blindly target the 100% - sometimes reaching it is not worth it

<!-- prettier-ignore-start -->
<!-- start_toc -->

<!-- end_toc -->
<!-- prettier-ignore-end -->