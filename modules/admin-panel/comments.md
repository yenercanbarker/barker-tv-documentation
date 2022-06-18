---
description: Comments API Documentation
---

# 💬 Comments

All available routes for Comments is written down below :&#x20;

{% swagger method="get" path="/panel/comment/list" baseUrl="" summary="Comment List" %}
{% swagger-description %}
Return Comment List as Datatable
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Comments' List as Datatable" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/comment/approve/{id}" baseUrl="" summary="Comment Approve" %}
{% swagger-description %}
Comment Approve transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Comment Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="patch" path="/comment/reject/{id}" baseUrl="" summary="Comment Reject" %}
{% swagger-description %}
Comment Reject transaction.
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Comment Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="delete" path="/panel/comment/delete/{id}" baseUrl="" summary="Comment Delete" %}
{% swagger-description %}
Delete Comment by Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Comment Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Deletes Comment, returns true" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
