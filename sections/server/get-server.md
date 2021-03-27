---
description: Get a server's information using it's name or ID
---

# Get Server

{% api-method method="get" host="https://api.minehut.com" path="/server/{server-id}" %}
{% api-method-summary %}
Get Server
{% endapi-method-summary %}

{% api-method-description %}
Get a server's information using it's name or ID.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="byName" type="boolean" required=false %}
Whether or not you want to search for the server using the name.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
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

