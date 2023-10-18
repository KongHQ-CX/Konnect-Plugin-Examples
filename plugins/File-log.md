# File log

Here is an example of the file logger with some custom fields set in Lua.

```docker
{
    "config": {
        "custom_fields_by_lua": {
            "actor_id": "return ((kong.ctx.shared.jwt_payload or {}).act or {}).sub",
            "auth_type": "return (kong.ctx.shared.jwt_payload or {}).auth_type",
            "client_ip": "return kong.client.get_forwarded_ip()",
            "dd.trace_id": "return kong.request.get_header('x-datadog-trace-id')",
            "org_id": "return (kong.ctx.shared.jwt_payload or {}).oid",
            "principal_id": "return (kong.ctx.shared.jwt_payload or {}).sub",
            "request.headers.cookie": "return nil",
            "response.headers.set-cookie": "return nil",
            "status": "return kong.response.get_status()",
            "time": "return ngx.ctx.KONG_PROCESSING_START or (ngx.req.start_time() * 1000)",
            "trace_id": "return kong.request.get_header('x-datadog-trace-id')",
            "ts": "return kong.request.get_start_time()",
            "uri": "return kong.request.get_path_with_query()"
        },
        "path": "/dev/stdout",
        "reopen": false
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "008fadc4-df99-4bd4-a983-87ce39048f15",
    "name": "file-log",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "updated_at": 1687534668
}
```