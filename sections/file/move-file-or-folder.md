---
description: Move a file or folder somewhere else.
---

# Move File or Folder

{% hint style="info" %}
This endpoint is currently only available on Minehut's Developer Network, as it is currently being tested.
{% endhint %}

{% api-method method="post" host="https://api.dev.minehut.com" path="/file/{server-id}/move" %}
{% api-method-summary %}
Move File or Folder
{% endapi-method-summary %}

{% api-method-description %}
Move a file or folder somewhere else.
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
{% api-method-parameter name="files" type="array" required=true %}
A list of file paths to move.
{% endapi-method-parameter %}

{% api-method-parameter name="movePath" type="string" required=true %}
A file path to move the files to.
{% endapi-method-parameter %}

{% api-method-parameter name="overwrite" type="boolean" required=true %}
Whether or not existing files should be overwritten by new files when being moved.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"overwriteFiles":[...],"prevPath":"..."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

