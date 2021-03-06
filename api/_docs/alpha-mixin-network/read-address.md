---
title: Read Address
category: Mixin Network
order: 13
---

Read an address by ID.

###### GET /addresses/:id

```
// cURL Example
curl -i -H "Content-Type: application/json" -H "Authorization: Bearer eyJhbGciOiJSUzUxMiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE1MzMxMTYzNjEsImlhdCI6MTUyNTM0MDM2MSwianRpIjoiNDRhOGRiZDAtODU3NC00Y2VhLTk3NWEtYzI5OWIwZWQyMTk4Iiwic2lkIjoiYTM0YzA3YTktNzU1ZC00YjU0LTk0YzUtZTQ1ZTlhMmRkNDNlIiwic2lnIjoiN2IzMzEwYTQ2NjY5YzNkNWJkMjFkNjRlNWRhNTJjMmQ4M2MzYWFjNTUzMmU3OTdkMjAzMzY0NzE3MDhiMDJjOCIsInVpZCI6IjA2YWVkMWUzLWJkNzctNGE1OS05OTFhLTViYjVhZTZmYmIwOSJ9.LSoJ0iWCo1g71SC_SYDsY6ZobUxh2Ue0e0D7VC1-cRfudJHCjR00OM2LhrTTub6BB--BnplPWNYOuz8zdxdZwNhY0OpwEpeVg2zxW202MDlp_PW3nQP1U_wv6SvdtqzdM6JswL-GGhl2CEDEGN8iivUGwv54ouOv4U2pqR5IrBc" "https://api.mixin.one/addresses/e1524f3c-2e4f-411f-8a06-b5e1b1601308"
```
```
// Sample Response
{  
  "data":{
    "type":"address",
      "address_id":"e1524f3c-2e4f-411f-8a06-b5e1b1601308",
      "asset_id":"43d61dcd-e413-450d-80b8-101d5e903357",
      "public_key":"0x86Fa049857E0209aa7D9e616F7eb3b3B78ECfdb0",
      "account_name":"",
      "account_tag":"",
      "label":"Eth Address",
      "fee":"0.016",
      "reserve":"0",
      "dust": "0.0001",
      "updated_at":"2018-07-10T03:58:17.5559296Z"
  }
}
```
