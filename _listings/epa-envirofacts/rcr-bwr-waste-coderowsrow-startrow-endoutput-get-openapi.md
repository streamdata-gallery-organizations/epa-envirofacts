---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: 'EPA Biennial Report API '
  description: ""
  contact:
    name: EP Envirofacts
    url: http://www.epa.gov/enviro/index.html
  version: v1
host: iaspub.epa.gov
basePath: /enviro/efservice/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /BGM_OFFSITE_SHIPMENT/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_BGM_Offsite_Shipment
      x-api-path-slug: bgm-offsite-shipmentrowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /BGM_ONSITE_TREATMENT/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_BGM_Onsite_Shipment
      x-api-path-slug: bgm-onsite-treatmentrowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /BGM_WASTE_CODE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_BGM_WASTE_CODE
      x-api-path-slug: bgm-waste-coderowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /BREPORT_CYCLE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_BREPORT_CYCLE
      x-api-path-slug: breport-cyclerowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /BWR_BASIC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_BWR_BASIC
      x-api-path-slug: bwr-basicrowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /RCR_BGM_BASIC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RCR_BGM_BASIC
      x-api-path-slug: rcr-bgm-basicrowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
  /RCR_BWR_WASTE_CODE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RCR_BWR_WASTE_CODE
      x-api-path-slug: rcr-bwr-waste-coderowsrow-startrow-endoutput-get
      parameters:
      - in: path
        name: output
        description: which format to output (JSON,XML,CSV,Excel)
      - in: path
        name: row_end
        description: which row to end on
      - in: path
        name: row_start
        description: which row to start on
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---