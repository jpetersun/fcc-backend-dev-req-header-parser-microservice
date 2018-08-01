# FCC Request Header Parser Microservice

Get the IP address, preferred language (from header Accept-Language)
and system info (from header User-Agent) for the device.

### Prerequisites

Node.js 8.10+

### Installing

```
yarn install

npm start
```

Local Demo: `localhost:8000/api/whoami`

Live Demo: https://fcc-req-header-parser-microservice-jp.glitch.me/api/whoami

Example Output:
```
{
  ipaddress: "12.123.12.123",
  language: "en-US",
  software: "Mac OS X 10.11.5"
}
```