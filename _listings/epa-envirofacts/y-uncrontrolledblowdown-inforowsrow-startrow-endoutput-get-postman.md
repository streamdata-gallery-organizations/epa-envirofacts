{
  "info": {
    "name": "EPA Greenhouse Gas API ",
    "_postman_id": "8611545c-d694-4f07-85ed-3780f1db0b28",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "5311ae09-09b4-4993-9934-f3f67cded89b",
      "name": "enviroFacts_AA_FOSSIL_FUEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_FOSSIL_FUEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "8bd4c5e6-85b8-4e2c-9773-9194b87e1065"
        }
      ]
    },
    {
      "id": "abee236f-50c8-4624-9511-5aaac561d316",
      "name": "enviroFacts_AA_FOSSIL_FUEL_TIER_2_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_FOSSIL_FUEL_TIER_2_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "a94bed70-1962-4be8-8859-faa58d876a46"
        }
      ]
    },
    {
      "id": "f41d2385-1b00-4b43-9a0a-0d8f39a4351f",
      "name": "enviroFacts_AA_MAKEUP_CHEMICAL_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_MAKEUP_CHEMICAL_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "98990d6c-abcb-4a9f-843b-cf37d41308ea"
        }
      ]
    },
    {
      "id": "73294a9a-1bda-4ca1-b526-6c0094320ef3",
      "name": "enviroFacts_AA_SPENT_LIQUOR_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_SPENT_LIQUOR_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "b4978ce3-1405-4fca-8856-89ecee4a1e91"
        }
      ]
    },
    {
      "id": "7801c60e-2378-42c5-992d-e960e8eb44be",
      "name": "enviroFacts_AA_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "62b851ec-41e7-4ece-8a75-d9307c29dd28"
        }
      ]
    },
    {
      "id": "b7220601-8dba-4138-ae3d-2fe6e4643ba2",
      "name": "enviroFacts_AA_TIER_4_CEMS_QUARTERLY_CO2",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "AA_TIER_4_CEMS_QUARTERLY_CO2/ROWS/:row_start::row_end/:output"
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
          "id": "eb768e25-efb8-43f4-9e45-df22cab3e7d0"
        }
      ]
    },
    {
      "id": "c1b4d994-b5b8-4c2d-ae3d-ab5a67e68fe7",
      "name": "enviroFacts_C_BIOGENIC_CO2_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_BIOGENIC_CO2_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "a847c891-4b41-49a9-838c-f9f53c3a6c16"
        }
      ]
    },
    {
      "id": "53e124ae-c922-4605-a883-5a6d732c6b9c",
      "name": "enviroFacts_C_CEMS_QUARTERLY_CO2",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_CEMS_QUARTERLY_CO2/ROWS/:row_start::row_end/:output"
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
          "id": "89570280-b8a4-4881-aad8-50791d6e579e"
        }
      ]
    },
    {
      "id": "b28a5b8a-fed2-4cb3-a992-8be5188a7483",
      "name": "enviroFacts_C_CONFIGURATION_LEVEL_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_CONFIGURATION_LEVEL_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "ba9774a1-db6a-41e7-98b2-3feb46678957"
        }
      ]
    },
    {
      "id": "87dd480a-13d6-4e76-b775-10935a82c4b5",
      "name": "enviroFacts_C_FUEL_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_FUEL_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "cb2ade82-c95e-4f98-a517-9ffee0788a8b"
        }
      ]
    },
    {
      "id": "e89fd9bb-8673-4258-9330-6fd10b17af0d",
      "name": "enviroFacts_C_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "71775ee5-4e15-478c-bbf6-b7822be7545b"
        }
      ]
    },
    {
      "id": "65a75c27-5817-480d-accc-32450a6eb37a",
      "name": "enviroFacts_C_TIER2_MONTHLY_HHV",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "C_TIER2_MONTHLY_HHV/ROWS/:row_start::row_end/:output"
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
          "id": "1cf9cf9d-cb9b-4603-8cf5-345a8719ab8f"
        }
      ]
    },
    {
      "id": "f44912b0-29d2-4286-9cc3-7e0546b05e4a",
      "name": "enviroFacts_DD_FACILITY_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_FACILITY_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "9db2d09f-7d42-4a15-bef8-b4cb578f3596"
        }
      ]
    },
    {
      "id": "3db5bbc5-05ff-4bb0-a98b-e0eb0186672c",
      "name": "enviroFacts_DD_INCREASE_NAMEPLATE",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_INCREASE_NAMEPLATE/ROWS/:row_start::row_end/:output"
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
          "id": "ea98ac83-38f1-43f4-afff-d57378b18aee"
        }
      ]
    },
    {
      "id": "da23bb6c-d1cd-47ec-b243-696673e8a907",
      "name": "enviroFacts_DD_SF6PFC_ACQUISITIONS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_SF6PFC_ACQUISITIONS/ROWS/:row_start::row_end/:output"
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
          "id": "aceec69f-ce05-41ed-a6d6-fd1beb421e62"
        }
      ]
    },
    {
      "id": "e02e481f-59b1-414f-b97e-5ce1b53487fb",
      "name": "enviroFacts_DD_SF6PFC_DECREASES",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_SF6PFC_DECREASES/ROWS/:row_start::row_end/:output"
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
          "id": "b0916df1-0a35-468f-aef4-e31bdcf6f124"
        }
      ]
    },
    {
      "id": "21aa60bb-f2ed-45a7-ae16-ab0f3e6061b5",
      "name": "enviroFacts_DD_SF6PFC_DISBURSEMENT",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_SF6PFC_DISBURSEMENT/ROWS/:row_start::row_end/:output"
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
          "id": "f8d67be7-d3a3-425a-8aa2-3d25a7cc7c9b"
        }
      ]
    },
    {
      "id": "dc32005a-6813-4abd-abe8-24fa59525b5c",
      "name": "enviroFacts_DD_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "cb379272-0a60-499f-9ebd-e00402faf41c"
        }
      ]
    },
    {
      "id": "23a5a856-f998-4b38-b5e7-fcc61e332bd9",
      "name": "enviroFacts_DD_TRANSMISSION_LINE",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_TRANSMISSION_LINE/ROWS/:row_start::row_end/:output"
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
          "id": "e5f874ae-56b6-4b78-b8f6-4fd3c674f491"
        }
      ]
    },
    {
      "id": "4a3de862-72cb-4029-838d-559bc0776489",
      "name": "enviroFacts_DD_USER_EMISSIONS_CALC",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "DD_USER_EMISSIONS_CALC/ROWS/:row_start::row_end/:output"
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
          "id": "d7fb239c-08e8-420f-aa5b-066833644773"
        }
      ]
    },
    {
      "id": "2c6f819c-3f8a-4332-a504-d3380ebaada2",
      "name": "enviroFacts_D_FUEL_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "D_FUEL_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "3374c38b-5217-4fda-bd1e-ee5ca04d24cc"
        }
      ]
    },
    {
      "id": "12e94d1e-5353-457d-a7b8-973160699044",
      "name": "enviroFacts_EE_CEMS_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_CEMS_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "4ce48659-cbb2-4698-a4f4-6559c2c1bf85"
        }
      ]
    },
    {
      "id": "6b85aefb-21aa-41a5-8dfa-f29ba02bcaf9",
      "name": "enviroFacts_EE_CEMS_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_CEMS_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "505f4959-b45d-478a-b7a2-aee6c40a1a4b"
        }
      ]
    },
    {
      "id": "7697cc55-1e4a-438e-8488-f24d07faf567",
      "name": "enviroFacts_EE_FACILITY_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_FACILITY_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "f262d2a5-e001-46f9-84ec-9f6ff357a9b3"
        }
      ]
    },
    {
      "id": "720dcf61-3daa-4a4c-a3ca-26b9077c79ee",
      "name": "enviroFacts_EE_NOCEMSTIO2DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_NOCEMSTIO2DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "b5410399-be76-4f00-9e7f-0f35b399b952"
        }
      ]
    },
    {
      "id": "1c67a67d-217c-46ca-a889-3a0d233e3323",
      "name": "enviroFacts_EE_NOCEMS_MONTHLYDETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_NOCEMS_MONTHLYDETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "93946f19-b621-4ff3-9551-c03e4e410065"
        }
      ]
    },
    {
      "id": "b2cafe4e-e72d-4f62-b14d-1d3e9cc02865",
      "name": "enviroFacts_EE_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "cf3d4641-99d8-4a36-bb42-fc2d45bc6d43"
        }
      ]
    },
    {
      "id": "c829acf0-edef-436a-a413-3b7a89c101ed",
      "name": "enviroFacts_EE_TIER4CEMS_QTRDTLS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "EE_TIER4CEMS_QTRDTLS/ROWS/:row_start::row_end/:output"
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
          "id": "a39b5c37-d0fa-464a-9267-f06ac0145d11"
        }
      ]
    },
    {
      "id": "d18b3dd1-3518-42fe-a5af-d1daf7155711",
      "name": "enviroFacts_FF_DEGASIFICATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DEGASIFICATION/ROWS/:row_start::row_end/:output"
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
          "id": "00bc8786-21bd-4abd-ac42-909025bb934e"
        }
      ]
    },
    {
      "id": "1f50ab3d-a2c4-4713-a460-ea0a1a9d83aa",
      "name": "enviroFacts_FF_DEGAS_QTRLY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DEGAS_QTRLY/ROWS/:row_start::row_end/:output"
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
          "id": "7ad0282f-8c50-481e-806b-68bc32decaa2"
        }
      ]
    },
    {
      "id": "75062d19-1351-4d88-acbd-bda5c0abda3b",
      "name": "enviroFacts_FF_DEGAS_WEEKLY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DEGAS_WEEKLY/ROWS/:row_start::row_end/:output"
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
          "id": "62e622c3-03aa-4e46-83c6-44c6953c4c28"
        }
      ]
    },
    {
      "id": "a0f834e5-1db9-4ab0-a01e-37777bb35576",
      "name": "enviroFacts_FF_DESTROFFSITE_BACKUP",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DESTROFFSITE_BACKUP/ROWS/:row_start::row_end/:output"
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
          "id": "6cb30c6a-ddd7-4623-956c-dc9913826613"
        }
      ]
    },
    {
      "id": "276d2d68-1085-451d-baee-5b0a949aa346",
      "name": "enviroFacts_FF_DESTROFFSITE_QTRLY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DESTROFFSITE_QTRLY/ROWS/:row_start::row_end/:output"
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
          "id": "c1a6b207-1395-4986-a4d2-f8cc992c8adf"
        }
      ]
    },
    {
      "id": "bda46ab3-78a4-4872-afa8-025900d5fb68",
      "name": "enviroFacts_FF_DESTROFFSITE_WEEKLY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_DESTROFFSITE_WEEKLY/ROWS/:row_start::row_end/:output"
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
          "id": "d9e972db-3893-462d-8536-5514add3c8ae"
        }
      ]
    },
    {
      "id": "3172ca61-2b3f-4310-a771-c86369277514",
      "name": "enviroFacts_FF_METHOD_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_METHOD_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "a96c2cf1-20a5-40a9-83b2-2e1ead838ae3"
        }
      ]
    },
    {
      "id": "b2c9f12d-8a03-42f1-929f-a247a8d99d25",
      "name": "enviroFacts_FF_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "79827e69-9395-4314-9373-58a755bef66e"
        }
      ]
    },
    {
      "id": "c866c5dd-8bdc-4483-b5c5-69c20e96ffcb",
      "name": "enviroFacts_FF_SUMMARY_SOURCE",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_SUMMARY_SOURCE/ROWS/:row_start::row_end/:output"
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
          "id": "8a02f5a6-492e-49a5-b046-ff9fd4535e09"
        }
      ]
    },
    {
      "id": "86a6606a-1efa-47ba-ac5f-5d64324950a7",
      "name": "enviroFacts_FF_VENTILATION_QTRL",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_VENTILATION_QTRL/ROWS/:row_start::row_end/:output"
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
          "id": "8e087d55-f55b-4986-8d2c-b795e7b2a517"
        }
      ]
    },
    {
      "id": "dc5e7693-e2a0-4adc-8517-17268abb36ce",
      "name": "enviroFacts_FF_WELL_AND_SHAFT",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "FF_WELL_AND_SHAFT/ROWS/:row_start::row_end/:output"
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
          "id": "d82388eb-87a2-45d0-8f50-248c4cf0767a"
        }
      ]
    },
    {
      "id": "f8e86881-5cb7-478f-a4ea-daed3d7fbbf8",
      "name": "enviroFacts_F_SMELTER_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "F_SMELTER_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "d6df195b-4545-476a-9910-f739cf00c469"
        }
      ]
    },
    {
      "id": "606d3f47-514b-4415-96d4-630df71ab918",
      "name": "enviroFacts_GG_FACILITY_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "GG_FACILITY_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "0de29ebb-6936-4951-9e96-bd314db31076"
        }
      ]
    },
    {
      "id": "8524762f-021d-408c-ab6f-263ea52ec216",
      "name": "enviroFacts_GG_NOCEMS_ZIN_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "GG_NOCEMS_ZIN_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "13649c79-7d44-46fe-9cf5-cdddf513b3fc"
        }
      ]
    },
    {
      "id": "b0b2d573-1ac2-4a0b-a43f-3cc21fb5eb89",
      "name": "enviroFacts_GG_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "GG_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "9e77419d-7c03-455a-97ab-fb5008d9730c"
        }
      ]
    },
    {
      "id": "390e2b76-bba3-45a0-b866-1a7f5ec9bd86",
      "name": "enviroFacts_G_CEMS_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "G_CEMS_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "f580e6b9-07ab-4f3e-a66c-91731239dc72"
        }
      ]
    },
    {
      "id": "dfc8325a-9053-4e4e-b766-1046a604b208",
      "name": "enviroFacts_G_FEEDSTOCK_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "G_FEEDSTOCK_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "9571292f-ed03-4171-a916-f2ed457680a3"
        }
      ]
    },
    {
      "id": "67d3b9e4-021c-4f89-9315-6e2286043fcf",
      "name": "enviroFacts_G_NON_CEMS_SOURCE_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "G_NON_CEMS_SOURCE_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "48faab32-4a67-49e6-a288-fbd04e18bcd5"
        }
      ]
    },
    {
      "id": "56479d26-28f4-4e96-98cb-65c1048de35b",
      "name": "enviroFacts_HH_ACTIVE_AERATION_SYS_DETLS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_ACTIVE_AERATION_SYS_DETLS/ROWS/:row_start::row_end/:output"
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
          "id": "018d448c-2ff6-4596-aabe-718e45dedf4a"
        }
      ]
    },
    {
      "id": "972f717d-3a31-4ec6-b80b-2f21466610b7",
      "name": "enviroFacts_HH_ANN_WASTE_DISPOSAL_QTY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_ANN_WASTE_DISPOSAL_QTY/ROWS/:row_start::row_end/:output"
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
          "id": "bd01b4d8-eb25-4320-84ae-7f7ac31c7efc"
        }
      ]
    },
    {
      "id": "5687e7ba-302a-4f8c-9fdc-7248fb3a544d",
      "name": "enviroFacts_HH_COVER_TYPE_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_COVER_TYPE_DETAILS/ROWS/:row_start::row_end/:output"
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
          "id": "9776f005-a658-4493-bc19-d9ce5de9d1bd"
        }
      ]
    },
    {
      "id": "c23b835b-0e9d-43c5-85b9-30ed250f1138",
      "name": "enviroFacts_HH_GAS_COLLECTION_MNTHLY_DETLS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_GAS_COLLECTION_MNTHLY_DETLS/ROWS/:row_start::row_end/:output"
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
          "id": "4e581532-7ba6-44b8-be42-1975dbca6c3e"
        }
      ]
    },
    {
      "id": "78abff8b-a4f1-4455-ab52-91736e70cd92",
      "name": "enviroFacts_HH_GAS_COLLECTION_SYSTEM_DETLS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_GAS_COLLECTION_SYSTEM_DETLS/ROWS/:row_start::row_end/:output"
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
          "id": "a67daeff-ad2b-4070-9b7c-7e137e27ca29"
        }
      ]
    },
    {
      "id": "c27c44f0-c31e-4574-8582-b5f6c2fc30f3",
      "name": "enviroFacts_HH_HIST_WASTE_QTY_METHOD",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_HIST_WASTE_QTY_METHOD/ROWS/:row_start::row_end/:output"
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
          "id": "ef772f87-6909-471c-8202-574428af17e1"
        }
      ]
    },
    {
      "id": "30bf0ca3-2233-42d2-91e7-01ce9e5cf135",
      "name": "enviroFacts_HH_HIST_YR_WASTE_QTY",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_HIST_YR_WASTE_QTY/ROWS/:row_start::row_end/:output"
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
          "id": "14553742-994c-4dfb-9f7c-4e4aa7e1d72c"
        }
      ]
    },
    {
      "id": "120e5b23-74da-4b24-b7fc-00e7c9f31b7d",
      "name": "enviroFacts_HH_HIST_YR_WASTE_QTY_DETL",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_HIST_YR_WASTE_QTY_DETL/ROWS/:row_start::row_end/:output"
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
          "id": "4e21c085-d8c4-4596-8a17-76d70aabe163"
        }
      ]
    },
    {
      "id": "f8a96651-5bd2-4965-92f2-49bd8d699398",
      "name": "enviroFacts_HH_LANDFILL_INFO",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_LANDFILL_INFO/ROWS/:row_start::row_end/:output"
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
          "id": "5c361639-7682-454b-b63c-321873cb9ac6"
        }
      ]
    },
    {
      "id": "d3e099aa-4d3f-4b5d-9500-0196ec0e73f3",
      "name": "enviroFacts_HH_LNDFIL_WITHOUT_GAS_CLCT_EMIS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_LNDFIL_WITHOUT_GAS_CLCT_EMIS/ROWS/:row_start::row_end/:output"
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
          "id": "c7e3fb07-dc58-42c3-baef-42a31b4b6a71"
        }
      ]
    },
    {
      "id": "bd0aab9e-ecad-439b-a1cf-ec3a10120b64",
      "name": "enviroFacts_HH_LNDFIL_WITH_GAS_CLCT_WST_DEP",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_LNDFIL_WITH_GAS_CLCT_WST_DEP/ROWS/:row_start::row_end/:output"
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
          "id": "46a3714d-97be-4ec0-ad71-a932ae412e6e"
        }
      ]
    },
    {
      "id": "fa4fcd23-9c54-4545-aeda-3d16bd64b4c3",
      "name": "enviroFacts_HH_SUBPART_LEVEL_INFORMATION",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_SUBPART_LEVEL_INFORMATION/ROWS/:row_start::row_end/:output"
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
          "id": "0404fab2-4ddc-47e8-a865-3abcff5c783b"
        }
      ]
    },
    {
      "id": "40f3b53a-ccd9-4ab3-9319-3e7ba7971368",
      "name": "enviroFacts_HH_WASTE_QTY_DETAILS",
      "request": {
        "url": {
          "protocol": "http",
          "host": "iaspub.epa.gov",
          "path": [
            "enviro",
            "efservice",
            "HH_WASTE_QTY_DETAILS/ROWS/:row_start: