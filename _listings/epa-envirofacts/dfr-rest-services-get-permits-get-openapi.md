---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report Permits Service
  description: |-
    This procedure obtains data for the following sections of the Detailed Facility Report.
    > Facility Information (FRS) in the Facility Summary.
    > Regulatory Interests in the Facility Summary.
    > Also Reports in the Facility Summary.
    > Facility/System Characteristics in Facility/System Characteristics.
    > Facility Contact Information in Facility/System Characteristics.
    > Facility SIC Codes in Facility/System Characteristics section.
    > Facility NAICS Codes in Facility/System Characteristics section.
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
  /dfr_rest_services.get_cwa_rnc_compliance:
    get:
      summary: Detailed Facility Report CWA RNC Compliance Service
      description: |-
        This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.
        > S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule
        > E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)
        > X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)
        > T = SNC/Category I - compliance schedule reporting violation
        > D = SNC/Category I - reporting violation - nonreceipt of DMR
        > N = RNC/Category II - reportable non-compliance
        > P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion
        > R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action
        > C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted "m".
        > Blank = Not considered in RNC/SNC
        > N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database.
      operationId: this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s
      x-api-path-slug: dfr-rest-services-get-cwa-rnc-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_cwa_se_compliance:
    get:
      summary: Detailed Facility Report CWA SEV Compliance Service
      description: This procedure obtains data for the CWA Single Event Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-se-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_demographics:
    get:
      summary: Detailed Facility Report Demographics Report Service
      description: Returns a complex object with Demographics from the 2010 Census
        and 2010 American Community Survey based on a 3 mile radius around the facility
        spatial coordinates.
      operationId: returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b
      x-api-path-slug: dfr-rest-services-get-demographics-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_dfr:
    get:
      summary: Detailed Facility Report Service
      description: This procedure is the overall service for the Detailed Facility
        Report. It returns all of the data displayed in the DFR web report by invoking
        individual procedures that each return a targeted portion of the DFR.
      operationId: this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d
      x-api-path-slug: dfr-rest-services-get-dfr-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_enforcement_summary:
    get:
      summary: Detailed Facility Report Enforcement Summary Service
      description: This procedure obtains data for the Enforcement and Compliance
        Summary in the Facility Summary section of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti
      x-api-path-slug: dfr-rest-services-get-enforcement-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_formal_actions:
    get:
      summary: Detailed Facility Report Formal Actions Service
      description: This procedure obtains data for the Formal Enforcement Actions
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-formal-actions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_icis_formal_actions:
    get:
      summary: Detailed Facility Report ICIS Formal Actions Service
      description: This procedure obtains data for the Integrated Compliance Information
        System, Formal Enforcement Actions section of the DFR.
      operationId: this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti
      x-api-path-slug: dfr-rest-services-get-icis-formal-actions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_inspections:
    get:
      summary: Detailed Facility Report Inspections Summary Service
      description: This procedure obtains data for Enforcement and Compliance Summary
        Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-
      x-api-path-slug: dfr-rest-services-get-inspections-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_map:
    get:
      summary: Detailed Facility Report Map Service
      description: Returns an object with the facility's latitude and longitude coordinates.
      operationId: returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-
      x-api-path-slug: dfr-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_naics:
    get:
      summary: Detailed Facility Report NAICS Code Service
      description: This procedure obtains data for the Facility NAICS Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o
      x-api-path-slug: dfr-rest-services-get-naics-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_nnnPermits:
    get:
      summary: Detailed Facility Report Permits by Statute Service
      description: This procedure obtains data for the Permits by Statute section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-nnnpermits-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_notices:
    get:
      summary: Detailed Facility Report Notices Service
      description: This procedure obtains data for the Notices/Informal Actions section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-notices-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ""
  /dfr_rest_services.get_permits:
    get:
      summary: Detailed Facility Report Permits Service
      description: |-
        This procedure obtains data for the following sections of the Detailed Facility Report.
        > Facility Information (FRS) in the Facility Summary.
        > Regulatory Interests in the Facility Summary.
        > Also Reports in the Facility Summary.
        > Facility/System Characteristics in Facility/System Characteristics.
        > Facility Contact Information in Facility/System Characteristics.
        > Facility SIC Codes in Facility/System Characteristics section.
        > Facility NAICS Codes in Facility/System Characteristics section.
      operationId: this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf
      x-api-path-slug: dfr-rest-services-get-permits-get
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