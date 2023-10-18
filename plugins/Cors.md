# Cors

many endpoints

```json
{
    "config": {
        "credentials": true,
        "exposed_headers": [
            "Date",
            "x-datadog-trace-id",
            "Konnect-Acting-As",
            "Konnect-Feature-Set"
        ],
        "headers": [
            "Accept",
            "Accept-Version",
            "Content-Length",
            "Content-MD5",
            "Content-Type",
            "Date",
            "Authorization",
            "x-datadog-trace-id",
            "x-datadog-parent-id",
            "x-datadog-origin",
            "x-datadog-sampling-priority",
            "x-datadog-sampled",
            "Konnect-Acting-As",
            "Konnect-Feature-Set",
            "X-LaunchDarkly-Event-Schema",
            "X-LaunchDarkly-Payload-ID",
            "X-LaunchDarkly-User-Agent",
            "LD-Private",
            "X-LD-AccountId",
            "X-LD-EnvId",
            "X-LD-PrjId",
            "X-LaunchDarkly-Wrapper",
            "LD-API-Version",
            "X-LaunchDarkly-Tags"
        ],
        "max_age": 3600,
        "methods": [
            "GET",
            "POST",
            "PUT",
            "PATCH",
            "DELETE"
        ],
        "origins": [
            "https://.+\\.konghq\\.tech",
            "https://.+\\.konghq\\.com",
            "https://konghq\\.com"
        ],
        "preflight_continue": false
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "d7c09a63-e45e-44f0-ad93-1ec665553654",
    "name": "cors",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "updated_at": 1687534668
}

```