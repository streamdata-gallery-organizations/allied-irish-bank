{
  "info": {
    "name": "Allied Irish Bank Account APIs Get Account Transactions",
    "_postman_id": "7ea50fe9-9615-4fc6-8e4e-e21715de9132",
    "description": "Get transactions related to an account",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banking",
      "item": [
        {
          "id": "ff728697-2e1a-4774-a8ce-d4e0b6233f54",
          "name": "GetAccountTransactions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "open-banking",
                "v1.1",
                "accounts/:AccountId/transactions"
              ],
              "query": [
                {
                  "key": "fromBookingDateTime",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toBookingDateTime",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "An Authorisation Token as per https://tools",
                "disabled": false
              },
              {
                "key": "x-fapi-customer-ip-address",
                "value": "{}",
                "description": "The PSUs IP address if the PSU is currently logged in with the TPP",
                "disabled": false
              },
              {
                "key": "x-fapi-customer-last-logged-time",
                "value": "{}",
                "description": "The time when the PSU last logged in with the TPP",
                "disabled": false
              },
              {
                "key": "x-fapi-financial-id",
                "value": "{}",
                "description": "The unique id of the ASPSP to which the request is issued",
                "disabled": false
              },
              {
                "key": "x-fapi-interaction-id",
                "value": "{}",
                "description": "An RFC4122 UID used as a correlation id",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get transactions related to an account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98c6c146-7f06-4443-a411-d5bde5eac2cd"
            }
          ]
        }
      ]
    }
  ]
}