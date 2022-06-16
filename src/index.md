# Learning Ballerina

[Ballerina](ballerina.io/) is an open-source programming language for the cloud that makes it easier to use, combine, and create network services. 

This is a collection of code examples that illustrate various Ballerina concepts and functionalities.

Let’s begin learning Ballerina.

## Language Basics

- [Introduction to Ballerina](introduction.md) - An introduction to the language.

- [Hello World](hello_world.md) - A traditional Hello World program.
- [Introduction to Type System](type_system.md) - An introduction to Ballerina type system.
    - [Type System Fundamentals](type_system/type_system_fundamentals.md)
    - [Values and Types](type_system/values_and_types.md)
    - [LangLib Modules](type_system/langlib.md)

- [Simple Basic Types](simple_basic_types.md)
    - [Integer](simple_basic_types/integer.md)
    - [Float](simple_basic_types/float.md)
    - [Decimal](simple_basic_types/decimal.md)
    - [Boolean](simple_basic_types/boolean.md)
    - [Nil](simple_basic_types/nil.md)

- [Sequence Types](sequence_types.md)    
    - [String](sequence_types/string.md)
        - [String Template Literal](sequence_types/string/string_template.md)
    - [XML](sequence_types/xml.md)

- [Structured Types](structured_types.md) 
    - [Lists](structured_types/lists.md)
        - [Array](structured_types/lists/array.md)
        - [Tuple](structured_types/lists/tuple.md)
    - [Mappings](structured_types/mappings.md)
        - [Map](structured_types/mappings/map.md)
        - [Record](structured_types/mappings/record.md)
    - [Table](structured_types/table.md)

- [Behavioral Types](behavioral_types.md)
    - [object](behavioral_types/object.md)
    - [stream](behavioral_types/stream.md)
    - [error](behavioral_types/error.md)
    - [typedesc](behavioral_types/typedesc.md)
    - [function](behavioral_types/function.md)
    - [future](behavioral_types/future.md)

- [Other Types](other_types.md)
    - [any](other_types/any.md)
    - [anydata](other_types/anydata.md)
    - [byte](other_types/byte.md)
    - [json](other_types/json.md)
    - [union](other_types/union.md)


## Use Cases

- [Ballerina with GraphQL](https://github.com/anupama-pathirage/ballerina-scenarios/tree/main/ballerina-graphql-with-multiple-datasources) - Bookstore example using Ballerina with MySQL DB and Google Books API as datasources. 
- [Ballerina with WebSocket](https://github.com/anupama-pathirage/ballerina-scenarios/tree/main/ballerina-websocket-for-realtime-stock-updates) - Stock data management service, exchange and client using WebSocket.  


## Articles

- [Real-Time Stock Data Updates with WebSockets using Ballerina](https://dzone.com/articles/real-time-stock-data-updates-with-websockets-using)
- [Event-Driven APIs With Webhook and WebSub](https://dzone.com/articles/event-driven-apis-with-webhook-and-websub)
- [Quickstart OpenAPI With Ballerina](https://dzone.com/articles/quickstart-openapi-with-ballerina)
- [Introduction to gRPC on Ballerina](https://medium.com/ballerina-techblog/introduction-to-grpc-on-ballerina-7819d98c4e2b)
- [SQL Injection — Introduction with Ballerina](https://medium.com/mycodeideas/sql-injection-introduction-with-ballerina-30b75abad8fe)
- [Managing data using Ballerina vs Go](https://medium.com/ballerina-techblog/managing-data-using-ballerina-vs-go-fcbc9d20f691)
- [Data Integration With Ballerina](https://dzone.com/articles/data-integration-with-ballerina)
- [Introduction to Data Integration With Ballerina](https://dzone.com/articles/introduction-to-data-integration-with-ballerina)
- [Introduction to Ballerina Tables](https://medium.com/ballerina-techblog/introduction-to-ballerina-tables-205286a53752)
- [Connect to your data with Ballerina](https://medium.com/ballerina-techblog/connect-to-your-data-with-ballerina-902b2bad872d)
- [Insert batch of data to DB using Ballerina](https://medium.com/ballerina-techblog/insert-batch-of-data-using-ballerina-4c1a7d72c35e)
- [Ballerina JDBC Client — Performing DB Operations](https://medium.com/ballerina-techblog/ballerina-sql-connector-performing-db-operations-8e555e3688be)
- [Ballerina JDBC Client— Connecting to DB](https://medium.com/ballerina-techblog/ballerina-sql-connector-connecting-to-db-ee31a81c8df6)