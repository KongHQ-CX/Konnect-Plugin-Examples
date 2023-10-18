# jq

customize body based on the item state passed in json

```json
{
    "config": {
        "request_if_media_type": [
            "application/json"
        ],
        "request_jq_program": null,
        "request_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        },
        "response_if_media_type": [
            "application/json"
        ],
        "response_if_status_code": [
            200
        ],
        "response_jq_program": "if (.item.state) then .item.state |= sub(\"COMPOSITE_STATE_\";\"\") else . end",
        "response_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        }
    },
    "created_at": 1695147582,
    "enabled": true,
    "id": "726b0dcd-1251-4cc8-a0b8-912ab0bcd1d7",
    "name": "jq",
    "protocols": [
        "http",
        "https"
    ],
    "route": {
        "id": "37bee830-d515-4194-ba4c-04d1234b75f1"
    },
    "updated_at": 1695147582
}
```

another example: fahrenheit to celsius 

```
{
    "config": {
        "request_if_media_type": [
            "application/json"
        ],
        "request_jq_program": ".fahrenheit = .celsius * 1.8 + 32",
        "request_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        },
        "response_if_media_type": [
            "application/json"
        ],
        "response_if_status_code": [
            200
        ],
        "response_jq_program": ".headers.jq = \"Hello, this is jq\"",
        "response_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        }
    },
    "created_at": 1694608151,
    "enabled": true,
    "id": "02d0618b-f80f-4179-98c5-4512431810ec",
    "name": "jq",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "b678e135-51ac-45c5-9ac2-9092b84aa806"
    },
    "tags": [
        "se-konnect-demo"
    ],
    "updated_at": 1694688363
}
```

```json
{
    "config": {
        "request_if_media_type": [
            "application/json"
        ],
        "request_jq_program": ".fahrenheit = .celsius * 1.8 + 32",
        "request_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        },
        "response_if_media_type": [
            "application/json"
        ],
        "response_if_status_code": [
            200
        ],
        "response_jq_program": ".headers.jq = \"Hello, this is jq\"",
        "response_jq_program_options": {
            "ascii_output": false,
            "compact_output": true,
            "join_output": false,
            "raw_output": false,
            "sort_keys": false
        }
    },
    "created_at": 1694608151,
    "enabled": true,
    "id": "02d0618b-f80f-4179-98c5-4512431810ec",
    "name": "jq",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "b678e135-51ac-45c5-9ac2-9092b84aa806"
    },
    "tags": [
        "se-konnect-demo"
    ],
    "updated_at": 1694688363
}
```