# Performance Testing Frameworks - Open Source

This Repository has the details of all the Open Source Performance Testing Frameworks available

## APIGEE: Simple and fast HTTP Performance Testing Tool

https://github.com/apigee/apib

**Installation on Mac**
$ brew update && brew install apib

**Sample Request**

Vamsis-MacBook-Pro:~ vamsiravi$ apib -c 10 -d 30 http://www.google.com
(5 / 30) 32.971 0% cpu
(10 / 30) 38.562 0% cpu
(15 / 30) 40.774 0% cpu
(20 / 30) 37.976 0% cpu
(25 / 30) 49.757 0% cpu
(30 / 30) 68.745 0% cpu
Duration:             30.024 seconds
Attempted requests:   1345
Successful requests:  1345
Non-200 results:      0
Connections opened:   854
Socket errors:        844

Throughput:           44.797 requests/second
Average latency:      222.671 milliseconds
Minimum latency:      76.098 milliseconds
Maximum latency:      695.203 milliseconds
Latency std. dev:     116.155 milliseconds
50% latency:          199.614 milliseconds
90% latency:          343.440 milliseconds
98% latency:          517.262 milliseconds
99% latency:          534.499 milliseconds

Client CPU average:    0%
Client CPU max:        0%
Client memory usage:    0%

Total bytes sent:      0.13 megabytes
Total bytes received:  14.64 megabytes
Send bandwidth:        0.03 megabits / second
Receive bandwidth:     3.90 megabits / second
Vamsis-MacBook-Pro:~ vamsiravi$


## Vegeta: HTTP Load Testing Tool and Library. Excellent Live Monitoring.  

https://github.com/tsenart/vegeta

**Installation on Mac OSX**
$ brew update && brew install vegeta

## LoadImpact: Modern Load Testing Tool Using Go and JavaScript

https://github.com/loadimpact/k6

**Installation on Mac**
$ brew update
$ brew tap loadimpact/k6
$ brew install k6

**Installation with Docker**
$ docker pull loadimpact/k6

## Blast: Blast is a simple tool for API load testing and batch jobs

https://github.com/dave/blast

**Installation in Mac**

$ brew tap dave/blast
$ brew install blast
