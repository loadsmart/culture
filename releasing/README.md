# Releasing

- Automate the deploy process.
- Always be prepared to revert a release.
- Revert button, blue/green deploy or canary deploy strategies.
- Use feature flag for features that may cause serious issues in production.
- Release soon and often:
- Preferably, no later than 2 weeks.
- What is the most simple thing we can build to generate some value?
- Iterative and incremental approach.

- Do not generate downtime while deploying (be careful with data migrations!).
- If downtime is inevitable:
- Do it in non-working hours. If in doubt about when people are not working, please ask the team’s lead.
- Warn everyone that is affected by it with some time in advance, whenever possible.
- Warn again just before the downtime and right after it.
- If we are not much sure on some product hypothesis, use a "low tech" or "no tech" solution first as a POC.
- Services Best Practices can be found here.


<!-- prettier-ignore-start -->
<!-- start_toc -->
| Doc | Overview |
|--|--|

<!-- end_toc -->
<!-- prettier-ignore-end -->

[TODO]