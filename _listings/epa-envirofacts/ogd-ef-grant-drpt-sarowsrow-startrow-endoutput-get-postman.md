{
  "info": {
    "name": "EPA Integrated Grants Management System API ",
    "_postman_id": "15b55c3c-63d4-4507-b61d-1d9077d9725e",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "30922f1b-9a9b-41d8-8184-f473625c7653",
      "name": "enviroFacts_OGD_CFDA",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "OGD_CFDA/ROWS/:row_start::row_end/:output"
          ],
          "variable": [
            {
              "id": "output",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_end",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_start",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": ""
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "96e3a43e-fec1-44c4-8dc7-d397a6b268b6"
        }
      ]
    },
    {
      "id": "a2d5f6c5-94bb-47d2-bdef-95644b99545a",
      "name": "enviroFacts_OGD_EF_GRANT_DRPT_CFDA",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "OGD_EF_GRANT_DRPT_CFDA/ROWS/:row_start::row_end/:output"
          ],
          "variable": [
            {
              "id": "output",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_end",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_start",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": ""
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6d1f38da-f7ec-4d78-8ca6-b9352b0aebc5"
        }
      ]
    },
    {
      "id": "1b790611-2e30-44b5-a9b9-b451565e6cf4",
      "name": "enviroFacts_OGD_EF_GRANT_DRPT_SA",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "OGD_EF_GRANT_DRPT_SA/ROWS/:row_start::row_end/:output"
          ],
          "variable": [
            {
              "id": "output",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_end",
              "value": "{}",
              "type": "string"
            },
            {
              "id": "row_start",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": ""
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d9b37588-f54d-4946-9a98-9af87e3b4c8d"
        }
      ]
    }
  ]
}