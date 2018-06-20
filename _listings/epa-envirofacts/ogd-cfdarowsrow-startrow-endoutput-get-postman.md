{
  "info": {
    "name": "EPA Integrated Grants Management System API ",
    "_postman_id": "9ae07d84-bc72-496d-b18f-0ca6ea3d9955",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "8839f340-71e0-4725-bdf6-77551d5a9d94",
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
          "id": "00191df9-7ddc-44cd-a437-66172ae9a979"
        }
      ]
    }
  ]
}