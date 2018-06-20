{
  "info": {
    "name": "EPA Integrated Grants Management System API ",
    "_postman_id": "aaa384e1-d46a-44a4-82d2-5d2088549afb",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "64cdd4a3-274f-4145-bc37-2b9f94bfb443",
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
          "id": "6ce1146b-b014-48e1-aee8-27a4a53ce84f"
        }
      ]
    },
    {
      "id": "c98ef18c-ec39-4b07-9adc-a93f4c70a884",
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
          "id": "516ee13c-06ea-43be-a16c-937e3d5b8d81"
        }
      ]
    },
    {
      "id": "3fe9009a-eb34-4059-915c-9abeb79ca89a",
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
          "id": "52cda253-af14-4ec3-b316-70c02710f075"
        }
      ]
    },
    {
      "id": "d8e6c2e7-0218-4479-b8ea-ac794042f238",
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
          "id": "211997a1-cbc4-4da5-82c9-77e4ffb41243"
        }
      ]
    },
    {
      "id": "04863231-24d6-4324-b197-f486080508e2",
      "name": "enviroFacts_OGD_EF_GRANT_SUM_RPT",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "OGD_EF_GRANT_SUM_RPT/ROWS/:row_start::row_end/:output"
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
          "id": "f8a7cccf-7e74-4a3b-94a2-d1414ec4d0eb"
        }
      ]
    }
  ]
}