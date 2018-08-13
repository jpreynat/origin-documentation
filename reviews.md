---
description: Last updated 2018-08-13T03:37:45-07:00
---

# Reviews

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/reviews" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/reviews" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="PATCH" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="PUT" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="DELETE" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    destroy
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-path-parameters %}
        {% api-method-parameter name="ida" type="string" %}
          ID of the cake to get, for free of course.
        {% endapi-method-parameter %}
      {% endapi-method-path-parameters %}

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
  {% endapi-method-spec %}
{% endapi-method %}
