## 接口描述
本接口用于获取数据库中某一只猫咪的数据信息。

## 请求方式
`GET`

## 请求地址
`api.ineko.cn/cats/<cat_id>`

## 输入参数
|参数名|参数说明|
|-|-|
|id|猫咪的id|

## 输出参数
|参数名|参数说明|
|-|-|
|cats_info|含有单一猫咪信息的序列|

## 示例

### 输出
    {
        "response": {
            "cat_info": [
                [
                    1,
                    "\u00e7\u009a\u00ae\u00e7\u009a\u00ae",
                    5,
                    "\u00e4\u00b8\u00ad\u00e5\u008d\u008e\u00e7\u0094\u00b0\u00e5\u009b\u00ad\u00e7\u008c\u00ab",
                    null,
                    null,
                    "\u00e5\u008c\u0097\u00e4\u00ba\u00ac"
                ]
            ]
        }
    }