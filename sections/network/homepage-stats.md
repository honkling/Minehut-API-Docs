---
description: Returns information for the homepage. (minehut.com)
---

# Homepage Stats

## Endpoint Info

### URL Path

GET `/network/homepage_stats`

### Requires Authorization?

No.

### Response

`{"server_count":(...),"user_count":(...)}`

{% api-method method="get" host="https://api.minehut.com" path="/network/homepage\_stats" %}
{% api-method-summary %}
Homepage Stats
{% endapi-method-summary %}

{% api-method-description %}
Returns information for the homepage. \(minehut.com\)
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"server_count":(...),"user_count":(...)}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

