---
description: Reset a plugin's config.
---

# Reset Plugin Configuration

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/remove_plugin_data" method="post" summary="Reset Plugin Configuration" %}
{% swagger-description %}
Reset a plugin's config.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="plugin" type="string" %}
The ID of the plugin.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
