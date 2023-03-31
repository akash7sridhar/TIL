# Different Metrics Types in Prometheus
There are three types of metrics in prometheus. They are as follows

**1. Counter**
This can be used to tell how many time X happen and this number can only increase.
eg: Total number of request , Total Exceptions

**2. Gauge**
This measures the current value, This can go up and down.
eg: CPU , Memory utilisation, no of concurrent request

**3. Histogram**
How long or how big something is. It groups on bucket size
eg: response time <1s <0.5s

**4. Summary**
Similar to histogram but it calculates how many %  below x
eg: 20% requests has .3s response time