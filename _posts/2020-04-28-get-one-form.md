---
category: Forms
url_path: '/api/v3/forms/:id'
title: 'Get all options for one form'
type: 'GET'

layout: null
---

This method allows users to retrieve one form.

Example for: 
`https://mx.mapa.frenalacurva.net/api/v3/forms/2`

### Request

* The headers must include a **valid authentication token**.

```Authentication: bearer TOKEN```

### Response

Sends back a the collection of surveys.

```Status: 200 OK```
```{
  "id": 2,
  "url": "https://mx.mapa.frenalacurva.net/api/v3/forms/2",
  "parent_id": null,
  "name": "Negocios y servicios locales",
  "description": "¿Estás buscando...",
  "color": "#274690",
  "type": "report",
  "disabled": false,
  "created": "2020-03-18T13:16:42+00:00",
  "updated": "2020-04-14T01:14:49+00:00",
  "hide_author": false,
  "hide_time": false,
  "hide_location": true,
  "require_approval": true,
  "everyone_can_create": true,
  "targeted_survey": false,
  "can_create": [
    "admin",
    "user",
    "Equipo de validación"
  ],
  "tags": [
    {
      "id": 1,
      "url": "https://mx.mapa.frenalacurva.net/api/v3/tags/1"
    },
    ...
  ],
  "allowed_privileges": [
    "read",
    "search"
  ]
}```
