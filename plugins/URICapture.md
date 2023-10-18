# URI Capture

example of URI capture
Example 1

```
{
    "config": {
        "add": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "append": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "http_method": null,
        "remove": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "rename": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "replace": {
            "body": [],
            "headers": [],
            "querystring": [],
            "uri": "/v2/$(uri_captures[1])"
        }
    },
    "created_at": 1694467863,
    "enabled": true,
    "id": "017f563f-0434-4b78-a7e4-ae2e97bca22e",
    "name": "request-transformer",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "868d4c1e-405e-4310-a226-047a2c5daa63"
    },
    "updated_at": 1694467863
}
```

Example 2:

```
/v2/$(uri_captures[1])

{
    "config": {
        "add": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "append": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "http_method": null,
        "remove": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "rename": {
            "body": [],
            "headers": [],
            "querystring": []
        },
        "replace": {
            "body": [],
            "headers": [],
            "querystring": [],
            "uri": "/v2/$(uri_captures[1])"
        }
    },
    "created_at": 1694526432,
    "enabled": true,
    "id": "04d9b63b-b00a-47b1-b9bb-cc6ebfacbdc5",
    "name": "request-transformer",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "9eb5a7c9-4db4-4c8c-b6a8-c27978105865"
    },
    "updated_at": 1694526432
}
```