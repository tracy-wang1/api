# 删除资源池-TerminateUDSet

删除资源池

# Request Parameters
|Parameter name|Type|Description|Required|
|---|---|---|---|
|Region|string|地域。 参见 [地域和可用区列表](api/summary/regionlist)|**Yes**|
|ProjectId|string|项目ID。不填写为默认项目，子帐号必须填写。 请参考[GetProjectList接口](api/summary/get_project_list)|No|
|HostId|string|资源池的短ID|**Yes**|

# Response Elements
|Parameter name|Type|Description|Required|
|---|---|---|---|
|RetCode|int|返回码|**Yes**|
|Action|string|操作名称|**Yes**|
|HostId|string|资源池的短ID|No|

# Request Example
```
https://api.ucloud.cn?Action=TerminateUDSet
&Region=cn-zj
&HostId=XbmlUoMo
&ProjectId=xpehJnbk
```

# Response Example
```
{
    "Action": "TerminateUDSetResponse", 
    "HostId": "uUvxmFVZ", 
    "RetCode": 0
}
```

