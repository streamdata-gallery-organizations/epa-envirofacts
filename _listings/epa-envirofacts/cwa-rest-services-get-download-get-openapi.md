---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services Clean Water Act (CWA) GeoJSON Service
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
  /cwa_rest_services.get_download:
    get:
      summary: Clean Water Act (CWA) GeoJSON Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return GeoJSON of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-geojson-of-the-fac
      x-api-path-slug: cwa-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
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