---
description: The central page for the API Documentation.
---

# Introduction

## Authorization

When authorizing yourself with the Minehut API, you need two values: your token, and your session id.

Currently, there is not a good way to login programmatically, so you will need to grab these two values yourself:

1. Open the Minehut panel
2. Press CTRL + Shift + I on the panel to open Developer Tools
3. Click on the tab named `Application` in Developer Tools.
4. Double click `Local Storage`, and a new panel labeled `https://minehut.com` will show up. Click that.
5. Now write down the values of the fields `minehut_auth_token` and `minehut_session_id` as your token and session id respectively.
6. &#x20;Now, when making a request to an API endpoint that requires authorization, pass your token as the `authorization` header, and your session id as the `x-session-id` header.
7. If all has been done correctly, you should now be authorized.

### Base URL

The base URL for the Minehut API is `https://api.minehut.com`. Whenever you want to make a request to an endpoint, you want to grab it's path and append it to the base URL. For example:

```
https://api.minehut.com/server/honclick?byName=true
https://api.minehut.com/file/5fd6bea356e73b13b37f2527/list//
```

{% hint style="info" %}
Tokens and session ids expire whenever you login or logout of your account.
{% endhint %}

