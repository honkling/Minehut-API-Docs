---
description: Modify the video shown when you're starting a server from hibernation.
---

# Transferring Page Video

{% swagger baseUrl="https://api.minehut.com" path="/website/transferring/promotion" method="post" summary="Transferring Page Video" %}
{% swagger-description %}
Modify the video shown when you're starting a server from hibernation.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="autoplay" type="integer" %}
Boolean as an integer (1 = true, 0 = false)
{% endswagger-parameter %}

{% swagger-parameter in="body" name="use_cloudinary" type="boolean" %}
Whether or not the video should use the custom video player or a YouTube embed.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="video_id" type="string" %}
The ID of the YouTube video. Leave empty if use_cloudinary is set to true.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
