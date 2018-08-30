{
  "info": {
    "name": "EPA Integrated Grants Management System API ",
    "_postman_id": "99c37167-4b6e-48d0-91e3-4501952d267d",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "6d308fba-e65f-4fba-b1f7-02a879e0d78e",
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
          "id": "efca7232-0475-4f89-84f0-e6ae4e9f5209"
        }
      ]
    },
    {
      "id": "d37f5d05-3cac-4996-a429-42678f2e2a07",
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
          "id": "14eea57d-fd9a-45f5-87b6-89afa6ae34ea"
        }
      ]
    },
    {
      "id": "88bd2c0f-0a4a-48fe-a14b-d6e68354442a",
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
          "id": "9226cda7-6772-4af4-8798-b5c26e4c2126"
        }
      ]
    },
    {
      "id": "8dac28b4-06e0-410e-9e73-64a85fb39567",
      "name": "enviroFacts_OGD_EF_GRANT_DTL_RPT",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "OGD_EF_GRANT_DTL_RPT/ROWS/:row_start::row_end/:output"
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
          "id": "c6803d60-a64c-4539-93ec-14ff0cac2ac4"
        }
      ]
    }
  ]
}