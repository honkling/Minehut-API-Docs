---
description: Returns up to(?) the latest 179 messages from logs.
---

# Get latest messages

{% tabs %}
{% tab title="Request" %}
```
{
    "type": "console:getscrollback"
}
```
{% endtab %}

{% tab title="Response" %}
```
{
    "type": "console:scrollback",
    "data": [
        {
            "type": "console:std",
            "data": {
                "msg": "Server starting, setting up fifo connections and writing server ready. (EXAMPLE OUTPUT)"
            }
        },
        ...
    ]
}
```
{% endtab %}
{% endtabs %}
