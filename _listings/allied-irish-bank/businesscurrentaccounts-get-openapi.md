---
swagger: "2.0"
x-collection-name: Allied Irish Bank
x-complete: 0
info:
  title: Allied Irish Bank Public APIs Get Current Business Accounts
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
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
  business-current-accounts/:
    get:
      summary: Get Current Business Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple BCA products.
      operationId: getCurentBusinessAccounts
      x-api-path-slug: businesscurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Current
      - Business
      - Accounts
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