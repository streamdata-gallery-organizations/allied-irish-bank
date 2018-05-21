---
swagger: "2.0"
x-collection-name: Allied Irish Bank
x-complete: 0
info:
  title: Allied Irish Bank Account APIs Delete an account request
  description: Delete an account request
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
  /account-requests:
    post:
      summary: Create an account request
      description: Create an account request
      operationId: CreateAccountRequest
      x-api-path-slug: accountrequests-post
      parameters:
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: body
        name: body
        description: Create an Account Request
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: x-fapi-customer-ip-address
        description: The PSUs IP address if the PSU is currently logged in with the
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
      - in: header
        name: x-jws-signature
        description: DO NOT USE
      responses:
        200:
          description: OK
      tags:
      - Banking
      - CreateAccounts
      - Requests
  /account-requests/{AccountRequestId}:
    get:
      summary: Get an account request
      description: Get an account request
      operationId: GetAccountRequest
      x-api-path-slug: accountrequestsaccountrequestid-get
      parameters:
      - in: path
        name: AccountRequestId
        description: Unique identification as assigned by the ASPSP to uniquely identify
          the account request resource
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: header
        name: x-fapi-customer-ip-address
        description: The PSUs IP address if the PSU is currently logged in with the
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
      - Banking
      - Accounts
      - Requests
    delete:
      summary: Delete an account request
      description: Delete an account request
      operationId: DeleteAccountRequest
      x-api-path-slug: accountrequestsaccountrequestid-delete
      parameters:
      - in: path
        name: AccountRequestId
        description: Unique identification as assigned by the ASPSP to uniquely identify
          the account request resource
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: header
        name: x-fapi-financial-id
        description: The unique id of the ASPSP to which the request is issued
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Accounts
      - Requests
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