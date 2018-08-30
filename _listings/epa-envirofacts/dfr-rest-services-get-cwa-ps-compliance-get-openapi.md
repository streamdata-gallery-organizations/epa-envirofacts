---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report CWA PSV Compliance Service
  description: This procedure obtains data for the CWA Permit Schedule Violations
    section of the DFR.
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
  /dfr_rest_services.get_air_compliance:
    get:
      summary: Detailed Facility Report Air Compliance Report Service
      description: This procedure obtains data for Air Compliance in the Environmental
        Conditions Section of the DFR.
      operationId: this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-air-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_air_quality:
    get:
      summary: Detailed Facility Report Air Quality Report Service
      description: This procedure obtains data for Air Quality in the Environmental
        Conditions Section of the DFR.
      operationId: this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-air-quality-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_compliance_history:
    get:
      summary: Detailed Facility Report 5 Year Compliance Monitoring History Service
      description: This procedure obtains data for the Compliance Monitoring History
        (5 years) in the Enforcement and Compliance Section of the Detailed Facility
        report.
      operationId: this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com
      x-api-path-slug: dfr-rest-services-get-compliance-history-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_compliance_summary:
    get:
      summary: Detailed Facility Report Compliance Summary Service
      description: This procedure obtains data for Compliance Summary Data in the
        Enforcement and Compliance Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of
      x-api-path-slug: dfr-rest-services-get-compliance-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_3yr_compliance:
    get:
      summary: Detailed Facility Report 3 Year CWA Facility-Level Status Service
      description: |-
        This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:
        > "In Viol" = Facility is in violation
        > "No Viol" = No violation found
        > "Unk" = Unknown status
        > "SNC/Cat 1" = SNC/Category I violation found
      operationId: this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl
      x-api-path-slug: dfr-rest-services-get-cwa-3yr-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_cs_compliance:
    get:
      summary: Detailed Facility Report CWA CSV Compliance Service
      description: This procedure obtains data for the CWA Compliance Schedule Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-cs-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_eff_alr:
    get:
      summary: Detailed Facility Report CWA Effluent ALR Service
      description: This procedure obtains data for the CWA Pollutant Discharge section
        located in the Three Year Compliance Status by Quarter portion of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli
      x-api-path-slug: dfr-rest-services-get-cwa-eff-alr-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_eff_compliance:
    get:
      summary: Detailed Facility Report CWA Effluent Compliance Service
      description: This procedure obtains data for the CWA Effluent Compliance section
        on the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---
      x-api-path-slug: dfr-rest-services-get-cwa-eff-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_ps_compliance:
    get:
      summary: Detailed Facility Report CWA PSV Compliance Service
      description: This procedure obtains data for the CWA Permit Schedule Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-ps-compliance-get
      parameters:
      - in: query
        name: No Name
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