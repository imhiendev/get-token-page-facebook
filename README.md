
## Install

### Bước 1
+ Lấy token EAABw. Nếu không biết hãy ấn vào [đây](https://github.com/imhiendev/get-token-instagram-facebook/) hoặc copy đường link bên dưới.

```text
https://github.com/imhiendev/get-token-instagram-facebook/
```


### Bước 2

```http
GET https://graph.facebook.com/v13.0/me/accounts
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `access_token` | `string` | **Bắt buộc**. Token của bạn |

### Response
```json
{
    "data": [
        {
            "access_token": "EAABwzLixnjYBO2OCtIZAZAZCekeg1FI4km3BUmZCZCBPi2cq9s3kujuFtl7ocCMRU2YaNwriyRZA4h9RwnBFTtZAZC4EGPJLfwNB9bafd41y1oB91pYiUexfW45l6cRqc0w2aEj8uqcyeId12XcnnovwqbspKrRi6hMESz0PqeXygZAEhGZ",
            "category": "Trung tâm giải trí",
            "category_list": [
                {
                    "id": "183013211744255",
                    "name": "Trung tâm giải trí"
                }
            ],
            "name": "We Are Meow",
            "id": "150501874805374",
            "perms": [
                "ADMINISTER",
                "CREATE_CONTENT",
                "MODERATE_CONTENT",
                "MESSAGING",
                "CREATE_ADS",
                "BASIC_ADMIN",
                "MANAGE_PAGE_CONTACTS"
            ],
            "tasks": [
                "PROFILE_PLUS_ADVERTISE",
                "PROFILE_PLUS_ANALYZE",
                "PROFILE_PLUS_CREATE_CONTENT",
                "PROFILE_PLUS_FACEBOOK_ACCESS",
                "PROFILE_PLUS_MESSAGING",
                "PROFILE_PLUS_MODERATE",
                "PROFILE_PLUS_FULL_CONTROL",
                "PROFILE_PLUS_MANAGE"
            ]
        }
    ]
}       
```

## 📁 Hỗ trợ

**Cần hỗ trợ? Hãy liên hệ với tôi [tại đây.](https://t.me/sironho)**


