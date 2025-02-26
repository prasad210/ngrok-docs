<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-26T10:13:06Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tZfzlIyqcsbZKO1njtszOFFB9d",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tZfzlIyqcsbZKO1njtszOFFB9d"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tZg0NOLf17S2LtwqtkuvNRfu8w",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-26T10:13:06Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tZg0NOLf17S2LtwqtkuvNRfu8w",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-26T10:13:05Z",
			"hostport": "0ecfcae43f10.ngrok.paid:443",
			"id": "ep_2tZg0D6HBoekms72uu1WgD0bwkP",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tZfxlD4DfsiU5zWFrmR3mYnGgj",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://0ecfcae43f10.ngrok.paid",
			"tunnel": {
				"id": "tn_2tZg0D6HBoekms72uu1WgD0bwkP",
				"uri": "https://api.ngrok.com/tunnels/tn_2tZg0D6HBoekms72uu1WgD0bwkP"
			},
			"tunnel_session": {
				"id": "ts_2tZg0JoWfaS7YmrmX3T1Tjpdlro",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tZg0JoWfaS7YmrmX3T1Tjpdlro"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-26T10:13:05Z",
			"upstream_url": "http://localhost:80",
			"url": "https://0ecfcae43f10.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-26T10:13:02Z",
			"domain": {
				"id": "rd_2tZfzlIyqcsbZKO1njtszOFFB9d",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tZfzlIyqcsbZKO1njtszOFFB9d"
			},
			"edge": {
				"id": "edgtls_2tZfzhW0uhgOEToVAQ258MeXdMb",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tZfzhW0uhgOEToVAQ258MeXdMb"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tZfzkCKAstehgdSIVOKuwajpsH",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-26T10:13:02Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
