# Load Balancer

A load balancer is a device that acts as a reverse proxy and distributes network or application traffic across a number of servers. Load balancers are used to increase capacity (concurrent users) and reliability of applications

## How to use

```
Usage:  
    -backends string
        Load balanced backends, use commas to separate
    -port int
        Port to serve (default 80)
```

## Example:

To add followings as load balanced backends

- http://localhost:8080
- http://localhost:8081
- http://localhost:8082
- http://localhost:8083

`go run . -backends http://localhost:8080,http://localhost:8081,http://localhost:8082,http://localhost:8083`
