# Prometheus

example of Prometheus on global level with extra metrics

```docker
{
    "config": {
        "bandwidth_metrics": true,
        "latency_metrics": true,
        "per_consumer": false,
        "status_code_metrics": true,
        "upstream_health_metrics": true
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "10f7bc6e-40c8-498d-b10b-3ad69e2c3947",
    "name": "prometheus",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "updated_at": 1687534668
}
```