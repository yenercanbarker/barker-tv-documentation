---
description: Admins API Documentation
---

# 🔓 Admins

All available routes for Admins is written down below :&#x20;

{% swagger method="get" path="/panel/admin/list" baseUrl="" summary="Admin List" %}
{% swagger-description %}
Return Admin List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Admins' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/admin/store" baseUrl="" summary="Admin Store" %}
{% swagger-description %}
Admin Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/admin/edit/{id}" baseUrl="" summary="Admin Edit" %}
{% swagger-description %}
Returns Admin Detail by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Admin Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Admin's Details" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/admin/update/{id}" baseUrl="" summary="Admin Update" %}
{% swagger-description %}
Admin Update transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Admin Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/admin/delete/{id}" baseUrl="" summary="Admin Delete" %}
{% swagger-description %}
Delete Admin by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Admin Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Admin, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/admin/change-status/{id}/{status}" baseUrl="" summary="Admin Change Status" %}
{% swagger-description %}
Ban or Unban Admin transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Admin Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Bans or unbans Admin, returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
