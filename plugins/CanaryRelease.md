# Canary Release

Example of canary release

```json
{
    "config": {
        "canary_by_header_name": null,
        "duration": 3600,
        "groups": null,
        "hash": "none",
        "hash_header": null,
        "percentage": 50,
        "start": null,
        "steps": 3600,
        "upstream_fallback": false,
        "upstream_host": "mockbin.org",
        "upstream_port": 80,
        "upstream_uri": "/albums"
    },
    "created_at": 1694608152,
    "enabled": true,
    "id": "66dd86f4-88dc-42ae-a78d-60de9d258d6b",
    "name": "canary",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "593bfbab-03c2-44b0-8741-bd9414c87335"
    },
    "tags": [
        "se-konnect-demo"
    ],
    "updated_at": 1694608152
}

```