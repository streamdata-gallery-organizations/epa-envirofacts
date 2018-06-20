---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: 'EPA Facility Registry System API '
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
  /AA_CEMS_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_CEMS_DETAILS
      x-api-path-slug: aa-cems-detailsrowsrow-startrow-endoutput-get
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
  /FRS_AFFILIATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_AFFILIATION
      x-api-path-slug: frs-affiliationrowsrow-startrow-endoutput-get
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
  /FRS_AGENCY_REF/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_AGENCY_REF
      x-api-path-slug: frs-agency-refrowsrow-startrow-endoutput-get
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
  /FRS_ALTERNATIVE_ID/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_ALTERNATIVE_ID
      x-api-path-slug: frs-alternative-idrowsrow-startrow-endoutput-get
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
  /FRS_ALT_NAME/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_ALT_NAME
      x-api-path-slug: frs-alt-namerowsrow-startrow-endoutput-get
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
  /FRS_CODE_DESCRIPTION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_CODE_DESCRIPTION
      x-api-path-slug: frs-code-descriptionrowsrow-startrow-endoutput-get
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
  /FRS_CONTACT/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_CONTACT
      x-api-path-slug: frs-contactrowsrow-startrow-endoutput-get
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
  /FRS_FACILITY_SITE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_FACILITY_SITE
      x-api-path-slug: frs-facility-siterowsrow-startrow-endoutput-get
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
  /FRS_INTEREST/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_INTEREST
      x-api-path-slug: frs-interestrowsrow-startrow-endoutput-get
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
  /FRS_INTEREST_REF/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_INTEREST_REF
      x-api-path-slug: frs-interest-refrowsrow-startrow-endoutput-get
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
  /FRS_MAILING_ADDRESS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_MAILING_ADDRESS
      x-api-path-slug: frs-mailing-addressrowsrow-startrow-endoutput-get
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
  /FRS_NAICS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_NAICS
      x-api-path-slug: frs-naicsrowsrow-startrow-endoutput-get
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
  /FRS_ORGANIZATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FRS_ORGANIZATION
      x-api-path-slug: frs-organizationrowsrow-startrow-endoutput-get
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