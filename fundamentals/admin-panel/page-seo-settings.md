---
description: Page SEO Settings API Documentation
---

# 🖥 Page SEO Settings

All available routes for General Settings is written down below :&#x20;

{% swagger method="get" path="/panel/page-meta-tag/" baseUrl="" summary="Page SEO Setting Data" %}
{% swagger-description %}
Return Page SEO Settings' Data as Form
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Page SEO Settings' Data as Form" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/panel/page-meta-tag/save" baseUrl="" summary="Page SEO Setting Store" %}
{% swagger-description %}
Page SEO Setting Store transaction.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
