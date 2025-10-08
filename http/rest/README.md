# rest

A PUT/GET counter rest example using [dropshot](https://github.com/oxidecomputer/dropshot/).

## Examples

Set the counter value:

    curl -X PUT http://127.0.0.1:12345/counter --json '{"counter": 33}' -v

Get the counter value:

    curl http://127.0.0.1:12345/counter -v
