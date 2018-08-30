---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: 'EPA Greenhouse Gas API '
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
  /AA_FOSSIL_FUEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_FOSSIL_FUEL_INFORMATION
      x-api-path-slug: aa-fossil-fuel-informationrowsrow-startrow-endoutput-get
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
  /AA_FOSSIL_FUEL_TIER_2_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_FOSSIL_FUEL_TIER_2_INFO
      x-api-path-slug: aa-fossil-fuel-tier-2-inforowsrow-startrow-endoutput-get
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
  /AA_MAKEUP_CHEMICAL_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_MAKEUP_CHEMICAL_INFO
      x-api-path-slug: aa-makeup-chemical-inforowsrow-startrow-endoutput-get
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
  /AA_SPENT_LIQUOR_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_SPENT_LIQUOR_INFORMATION
      x-api-path-slug: aa-spent-liquor-informationrowsrow-startrow-endoutput-get
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
  /AA_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: aa-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /AA_TIER_4_CEMS_QUARTERLY_CO2/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_AA_TIER_4_CEMS_QUARTERLY_CO2
      x-api-path-slug: aa-tier-4-cems-quarterly-co2rowsrow-startrow-endoutput-get
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
  /C_BIOGENIC_CO2_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_BIOGENIC_CO2_DETAILS
      x-api-path-slug: c-biogenic-co2-detailsrowsrow-startrow-endoutput-get
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
  /C_CEMS_QUARTERLY_CO2/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_CEMS_QUARTERLY_CO2
      x-api-path-slug: c-cems-quarterly-co2rowsrow-startrow-endoutput-get
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
  /C_CONFIGURATION_LEVEL_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_CONFIGURATION_LEVEL_INFO
      x-api-path-slug: c-configuration-level-inforowsrow-startrow-endoutput-get
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
  /C_FUEL_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_FUEL_LEVEL_INFORMATION
      x-api-path-slug: c-fuel-level-informationrowsrow-startrow-endoutput-get
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
  /C_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: c-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /C_TIER2_MONTHLY_HHV/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_C_TIER2_MONTHLY_HHV
      x-api-path-slug: c-tier2-monthly-hhvrowsrow-startrow-endoutput-get
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
  /DD_FACILITY_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_FACILITY_INFO
      x-api-path-slug: dd-facility-inforowsrow-startrow-endoutput-get
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
  /DD_INCREASE_NAMEPLATE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_INCREASE_NAMEPLATE
      x-api-path-slug: dd-increase-nameplaterowsrow-startrow-endoutput-get
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
  /DD_SF6PFC_ACQUISITIONS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_SF6PFC_ACQUISITIONS
      x-api-path-slug: dd-sf6pfc-acquisitionsrowsrow-startrow-endoutput-get
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
  /DD_SF6PFC_DECREASES/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_SF6PFC_DECREASES
      x-api-path-slug: dd-sf6pfc-decreasesrowsrow-startrow-endoutput-get
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
  /DD_SF6PFC_DISBURSEMENT/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_SF6PFC_DISBURSEMENT
      x-api-path-slug: dd-sf6pfc-disbursementrowsrow-startrow-endoutput-get
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
  /DD_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: dd-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /DD_TRANSMISSION_LINE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_TRANSMISSION_LINE
      x-api-path-slug: dd-transmission-linerowsrow-startrow-endoutput-get
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
  /DD_USER_EMISSIONS_CALC/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_DD_USER_EMISSIONS_CALC
      x-api-path-slug: dd-user-emissions-calcrowsrow-startrow-endoutput-get
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
  /D_FUEL_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_D_FUEL_LEVEL_INFORMATION
      x-api-path-slug: d-fuel-level-informationrowsrow-startrow-endoutput-get
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
  /EE_CEMS_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_CEMS_DETAILS
      x-api-path-slug: ee-cems-detailsrowsrow-startrow-endoutput-get
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
  /EE_CEMS_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_CEMS_INFO
      x-api-path-slug: ee-cems-inforowsrow-startrow-endoutput-get
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
  /EE_FACILITY_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_FACILITY_INFO
      x-api-path-slug: ee-facility-inforowsrow-startrow-endoutput-get
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
  /EE_NOCEMSTIO2DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_NOCEMSTIO2DETAILS
      x-api-path-slug: ee-nocemstio2detailsrowsrow-startrow-endoutput-get
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
  /EE_NOCEMS_MONTHLYDETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_NOCEMS_MONTHLYDETAILS
      x-api-path-slug: ee-nocems-monthlydetailsrowsrow-startrow-endoutput-get
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
  /EE_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: ee-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /EE_TIER4CEMS_QTRDTLS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_EE_TIER4CEMS_QTRDTLS
      x-api-path-slug: ee-tier4cems-qtrdtlsrowsrow-startrow-endoutput-get
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
  /FF_DEGASIFICATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DEGASIFICATION
      x-api-path-slug: ff-degasificationrowsrow-startrow-endoutput-get
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
  /FF_DEGAS_QTRLY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DEGAS_QTRLY
      x-api-path-slug: ff-degas-qtrlyrowsrow-startrow-endoutput-get
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
  /FF_DEGAS_WEEKLY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DEGAS_WEEKLY
      x-api-path-slug: ff-degas-weeklyrowsrow-startrow-endoutput-get
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
  /FF_DESTROFFSITE_BACKUP/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DESTROFFSITE_BACKUP
      x-api-path-slug: ff-destroffsite-backuprowsrow-startrow-endoutput-get
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
  /FF_DESTROFFSITE_QTRLY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DESTROFFSITE_QTRLY
      x-api-path-slug: ff-destroffsite-qtrlyrowsrow-startrow-endoutput-get
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
  /FF_DESTROFFSITE_WEEKLY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_DESTROFFSITE_WEEKLY
      x-api-path-slug: ff-destroffsite-weeklyrowsrow-startrow-endoutput-get
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
  /FF_METHOD_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_METHOD_DETAILS
      x-api-path-slug: ff-method-detailsrowsrow-startrow-endoutput-get
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
  /FF_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: ff-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /FF_SUMMARY_SOURCE/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_SUMMARY_SOURCE
      x-api-path-slug: ff-summary-sourcerowsrow-startrow-endoutput-get
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
  /FF_VENTILATION_QTRL/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_VENTILATION_QTRL
      x-api-path-slug: ff-ventilation-qtrlrowsrow-startrow-endoutput-get
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
  /FF_WELL_AND_SHAFT/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_FF_WELL_AND_SHAFT
      x-api-path-slug: ff-well-and-shaftrowsrow-startrow-endoutput-get
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
  /F_SMELTER_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_F_SMELTER_DETAILS
      x-api-path-slug: f-smelter-detailsrowsrow-startrow-endoutput-get
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
  /GG_FACILITY_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_GG_FACILITY_INFO
      x-api-path-slug: gg-facility-inforowsrow-startrow-endoutput-get
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
  /GG_NOCEMS_ZIN_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_GG_NOCEMS_ZIN_DETAILS
      x-api-path-slug: gg-nocems-zin-detailsrowsrow-startrow-endoutput-get
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
  /GG_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_GG_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: gg-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /G_CEMS_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_G_CEMS_DETAILS
      x-api-path-slug: g-cems-detailsrowsrow-startrow-endoutput-get
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
  /G_FEEDSTOCK_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_G_FEEDSTOCK_DETAILS
      x-api-path-slug: g-feedstock-detailsrowsrow-startrow-endoutput-get
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
  /G_NON_CEMS_SOURCE_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_G_NON_CEMS_SOURCE_INFO
      x-api-path-slug: g-non-cems-source-inforowsrow-startrow-endoutput-get
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
  /HH_ACTIVE_AERATION_SYS_DETLS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_ACTIVE_AERATION_SYS_DETLS
      x-api-path-slug: hh-active-aeration-sys-detlsrowsrow-startrow-endoutput-get
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
  /HH_ANN_WASTE_DISPOSAL_QTY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_ANN_WASTE_DISPOSAL_QTY
      x-api-path-slug: hh-ann-waste-disposal-qtyrowsrow-startrow-endoutput-get
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
  /HH_COVER_TYPE_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_COVER_TYPE_DETAILS
      x-api-path-slug: hh-cover-type-detailsrowsrow-startrow-endoutput-get
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
  /HH_GAS_COLLECTION_MNTHLY_DETLS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_GAS_COLLECTION_MNTHLY_DETLS
      x-api-path-slug: hh-gas-collection-mnthly-detlsrowsrow-startrow-endoutput-get
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
  /HH_GAS_COLLECTION_SYSTEM_DETLS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_GAS_COLLECTION_SYSTEM_DETLS
      x-api-path-slug: hh-gas-collection-system-detlsrowsrow-startrow-endoutput-get
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
  /HH_HIST_WASTE_QTY_METHOD/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_HIST_WASTE_QTY_METHOD
      x-api-path-slug: hh-hist-waste-qty-methodrowsrow-startrow-endoutput-get
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
  /HH_HIST_YR_WASTE_QTY/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_HIST_YR_WASTE_QTY
      x-api-path-slug: hh-hist-yr-waste-qtyrowsrow-startrow-endoutput-get
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
  /HH_HIST_YR_WASTE_QTY_DETL/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_HIST_YR_WASTE_QTY_DETL
      x-api-path-slug: hh-hist-yr-waste-qty-detlrowsrow-startrow-endoutput-get
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
  /HH_LANDFILL_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_LANDFILL_INFO
      x-api-path-slug: hh-landfill-inforowsrow-startrow-endoutput-get
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
  /HH_LNDFIL_WITHOUT_GAS_CLCT_EMIS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_LNDFIL_WITHOUT_GAS_CLCT_EMIS
      x-api-path-slug: hh-lndfil-without-gas-clct-emisrowsrow-startrow-endoutput-get
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
  /HH_LNDFIL_WITH_GAS_CLCT_WST_DEP/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_LNDFIL_WITH_GAS_CLCT_WST_DEP
      x-api-path-slug: hh-lndfil-with-gas-clct-wst-deprowsrow-startrow-endoutput-get
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
  /HH_SUBPART_LEVEL_INFORMATION/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_SUBPART_LEVEL_INFORMATION
      x-api-path-slug: hh-subpart-level-informationrowsrow-startrow-endoutput-get
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
  /HH_WASTE_QTY_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_HH_WASTE_QTY_DETAILS
      x-api-path-slug: hh-waste-qty-detailsrowsrow-startrow-endoutput-get
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
  /H_CEMS_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_H_CEMS_DETAILS
      x-api-path-slug: h-cems-detailsrowsrow-startrow-endoutput-get
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
  /H_CEMS_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_H_CEMS_INFO
      x-api-path-slug: h-cems-inforowsrow-startrow-endoutput-get
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
  /H_NO_CEMS_MONTH_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_H_NO_CEMS_MONTH_DETAILS
      x-api-path-slug: h-no-cems-month-detailsrowsrow-startrow-endoutput-get
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
  /H_NO_CEMS_QRTR_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_H_NO_CEMS_QRTR_DETAILS
      x-api-path-slug: h-no-cems-qrtr-detailsrowsrow-startrow-endoutput-get
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
  /H_NO_CEMS_RAW_MATERIAL_DETAILS/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_H_NO_CEMS_RAW_MATERIAL_DETAILS
      x-api-path-slug: h-no-cems-raw-material-detailsrowsrow-startrow-endoutput-get
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
  /I-SEMICONDUCTOR_INFO/ROWS/{row_start}:{row_end}/{output}:
    get:
      summary: ""
      description: ""
      operationId: enviroFacts_I-SEMICONDUCTOR_INFO
      x-api-path-slug: isemiconductor-inforowsrow-startrow-endoutput-get
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