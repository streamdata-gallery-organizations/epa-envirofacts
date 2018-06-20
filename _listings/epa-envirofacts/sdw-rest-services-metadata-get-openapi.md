---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act Safe Drinking Water Act (SDWA) Metadata Service
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_systems endpoint.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sdw_rest_services.get_download:
    get:
      summary: Safe Drinking Water Act (SDWA) Download Data Service
      description: Based on the QID obtained from a get_systems query, return a comma
        sepated vaule (CSV) file of the water systems found.
      operationId: based-on-the-qid-obtained-from-a-get-systems-query-return-a-comma-sepated-vaule-csv-file-of-the-wate
      x-api-path-slug: sdw-rest-services-get-download-get
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
  /sdw_rest_services.get_qid:
    get:
      summary: Safe Drinking Water Act (SDWA) Paginated Results Service
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_systems query. It then returns a Systems object containing all matching
        water systems. The main purpose of GET_QID is for large querysets that contain
        multiple pages (responsesets) of output. GET_QID allows for pagination and
        for the selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-systems-query--it-then-retur
      x-api-path-slug: sdw-rest-services-get-qid-get
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
  /sdw_rest_services.get_systems:
    get:
      summary: Safe Drinking Water Act (SDWA) Systems Search Service
      description: Returns an array of public water systems that meet the specified
        search criteria.
      operationId: returns-an-array-of-public-water-systems-that-meet-the-specified-search-criteria-
      x-api-path-slug: sdw-rest-services-get-systems-get
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
  /sdw_rest_services.metadata:
    get:
      summary: Safe Drinking Water Act (SDWA) Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_systems endpoint.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-systems-endp
      x-api-path-slug: sdw-rest-services-metadata-get
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