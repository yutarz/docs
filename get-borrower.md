# Get Borrower

{% api-method method="get" host="https://api.yutars.com" path="/v1/borrower/:id" %}
{% api-method-summary %}
Get Borrower
{% endapi-method-summary %}

{% api-method-description %}
This resource allows you to get a Borrower's financial (credit) record  for the past 6 Months.

{% api-method-parameter name="id" type="string" %}
  ###### Could be any of the below;
  - IPPIS - For public sector borrowers, GOvernment salary workers.
  - NIN - National Identity Number
  - BVN - Bank verification Number
{% endapi-method-parameter %}

```js
{ "id": "237584dhd8s" }
```
{% endapi-method-description %}

{% endapi-method %}