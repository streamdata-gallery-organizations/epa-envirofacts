---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services ECHO NAICS Codes Lookup Service
  description: ""
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
  /cwa_rest_services.get_facilities:
    get:
      summary: Clean Water Act (CWA) Facility Search Service
      description: Validates query search parameters and returns query identifier.  Use
        the responseset parameter to set the page size
      operationId: validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se
      x-api-path-slug: cwa-rest-services-get-facilities-get
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
  /cwa_rest_services.get_facility_info:
    get:
      summary: Clean Water Act (CWA) Facility Enhanced Search Service
      description: Returns either an array of Facilities or an array of Clusters that
        meet the specified search criteria.
      operationId: returns-either-an-array-of-facilities-or-an-array-of-clusters-that-meet-the-specified-search-criteri
      x-api-path-slug: cwa-rest-services-get-facility-info-get
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
  /cwa_rest_services.get_geojson:
    get:
      summary: Clean Water Act (CWA) Download Data Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return a comma sepated vaule (CSV) file of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va
      x-api-path-slug: cwa-rest-services-get-geojson-get
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
  /cwa_rest_services.get_info_clusters:
    get:
      summary: Clean Water Act (CWA) Info Clusters Service
      description: Based on the QID obtained from a clustered get_facility_info query,
        download cluster facility information as either a CSV or GEOJSON file.
      operationId: based-on-the-qid-obtained-from-a-clustered-get-facility-info-query-download-cluster-facility-informa
      x-api-path-slug: cwa-rest-services-get-info-clusters-get
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
  /cwa_rest_services.get_map:
    get:
      summary: Clean Water Act (CWA) Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: cwa-rest-services-get-map-get
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
  /cwa_rest_services.get_qid:
    get:
      summary: Clean Water Act (CWA) Paginated Results Service
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_facilities query. It then returns a Facility object containing all
        matching facilities. The main purpose of GET_QID is for large querysets that
        contain multiple pages (responsesets) of output. GET_QID allows for pagination
        and for the selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-facilities-query--it-then-re
      x-api-path-slug: cwa-rest-services-get-qid-get
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
  /cwa_rest_services.metadata:
    get:
      summary: Clean Water Act (CWA) Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_qid, get_facility_info and other service endpoints.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-qid-get-faci
      x-api-path-slug: cwa-rest-services-metadata-get
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
  /rest_lookups.bp_tribes:
    get:
      summary: ECHO BP Tribes Lookup Service
      description: Returns the EPA Standard Indian Tribes and Native Alaskan Villages
        tribal_id and tribe_name.
      operationId: returns-the-epa-standard-indian-tribes-and-native-alaskan-villages-tribal-id-and-tribe-name-
      x-api-path-slug: rest-lookups-bp-tribes-get
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
  /rest_lookups.cwa_parameters:
    get:
      summary: ECHO CWA Parameter Lookup Service
      description: Look up Clean Water Act parameter codes and descriptions in the
        Integrated Compliance Information System - National Pollutant Discharge Elimination
        System (ICIS-NPDES) by code or term.
      operationId: look-up-clean-water-act-parameter-codes-and-descriptions-in-the-integrated-compliance-information-sy
      x-api-path-slug: rest-lookups-cwa-parameters-get
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
  /rest_lookups.cwa_pollutants:
    get:
      summary: ECHO CWA Pollutants Lookup Service
      description: ""
      operationId: ""
      x-api-path-slug: rest-lookups-cwa-pollutants-get
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
  /rest_lookups.federal_agencies:
    get:
      summary: ECHO Federal Agency Lookup Service
      description: Look up Federal Agency Code
      operationId: look-up-federal-agency-code
      x-api-path-slug: rest-lookups-federal-agencies-get
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
  /rest_lookups.icis_inspection_types:
    get:
      summary: ECHO ICIS NPDES Inspection Types Lookup Service
      description: Returns the ICIS NPDES Compliance Monitoring Type Code and Description.
      operationId: returns-the-icis-npdes-compliance-monitoring-type-code-and-description-
      x-api-path-slug: rest-lookups-icis-inspection-types-get
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
  /rest_lookups.icis_law_sections:
    get:
      summary: ECHO ICIS Law Sections Lookup Service
      description: Returns the ICIS Law Section Descriptions.
      operationId: returns-the-icis-law-section-descriptions-
      x-api-path-slug: rest-lookups-icis-law-sections-get
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
  /rest_lookups.naics_codes:
    get:
      summary: ECHO NAICS Codes Lookup Service
      description: ""
      operationId: ""
      x-api-path-slug: rest-lookups-naics-codes-get
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