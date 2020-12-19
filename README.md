---
description: The central page for the API Documentation.
---

# Introduction

## Authorization

When authorizing yourself with the Minehut API, you need two values: your token, and your session id.

Currently, there is not a good way to login programmatically, so you will need to grab these two values yourself:

1. Open the Minehut panel
2. Press CTRL + Shift + I on the panel to open Developer Tools
3. Go to the `Network` tab in Developer Tools
4. Wait until you see a box that has the label `all_data`. Click that box. If there are multiple, just click any of them, it doesn't matter.
5. A new section will pop up, scroll down until you find the `Request Headers` section, you will see lots of fields and values. The ones you want are `authorization` and `x-session-id` being your token and session id respectively. Copy these fields, note them down, write it on your hand, whatever. Just have them available to paste.
6. Now, when making a request to an API endpoint that requires authorization, pass your token as the `authorization` header, and your session id as the `x-session-id` header.
7. If all has been done correctly, you should now be authorized.

{% hint style="info" %}
Tokens and session ids expire whenever you login or logout of your account.
{% endhint %}



