---
description: Users API Documentation
---

# 👨👩👧👦 Users

All available routes for Users is written down below :&#x20;

{% swagger method="get" path="/panel/user/list" baseUrl="" summary="User List" %}
{% swagger-description %}
Return User List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Users' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/panel/user/ban/{id}" baseUrl="" summary="User Ban" %}
{% swagger-description %}
User Ban transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
User Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/panel/user/unban/{id}" baseUrl="" summary="User Unban" %}
{% swagger-description %}
User Unban transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
User Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/user/delete/{id}" baseUrl="" summary="User Delete" %}
{% swagger-description %}
Delete User by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
User Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes User, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
