{
  "info": {
    "name": "Allied Irish Bank Public APIs Get Current Business Accounts",
    "_postman_id": "ae667c96-849b-40b4-b985-d4adcd815d5e",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "6983afb7-97f4-4314-91ab-063e647983a5",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.aibgb.co.uk/open-banking/v2.1/business-current-accounts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6edcd2c8-0a91-4062-b622-0a33ee23ea14"
            }
          ]
        }
      ]
    }
  ]
}