---
category: Collections
url_path: '/api/v3/collections'
title: 'Get collections'
type: 'GET'

layout: null
---

This method allows users to retrieve all collections.

Example for: 
`https://mx.mapa.frenalacurva.net/api/v3/collections`

### Request

* The headers must include a **valid authentication token**.

```Authentication: bearer TOKEN```

### Response

Sends back a the collection of surveys.

```Status: 200 OK```
```{
  "count": 3,
  "results": [
    {
      "id": 5,
      "url": null,
      "user": {
        "id": 115,
        "url": "https://mx.mapa.frenalacurva.net/api/v3/users/115"
      },
      "name": "Lado B / Manatí",
      "description": "Negocios locales en Puebla...",
      "view": "map",
      "view_options": null,
      "role": null,
      "featured": false,
      "created": "2020-04-05T15:46:38+00:00",
      "updated": null,
      "allowed_privileges": [
        "read",
        "search"
      ]
    },
    ...
  ]
}```
