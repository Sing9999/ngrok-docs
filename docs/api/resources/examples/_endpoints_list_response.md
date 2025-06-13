<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-13T10:06:37Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yRtPx034vRDGaSEDVT2WRurtxO",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yRtPx034vRDGaSEDVT2WRurtxO"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yRtQgeAejdQUEybfglFsLKH7i5",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-13T10:06:37Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yRtQgeAejdQUEybfglFsLKH7i5",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-13T10:06:35Z",
      "hostport": "41c04f52c608.ngrok.paid:443",
      "id": "ep_2yRtQJoap5i5JHfwRWC5VfQ8elS",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yRtNvFm0KjYDHqLrxyuW6y9Cfm",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://41c04f52c608.ngrok.paid",
      "tunnel": {
        "id": "tn_2yRtQJoap5i5JHfwRWC5VfQ8elS",
        "uri": "https://api.ngrok.com/tunnels/tn_2yRtQJoap5i5JHfwRWC5VfQ8elS"
      },
      "tunnel_session": {
        "id": "ts_2yRtQIfVBPEotr3K8X1FTQqeYnH",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yRtQIfVBPEotr3K8X1FTQqeYnH"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-13T10:06:35Z",
      "upstream_url": "http://localhost:80",
      "url": "https://41c04f52c608.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-13T10:06:33Z",
      "domain": {
        "id": "rd_2yRtPx034vRDGaSEDVT2WRurtxO",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yRtPx034vRDGaSEDVT2WRurtxO"
      },
      "edge": {
        "id": "edgtls_2yRtPvTZj1BGOis3u10mwCXopWB",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yRtPvTZj1BGOis3u10mwCXopWB"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yRtPw31BpeeDHMFxIkEfhJkmR9",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-13T10:06:33Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
