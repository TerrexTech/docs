**DBMS**: Cassandra  
**Keyspace**: rns_eventstore  
**Table**: events

| Key          | Data-Type |
|-------------:|-----------|
| action       | text      |
| aggregate_id | int       |
| data         | text      |
| timestamp    | timestamp |
| user_id      | int       |
| uuid         | uuid      |
| version      | int       |
| year_bucket  | int       |

**Partition Key**: year_bucket  
**Clustering Key**: (aggregate_id, version, action, timestamp, uuid)
