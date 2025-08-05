# MasterscripFiles.DefaultApi

All URIs are relative to *https://nsbxapi-gw.kotaksecurities.com/files/1.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**masterscripFilePathsGet**](DefaultApi.md#masterscripFilePathsGet) | **GET** /masterscrip/file-paths | 
[**masterscripV1FilePathsGet**](DefaultApi.md#masterscripV1FilePathsGet) | **GET** /masterscrip/v1/file-paths | 
[**masterscripV2FilePathsGet**](DefaultApi.md#masterscripV2FilePathsGet) | **GET** /masterscrip/v2/file-paths | 
[**masterscripV4FilePathsGet**](DefaultApi.md#masterscripV4FilePathsGet) | **GET** /masterscrip/v4/file-paths | 



## masterscripFilePathsGet

> masterscripFilePathsGet()



### Example

```javascript
import MasterscripFiles from 'masterscrip_files';
let defaultClient = MasterscripFiles.ApiClient.instance;
// Configure OAuth2 access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = 'YOUR ACCESS TOKEN';

let apiInstance = new MasterscripFiles.DefaultApi();
apiInstance.masterscripFilePathsGet((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## masterscripV1FilePathsGet

> masterscripV1FilePathsGet()



Use this endpoint to get ScripMaster Files with Headers

### Example

```javascript
import MasterscripFiles from 'masterscrip_files';
let defaultClient = MasterscripFiles.ApiClient.instance;
// Configure OAuth2 access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = 'YOUR ACCESS TOKEN';

let apiInstance = new MasterscripFiles.DefaultApi();
apiInstance.masterscripV1FilePathsGet((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## masterscripV2FilePathsGet

> masterscripV2FilePathsGet()



ScripMaster Files with Surveillance message 

### Example

```javascript
import MasterscripFiles from 'masterscrip_files';
let defaultClient = MasterscripFiles.ApiClient.instance;
// Configure OAuth2 access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = 'YOUR ACCESS TOKEN';

let apiInstance = new MasterscripFiles.DefaultApi();
apiInstance.masterscripV2FilePathsGet((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## masterscripV4FilePathsGet

> masterscripV4FilePathsGet()



### Example

```javascript
import MasterscripFiles from 'masterscrip_files';
let defaultClient = MasterscripFiles.ApiClient.instance;
// Configure OAuth2 access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = 'YOUR ACCESS TOKEN';

let apiInstance = new MasterscripFiles.DefaultApi();
apiInstance.masterscripV4FilePathsGet((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

