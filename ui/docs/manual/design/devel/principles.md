---
filename: design/devel/principles.md
title: Guiding Design Principles for Taskcluster
order: 10
---

# Guiding Design Principles for Taskcluster

At the [2016 tc-worker workweek](http://www.chesnok.com/daily/2016/03/11/workweek-tc-worker-workweek-recap/) the Taskcluster Platform team laid out our _core design principles_. The four key principles are:

* Self-service
* Robustness
* Enable rapid change
* Community friendliness

These are all under an umbrella we call Getting Things Built&#8482;. None of our work matters unless __it works__! Read further for a slightly expanded list of principles!

### Getting Things Built™

#### Self-service

- Task Isolation
- API-driven UI Tools
- Extensibility
- Granular Security
- Clearly-defined interfaces
- Separation of concerns

#### Robustness

- Scalability
- Correctness
  - [Idempotent APIs](/docs/manual/design/devel/idempotency)
- Minimal Self-hosting
  - Use managed services, e.g. S3, Azure Storage
  - Don't self-host mutable services
- Stateless services
- 12-factor applications

#### Enable Rapid Change

- Agility
- Clearly-defined interfaces
- Microservices
- Separation of concerns

#### Community Friendly

- Transparency
  - Granular Security
- Public by Default
- Self-Service

<img src="/docs/assets/principles.svg" alt="Taskcluster Principles Diagram" width="100%" />
