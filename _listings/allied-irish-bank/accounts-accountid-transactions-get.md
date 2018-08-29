---
swagger: "2.0"
info:
  title: Account and Transaction API Specification
  description: Swagger for Account and Transaction API Specification
  termsOfService: https://www.openbanking.org.uk/terms
  contact:
    name: Service Desk
    email: ServiceDesk@openbanking.org.uk
  version: 1.0.0
basePath: /open-banking/v1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{AccountId}/transactions:
    get:
      summary: Get Account Transactions
      description: Get transactions related to an account
      operationId: GetAccountTransactions
      parameters:
      - in: path
        name: AccountId
        description: A unique identifier used to identify the account resource
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: query
        name: fromBookingDateTime
        description: "The UTC ISO 8601 Date Time to filter transactions FROM \nNB
          Time component is optional - set to 00:00:00 for just Date"
      - in: query
        name: toBookingDateTime
        description: "The UTC ISO 8601 Date Time to filter transactions TO \nNB Time
          component is optional - set to 00:00:00 for just Date"
      - in: header
        name: x-fapi-customer-ip-address
        description: The PSU's IP address if the PSU is currently logged in with the
          TPP
      - in: header
        name: x-fapi-customer-last-logged-time
        description: The time when the PSU last logged in with the TPP
      - in: header
        name: x-fapi-financial-id
        description: The unique id of the ASPSP to which the request is issued
      - in: header
        name: x-fapi-interaction-id
        description: An RFC4122 UID used as a correlation id
      responses:
        200:
          description: OK
      tags:
      - banking
      - account
      - transactions
definitions: []
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