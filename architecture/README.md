# Guidelines for Architecture Design

_(This article needs help)_

Always design the architecture of a new system over an [RFC](https://github.com/loadsmart/rfcs). Get feedback from peers and whoever is possibly being impacted by it. Also make sure you also include [@loadsmart/security](https://github.com/orgs/loadsmart/teams/security) to review it, as they are in a better position to spot any possible security flaw the new system may have.

It's also highly recommended that you include drawings in your RFC. The power of having something easy to visually digest makes everything easier to understand and avoids confusion and expectations that are poorly managed. You can use any tool for that: [draw.io](https://draw.io), [Mermaid](https://mermaid-js.github.io/mermaid/#/), [Miro](http://miro.com), or a simple picture of a physical white board taken by your phone.

Also:

- Promote architectures that are loosely coupled and highly cohesive
- Hide implementation details behind well designed interfaces
- Use APIs to connect different systems
- Don't build systems that are too big and with wide responsibilities
