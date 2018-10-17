### Protocol Buffer Python Example

Generate the client library from the `proto` file using the command:

```bash
protoc --python_out=. addressbook.proto
```

This will generate the file `addressbook_pb2.py`.

#### Running the examples

```bash
python write_a_message.py
```
