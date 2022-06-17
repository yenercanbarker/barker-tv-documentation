---
description: Users can Suggest Channels.
---

# 🙌 Channel Suggestions

All available routes for Channel Suggestions are written down below :&#x20;

{% swagger method="get" path="/panel/channel-suggestion/datatable" baseUrl="" summary="List Of Channel Suggestions" %}
{% swagger-description %}
Return Channel Suggestion List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel Suggestions' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/panel/channel-suggestion/edit/{id}" baseUrl="" summary="Edit Channel Suggestion" %}
{% swagger-description %}
Returns Channel Suggestion By Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Suggestion Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Channel Suggestion's Detail" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/channel-suggestion/update/{id}" baseUrl="" summary="Update Channel Suggestion" %}
{% swagger-description %}
Updates Channel Suggestion by id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Suggestion Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/channel-suggestion/delete/{id}" baseUrl="" summary="Delete Channel Suggestion" %}
{% swagger-description %}
Deletes Channel Suggestion
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

{% swagger method="get" path="/panel/channel-suggestion/approve/{id}" baseUrl="" summary="Approve Channel Suggestion" %}
{% swagger-description %}
Approve Channel Suggestion (Deletes Channel Suggestion Request, creates a Channel with the values of Channel Suggestion)
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
