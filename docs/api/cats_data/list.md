## 接口描述
本接口用于获取数据库中所有猫咪的特征向量信息。

## 请求方式
`GET`

## 请求地址
`api.ineko.cn/cats_data`

## 输入参数
无

## 输出参数
|参数名|参数说明|
|-|-|
|cats_datas|含有所有猫咪特征向量信息的序列|

## 示例

### 输出
    {
        "response": {
            "cats_datas": [
                [
                    2,
                    "r31rda"
                ],
                [
                    2,
                    "sfageq"
                ],
                [
                    1,
                    "adfasfa"
                ]
            ]
        }
    }
