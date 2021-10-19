---
description: Set the server's icon.
---

# Change Server Icon

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/icon/equip" method="post" summary="Change Server Icon" %}
{% swagger-description %}
Set the server's icon.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="icon_id" type="string" %}
The ID of the icon you want to use.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
