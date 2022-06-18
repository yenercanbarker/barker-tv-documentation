---
description: Broken Links API Documentation
---

# 🔗 Broken Links

All available routes for Broken Links is written down below :&#x20;

{% swagger method="get" path="/panel/broken-link/list" baseUrl="" summary="Broken Link List" %}
{% swagger-description %}
Return Broken Link List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Broken Links' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/broken-link/delete/{id}" baseUrl="" summary="Broken Link Delete" %}
{% swagger-description %}
Delete Broken Link by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Broken Link Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Broken Link, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
