---
description: Featured Channels API Documentation
---

# 🌟 Featured Channels

All available routes for Featured Channels is written down below :&#x20;

{% swagger method="get" path="/panel/featured-channel/list" baseUrl="" summary="Featured Channel List" %}
{% swagger-description %}
Returns Featured Channel List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Featured Channels' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/featured-channel/edit/{id}" baseUrl="" summary="Featured Channel Edit" %}
{% swagger-description %}
Returns Featured Channel Details By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Featured Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Featured Channel Detail" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/featured-channel/update/{id}" baseUrl="" summary="Featured Channel Update" %}
{% swagger-description %}
Updates Featured Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Featured Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/featured-channel/delete/{id}" baseUrl="" summary="Featured Channel Delete" %}
{% swagger-description %}
Delete Featured Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Featured Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Featured Channel returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/featured-channel/change-status/{id}/{status}" baseUrl="" summary="Featured Channel Change Status" %}
{% swagger-description %}
Activate or Deactivate a Featured Channel by Id
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

{% swagger method="get" path="/panel/featured-channel/un-feature/{id}" baseUrl="" summary="Unfeature Featured Channel" %}
{% swagger-description %}
Unfeature Featured Channel By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Featured Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="status" type="boolean" required="true" %}
Feature or unfeature(returns true or false)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
