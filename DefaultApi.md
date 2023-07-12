# OpenSessionApi.DefaultApi

All URIs are relative to *{replyTo}/test*

Method | HTTP request | Description
------------- | ------------- | -------------
[**testPost**](DefaultApi.md#testPost) | **POST** /test | 

<a name="testPost"></a>
# **testPost**
> testPost(command, alias, pwdhash, pin)



This API helps user login

### Example
```javascript
import {OpenSessionApi} from 'open_session_api';

let apiInstance = new OpenSessionApi.DefaultApi();
let command = "command_example"; // String | indicates the type of action
let alias = "alias_example"; // String | username
let pwdhash = "pwdhash_example"; // String | password
let pin = 56; // Number | pin number

apiInstance.testPost(command, alias, pwdhash, pin, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **command** | **String**| indicates the type of action | 
 **alias** | **String**| username | 
 **pwdhash** | **String**| password | 
 **pin** | **Number**| pin number | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

