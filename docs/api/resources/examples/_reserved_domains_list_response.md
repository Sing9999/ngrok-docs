<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-06-13T10:06:17Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.51fbxxbhadzwbqpao.local-ngrok-cname.com",
      "created_at": "2025-06-13T10:06:17Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yRtNyYnE4c5f32w5EUyC52KHZY",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yRtNyYnE4c5f32w5EUyC52KHZY"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2yRtO1xwutXAj5KUqZblElc9f9c",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2yRtO1xwutXAj5KUqZblElc9f9c"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.51fbxxbhadzwbqpao.local-ngrok-cname.com",
      "created_at": "2025-06-13T10:06:17Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yRtNxWY50osEDan3XAqbpp21Mc",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yRtNxWY50osEDan3XAqbpp21Mc"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
