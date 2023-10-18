# HTTP Log

logging http messages

```json
{
    "config": {
        "content_type": "application/json",
        "custom_fields_by_lua": {
            "streams": "local ts=string.format('%18.0f', os.time()*1000000000) local log_payload         = kong.log.serialize() local service = log_payload['service'] or 'noService' local cjson         = require \"cjson\" local payload_string = cjson.encode(log_payload) local t         = { {stream = {gateway='kong-gateway', service=service['name']}, values={{ts,         payload_string}}} } return t"
        },
        "flush_timeout": 2,
        "headers": null,
        "http_endpoint": "http://loki.mesh-observability.svc:3100/loki/api/v1/push",
        "keepalive": 60000,
        "method": "POST",
        "queue": {
            "initial_retry_delay": 0.01,
            "max_batch_size": 1,
            "max_bytes": null,
            "max_coalescing_delay": 1,
            "max_entries": 10000,
            "max_retry_delay": 60,
            "max_retry_time": 60
        },
        "queue_size": 1,
        "retry_count": 10,
        "timeout": 10000
    },
    "created_at": 1694608152,
    "enabled": true,
    "id": "7f5dcf7d-3c5c-45fc-b320-b9b96378add3",
    "name": "http-log",
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