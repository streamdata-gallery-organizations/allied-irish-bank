{
  "info": {
    "name": "Allied Irish Bank Account APIs Get Transactions",
    "_postman_id": "e895f2a6-ba40-4af8-97c2-086ed395183b",
    "description": "Get Transactions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banking",
      "item": [
        {
          "id": "cc453ad2-a669-4e5b-b151-1a177885b456",
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
              "id": "dcd89728-1cc0-482c-9341-20942b60a46a"
            }
          ]
        },
        {
          "id": "bae51e1f-0a40-4bd1-b49f-ac6684036ac0",
          "name": "GetTransactions",
          "request": {
            "url": "http://example.com/open-banking/v1.1/transactions?fromBookingDateTime=%7B%7D&toBookingDateTime=%7B%7D",
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
            "description": "Get Transactions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8649eac-5c09-4195-a253-19a5d5a946e5"
            }
          ]
        }
      ]
    }
  ]
}