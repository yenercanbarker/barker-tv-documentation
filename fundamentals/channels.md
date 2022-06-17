---
description: One of the app's core feature is Channel
---

# 🎬 Channels

All available routes for Channels is written down below :&#x20;

{% swagger method="get" path="/panel/channel/list" baseUrl="" summary="Channel List" %}
{% swagger-description %}
Return Channel List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel's List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/channel/edit/{id}" baseUrl="" summary="Channel Edit" %}
{% swagger-description %}
Returns Channel By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Channel Detail" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/channel/update/{id}" baseUrl="" summary="Channel Update" %}
{% swagger-description %}
Updates channel by id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/channel/change-featured/{id}/{feature}" baseUrl="" summary="Feature/Unfeature Channel" %}
{% swagger-description %}
Feature or Unfeature a Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="feature" type="boolean" required="true" %}
Feature it or un feature (true or false)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/channel/change-status/{id}/{status}" baseUrl="" summary="Enable/Disable Channel" %}
{% swagger-description %}
Enable or disable a Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="status" type="boolean" required="true" %}
Enable it or unable (true or false)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/channel/delete/{id}" baseUrl="" summary="Delete Channel" %}
{% swagger-description %}
Delete Channel by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Channel returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
