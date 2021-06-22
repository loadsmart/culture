# Tech Debts

Everything that wasn't properly done for whatever is the reason and that has undesired side effects is considered a tech debt. Examples of side effects are:
- Things that slow the team down
- Decrease of the quality of the code base (lack of patterns, code duplication, untested code, etc.)
- Security flaws
- Outdated dependencies
- and others

As engineers, we should be constantly paying those tech debts while still being able to deliver great products and meet deadlines. Keep always an eye on the [Tech Debts Overview](https://loadsmart.atlassian.net/secure/Dashboard.jspa?selectPageId=10611) 🔒 dashboard to make sure the # of tech debts is not increasing over time.

## Paying debts

### Single-squad debts

Tech debts for projects that are owned by a single squad should usually be tackled within the squad's sprint. For every every sprint (or a certain window of time for teams that don't run sprints), it is recommended that around 15% of its time is dedicated to tech debt payment.

### Multi-squad debts

When tech debts are big enough that paying them would require a coordinated effort of more than one squad, then those should be better planned.

As it may touch the work of many individuals, these type of tech debts are better suitable to be discussed through an [RFC](https://github.com/loadsmart/rfcs) 🔒, so that those involved can chime in and share their thoughts on possible solutions and on the problem itself.

<!-- TODO: Link the Working Group reference in this repo when it's done -->
After having a technical plan on how this multi-squad tech debt is going to be tackled, now it's time to organize the individuals (or teams) that will be working on it. [Working Groups](https://loadsmart.atlassian.net/wiki/spaces/engineering/pages/1878130703/Working+Groups) 🔒 are a great format when it comes to solving multi-squad tech debts, as they are short-lived, temporary, diverse, and they are formed to solve a cross-organization issue.<!-- prettier-ignore-start -->

<!-- prettier-ignore-start -->
<!-- start_toc -->

<!-- end_toc -->
<!-- prettier-ignore-end -->