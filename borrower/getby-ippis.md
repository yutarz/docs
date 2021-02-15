# Get Borrower

{% api-method method="get" host="https://api.yutars.com" path="/v1/borrower/ippis/:ippis" %}
{% api-method-summary %}
By IPPIS
{% endapi-method-summary %}

{% api-method-description %}
This resource allows you to get a Borrower's financial (credit) record  for the past 6 Months.

{% api-method-parameter name="ippis" type="string" %}
  - IPPIS - For public sector borrowers, GOvernment salary workers.
{% endapi-method-parameter %}

```js
{ "ippis": "123456" }
```
{% endapi-method-description %}

{% endapi-method %}