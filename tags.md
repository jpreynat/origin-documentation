---
description: Last updated 2018-08-13T03:10:22-07:00
---

# Tags

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/tags" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:10:22.307+00:00">2018-08-13T10:10:22.307+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-spec %}
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
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/tags/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T10:10:22.308+00:00">2018-08-13T10:10:22.308+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-spec %}
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
  {% endapi-method-spec %}
{% endapi-method %}
