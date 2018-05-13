## 接口描述
本接口用于搜索数据库中是否有与提交的猫脸信息匹配或相似的内容

## 请求方式
`GET`

## 请求地址
`api.ineko.cn/identify`

## 输入参数
|参数名|参数说明|
|-|-|
|url|需要进行识别的URL|

## 输出参数
|参数名|参数说明|
|-|-|
|id|猫的id|
|name|猫的姓名|

## 示例

### 输入
    url:https://raw.githubusercontent.com/El-Chiang/iNeko/master/images/pipi/63.jpg

### 输出
    {
        "response": {
            "id": 1,
            "cat": "pipi"
        }
    }