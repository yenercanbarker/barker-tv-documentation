---
description: Channel Suggestion (for User Interface) API Documentation
---

# 🙌 Channel Suggestion

All available routes for User Profile is written down below :&#x20;

{% swagger method="get" path="/suggest-channel" baseUrl="" summary="Suggest Channel" %}
{% swagger-description %}
Returns Suggest Channel modal
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Suggest Channel modal" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/suggest-channel" baseUrl="" summary="Suggest Channel Post" %}
{% swagger-description %}
Suggests a Channel with Inputs
{% endswagger-description %}

{% swagger-response status="200: OK" description="Add channel to suggestions or return error" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
