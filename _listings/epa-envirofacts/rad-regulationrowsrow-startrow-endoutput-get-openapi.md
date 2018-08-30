---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: 'EPA Radiation Information Database API '
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
  /RAD_FACILITY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RAD_FACILITY
      x-api-path-slug: rad-facilityrowsrow-startrow-endoutput-get
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
  /RAD_FACILITY_TYPE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RAD_FACILITY_TYPE
      x-api-path-slug: rad-facility-typerowsrow-startrow-endoutput-get
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
  /RAD_GEO_LOCATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RAD_GEO_LOCATION
      x-api-path-slug: rad-geo-locationrowsrow-startrow-endoutput-get
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
  /RAD_REGULATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_RAD_REGULATION
      x-api-path-slug: rad-regulationrowsrow-startrow-endoutput-get
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