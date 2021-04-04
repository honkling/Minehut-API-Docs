---
description: Returns a list of 5 servers sorted by player counts. (The top 5 servers.)
---

# Top Servers

{% api-method method="get" host="https://api.minehut.com" path="/network/top\_servers" %}
{% api-method-summary %}
Top Servers
{% endapi-method-summary %}

{% api-method-description %}
Returns a list of the top 5 servers, sorted by player count.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"servers":[...]}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

