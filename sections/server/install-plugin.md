---
description: Add a plugin to a server.
---

# Install Plugin

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/install_plugin" method="post" summary="Install Plugin" %}
{% swagger-description %}
Add a plugin to a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="plugin" type="string" %}
The ID of the plugin you want to install.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
