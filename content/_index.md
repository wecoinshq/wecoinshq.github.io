# WeCrypt

Code and APIs to make crypto currency easier.

## Ripple API

The [`rippled` server](https://github.com/ripple/rippled) comes with a variety of APIs, however it does not come with a REST-like HTTP API.

The [`github.com/ripple/ripple-rest`](https://github.com/ripple/ripple-rest) project is frozen with a recommendation to migrate to a JavaScript / TypeScript library `github.com/ripple/ripple-lib`(https://github.com/ripple/ripple-lib) (aka RippleAPI).

WeCrypt provides a HTTP-RPC API that supports all `rippled` functions.

### Hosted REST-like HTTP API Proxy

### Ripple API Proxy Service

**Run you own REST-like HTTP API Proxy**

Runs locally or as an AWS Lambda function.

Code: https://github.com/wecrypt/ripple-api