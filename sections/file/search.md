---
description: Searches for files and folders by name in a given directory.
---

# Search

{% hint style="info" %}
This endpoint is currently only available on Minehut's Developer Network, as it is currently being tested.
{% endhint %}

{% api-method method="get" host="https://api.dev.minehut.com" path="/file/{server-id}/search/{name}" %}
{% api-method-summary %}
Search
{% endapi-method-summary %}

{% api-method-description %}
Searches for files and folders by name in a given directory.
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
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"result":[{"id":"full path to file","name":"name of file with extension","directory":true/false},{...}]}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

