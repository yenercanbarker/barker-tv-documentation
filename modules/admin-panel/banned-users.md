---
description: Banned Users API Documentation
---

# 🚷 Banned Users

All available routes for Banned Users is written down below :&#x20;

{% swagger method="get" path="/panel/banned-user/list" baseUrl="" summary="Banned User List" %}
{% swagger-description %}
Return Banned User List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Banned Users' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/panel/banned-user/unban/{id}" baseUrl="" summary="Banned User Unban" %}
{% swagger-description %}
Banned User Unban transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Banned User Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/banned-user/delete/{id}" baseUrl="" summary="Banned User Delete" %}
{% swagger-description %}
Delete Banned User by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Banned User Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Banned User, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
