### HTTP server for favicon. Store in binary with server. 

> go run cmd/main.go

rps: `56k`


```
wrk "http://localhost:8080/"

Running 10s test @ http://localhost:8080/
  2 threads and 10 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency   243.17us  656.85us  13.35ms   96.76%
    Req/Sec    28.34k     3.60k   40.07k    74.50%
  564829 requests in 10.02s, 134.67MB read
Requests/sec:  56379.19
Transfer/sec:     13.44MB

```
