# request termination

req term with custom message and status code on route

```
{
    "config": {
        "body": "{\"type\": \"https://kongapi.info/konnect/not-found\",\"status\": 404,\"title\": \"Not Found\",\"detail\": \"The resource requested was not found.\"}",
        "content_type": "application/problem+json",
        "echo": false,
        "message": null,
        "status_code": 404,
        "trigger": null
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "2493e583-5a8f-430e-ad2f-2f67c75afdf6",
    "name": "request-termination",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "257285b7-e84a-4300-96e4-635c74f19d1c"
    },
    "updated_at": 1687534668
}
```