# Releasing

## Process
- Automate the deploy process. We do it through [CircleCI](https://app.circleci.com/pipelines/github/loadsmart).
- Always be prepared to revert a release if needed.
- Revert button, blue/green deploy or canary deploy strategies are encouraged.
- Use feature flags when possible. Turn it on for staging, test it, then turn it on for production. For Django-based projects, we have been using [django-waffle](https://github.com/django-waffle/django-waffle).
- Release soon and often - preferably, no later than 2 weeks
- Always question yourself: _"What is the simplest thing we can build to generate value?"_
- Practice the iterative and incremental approach
- If we are not much sure on some product hypothesis, use a "low tech" or "no tech" solution first as a POC.
- Services Best Practices can be found [here](https://loadsmart.atlassian.net/wiki/spaces/engineering/pages/48529412/Services+Best+Practices) 🔒

## Downtime
Do not generate downtime while deploying - _be especially careful with data migrations!_  
Check [this article](https://loadsmart.atlassian.net/wiki/spaces/engineering/pages/635994219/Migrations+with+zero+downtime+django) about how to do it in Django. 

However, if downtime is inevitable:
- Do it outside of working hours. For systems that our own employees use, consider working hours as 8am-6pm Central Time
- Warn everyone that is affected by it with some time in advance
- Warn again just before the downtime and right after it

<!-- prettier-ignore-start -->
<!-- start_toc -->

<!-- end_toc -->
<!-- prettier-ignore-end -->
