---
description: Modify the proxy's MOTD shown in the server list.
---

# Proxy MOTD

{% api-method method="post" host="https://api.minehut.com" path="/network/motd" %}
{% api-method-summary %}
Proxy MOTD
{% endapi-method-summary %}

{% api-method-description %}
Modify the proxy's MOTD shown in the server list.
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
{% api-method-parameter name="motd" type="string" required=true %}
The new MOTD.
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

