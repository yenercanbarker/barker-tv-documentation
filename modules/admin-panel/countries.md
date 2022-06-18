---
description: Countries API Documentation
---

# 🗺 Countries

All available routes for Countries is written down below :&#x20;

{% swagger method="get" path="/panel/country/list" baseUrl="" summary="Country List" %}
{% swagger-description %}
Return Country List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Countries' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/country/store" baseUrl="" summary="Country Store" %}
{% swagger-description %}
Country Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/country/edit/{id}" baseUrl="" summary="Country Edit" %}
{% swagger-description %}
Returns Country by id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Country Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Country Details" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/country/update/{id}" baseUrl="" summary="Country Update" %}
{% swagger-description %}
Country Update transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Country Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/country/delete/{id}" baseUrl="" summary="Country Delete" %}
{% swagger-description %}
Delete Country by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Country Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Country, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
