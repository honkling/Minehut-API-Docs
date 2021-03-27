---
description: Modify the video shown when you're starting a server from hibernation.
---

# Transferring Page Video

{% api-method method="post" host="https://api.minehut.com" path="/website/transferring/promotion" %}
{% api-method-summary %}
Transferring Page Video
{% endapi-method-summary %}

{% api-method-description %}
Modify the video shown when you're starting a server from hibernation.
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
{% api-method-parameter name="autoplay" type="integer" required=true %}
Boolean as an integer \(1 = true, 0 = false\)
{% endapi-method-parameter %}

{% api-method-parameter name="use\_cloudinary" type="boolean" required=true %}
Whether or not the video should use the custom video player or a YouTube embed.
{% endapi-method-parameter %}

{% api-method-parameter name="video\_id" type="string" required=true %}
The ID of the YouTube video. Leave empty if use\_cloudinary is set to true.
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

