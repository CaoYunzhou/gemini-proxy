# Gemini-proxy

- gemini-proxy-vercel

## 这是利用vercel反向代理google的gemini的API接口

- [参考官方Gemini文档](https://ai.google.dev/tutorials/rest_quickstart)

### 部署方式

- fork仓库
- 打开vercel.com，进行部署自己克隆的仓库代码
- 点击部署，在设置里面配置域名
- [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/CaoYunzhou/gemini-proxy)

### 官方使用示例

```shell
curl https://generativelanguage.googleapis.com/v1beta/models/gemini-pro?key=$API_KEY
```

### Vercel反代后的使用示例

```shell
curl https://gemini.aivvm.com/v1beta/models/gemini-pro?key=$API_KEY
```

### 沉浸式翻译配置如下

- API KEY 填Google的秘钥
- 自定义 API 接口地址： **https://gemini.aivvm.com/v1/models/gemini-pro:generateContent?key={key}**

### 感谢源代码仓库作者

- <https://github.com/antergone/palm-proxy>
