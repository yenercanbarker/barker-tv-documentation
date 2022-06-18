---
description: User Interface Channel API Documentation
---

# 🎬 Channel

All available routes for Channel (in User Interface for Users) is written down below :&#x20;

{% swagger method="get" path="/like-channel/{channelId}" baseUrl="" summary="Channel Like" %}
{% swagger-description %}
Channel Like by Channel Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Likes Channel, Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/unlike-channel/{channelId}" baseUrl="" summary="Channel Unlike" %}
{% swagger-description %}
Channel Unlike by Channel Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Unlikes Channel, Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/send-comment/{channelId}" baseUrl="" summary="Channel Send Comment" %}
{% swagger-description %}
Channel Send Comment By Channel Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Adds Comment to Channel, Returns true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="If i" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/rate-channel/{channelId}/{rate}" baseUrl="" summary="Channel Rate" %}
{% swagger-description %}
Channel Rate by Channel Id And Rate
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" name="channelId" %}
Channel Id
{% endswagger-parameter %}

{% swagger-parameter in="path" name="rate" type="Integer" %}
Rate
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Rate Channel, return true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/report-channel/{channelId}" baseUrl="" summary="Channel Report" %}
{% swagger-description %}
Channel Report by Channel Id
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" %}
Channel Id
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Reports broken link and return true or false" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/increase-view-count/{channelId}" baseUrl="" summary="Channel Increase View" %}
{% swagger-description %}
Increases Channel's View
{% endswagger-description %}

{% swagger-response status="200: OK" description="Increases Channel's View" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
