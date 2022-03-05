# Saying

## introduce
---
Open free API every day; For use by oneself and others;  

Store tens of thousands of aphorisms; It will climb and increase in the future;  

Can directly access, do not need to take token and other troublesome configuration verification;  

Access restriction: each IP address must be 0.5 seconds between each request, otherwise 503 is returned.  

## Get Use
---
Request link：  

```
https://saying.api.azwcl.com/saying/get
```

Returned value：

```json
{
    "code": 200             # Request success code 200
    "data": {               # data
        "author": "...",    # author
        "content": "..."    # content
    }
}
```

Sample：

```json
{
    "code": 200,
    "data": {
        "author": "azwcl",
        "content": "爱你!"
    }
}
```