# distributed-services-with-go

### To generate ssl certs:
```
> cd proglog
> make gencert
```

### To compile protocol buffer objects:
```
> cd proglog
> make compile
... compiles v1 .proto files
> make test
... runs tests
> make build
... builds application
> make run
... runs application
```

### To run :
```
> cd proglog/cmd/server
> go run main.go
```
- Open /proglog/test.http
- Add base 64 encoded values to the log
  - Server returns the offset of the inserted entry
- Retrieve entries by offset