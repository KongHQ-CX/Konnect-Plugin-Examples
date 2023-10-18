# kafka log

Log pipleline for Kafka

```json
{
    "config": {
        "authentication": {
            "mechanism": "SCRAM-SHA-512",
            "password": "APASSWORD",
            "strategy": "sasl",
            "tokenauth": null,
            "user": "msk-konnect-cloud-gateway-plugin"
        },
        "bootstrap_servers": [
            {
                "host": "b-1.konnectmsk.dew4mj.c3.kafka.us-east-2.amazonaws.com",
                "port": 9096
            },
            {
                "host": "b-2.konnectmsk.dew4mj.c3.kafka.us-east-2.amazonaws.com",
                "port": 9096
            },
            {
                "host": "b-3.konnectmsk.dew4mj.c3.kafka.us-east-2.amazonaws.com",
                "port": 9096
            }
        ],
        "cluster_name": "konnect-msk",
        "custom_fields_by_lua": null,
        "keepalive": 60000,
        "keepalive_enabled": false,
        "producer_async": true,
        "producer_async_buffering_limits_messages_in_memory": 50000,
        "producer_async_flush_timeout": 1000,
        "producer_request_acks": 1,
        "producer_request_limits_bytes_per_request": 1048576,
        "producer_request_limits_messages_per_request": 200,
        "producer_request_retries_backoff_timeout": 100,
        "producer_request_retries_max_attempts": 10,
        "producer_request_timeout": 2000,
        "security": {
            "certificate_id": null,
            "ssl": true
        },
        "timeout": 10000,
        "topic": "konnect.auditlogs.gateway-access-logs"
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "38c1c37e-a5f0-4543-af86-efcd23188402",
    "name": "kafka-log",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https",
        "ws",
        "wss"
    ],
    "updated_at": 1691081697
}
```