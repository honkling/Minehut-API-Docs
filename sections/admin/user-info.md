---
description: 'Search for information of Minehut users by Minecraft IGN, email, or User ID.'
---

# User Info

{% api-method method="get" host="https://api.minehut.com" path="/v2/admin/users" %}
{% api-method-summary %}
User Info
{% endapi-method-summary %}

{% api-method-description %}
Search for information of Minehut users by Minecraft IGN, email, or User ID.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="q" type="string" required=true %}
Your search query.
{% endapi-method-parameter %}

{% api-method-parameter name="role" type="string" required=true %}
A filter of users based on role. This can either be "" \(anybody\), "creator" \(market creator\), or "admin" \(minehut admin\)
{% endapi-method-parameter %}

{% api-method-parameter name="limit" type="integer" required=true %}
How many users should appear in one page.
{% endapi-method-parameter %}

{% api-method-parameter name="offset" type="integer" required=true %}
Counts from 0. Tells the api which page of users it should return.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

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
Unknown. All known is, it returns the user email, the user id, the Minecraft IGN, the credits belonging to the account, and the roles associated with the account.
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

