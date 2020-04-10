# envoy

Pratices and minimal demo of envoy that work with nginx and websocket.

## Quick Start

```sh
git clone https://github.com/icmdb/envoy.git

cd envoy

docker-compose up -d 
```

Then you can access:

|Routes|URLs|
|:-----|:---|
|user -> nginix -> envoy -> web|http://localhost/|
|user -> nginix -> envoy -> ennvoy-admin|http://localhost/envoy|
|user -> nginix -> envoy -> websocketd|ws://localhost/websocket|

## Reference

* [Deprecated - Envoy Docs](https://www.envoyproxy.io/docs/envoy/latest/intro/deprecated)
* [Envoy Integration - Consul Docs](https://www.consul.io/docs/connect/proxies/envoy.html)

## @TODO:

* [ ] consul
* [ ] envoy with dynamic
