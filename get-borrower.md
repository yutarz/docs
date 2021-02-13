# Get Borrower

{% api-method method="get" host="https://api.yutars.com/borrower/" path="/v1/borrower/:id" %}
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

{% endapi-method-description %}
```js
{ "id": "237584dhd8s" }
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```js
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



