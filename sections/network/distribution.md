---
description: Distributed stats for Minehut
---

# Distribution

{% swagger baseUrl="https://api.minehut.com" path="/network/players/distribution" method="get" summary="Distribution" %}
{% swagger-description %}
Returns distributed stats used in Minehut's admin panel.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
{"bedrockTotal":(...),"javaTotal":(...),"bedrockLobby":(...),"bedrockPlayerServer":(...),"javaLobby":(...),"javaPlayerServer":(...)}
```
{% endswagger-response %}
{% endswagger %}
