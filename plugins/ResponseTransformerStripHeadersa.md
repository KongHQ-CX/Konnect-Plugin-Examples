# Response Transformer

Strip headers with response transformer

```json
{
    "config": {
        "add": {
            "headers": [
                "server:kong-mesh",
                "via:kong-enterprise-edition"
            ],
            "json": [],
            "json_types": []
        },
        "append": {
            "headers": [],
            "json": [],
            "json_types": []
        },
        "remove": {
            "headers": [
                "server",
                "via"
            ],
            "json": []
        },
        "rename": {
            "headers": []
        },
        "replace": {
            "headers": [],
            "json": [],
            "json_types": []
        }
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "4884f444-0645-457a-b7c2-b85b1a1015b5",
    "name": "response-transformer",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "updated_at": 1687534668
}
```