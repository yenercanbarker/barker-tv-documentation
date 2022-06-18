---
description: Languages API Documentation
---

# 🌐 Languages

All available routes for Languages is written down below :&#x20;

{% swagger method="get" path="/panel/language/list" baseUrl="" summary="Language List" %}
{% swagger-description %}
Return Language List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Language's List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/language/store" baseUrl="" summary="Language Store" %}
{% swagger-description %}
Language Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/langauge/edit/{id}" baseUrl="" summary="Language Edit" %}
{% swagger-description %}
Returns Language by id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Language Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Language Details" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/langauge/update/{id}" baseUrl="" summary="Language Update" %}
{% swagger-description %}
Language Update transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Language Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/language/delete/{id}" baseUrl="" summary="Language Delete" %}
{% swagger-description %}
Delete Language by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Language Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Language, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
