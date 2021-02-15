# Get Borrower

{% api-method method="get" host="https://api.yutars.com" path="/v1/borrower/nin/:nin" %}
{% api-method-summary %}
By NIN
{% endapi-method-summary %}

{% api-method-description %}
This resource allows you to get a Borrower's financial (credit) record  for the past 6 Months.

{% api-method-parameter name="nin" type="string" %}
  - NIN - National Identity Number
{% endapi-method-parameter %}

```js
{ "nin": "12345678901" }
```
{% endapi-method-description %}

{% endapi-method %}