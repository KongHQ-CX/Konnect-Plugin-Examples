# Adv Rate Limit

using Redis cache

```
{
    "config": {
        "consumer_groups": null,
        "dictionary_name": "kong_rate_limiting_counters",
        "disable_penalty": false,
        "enforce_consumer_groups": false,
        "error_code": 429,
        "error_message": "API rate limit exceeded",
        "header_name": "Authorization",
        "hide_client_headers": false,
        "identifier": "header",
        "limit": [
            2000
        ],
        "namespace": "kgateway",
        "path": null,
        "redis": {
            "cluster_addresses": null,
            "connect_timeout": null,
            "database": 0,
            "host": "rw.konnect-global-redis.global-redis.internal.kongcloud.io",
            "keepalive_backlog": null,
            "keepalive_pool_size": 30,
            "password": "tDyKtSxhMgkfJhPO",
            "port": 6379,
            "read_timeout": null,
            "send_timeout": null,
            "sentinel_addresses": null,
            "sentinel_master": null,
            "sentinel_password": null,
            "sentinel_role": null,
            "sentinel_username": null,
            "server_name": null,
            "ssl": true,
            "ssl_verify": false,
            "timeout": 2000,
            "username": null
        },
        "retry_after_jitter_max": 64,
        "strategy": "redis",
        "sync_rate": 2,
        "window_size": [
            60
        ],
        "window_type": "sliding"
    },
    "created_at": 1687462742,
    "enabled": true,
    "id": "09710454-602d-4e5e-91a4-50fe54171012",
    "name": "rate-limiting-advanced",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "service": {
        "id": "ecba0107-ede7-46ff-87e2-edef4359c1be"
    },
    "updated_at": 1687462742
}
```