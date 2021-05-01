---
description: Creates a plugin that Minehut servers can install.
---

# Create plugin

{% api-method method="post" host="https://api.minehut.com" path="/plugins" %}
{% api-method-summary %}
Create plugin
{% endapi-method-summary %}

{% api-method-description %}
Creates a plugin that Minehut servers can install.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="authorization" type="string" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="x-session-id" type="string" required=true %}

{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
The name of the plugin.
{% endapi-method-parameter %}

{% api-method-parameter name="credits" type="integer" required=true %}
How many credits the plugin should cost.
{% endapi-method-parameter %}

{% api-method-parameter name="desc" type="string" required=true %}
A short description of the plugin.
{% endapi-method-parameter %}

{% api-method-parameter name="desc\_extended" type="string" required=true %}
An extended description of the plugin.
{% endapi-method-parameter %}

{% api-method-parameter name="file\_name" type="string" required=true %}
The name of the jar file.
{% endapi-method-parameter %}

{% api-method-parameter name="config\_file\_name" type="string" required=true %}
The name of the jar file's config file.
{% endapi-method-parameter %}

{% api-method-parameter name="platform" type="string" required=true %}
The platform for the plugin. Put "java" here.
{% endapi-method-parameter %}

{% api-method-parameter name="version" type="string" required=true %}
The version of the plugin.
{% endapi-method-parameter %}

{% api-method-parameter name="disabled" type="boolean" required=true %}
Whether the plugin should be disabled or not.
{% endapi-method-parameter %}

{% api-method-parameter name="media\_id" type="string" required=true %}
The media id for the plugin. What does this do? I have no idea. No plugins use it.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

