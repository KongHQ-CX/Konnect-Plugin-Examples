# Proxy Caching

Example of proxy for caching

```json
{
    "config": {
        "cache_control": false,
        "cache_ttl": 300,
        "content_type": [
            "text/plain",
            "application/json"
        ],
        "ignore_uri_case": false,
        "memory": {
            "dictionary_name": "kong_db_cache"
        },
        "request_method": [
            "GET",
            "HEAD"
        ],
        "response_code": [
            200,
            301,
            404
        ],
        "storage_ttl": null,
        "strategy": "memory",
        "vary_headers": null,
        "vary_query_params": null
    },
    "created_at": 1694608151,
    "enabled": true,
    "id": "1b46e25c-bdb2-457b-9846-bc622ff366b4",
    "name": "proxy-cache",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "route": {
        "id": "fa7f8c99-99d0-4965-a96e-84997bef9601"
    },
    "tags": [
        "se-konnect-demo"
    ],
    "updated_at": 1694608151
}
```