<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
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
}
```
