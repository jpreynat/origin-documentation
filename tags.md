---
description: Last updated 2018-08-13T03:40:33-07:00
---

# Tags

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/tags" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/tags/{id}" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
