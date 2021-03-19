- APM: NewRelic -> Datadog.
- Logs: Datadog (Logentries is deprecated).
- Metrics: Datadog (Librato is deprecated).
- Synthetics: Datadog Synthetics;
- Paging: PagerDuty.
- Alerting: Datadog (Librato is deprecated).
- Engineering error tracking and notifications: Sentry.
- General internal or external notifications: Notification Hub (internal tool).


- Do not adopt any new technology without a good reason.
- Before building something inside, make sure there's no 3rd party tool to solve our problem.
- About using 3rd party tools or build it inside:
- If it is core, prefer building it inside so that we can have more flexibility.
- If it is not core, prefer 3rd party tools.
- Prefer 3rd party managed services instead of libraries because the operational cost is lower.

- Software reuse: Whenever possible, build generic and reusable components.
- Open source:
- Be careful with GPLike projects. Some licenses may force us their license (like AGPL). For GPL licenses, it cannot be used if the software is distributed (mobile and frontend, for example).
- Avoid branching open source projects because we create another thing to maintain.
- Feel free to retribute and contribute for open source projects! If you think we should open source some current proprietary code, let's talk about it!
- Do not open source any internal code without communicating to Loadsmart leadership.
