---
description: Closed Channels API Documentation
---

# ❌ Closed Channels

All available routes for Closed Channels is written down below :&#x20;

{% swagger method="get" path="/panel/disabled-channel/list" baseUrl="" summary="Disabled Channel List" %}
{% swagger-description %}
Returns Disabled Channel List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Disabled Channels' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/disabled-channel/edit/{id}" baseUrl="" summary="Disabled Channel Edit" %}
{% swagger-description %}
Returns Disabled Channel Details By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Disabled Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Disabled Channel Detail" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/disabled-channel/update/{id}" baseUrl="" summary="Disabled Channel Update" %}
{% swagger-description %}
Updates Disabled Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Disabled Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/disabled-channel/delete/{id}" baseUrl="" summary="Disabled Channel Delete" %}
{% swagger-description %}
Delete Disabled Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Disabled Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Featured Channel returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/panel/disabled-channel/enable/{id}" baseUrl="" summary="Disabled Channel Enable" %}
{% swagger-description %}
Activate or Deactivate a Disabled Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Featured Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="feature" type="boolean" required="true" %}
Actvate it or deactivate (true or false)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/disabled-channel/change-featured/{id}/{featured}" baseUrl="" summary="Disabled Channel Change Feature" %}
{% swagger-description %}
Change Feature of Disabled Channel By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Disabled Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="status" type="boolean" required="true" %}
Feature or unfeature (true or false)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
