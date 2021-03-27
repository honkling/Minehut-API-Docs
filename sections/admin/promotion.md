---
description: Modify the promotion text in the top right of the panel.
---

# Promotion

{% api-method method="post" host="https://api.minehut.com" path="/website/navbar/promotion" %}
{% api-method-summary %}
Promotion
{% endapi-method-summary %}

{% api-method-description %}
Modify the promotion text in the top right of the panel.
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
{% api-method-parameter name="link" type="string" required=true %}
The link that you're redirected to when you click on the promotion text.
{% endapi-method-parameter %}

{% api-method-parameter name="text" type="string" required=true %}
The new promotion text.
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

