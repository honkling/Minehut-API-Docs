---
description: Search for information of Minehut users by Minecraft IGN, email, or User ID.
---

# User Info

{% swagger baseUrl="https://api.minehut.com" path="/v2/admin/users" method="get" summary="User Info" %}
{% swagger-description %}
Search for information of Minehut users by Minecraft IGN, email, or User ID.
{% endswagger-description %}

{% swagger-parameter in="path" name="q" type="string" %}
Your search query.
{% endswagger-parameter %}

{% swagger-parameter in="path" name="role" type="string" %}
A filter of users based on role. This can either be "" (anybody), "creator" (market creator), or "admin" (minehut admin)
{% endswagger-parameter %}

{% swagger-parameter in="path" name="limit" type="integer" %}
How many users should appear in one page.
{% endswagger-parameter %}

{% swagger-parameter in="path" name="offset" type="integer" %}
Counts from 0. Tells the api which page of users it should return.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
Unknown. All known is, it returns the user email, the user id, the Minecraft IGN, the credits belonging to the account, and the roles associated with the account.
```
{% endswagger-response %}
{% endswagger %}
