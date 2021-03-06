---
title: Rancher API - subnet
layout: rancher-api-v2-beta-default-v1.2
version: v1.2
lang: zh
apiVersion: v2-beta
---

## Subnet



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
cidrSize | int | Yes | - | 24 | 
description | string | Optional | Yes | - | 
endAddress | string | Optional | - | - | 
gateway | string | Optional | - | - | 
name | string | Optional | Yes | - | 
networkAddress | string | Yes | - | - | 
startAddress | string | Optional | - | - | 


#### Read Only Fields

Field | Type   | Notes
---|---|---
id | int  | The unique identifier for the subnet
networkId | [network]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/network/)  | 


<br>

Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/common/). These fields are read only and applicable to almost every resource. We have segregated them from the list above.




