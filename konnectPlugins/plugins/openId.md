# openId

with introspection cache enabled

```json
{
    "config": {
        "anonymous": null,
        "audience": null,
        "audience_claim": [
            "aud"
        ],
        "audience_required": null,
        "auth_methods": [
            "bearer"
        ],
        "authenticated_groups_claim": null,
        "authorization_cookie_domain": null,
        "authorization_cookie_http_only": true,
        "authorization_cookie_name": "authorization",
        "authorization_cookie_path": "/",
        "authorization_cookie_same_site": "Default",
        "authorization_cookie_secure": null,
        "authorization_endpoint": null,
        "authorization_query_args_client": null,
        "authorization_query_args_names": null,
        "authorization_query_args_values": null,
        "authorization_rolling_timeout": 600,
        "bearer_token_cookie_name": null,
        "bearer_token_param_type": [
            "header",
            "query",
            "body"
        ],
        "by_username_ignore_case": false,
        "cache_introspection": true,
        "cache_token_exchange": true,
        "cache_tokens": true,
        "cache_tokens_salt": "tokenakdflkkdasfkdsa",
        "cache_ttl": 3600,
        "cache_ttl_max": null,
        "cache_ttl_min": null,
        "cache_ttl_neg": null,
        "cache_ttl_resurrect": null,
        "cache_user_info": true,
        "client_alg": null,
        "client_arg": "client_id",
        "client_auth": null,
        "client_credentials_param_type": [
            "header",
            "query",
            "body"
        ],
        "client_id": null,
        "client_jwk": null,
        "client_secret": null,
        "consumer_by": [
            "username",
            "custom_id"
        ],
        "consumer_claim": null,
        "consumer_optional": false,
        "credential_claim": [
            "sub"
        ],
        "disable_session": null,
        "discovery_headers_names": null,
        "discovery_headers_values": null,
        "display_errors": false,
        "domains": null,
        "downstream_access_token_header": null,
        "downstream_access_token_jwk_header": null,
        "downstream_headers_claims": null,
        "downstream_headers_names": null,
        "downstream_id_token_header": null,
        "downstream_id_token_jwk_header": null,
        "downstream_introspection_header": null,
        "downstream_introspection_jwt_header": null,
        "downstream_refresh_token_header": null,
        "downstream_session_id_header": null,
        "downstream_user_info_header": null,
        "downstream_user_info_jwt_header": null,
        "enable_hs_signatures": false,
        "end_session_endpoint": null,
        "expose_error_code": true,
        "extra_jwks_uris": [
            "https://global.api.konghq.com/.well-known/jwks.json"
        ],
        "forbidden_destroy_session": true,
        "forbidden_error_message": "Forbidden",
        "forbidden_redirect_uri": null,
        "groups_claim": [
            "groups"
        ],
        "groups_required": null,
        "hide_credentials": false,
        "http_proxy": null,
        "http_proxy_authorization": null,
        "http_version": 1.1,
        "https_proxy": null,
        "https_proxy_authorization": null,
        "id_token_param_name": null,
        "id_token_param_type": [
            "header",
            "query",
            "body"
        ],
        "ignore_signature": [],
        "introspect_jwt_tokens": false,
        "introspection_accept": "application/json",
        "introspection_check_active": true,
        "introspection_endpoint": null,
        "introspection_endpoint_auth_method": null,
        "introspection_headers_client": null,
        "introspection_headers_names": null,
        "introspection_headers_values": null,
        "introspection_hint": "access_token",
        "introspection_post_args_client": null,
        "introspection_post_args_names": null,
        "introspection_post_args_values": null,
        "issuer": "https://global.api.konghq.com",
        "issuers_allowed": null,
        "jwt_session_claim": "sid",
        "jwt_session_cookie": null,
        "keepalive": true,
        "leeway": 0,
        "login_action": "upstream",
        "login_methods": [
            "authorization_code"
        ],
        "login_redirect_mode": "fragment",
        "login_redirect_uri": null,
        "login_tokens": [
            "id_token"
        ],
        "logout_methods": [
            "POST",
            "DELETE"
        ],
        "logout_post_arg": null,
        "logout_query_arg": null,
        "logout_redirect_uri": null,
        "logout_revoke": false,
        "logout_revoke_access_token": true,
        "logout_revoke_refresh_token": true,
        "logout_uri_suffix": null,
        "max_age": null,
        "no_proxy": null,
        "password_param_type": [
            "header",
            "query",
            "body"
        ],
        "preserve_query_args": false,
        "redirect_uri": null,
        "rediscovery_lifetime": 30,
        "refresh_token_param_name": null,
        "refresh_token_param_type": [
            "header",
            "query",
            "body"
        ],
        "refresh_tokens": true,
        "resolve_distributed_claims": false,
        "response_mode": "query",
        "response_type": [
            "code"
        ],
        "reverify": false,
        "revocation_endpoint": null,
        "revocation_endpoint_auth_method": null,
        "roles_claim": [
            "roles"
        ],
        "roles_required": null,
        "run_on_preflight": true,
        "scopes": [
            "openid"
        ],
        "scopes_claim": [
            "scope"
        ],
        "scopes_required": null,
        "search_user_info": false,
        "session_absolute_timeout": 86400,
        "session_audience": "default",
        "session_compressor": "none",
        "session_cookie_domain": null,
        "session_cookie_http_only": true,
        "session_cookie_maxsize": 4000,
        "session_cookie_name": "session",
        "session_cookie_path": "/",
        "session_cookie_renew": 600,
        "session_cookie_same_site": "Lax",
        "session_cookie_secure": null,
        "session_enforce_same_subject": false,
        "session_hash_storage_key": false,
        "session_hash_subject": false,
        "session_idling_timeout": 900,
        "session_memcached_host": "127.0.0.1",
        "session_memcached_port": 11211,
        "session_memcached_prefix": null,
        "session_memcached_socket": null,
        "session_redis_cluster_max_redirections": null,
        "session_redis_cluster_nodes": null,
        "session_redis_connect_timeout": null,
        "session_redis_host": "127.0.0.1",
        "session_redis_password": null,
        "session_redis_port": 6379,
        "session_redis_prefix": null,
        "session_redis_read_timeout": null,
        "session_redis_send_timeout": null,
        "session_redis_server_name": null,
        "session_redis_socket": null,
        "session_redis_ssl": false,
        "session_redis_ssl_verify": false,
        "session_redis_username": null,
        "session_remember": false,
        "session_remember_absolute_timeout": 2592000,
        "session_remember_cookie_name": "remember",
        "session_remember_rolling_timeout": 604800,
        "session_request_headers": null,
        "session_response_headers": null,
        "session_rolling_timeout": 3600,
        "session_secret": null,
        "session_storage": "cookie",
        "session_store_metadata": false,
        "session_strategy": "default",
        "ssl_verify": false,
        "timeout": 10000,
        "token_cache_key_include_scope": false,
        "token_endpoint": null,
        "token_endpoint_auth_method": null,
        "token_exchange_endpoint": null,
        "token_headers_client": null,
        "token_headers_grants": null,
        "token_headers_names": null,
        "token_headers_prefix": null,
        "token_headers_replay": null,
        "token_headers_values": null,
        "token_post_args_client": null,
        "token_post_args_names": null,
        "token_post_args_values": null,
        "unauthorized_destroy_session": true,
        "unauthorized_error_message": "Unauthorized",
        "unauthorized_redirect_uri": null,
        "unexpected_redirect_uri": null,
        "upstream_access_token_header": "authorization:bearer",
        "upstream_access_token_jwk_header": null,
        "upstream_headers_claims": null,
        "upstream_headers_names": null,
        "upstream_id_token_header": null,
        "upstream_id_token_jwk_header": null,
        "upstream_introspection_header": null,
        "upstream_introspection_jwt_header": null,
        "upstream_refresh_token_header": null,
        "upstream_session_id_header": null,
        "upstream_user_info_header": null,
        "upstream_user_info_jwt_header": null,
        "userinfo_accept": "application/json",
        "userinfo_endpoint": null,
        "userinfo_headers_client": null,
        "userinfo_headers_names": null,
        "userinfo_headers_values": null,
        "userinfo_query_args_client": null,
        "userinfo_query_args_names": null,
        "userinfo_query_args_values": null,
        "using_pseudo_issuer": false,
        "verify_claims": true,
        "verify_nonce": true,
        "verify_parameters": false,
        "verify_signature": true
    },
    "created_at": 1687534668,
    "enabled": true,
    "id": "897d2f0c-f6fa-4d8a-9c8a-6092f6ad1f3e",
    "name": "openid-connect",
    "protocols": [
        "grpc",
        "grpcs",
        "http",
        "https"
    ],
    "service": {
        "id": "775edf8f-8bac-44e4-8283-766b39ea631c"
    },
    "updated_at": 1696535185
}
```