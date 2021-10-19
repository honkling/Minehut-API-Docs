---
description: Returns a list of 5 servers sorted by player counts. (The top 5 servers.)
---

# Top Servers

{% swagger baseUrl="https://api.minehut.com" path="/network/top_servers" method="get" summary="Top Servers" %}
{% swagger-description %}
Returns a list of the top 5 servers, sorted by player count.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
{"servers":[...]}
```
{% endswagger-response %}
{% endswagger %}
