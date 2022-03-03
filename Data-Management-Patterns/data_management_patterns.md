*** About Me ***

- Data is hosted in different location and across multiple servers for performance, scalability and availability.
- Data consistency must be maintained and will need to be synchronized across different
locations.
- Data should be protected at rest, in transit and via auth access to maintain confidentiality, integrity and availability.

Patterns - 

1. Cache-Aside
- Load data on demand into a cache from a data store.

2. CQRS
- Segregate Read and Write operations using separate interfaces.

3. Event Sourcing
- Append-only store to record full series of events to describe actions on data.

4. Index Table
- Create indexes over fields frequently referenced by queries.

5. Materialized View
- Generate pre-populated view over data when data isn't ideally formatted for query ops.

6. Sharding
- Divide a data store into a set of horizontal partitions.

7. Static Content Hosting
- Deploy static content to a cloud based storage service that can deliver them directly to
client.

8. Valet Key
- Token / key to provide restricted direct access to specific resource or service.