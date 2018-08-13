---
description: Last updated 2018-08-13T03:34:14-07:00
---

# Searches

{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/searches" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated 2018-08-13T10:34:14.120+00:00*.
  {% endapi-method-description %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" required=false %}
          [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
        {% endapi-method-parameter %}
    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/searches/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated 2018-08-13T10:34:14.123+00:00*.
  {% endapi-method-description %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" required=false %}
          [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
        {% endapi-method-parameter %}
    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
