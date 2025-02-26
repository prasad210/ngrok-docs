<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-26T10:13:12Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tZg15ZMWWqJbr9Y8xP1ARrxcdT",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tZg15ZMWWqJbr9Y8xP1ARrxcdT"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tZfzlJZ9m8G8pIR5WFQ5tEXHkb",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tZfzlJZ9m8G8pIR5WFQ5tEXHkb"
				},
				"enabled": true
			},
			"created_at": "2025-02-26T10:13:01Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tZfzhW0uhgOEToVAQ258MeXdMb",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tZfzhW0uhgOEToVAQ258MeXdMb"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
