---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search Enforcement Case Map Service
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_cases query. Currently, the maximum number
    of coordinates returned is 500. GET_MAP performs automatic clustering at the state,
    county, and zip code levels to maximize the number of coordinates returned.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 1.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /case_rest_services.get_case_report:
    get:
      summary: Enforcement Case Summary Report Search
      description: The get_case_report service endpoint returns a complex object of
        civil enforcement case details based on the provided case id.
      operationId: the-get-case-report-service-endpoint-returns-a-complex-object-of-civil-enforcement-case-details-base
      x-api-path-slug: case-rest-services-get-case-report-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: p_id
        description: Case Number
      responses:
        200:
          description: OK
      tags:
      - ""
  /case_rest_services.get_cases:
    get:
      summary: Enforcement Case Search
      description: The get_cases service end point searches for civil enforcement
        and criminal cases based on the provided selection criteria.
      operationId: the-get-cases-service-end-point-searches-for-civil-enforcement-and-criminal-cases-based-on-the-provi
      x-api-path-slug: case-rest-services-get-cases-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - ""
  /case_rest_services.get_crcase_report:
    get:
      summary: Enforcement Criminal Case Summary Report Search
      description: The get_crcase_report service end point returns a complex object
        of criminal case detials based on the provided criminal case id.
      operationId: the-get-crcase-report-service-end-point-returns-a-complex-object-of-criminal-case-detials-based-on-t
      x-api-path-slug: case-rest-services-get-crcase-report-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: p_id
        description: Prosecution Summary Identifier
      responses:
        200:
          description: OK
      tags:
      - ""
  /case_rest_services.get_download:
    get:
      summary: Enforcement Case Download Data Service
      description: Based on the QID obtained from a get_cases query, return a comma
        sepated vaule (CSV) file of the cases found.
      operationId: based-on-the-qid-obtained-from-a-get-cases-query-return-a-comma-sepated-vaule-csv-file-of-the-cases-
      x-api-path-slug: case-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - ""
  /case_rest_services.get_map:
    get:
      summary: Enforcement Case Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_cases query. Currently, the maximum
        number of coordinates returned is 500. GET_MAP performs automatic clustering
        at the state, county, and zip code levels to maximize the number of coordinates
        returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: case-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
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