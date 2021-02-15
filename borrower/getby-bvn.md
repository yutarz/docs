# Get Borrower

{% api-method method="get" host="https://api.yutars.com" path="/v1/borrower/bvn/:bvn" %}
{% api-method-summary %}
By BVN
{% endapi-method-summary %}

{% api-method-description %}
This resource allows you to get a Borrower's financial (credit) record  for the past 6 Months.

{% api-method-parameter name="bvn" type="string" %}
  - BVN - Bank verification Number
{% endapi-method-parameter %}

```js
{ "id": "01234567890" }
```
{% endapi-method-description %}

{% endapi-method %}