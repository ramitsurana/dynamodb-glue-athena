# Menu

* [Glue](#glue)
* [Dynamodb](#dynamodb)
* [Athena](#athena)

## Glue

## Dynamodb

## Athena

Advantages -

- High Concurrency , can run thousands of queries per day
- In-memory processing
- Low I/O and latency
- Can run query of different types from sources such as RDBMS, NoSQL DB's & Frameworks like Hive, Stream processing & Kafka
- No need of interpreter layer like Hive does (Tez)

Disadvantages -

- Not designed for OLTP
- Joining very large (100M+) rows not possible, use Hive intead
- Not able to perform Batch Processing
