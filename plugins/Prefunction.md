# Prefunction

If body null send this body and http code

s

```json
{
    "config": {
        "access": [
            "local body = kong.request.get_body() if not body then\n  return kong.response.exit(400, \"Invalid Body\")\nend local token = body[\"x-amzn-marketplace-token\"] if not token then\n  return kong.response.exit(400, \"Invalid Token\")\nend kong.response.set_header('Location', 'https://cloud.konghq.com/register?consumption=true&' .. ngx.encode_args({aws = token})) kong.response.exit(302)\n"
        ],
        "body_filter": [],
        "certificate": [],
        "functions": [],
        "header_filter": [],
        "log": [],
        "rewrite": [],
        "ws_client_frame": [],
        "ws_close": [],
        "ws_handshake": [],
        "ws_upstream_frame": []
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "6c61877a-dfa2-46ef-99f3-b7817f1bebfb",
    "name": "pre-function",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https",
        "ws",
        "wss"
    ],
    "route": {
        "id": "2bbeb679-441d-4ac6-8c5a-6291334ae3e0"
    },
    "updated_at": 1687534668
}
```