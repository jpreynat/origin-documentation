---
description: Last updated 2018-08-13T03:40:33-07:00
---

# Establishments

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/establishments" %}
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
{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/establishments" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/establishments/{id}" %}
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
{% api-method method="PATCH" host="https://origin.poutineer.com" path="/v1/establishments/{id}" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="PUT" host="https://origin.poutineer.com" path="/v1/establishments/{id}" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="DELETE" host="https://origin.poutineer.com" path="/v1/establishments/{id}" %}
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

    {% endapi-method-request %}
  {% endapi-method-spec %}
{% endapi-method %}
