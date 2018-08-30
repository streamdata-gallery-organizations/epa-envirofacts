{
  "info": {
    "name": "EPA Integrated Grants Management System API ",
    "_postman_id": "33b2754a-c5b5-4f46-baff-04dd8a4b81c2",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c893dd91-4f89-40db-8e0f-bb38a9a57f15",
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
          "id": "8d4d79d8-eb76-45b7-b067-74840e7c93bc"
        }
      ]
    },
    {
      "id": "3581d999-5ed7-465e-af24-3cec25bc1361",
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
          "id": "63810e63-4ee6-42f4-bab2-afedff614f88"
        }
      ]
    }
  ]
}