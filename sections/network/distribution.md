---
description: Distributed stats for Minehut
---

# Distribution

{% api-method method="get" host="https://api.minehut.com" path="/network/players/distribution" %}
{% api-method-summary %}
Distribution
{% endapi-method-summary %}

{% api-method-description %}
Returns distributed stats used in Minehut's admin panel.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"bedrockTotal":(...),"javaTotal":(...),"bedrockLobby":(...),"bedrockPlayerServer":(...),"javaLobby":(...),"javaPlayerServer":(...)}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

