# AI-Platform-study

## kling

### kling doc
接口鉴权配置：https://klingai.com/document-api/quickStart/userManual

JWT字段构建：https://klingai.com/document-api/apiReference/commonInfo

api请求方法：https://klingai.com/document-api/apiReference/model/multiElements

### apifox
#### 配置环境变量
<img width="1747" height="958" alt="image" src="https://github.com/user-attachments/assets/1f6d390e-7f11-4106-a170-2b0f5cb46f72" />

#### 配置JWT认证
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/c08e15c6-e7ed-45ca-b0a1-c31d8c9480ff" />

Apifox Secret = Kling API Secret Key

``` python
"iss": ak,
"exp": int(time.time()) + 1800, # 有效时间，此处示例代表当前时间+1800s(30min)
"nbf": int(time.time()) - 5 # 开始生效的时间，此处示例代表当前时间-5秒
```

#### 配置API
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/5e6771f1-07c2-4fd7-ab92-ffcc3f3f3308" />


