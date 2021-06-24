---
description: >-
  Copies a file or folder. When copying, a new file or folder will be created
  with the name and "-Copy" appended to the end.
---

# Copy File or Folder

{% hint style="info" %}
This endpoint is currently only available on Minehut's Developer Network, as it is currently being tested.
{% endhint %}

{% api-method method="post" host="https://api.dev.minehut.com" path="/file/{server-id}/copy" %}
{% api-method-summary %}
Copy File or Folder
{% endapi-method-summary %}

{% api-method-description %}
Copies a file or folder. When copying, a new file or folder will be created with the name and "-Copy" appended to the end.
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
{% api-method-parameter name="copyPath" type="string" required=true %}
A directory path to copy the files to. You cannot specify the name of the new file or folder here.
{% endapi-method-parameter %}

{% api-method-parameter name="files" type="array" required=true %}
Files and folders to copy.
{% endapi-method-parameter %}

{% api-method-parameter name="overwrite" type="boolean" required=true %}
Whether or not to overwrite previously existing files.
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

