# Redis Streams (redis-streams)

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
