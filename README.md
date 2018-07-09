# 资产中心

## 账户资产信息
> GET /api/v2/inner/finance
### 入参信息
参数  |  必须  | 类型  | 描述  | 取值范围  | 特别说明或默认值|位置
--- | --- | --- | --- | --- | --- | ---
headerToken | 是 | string | 用户登录token | - | - | body
### 返回数据
```javascript

```
### 返回示例
```javascript

```
## 资金流水
> GET /api/v2/inner/finance/accountRecord
### 入参信息
参数  |  必须  | 类型  | 描述  | 取值范围  | 特别说明或默认值|位置
--- | --- | --- | --- | --- | --- | ---
headerToken | 是 | string | 用户登录token | - | - | body
assetType | 否 | string | 资产类型 | --- | --- | body
handleType | 否 | string | 流水类型 | --- | --- | body
start | 否 | string | 查询开始时间 | 0000-00-00 00:00:00 | --- | body
end | 否 | string | 查询结束时间 | 0000-00-00 00:00:00 | --- | body
from | 否 | string | 查询起始id | --- | --- | body
to | 否 
