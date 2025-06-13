<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-13T10:06:43Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yRtRKRQGfg8TVvYrCNOFk2vKee",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yRtRKRQGfg8TVvYrCNOFk2vKee"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yRtPtQ38lyX3rHsWJQLLW2Po8z",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yRtPtQ38lyX3rHsWJQLLW2Po8z"
        },
        "enabled": true
      },
      "created_at": "2025-06-13T10:06:32Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yRtPvTZj1BGOis3u10mwCXopWB",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yRtPvTZj1BGOis3u10mwCXopWB"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
