---
description: Change Language API Documentation
---

# 🌐 Change Language

All available routes for Change Language is written down below :&#x20;

{% swagger method="get" path="/change-language" baseUrl="" summary="Change Language" %}
{% swagger-description %}
Changes Application's Language
{% endswagger-description %}

{% swagger-parameter in="body" name="language" type="String" %}
language code (en, tr, es)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Suggest Channel modal" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
