---
description: Creates a plugin that Minehut servers can install.
---

# Create plugin

{% swagger baseUrl="https://api.minehut.com" path="/plugins" method="post" summary="Create plugin" %}
{% swagger-description %}
Creates a plugin that Minehut servers can install.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}

{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="name" type="string" %}
The name of the plugin.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="credits" type="integer" %}
How many credits the plugin should cost.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="desc" type="string" %}
A short description of the plugin.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="desc_extended" type="string" %}
An extended description of the plugin.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="file_name" type="string" %}
The name of the jar file.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="config_file_name" type="string" %}
The name of the jar file's config file.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="platform" type="string" %}
The platform for the plugin. Put "java" here.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="version" type="string" %}
The version of the plugin.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="disabled" type="boolean" %}
Whether the plugin should be disabled or not.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="media_id" type="string" %}
The media id for the plugin. What does this do? I have no idea. No plugins use it.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
