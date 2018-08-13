---
description: Last updated 2018-08-13T03:41:55-07:00
---

# Accounts

{% api-method method="get" host="https://origin.poutineer.com" path="/v1/accounts" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="post" host="https://origin.poutineer.com" path="/v1/accounts" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="get" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="patch" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="put" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
{% api-method method="delete" host="https://origin.poutineer.com" path="/v1/accounts/{id}" %}
  {% api-method-summary %}
    destroy
  {% endapi-method-summary %}

  {% api-method-spec %}
    {% api-method-request %}
      {% api-method-headers %}
        {% api-method-parameter name="If-Match" type="string" %}
        {% endapi-method-parameter %}
      {% endapi-method-headers %}
    {% endapi-method-request %}
    {% api-method-response %}
    {% endapi-method-response %}
  {% endapi-method-spec %}
{% endapi-method %}
