---
title: Modify Webhook With Token
category: Webhook
order: 7
---

# `modifyWebhookWithToken`

```php
$client->webhook->modifyWebhookWithToken($parameters);
```

## Description

Same as above, except this call does not require authentication, does not accept a channel_id parameter in the body, and does not return a user in the webhook object.

## Parameters


Name | Type | Required | Default
--- | --- | --- | ---
webhook.id | snowflake | true | *null*
webhook.token | string | true | *null*

## Response

Possibly No Response

