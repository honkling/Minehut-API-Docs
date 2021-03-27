---
description: Edit a file. Creates a new file if it doesn't already exist.
---

# Edit File

{% api-method method="post" host="https://api.minehut.com" path="/file/{server-id}/edit/{path}" %}
{% api-method-summary %}
Edit File
{% endapi-method-summary %}

{% api-method-description %}
Edit a file. If the file doesn't exist, it will be created for you automatically.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="authorization" type="string" required=true %}
Your Minehut token.
{% endapi-method-parameter %}

{% api-method-parameter name="x-session-id" type="string" required=true %}
Your Minehut session id.
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="content" type="string" required=true %}
The new content of the file.
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

