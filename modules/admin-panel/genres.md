---
description: Genres API Documentation
---

# 🎵 Genres

All available routes for Genres is written down below :&#x20;

{% swagger method="get" path="/panel/genre/list" baseUrl="" summary="Genre List" %}
{% swagger-description %}
Return Genre List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Genres' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/genre/store" baseUrl="" summary="Genre Store" %}
{% swagger-description %}
Genre Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/genre/edit/{id}" baseUrl="" summary="Genre Edit" %}
{% swagger-description %}
Returns Genre by id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Genre Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Genre Details" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/genre/update/{id}" baseUrl="" summary="Genre Update" %}
{% swagger-description %}
Genre Update transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Genre Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/genre/delete/{id}" baseUrl="" summary="Genre Delete" %}
{% swagger-description %}
Delete Genre by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Genre Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Genre, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
