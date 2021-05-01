---
description: Returns the amount of votes for Minehut in a month.
---

# Votes/month

{% api-method method="get" host="https://api.minehut.com" path="/admin/stats/votes/month" %}
{% api-method-summary %}
Votes/month
{% endapi-method-summary %}

{% api-method-description %}
Returns the amount of votes for Minehut in a month.
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
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
Unknown
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

