# resumeLiveStream


## 描述
恢复直播流推送

## 请求方式
PUT

## 请求地址
https://live.jdcloud-api.com/v1/streams:resume


## 请求参数
|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**appName**|String|True| |应用名称|
|**publishDomain**|String|True| |您的加速域名|
|**streamName**|String|True| |流名称|


## 返回参数
|名称|类型|描述|
|---|---|---|
|**requestId**|String|ruquestId|
|**result**|Result| |

### Result
|名称|类型|描述|
|---|---|---|
|**publishDomain**|String|您的加速域名|

## 返回码
|返回码|描述|
|---|---|
|**400**|Invalid parameter|
|**401**|Authentication failed|
|**404**|Not found|
|**503**|Service unavailable|
|**200**|OK|
|**500**|Internal server error|