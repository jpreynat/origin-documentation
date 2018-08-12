# Welcome!

Welcome to the Poutineer Origin Service developer hub. You'll find comprehensive guides and documentation to help you start working with Poutineer Origin Service as quickly as possible, as well as support if you get stuck. Let's jump right in!

## Service Understanding

This document describes the basic concepts for using the HTTP API for Poutineer's origin service. Each resource uses [the JSON:API standard](https://jsonapi.org). You can find all resources via [JSON:API Home](#) by accessing the [Origin Resources](#) resource.

A request **MUST** contain the `Accept` header with the [JSON:API mediatype](http://jsonapi.org/format/#introduction).

``` http
GET https://origin.poutineer.com/v1/establishments/
Accept: application/vnd.api+json
```

A resource *MAY* require authentication, which you can either get [by requesting a cookie](http://google.com) or by using the account's `authentication_secret` (Encoded in base64) as a [Authorization Bearer Token](https://swagger.io/docs/specification/authentication/bearer-authentication/).

``` http
GET https://origin.poutineer.com/v1/establishments/smoke-s-poutinerie
Authorization: Bearer am1OdWpQb3BTbnhnYi1FaGN5Skg=
Accept: application/vnd.api+json
```

If a request has a body (`PUT`, `PATCH`, `POST`) then you **MUST** provide a `Content-Type` header.

``` http
POST https://origin.poutineer.com/v1/accounts/krainboltgreene
Authorization: Bearer am1OdWpQb3BTbnhnYi1FaGN5Skg=
Accept: application/vnd.api+json
Content-Type: application/vnd.api+json
{
  "data": {
    "id": "krainboltgreene",
    "type": "accounts",
    "attributes": {
      "name": "Jurtis Rainbolt-Greene"
    }
  }
}
```
