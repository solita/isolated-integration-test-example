# Isolated integration test example

Demonstrates the usage of `session_replication_role` in integration tests.

## Usage

Run tests with:

`lein midje`

Examples can be found under `src/tests` directory.

Prerequisites:

- postgresql (tested on 9.4)
- postgresql database `isolated-integration-test`
- postgresql superuser `isolated-integration-test` with same password
- install postgresql-contrib-9.4 as dependency

## License

Copyright © Solita

Released under the MIT license.
