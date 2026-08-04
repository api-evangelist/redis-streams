# Redis Streams (redis-streams)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Redis Streams is a data structure in Redis that models an append-only log for managing streams of data. It provides consumer groups, message acknowledgment, range queries, and the ability to process data in real time with high throughput and low latency. Redis Streams supports event-driven architectures, real-time pipelines, activity feeds, and messaging use cases.

**URL:** [https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

Consumer Groups, Event-Driven, In-Memory, Messaging, Redis, Streaming

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-02

## APIs

### Redis Streams

Redis Streams is a Redis data structure that acts as an append-only log, supporting consumer groups, range queries, and message acknowledgment for building event-driven architectures and real-time data processing pipelines.

**Human URL:** [https://redis.io/docs/latest/develop/data-types/streams/](https://redis.io/docs/latest/develop/data-types/streams/)

#### Tags

Consumer Groups, Event-Driven, In-Memory, Messaging, Redis, Streaming

#### Properties

- [Documentation](https://redis.io/docs/latest/develop/data-types/streams/)
- [JSONSchema](json-schema/redis-stream-entry.json)
- [JSONSchema](json-schema/redis-consumer-group.json)
- [JSONSchema](json-schema/redis-stream-info.json)
- [JSONStructure](json-structure/redis-stream-entry-structure.json)
- [JSONStructure](json-structure/redis-consumer-group-structure.json)
- [JSONStructure](json-structure/redis-stream-info-structure.json)
- [JSON-LD](json-ld/redis-streams-context.jsonld)
- [Vocabulary](vocabulary/redis-streams-vocabulary.yml)

## Examples

| File | Description |
|---|---|
| [examples/redis-xadd-example.json](examples/redis-xadd-example.json) | XADD command — append a new entry to a stream |
| [examples/redis-xread-example.json](examples/redis-xread-example.json) | XREAD command — read entries from a stream |
| [examples/redis-consumer-group-example.json](examples/redis-consumer-group-example.json) | Consumer group workflow — create, read, and acknowledge |

## Common Properties

- [Website](https://redis.io/)
- [Documentation](https://redis.io/docs/latest/develop/data-types/streams/)
- [Getting Started](https://redis.io/docs/latest/get-started/)
- [GitHub](https://github.com/redis/redis)
- [Blog](https://redis.io/blog/)
- [Community](https://redis.io/community/)
- [Commands Reference](https://redis.io/docs/latest/commands/?group=stream)
- [Tutorial](https://redis.io/docs/latest/develop/data-types/streams-tutorial/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
