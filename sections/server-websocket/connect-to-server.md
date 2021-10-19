---
description: Connect to a server's websocket.
---

# Connect to Server

{% swagger method="get" path="/socket" baseUrl="wss://{server-id}.manager.minehut.com" summary="Connect to a server's websocket." %}
{% swagger-description %}
Opens a websocket connection between the client and the server.
{% endswagger-description %}

{% swagger-response status="101: Switching Protocols" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
