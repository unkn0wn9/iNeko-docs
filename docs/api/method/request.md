## 请求地址

域名:https://api.ineko.cn

## 通信协议

喵脸识别的所有接口均通过HTTPS进行通信，提供高安全性的通信通道。

## 请求方法

同时支持 POST 和 GET 请求，需要注意不能混合使用。即如果使用 GET 方式，则参数均从 Querystring 取得；如果使用 POST 方式，则参数均从 Request Body 中取得，Querystring 中的参数将忽略。两种方式参数格式规则相同，一般使用GET，当参数字符串过长时使用POST，请见各接口详细描述。

## 字符编码

均使用UTF-8编码