# Insert Soil

{% api-method method="post" host="http://samadhanv2api.em3agri.com/api/" path="soil/InsertSoil" %}
{% api-method-summary %}
Insert Soil
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="" type="string" required=false %}
{  
      "Cd":"t1",  
      "Nm":"Test 2",  
        "Uid":1  
 }
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Soil Inserted Successfully
{% endapi-method-response-example-description %}

```javascript
{
    "status": true,
    "message": "Soil Inserted successfully.",
    "data": null,
    "SyncDate": null,
    "PageSize": null,
    "error": ""
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "status": false,
    "message": "Something went wrong.",
    "data": null,
    "SyncDate": null,
    "PageSize": null,
    "error": ""
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



