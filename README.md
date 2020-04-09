# envoy

Pratices of envoy.

## Quick Start

```sh
git clone https://github.com/icmdb/envoy.git

cd envoy

docker-compose up -d 
```

Then you can access:

|Routes|URLs|
|:-----|:---|
|envoy -> nginx|http://localhost/|
|envoy -> ennvoy-admin|http://localhost/envoy|
|envoy -> websocketd|ws://localhost/websocket|

## Reference

* [Deprecated - Envoy Docs](https://www.envoyproxy.io/docs/envoy/latest/intro/deprecated)
* [Envoy Integration - Consul Docs](https://www.consul.io/docs/connect/proxies/envoy.html)

## @TODO:

* [ ] consul
* [ ] envoy with dynamic