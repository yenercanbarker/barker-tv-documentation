---
description: General Settings API Documentation
---

# ⚙ General Settings

All available routes for General Settings is written down below :&#x20;

{% swagger method="get" path="/panel/general-setting/" baseUrl="" summary="General Setting Data" %}
{% swagger-description %}
Return General Settings' Data as Form
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns General Settings' Data as Form" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/general-setting/save" baseUrl="" summary="General Setting Store" %}
{% swagger-description %}
General Setting Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
