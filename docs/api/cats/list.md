## 接口描述
本接口用于获取数据库中所有猫咪的数据信息

## 请求方式
`GET`

## 请求地址
`api.ineko.cn/cats`

## 输入参数
无

## 输出参数
|参数名|参数说明|
|-|-|
|cats_list|含有所有猫咪信息的序列|

## 示例

### 输出
    {
        "reponse": {
            "cats_list": [
                [
                    1,
                    "\u00e7\u009a\u00ae\u00e7\u009a\u00ae",
                    5,
                    "\u00e4\u00b8\u00ad\u00e5\u008d\u008e\u00e7\u0094\u00b0\u00e5\u009b\u00ad\u00e7\u008c\u00ab",
                    null,
                    null,
                    "\u00e5\u008c\u0097\u00e4\u00ba\u00ac"
                ],
                [
                    2,
                    "\u00e8\u0090\u008c\u00e8\u0090\u008c",
                    3,
                    "\u00e7\u008b\u00b8\u00e8\u008a\u00b1",
                    null,
                    null,
                    "\u00e5\u008c\u0097\u00e4\u00ba\u00ac"
                ],
                [
                    4,
                    "banban",
                    null,
                    null,
                    "123",
                    "123",
                    null
                ]
            ]
        }
    }
