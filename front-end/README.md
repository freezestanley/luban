## h5

与后台系统配套的渲染器

## user
admin/Zzc110110.
面向C端的编辑器

### 功能

- [] 账号新增/登陆/修改/权限设置
1. 新增
```bash
curl 'http://localhost:1337/content-manager/collection-types/plugins::users-permissions.user/1' \
  -H 'Accept: */*' \
  -H 'Accept-Language: zh-CN,zh;q=0.9' \
  -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MSwiaWF0IjoxNzEzMzM4MTcyLCJleHAiOjE3MTU5MzAxNzJ9.t4e-yTytPCAiqU_oT6WxUddZSFILeoQmsiYvzGszBLE' \
  -H 'Connection: keep-alive' \
  -H 'Content-Type: application/json' \
  -H 'DNT: 1' \
  -H 'Referer: http://localhost:1337/admin/plugins/content-manager/collectionType/plugins::users-permissions.user/1' \
  -H 'Sec-Fetch-Dest: empty' \
  -H 'Sec-Fetch-Mode: cors' \
  -H 'Sec-Fetch-Site: same-origin' \
  -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="123", "Not:A-Brand";v="8", "Chromium";v="123"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "macOS"'
```


```json
{
    "id": 1,
    "username": "test01",
    "email": "test@test01.com",
    "provider": "local",
    "resetPasswordToken": null,
    "confirmationToken": null,
    "confirmed": true,
    "blocked": true,
    "role": {
        "id": 1,
        "name": "Authenticated",
        "description": "Default role given to authenticated user.",
        "type": "authenticated",
        "created_by": null,
        "updated_by": null
    },
    "created_by": {
        "id": 1,
        "firstname": "admin",
        "lastname": "admin",
        "username": "Joz",
        "email": "zzc5464@foxmail.com",
        "resetPasswordToken": null,
        "registrationToken": null,
        "isActive": true,
        "blocked": null
    },
    "updated_by": {
        "id": 1,
        "firstname": "admin",
        "lastname": "admin",
        "username": "Joz",
        "email": "zzc5464@foxmail.com",
        "resetPasswordToken": null,
        "registrationToken": null,
        "isActive": true,
        "blocked": null
    },
    "created_at": "2024-04-17T08:09:32.448Z",
    "updated_at": "2024-04-17T08:09:32.455Z"
}
```




- [] 下载模板