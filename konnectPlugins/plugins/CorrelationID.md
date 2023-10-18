# Correlation ID

For tracing end to end with an id

```json
{
    "config": {
        "echo_downstream": false,
        "generator": "uuid#counter",
        "header_name": "Kong-Request-ID"
    },
    "created_at": 1694608152,
    "enabled": true,
    "id": "5cd6b1f9-45b8-4f3b-ab82-ddda52559969",
    "name": "correlation-id",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "fc3c9167-6309-4ff3-91e5-328da74bb0d8"
    },
    "tags": [
        "se-konnect-demo"
    ],
    "updated_at": 1694608152
}
```