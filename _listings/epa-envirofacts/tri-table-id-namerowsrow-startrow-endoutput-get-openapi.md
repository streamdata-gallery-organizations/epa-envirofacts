---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: 'EPA Toxics Release Inventory API '
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
  /TRI_CHEM_ACTIVITY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_CHEM_ACTIVITY
      x-api-path-slug: tri-chem-activityrowsrow-startrow-endoutput-get
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
  /TRI_CHEM_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_CHEM_INFO
      x-api-path-slug: tri-chem-inforowsrow-startrow-endoutput-get
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
  /TRI_CODE_DESC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_CODE_DESC
      x-api-path-slug: tri-code-descrowsrow-startrow-endoutput-get
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
  /TRI_COUNTY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_COUNTY
      x-api-path-slug: tri-countyrowsrow-startrow-endoutput-get
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
  /TRI_ENERGY_RECOVERY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_ENERGY_RECOVERY
      x-api-path-slug: tri-energy-recoveryrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY
      x-api-path-slug: tri-facilityrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_DB/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_DB
      x-api-path-slug: tri-facility-dbrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_DB_HISTORY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_DB_HISTORY
      x-api-path-slug: tri-facility-db-historyrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_HISTORY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_HISTORY
      x-api-path-slug: tri-facility-historyrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_NPDES/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_NPDES
      x-api-path-slug: tri-facility-npdesrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_NPDES_HISTORY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_NPDES_HISTORY
      x-api-path-slug: tri-facility-npdes-historyrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_RCRA/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_RCRA
      x-api-path-slug: tri-facility-rcrarowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_SIC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_SIC
      x-api-path-slug: tri-facility-sicrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_SIC_HISTORY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_SIC_HISTORY
      x-api-path-slug: tri-facility-sic-historyrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_UIC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_UIC
      x-api-path-slug: tri-facility-uicrowsrow-startrow-endoutput-get
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
  /TRI_FACILITY_UIC_HISTORY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FACILITY_UIC_HISTORY
      x-api-path-slug: tri-facility-uic-historyrowsrow-startrow-endoutput-get
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
  /TRI_FORM_R_SCHEDULE_ONE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_FORM_R_SCHEDULE_ONE
      x-api-path-slug: tri-form-r-schedule-onerowsrow-startrow-endoutput-get
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
  /TRI_OFF_SITE_TRANSFER_LOCATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_OFF_SITE_TRANSFER_LOCATION
      x-api-path-slug: tri-off-site-transfer-locationrowsrow-startrow-endoutput-get
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
  /TRI_ONSITE_WASTESTREAM/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_ONSITE_WASTESTREAM
      x-api-path-slug: tri-onsite-wastestreamrowsrow-startrow-endoutput-get
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
  /TRI_ONSITE_WASTE_TREATMENT_MET/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_ONSITE_WASTE_TREATMENT_MET
      x-api-path-slug: tri-onsite-waste-treatment-metrowsrow-startrow-endoutput-get
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
  /TRI_POTW_LOCATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_POTW_LOCATION
      x-api-path-slug: tri-potw-locationrowsrow-startrow-endoutput-get
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
  /TRI_RECYCLING_PROCESS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_RECYCLING_PROCESS
      x-api-path-slug: tri-recycling-processrowsrow-startrow-endoutput-get
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
  /TRI_RELEASE_QTY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_RELEASE_QTY
      x-api-path-slug: tri-release-qtyrowsrow-startrow-endoutput-get
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
  /TRI_REPORTING_FORM/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_REPORTING_FORM
      x-api-path-slug: tri-reporting-formrowsrow-startrow-endoutput-get
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
  /TRI_SOURCE_REDUCTION_METHOD/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_SOURCE_REDUCTION_METHOD
      x-api-path-slug: tri-source-reduction-methodrowsrow-startrow-endoutput-get
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
  /TRI_SOURCE_REDUCT_QTY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_SOURCE_REDUCT_QTY
      x-api-path-slug: tri-source-reduct-qtyrowsrow-startrow-endoutput-get
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
  /TRI_SUBMISSION_NAICS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_SUBMISSION_NAICS
      x-api-path-slug: tri-submission-naicsrowsrow-startrow-endoutput-get
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
  /TRI_SUBMISSION_SIC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_SUBMISSION_SIC
      x-api-path-slug: tri-submission-sicrowsrow-startrow-endoutput-get
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
  /TRI_TABLE_ID_NAME/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_TRI_TABLE_ID_NAME
      x-api-path-slug: tri-table-id-namerowsrow-startrow-endoutput-get
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