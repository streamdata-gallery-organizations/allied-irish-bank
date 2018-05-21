---
swagger: "2.0"
x-collection-name: Allied Irish Bank
x-complete: 0
info:
  title: Allied Irish Bank Payment APIs Get a single immediate payment
  description: Get a single immediate payment
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
  /payments:
    post:
      summary: Create a single immediate payment
      description: Create a single immediate payment
      operationId: CreateSingleImmediatePayment
      x-api-path-slug: payments-post
      parameters:
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: body
        name: body
        description: Setup a single immediate payment
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
        name: x-idempotency-key
        description: Every request will be processed only once per x-idempotency-key
      - in: header
        name: x-jws-signature
        description: DO NOT USE
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Payments
  /payments/{PaymentId}:
    get:
      summary: Get a single immediate payment
      description: Get a single immediate payment
      operationId: GetSingleImmediatePayment
      x-api-path-slug: paymentspaymentid-get
      parameters:
      - in: header
        name: Authorization
        description: An Authorisation Token as per https://tools
      - in: path
        name: PaymentId
        description: Unique identification as assigned by the ASPSP to uniquely identify
          the payment setup resource
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
      - Payments
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