<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tunnels": [
    {
      "endpoint": {
        "id": "ep_2yRtP4MFxrHqZqlJIG6lFsBbA1E",
        "uri": "https://api.ngrok.com/endpoints/ep_2yRtP4MFxrHqZqlJIG6lFsBbA1E"
      },
      "forwards_to": "http://localhost:80",
      "id": "tn_2yRtP4MFxrHqZqlJIG6lFsBbA1E",
      "proto": "https",
      "public_url": "https://b4091c34d2b8.ngrok.paid",
      "region": "us",
      "started_at": "2025-06-13T10:06:25Z",
      "tunnel_session": {
        "id": "ts_2yRtP1OOG716JUkO32zkqzikbWr",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yRtP1OOG716JUkO32zkqzikbWr"
      }
    },
    {
      "forwards_to": "http://localhost:80",
      "id": "tn_2yRtOehPOPgdi7ItyB9Yh9Yp8E1",
      "labels": {
        "baz": "qux",
        "foo": "bar"
      },
      "region": "us",
      "started_at": "2025-06-13T10:06:22Z",
      "tunnel_session": {
        "id": "ts_2yRtOdksJtIE6CvyUmQcaIfVeqU",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yRtOdksJtIE6CvyUmQcaIfVeqU"
      }
    }
  ],
  "uri": "https://api.ngrok.com/tunnels"
}
```
