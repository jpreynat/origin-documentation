---
description: Last updated 2018-08-13T01:43:27-07:00
---

# Menu Items v1

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/menu_items" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.641+00:00">2018-08-13T08:43:27.641+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/menu_items" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.644+00:00">2018-08-13T08:43:27.644+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/menu_items/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.647+00:00">2018-08-13T08:43:27.647+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="PATCH" host="https://origin.poutineer.com" path="/v1/menu_items/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.650+00:00">2018-08-13T08:43:27.650+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="PUT" host="https://origin.poutineer.com" path="/v1/menu_items/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.652+00:00">2018-08-13T08:43:27.652+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="DELETE" host="https://origin.poutineer.com" path="/v1/menu_items/{id}" %}
  {% api-method-summary %}
    destroy
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.654+00:00">2018-08-13T08:43:27.654+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}
