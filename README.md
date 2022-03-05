# 每日一言

## 介绍
---
每日一言的开放免费 api；供自己以及他人使用；

存储数万条名言警句；日后还会爬取增加；

可直接访问，不需要带 token 等麻烦配置验证；

访问限制：每个 ip 每次请求之间需要隔 0.5 秒，否则返回 503;  

## 获取使用
---
请求链接：  

```
https://saying.api.azwcl.com/saying/get
```

返回值：

```json
{
    "code": 200             # 请求成功均为 200
    "data": {               # 数据
        "author": "...",    # 作者
        "content": "..."    # 内容
    }
}
```

示例：

```json
{
    "code": 200,
    "data": {
        "author": "azwcl",
        "content": "爱你!"
    }
}
```