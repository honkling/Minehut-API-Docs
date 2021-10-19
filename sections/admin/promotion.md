---
description: Modify the promotion text in the top right of the panel.
---

# Promotion

{% swagger baseUrl="https://api.minehut.com" path="/website/navbar/promotion" method="post" summary="Promotion" %}
{% swagger-description %}
Modify the promotion text in the top right of the panel.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="link" type="string" %}
The link that you're redirected to when you click on the promotion text.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="text" type="string" %}
The new promotion text.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
