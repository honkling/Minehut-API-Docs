---
description: Create a Minehut server.
---

# Create Server

{% api-method method="post" host="https://api.minehut.com" path="/servers/create" %}
{% api-method-summary %}
Create Server
{% endapi-method-summary %}

{% api-method-description %}
Create a new Minehut server.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="authorization" type="string" required=true %}
Your Minehut token.
{% endapi-method-parameter %}

{% api-method-parameter name="x-session-id" type="string" required=true %}
Your Minehut session id.
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
The name of the server.
{% endapi-method-parameter %}

{% api-method-parameter name="platform" type="string" required=true %}
The server's platform \(must be "java".\)
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"server":{...}}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

