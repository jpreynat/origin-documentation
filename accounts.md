---
description: Last updated 2018-08-13T03:09:04-07:00
---

# Accounts

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/accounts" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.866+00:00">2018-08-13T10:09:03.866+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/accounts" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.868+00:00">2018-08-13T10:09:03.868+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.869+00:00">2018-08-13T10:09:03.869+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
{% api-method method="PATCH" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.870+00:00">2018-08-13T10:09:03.870+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
{% api-method method="PUT" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.872+00:00">2018-08-13T10:09:03.872+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
{% api-method method="DELETE" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    destroy
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:09:03.873+00:00">2018-08-13T10:09:03.873+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %}
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-None-Match" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Modified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="If-Unmodified-Since" type="string" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}

      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}

    {% endapi-method-headers %}
  {% endapi-method-request %}
{% endapi-method %}
