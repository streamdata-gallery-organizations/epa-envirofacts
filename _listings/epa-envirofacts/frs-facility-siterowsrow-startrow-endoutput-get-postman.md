{
  "info": {
    "name": "EPA Locational information API ",
    "_postman_id": "14218685-b6b6-43a1-872e-1acf223f1714",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "41ac7050-335a-49fe-8c2f-fc7a907e7bd6",
      "name": "enviroFacts_FRS_FACILITY_SITE",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FRS_FACILITY_SITE/ROWS/:row_start::row_end/:output"
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
          "id": "40d7b220-f444-4cac-b875-6f64c785d3d9"
        }
      ]
    }
  ]
}