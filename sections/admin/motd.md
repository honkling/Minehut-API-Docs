---
description: Modify the proxy's MOTD shown in the server list.
---

# Proxy MOTD

{% swagger baseUrl="https://api.minehut.com" path="/network/motd" method="post" summary="Proxy MOTD" %}
{% swagger-description %}
Modify the proxy's MOTD shown in the server list.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="motd" type="string" %}
The new MOTD.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
