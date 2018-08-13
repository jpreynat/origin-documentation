# Introduction to the Service

Welcome to the Poutineer Origin Service developer hub. You'll find comprehensive guides and documentation to help you start working with Poutineer Origin Service as quickly as possible, as well as support if you get stuck. Let's jump right in!

## Service Understanding

This document describes the basic concepts for using the HTTP API for Poutineer's origin service. Each resource uses [the JSON:API standard](https://jsonapi.org). You can find all resources via [JSON:API Home](./) by accessing the [Origin JSON:API Home Resources](./) resource.

### Requests

A request **MUST** contain the `Accept` header with the [JSON:API mediatype](http://jsonapi.org/format/#introduction).

```http
GET https://origin.poutineer.com/v1/establishments/
Accept: application/vnd.api+json
```

A resource _MAY_ require authentication, which you can either get [by requesting a cookie](http://google.com) or by using the account's `authentication_secret` \(Encoded in base64\) as a [Authorization Bearer Token](https://swagger.io/docs/specification/authentication/bearer-authentication/).

```http
GET https://origin.poutineer.com/v1/establishments/smoke-s-poutinerie
Authorization: Bearer am1OdWpQb3BTbnhnYi1FaGN5Skg=
Accept: application/vnd.api+json
```

If a request has a body \(`PUT`, `PATCH`, `POST`\) then you **MUST** provide a `Content-Type` header.

```http
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

### Responses

```http
POST /v1/accounts HTTP/1.1
Host: origin.poutineer.com
User-Agent: insomnia/6.0.2
Content-Type: application/vnd.api+json
Accept: application/vnd.api+json
Content-Length: 141
{
    "data": {
        "type": "accounts",
        "attributes": {
            "email": "kurtis7209b4e6-0611-4956-9769-1c8b846630be@rainbolt-greene.online"
        }
    }
}
```

```http
HTTP/1.1 201 Created
Server: Cowboy
Connection: keep-alive
Content-Type: application/vnd.api+json; charset=utf-8
Vary: Accept-Encoding, Origin
Set-Cookie: _poutineer_session=bGszTkN4SzFVWnkzcHR3QVhkSW9vZE96eTlzN1lVbHJZdlRPZDk0ekVnZ3BsWGJYR2xmVlM3WTdOV0dnQWF2Mk9HMUdiS2RFQXFBY3ZWSDdXQUJRTnBSV21pT20yZVZtRHowaHNrVVBDS1ppNzNJWEllYmJyNlpaNWZXNlYrUkZGSzlaNS9UWUJSdHFOV0NiQURGdDhwRzQxb25uNE8vc1lLM3ZJSXJtcHRmaXVMOWVURUpvbVlrdWFsSlZvUlZrdDQvc3FBOVpFREhTNjJqT2tNb2tlaFNDaGtVQUFCZnRhaC84NDBTaHhPTT0tLVBFWjVzRWNPOFZqV0pPNitYQng4WkE9PQ%3D%3D--de19b8ef95ae50ed8fbaa7c6dac8934aaed80e89; path=/; HttpOnly; secure; SameSite=Lax
Etag: W/"0060d479725d0a7a7455690ca246a2d4"
Cache-Control: max-age=0, private, must-revalidate
X-Request-Id: 2c474283-bb07-4833-9f2b-9f10910bb8f0
X-Runtime: 0.730340
Date: Sun, 12 Aug 2018 05:24:55 GMT
X-Rack-Cache: invalidate, pass
Strict-Transport-Security: max-age=631138519
X-Frame-Options: sameorigin
X-Content-Type-Options: nosniff
X-Xss-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Content-Security-Policy: default-src 'self' https:; font-src 'self' https: data:; img-src 'self' https: data:; object-src 'none'; script-src https:; style-src 'self' https: 'unsafe-inline'
Transfer-Encoding: chunked
Via: 1.1 vegur
{
    "data": {
        "type": "accounts",
        "id": "0e53d53f-8d51-4921-8d9c-b05e87136bbc",
        "links": {
            "self": "/accounts/0e53d53f-8d51-4921-8d9c-b05e87136bbc"
        }
    },
    "jsonapi": {
        "version": "1.0"
    },
    "meta": {
        "api": {
            "version": "1"
        }
    },
    "links": {
        "discovery": {
            "href": "/"
        }
    }
}
```

