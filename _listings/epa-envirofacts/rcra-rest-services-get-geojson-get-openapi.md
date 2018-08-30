---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  Resource Conservation and Recovery Act (RCRA) GeoJSON Service
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return GeoJSON of the facilities found.
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
  /rcra_rest_services.get_download:
    get:
      summary: Resource Conservation and Recovery Act (RCRA) Download Data Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return a comma sepated vaule (CSV) file of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va
      x-api-path-slug: rcra-rest-services-get-download-get
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
  /rcra_rest_services.get_facilities:
    get:
      summary: Resource Conservation and Recovery Act (RCRA) Facility Search Service
      description: Validates query search parameters and returns query identifier.  Use
        the responseset parameter to set the page size
      operationId: validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se
      x-api-path-slug: rcra-rest-services-get-facilities-get
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
  /rcra_rest_services.get_facility_info:
    get:
      summary: Resource Conservation and Recovery Act (RCRA) Facility Enhanced Search
        Service
      description: Returns either an array of Facilities or an array of Clusters that
        meet the specified search criteria.
      operationId: returns-either-an-array-of-facilities-or-an-array-of-clusters-that-meet-the-specified-search-criteri
      x-api-path-slug: rcra-rest-services-get-facility-info-get
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
  /rcra_rest_services.get_geojson:
    get:
      summary: Resource Conservation and Recovery Act (RCRA) GeoJSON Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return GeoJSON of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-geojson-of-the-fac
      x-api-path-slug: rcra-rest-services-get-geojson-get
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