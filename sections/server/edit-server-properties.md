---
description: Change the properties of a server.
---

# Edit Server Properties

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-id}/edit\_server\_properties" %}
{% api-method-summary %}
Edit Server Properties
{% endapi-method-summary %}

{% api-method-description %}
Change the properties of a server.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="" type="string" required=true %}
Your Minehut token.
{% endapi-method-parameter %}

{% api-method-parameter name="" type="string" required=true %}
Your Minehut session id.
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="field" type="string" required=true %}
The name of the property.
{% endapi-method-parameter %}

{% api-method-parameter name="value" type="string" required=true %}
The new value for the property.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

