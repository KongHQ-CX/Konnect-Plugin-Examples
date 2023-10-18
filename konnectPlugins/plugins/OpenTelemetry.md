# OpenTelemetry

for end to end tracing. OpenTelemetry helm chart would need to be deployed. 

Examples for that can be provided

```json
{
    "config": {
        "batch_flush_delay": null,
        "batch_span_count": null,
        "connect_timeout": 1000,
        "endpoint": "http://jaeger-collector.mesh-observability.svc:4318/v1/traces",
        "header_type": "b3",
        "headers": null,
        "http_response_header_for_traceid": "x-kong-traceid",
        "queue": {
            "initial_retry_delay": 0.01,
            "max_batch_size": 1,
            "max_bytes": null,
            "max_coalescing_delay": 1,
            "max_entries": 10000,
            "max_retry_delay": 60,
            "max_retry_time": 60
        },
        "read_timeout": 5000,
        "resource_attributes": null,
        "send_timeout": 5000
    },
    "created_at": 1694608156,
    "enabled": true,
    "id": "7725d8c9-0d05-4809-a608-6ce91efc15f5",
    "name": "opentelemetry",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "service": {
        "id": "4838ae0e-4722-41b0-9a73-6b596f44787b"
    },
    "tags": [
        "se-konnect-ops"
    ],
    "updated_at": 1694608156
}
```