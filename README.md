# ReQL Specification

This repository holds files and folders specifying ReQL, to some extent or another, in a parseable way.

## ql2.proto

Protobuf file which defines the basic communication between clients and servers. [Original file](https://github.com/rethinkdb/rethinkdb/blob/next/src/rdb_protocol/ql2.proto).

## ql2.proto.json

Protobuf file parsed as JSON. Contains the same information as the `ql2.proto` file, but can be parsed by any standard JSON parser.

## error_hierarchy.json

Hierarchy of the errors. Parseable version of [this article](https://rethinkdb.com/docs/error-types/).

## rql_test/

Folder containing polyglot ReQL tests. [Original folder](https://github.com/rethinkdb/rethinkdb/tree/next/test/rql_test).
