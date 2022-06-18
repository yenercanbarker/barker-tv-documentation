---
description: User Profile API Documentation
---

# 👨👩👧👦 User Profile

All available routes for User Profile is written down below :&#x20;

{% swagger method="get" path="/user-profile" baseUrl="" summary="User Profile" %}
{% swagger-description %}
Returns User Profile page
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns User Profile page" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/user-profile/update" baseUrl="" summary="User Profile Update" %}
{% swagger-description %}
Updates User Profile by Auth Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Updates User Profile if User is logged in, or send error" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
