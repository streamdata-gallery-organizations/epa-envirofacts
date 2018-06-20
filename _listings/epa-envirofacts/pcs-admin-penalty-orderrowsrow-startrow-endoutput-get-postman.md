{
  "info": {
    "name": "EPA Permit Compliance System API ",
    "_postman_id": "1a093151-456f-477b-8273-03cb2a14cc4e",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "3969c54a-8543-4dee-9abf-453385e86dce",
      "name": "enviroFacts_PCS_ADMIN_PENALTY_ORDER",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "PCS_ADMIN_PENALTY_ORDER/ROWS/:row_start::row_end/:output"
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
          "id": "44ae57c3-106c-4484-953c-64ed7d4556e2"
        }
      ]
    }
  ]
}