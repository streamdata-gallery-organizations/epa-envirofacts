{
  "info": {
    "name": "EPA Radiation Ambient Monitoring API ",
    "_postman_id": "461d60f0-71c6-4e95-9fca-6c0fc9f8e7cb",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "1a38909e-0128-4cbd-8d5c-7ab8704d35f4",
      "name": "enviroFacts_BGM_ONSITE_TREATMENT",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "BGM_ONSITE_TREATMENT/ROWS/:row_start::row_end/:output"
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
          "id": "12099add-a1c1-46ad-80da-13a0e860b271"
        }
      ]
    }
  ]
}