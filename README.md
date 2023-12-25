# Gemini-proxy

- gemini-proxy-vercel

## 这是利用vercel反向代理google的gemini的API接口

- [参考官方Gemini文档](https://ai.google.dev/tutorials/rest_quickstart)

### 部署方式

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/CaoYunzhou/gemini-proxy)


## 官方使用示例

```shell
curl https://generativelanguage.googleapis.com/v1beta/models/gemini-pro?key=$API_KEY
```

## cloudflare反代后的使用示例

```shell
curl https://gemini.aivvm.com/v1beta/models/gemini-pro?key=$API_KEY
```
