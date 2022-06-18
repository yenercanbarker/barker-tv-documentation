---
description: Home Page API Documentation
---

# 🏠 Home Page

All available routes for Home Page is written down below :&#x20;

{% swagger method="get" path="/" baseUrl="" summary="Home Page" %}
{% swagger-description %}
Return Home Page
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Home Page" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/watch/{slug}" baseUrl="" summary="Channel Page" %}
{% swagger-description %}
Returns Channel Page By Slug
{% endswagger-description %}

{% swagger-parameter in="path" type="integer" required="true" %}
Channel Slug
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Returns Channel's Page" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="404: Not Found" description="Returns Not Found if Channel's slug is not found" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/channel-list" baseUrl="" summary="Channel List" %}
{% swagger-description %}
Returns Channel List Page
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel List Page" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/favorite-channels" baseUrl="" summary="Favorite Channels List" %}
{% swagger-description %}
Return Favorite Channels List
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Favorite Channel if user logged in." %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="Returns Error if user not logged in." %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/search" baseUrl="" summary="Channel Search" %}
{% swagger-description %}
Returns Channel Search Page
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel Search Page." %}
```javascript

{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/search-language/{languageId}" baseUrl="" summary="Channel Search By Language" %}
{% swagger-description %}
Returns Founded Channels by Language Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel List by Language Id" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="Returns empty search page if there is no Channel found by Language Id." %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/search-country/{countryId}" baseUrl="" summary="Channel Search By Country" %}
{% swagger-description %}
Returns Founded Channels by Country Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel List by Country Id" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="Returns empty search page if there is no Channel found by Country Id." %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/search-genre/{genreId}" baseUrl="" summary="Channel Search By Genre" %}
{% swagger-description %}
Returns Founded Channels by Genre Id
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel List by Genre Id" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="Returns empty search page if there is no Channel found by Genre Id." %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/search-channel/{text}" baseUrl="" summary="Channel Search By Channel Name" %}
{% swagger-description %}
Returns Founded Channels by Channel Name
{% endswagger-description %}

{% swagger-response status="200: OK" description="Returns Channel List by Channel Name" %}
```javascript

{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="200: OK" description="Returns empty search page if there is no Channel found by Channel Name." %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
