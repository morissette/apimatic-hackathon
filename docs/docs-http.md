# 

**`API Version:`** `1.0`

DeveloperWeek Austin 2017 Project



## Base URL

The base URL for this API is `http://change.opless.io/v1/`









# <a name="api_reference"></a>API Reference

* [API](#api)

## <a name="api"></a>![Endpoint Group: ](https://apidocs.io/img/class.png "API") API


### <a name="test_curl_endpoint"></a>![Endpoint: ](https://apidocs.io/img/method.png "TestCurlEndpoint") TestCurlEndpoint


**`POST`** `/change`



#### Base URL
This endpoint uses server ``.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [changeDetectionAPI Model](#change_detection_api_model) |  ``` Required ```  | - | 

 *Example Body* 
``` 
{
  "old": "oldtest",
  "new": "newtest"
}
``` 

#### Responses
**200** 


 *Example Body* (**dynamic**) 

```
{
  "old": "oldtest",
  "new": "newtest"
}
```


[Back to API Reference](#api_reference)

# <a name="models"></a> Models

### List of Models

* [changeDetectionAPI Model](#change_detection_api_model)
## <a name="change_detection_api_model"></a>![Type: ](https://apidocs.io/img/method.png "changeDetectionAPI Model") changeDetectionAPI Model



> Body





| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| old | string |  ``` Required ```  | The old api description file | 
| new | string |  ``` Required ```  | The new api description file | 



#### Example
```
{
  "old": "oldtest",
  "new": "newtest"
}
```




