---
swagger: "2.0"
info:
  title: Allied Irish Bank
  description: This is an OpenAPI definition for the standard set of Open Banking
    (http://openbankingapis.io/) APIs, covering the Allied Irish Bank APIs.
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: openapi.aibgb.co.uk
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  unsecured-sme-loans/:
    get:
      summary: Get Unsecured SME Loans
      description: This endpoint can contain multiple brands owned by a particular
        banking group
      operationId: pathOperation
      responses:
        200:
          description: OK
      tags:
      - unsecured
      - sme
      - loans
definitions:
  atms:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  branches:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  personal_current_accounts:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  business_current_accounts:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  unsecured_sme_loans:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  commercial_credit_cards:
    properties:
      meta:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
x-collection-name: Allied Irish Bank
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