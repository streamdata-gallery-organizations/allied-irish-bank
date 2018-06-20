---
name: Allied Irish Bank
x-slug: allied-irish-bank
description: Allied Irish Banks (AIB) is one of the so-called Big Four commercial
  banks in Ireland. AIB offers a full range of personal and corporate banking services.
  AIB Capital Markets is the division of the company that offers international banking
  and treasury operations. The bank also offers a range of general insurance products
  such as home, travel, and health insurance. It offers life assurance and pensions
  through its tied agency with Irish Life Assurance plc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
x-kinRank: "8"
x-alexaRank: "0"
tags: Allied Irish Bank
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/apis.md
specificationVersion: "0.14"
apis:
- name: Allied Irish Bank Account APIs Create an account request
  x-api-slug: allied-irish-bank-account-apis
  description: Create an account request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//account-requests
  tags: Banking,CreateAccounts, Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountrequests-post-openapi.md
- name: Allied Irish Bank Account APIs Get an account request
  x-api-slug: allied-irish-bank-account-apis
  description: Get an account request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//account-requests/{AccountRequestId}
  tags: Banking,Accounts, Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountrequestsaccountrequestid-get-openapi.md
- name: Allied Irish Bank Account APIs Delete an account request
  x-api-slug: allied-irish-bank-account-apis
  description: Delete an account request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//account-requests/{AccountRequestId}
  tags: Banking,Accounts, Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountrequestsaccountrequestid-delete-openapi.md
- name: Allied Irish Bank Account APIs Get Accounts
  x-api-slug: allied-irish-bank-account-apis
  description: Get a list of accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts
  tags: Banking,Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accounts-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account
  x-api-slug: allied-irish-bank-account-apis
  description: Get an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}
  tags: Banking,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountid-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Transactions
  x-api-slug: allied-irish-bank-account-apis
  description: Get transactions related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/transactions
  tags: Banking,Account, Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidtransactions-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Beneficiaries
  x-api-slug: allied-irish-bank-account-apis
  description: Get Beneficiaries related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/beneficiaries
  tags: Banking,Account, Beneficiaries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidbeneficiaries-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Balances
  x-api-slug: allied-irish-bank-account-apis
  description: Get Balances related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/balances
  tags: Banking,Account, Balances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidbalances-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Direct Debits
  x-api-slug: allied-irish-bank-account-apis
  description: Get Direct Debits related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/direct-debits
  tags: Banking,Account, Direct, Debits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountiddirectdebits-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Standing Orders
  x-api-slug: allied-irish-bank-account-apis
  description: Get Standing Orders related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/standing-orders
  tags: Banking,Account, Standing, Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidstandingorders-get-openapi.md
- name: Allied Irish Bank Account APIs Get Account Product
  x-api-slug: allied-irish-bank-account-apis
  description: Get Product related to an account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//accounts/{AccountId}/product
  tags: Banking,Account, Product
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/accountsaccountidproduct-get-openapi.md
- name: Allied Irish Bank Account APIs Get Standing Orders
  x-api-slug: allied-irish-bank-account-apis
  description: Get Standing Orders
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//standing-orders
  tags: Banking,Standing, Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/standingorders-get-openapi.md
- name: Allied Irish Bank Account APIs Get Direct Debits
  x-api-slug: allied-irish-bank-account-apis
  description: Get Direct Debits
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//direct-debits
  tags: Banking,Direct, Debits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/directdebits-get-openapi.md
- name: Allied Irish Bank Account APIs Get Beneficiaries
  x-api-slug: allied-irish-bank-account-apis
  description: Get Beneficiaries
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//beneficiaries
  tags: Banking,Beneficiaries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/beneficiaries-get-openapi.md
- name: Allied Irish Bank Account APIs Get Transactions
  x-api-slug: allied-irish-bank-account-apis
  description: Get Transactions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//transactions
  tags: Banking,Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/transactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/transactions-get-openapi.md
- name: Allied Irish Bank Account APIs Get Balances
  x-api-slug: allied-irish-bank-account-apis
  description: Get Balances
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//balances
  tags: Banking,Balances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/balances-get-openapi.md
- name: Allied Irish Bank Account APIs Get Products
  x-api-slug: allied-irish-bank-account-apis
  description: Get Products
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//products
  tags: Banking,Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/products-get-openapi.md
- name: Allied Irish Bank Account APIs
  x-api-slug: allied-irish-bank-account-apis
  description: Allied Irish Banks (AIB) is one of the so-called Big Four commercial
    banks in Ireland. AIB offers a full range of personal and corporate banking services.
    AIB Capital Markets is the division of the company that offers international banking
    and treasury operations. The bank also offers a range of general insurance products
    such as home, travel, and health insurance. It offers life assurance and pensions
    through its tied agency with Irish Life Assurance plc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1
  tags: Allied Irish Bank
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/openapi.md
- name: Allied Irish Bank Payment APIs Create a single immediate payment
  x-api-slug: allied-irish-bank-payment-apis
  description: Create a single immediate payment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//payments
  tags: Banking, Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/payments-post-openapi.md
- name: Allied Irish Bank Payment APIs Get a single immediate payment
  x-api-slug: allied-irish-bank-payment-apis
  description: Get a single immediate payment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//payments/{PaymentId}
  tags: Banking, Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/paymentspaymentid-get-openapi.md
- name: Allied Irish Bank Payment APIs Create a payment submission
  x-api-slug: allied-irish-bank-payment-apis
  description: Submit a previously setup payment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//payment-submissions
  tags: Banking, Payments, Submissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/paymentsubmissions-post-openapi.md
- name: Allied Irish Bank Payment APIs Get a payment submission
  x-api-slug: allied-irish-bank-payment-apis
  description: Get payment submission
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1//payment-submissions/{PaymentSubmissionId}
  tags: Banking, Payments, Submissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/paymentsubmissionspaymentsubmissionid-get-openapi.md
- name: Allied Irish Bank Payment APIs
  x-api-slug: allied-irish-bank-payment-apis
  description: Allied Irish Banks (AIB) is one of the so-called Big Four commercial
    banks in Ireland. AIB offers a full range of personal and corporate banking services.
    AIB Capital Markets is the division of the company that offers international banking
    and treasury operations. The bank also offers a range of general insurance products
    such as home, travel, and health insurance. It offers life assurance and pensions
    through its tied agency with Irish Life Assurance plc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https:////open-banking/v1.1
  tags: Allied Irish Bank
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/openapi.md
- name: Allied Irish Bank Public APIs Get Current Business Accounts
  x-api-slug: allied-irish-bank-public-apis
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https://openapi.aibgb.co.uk/open-banking/v2.1//business-current-accounts/
  tags: Current, Business, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/businesscurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/businesscurrentaccounts-get-openapi.md
- name: Allied Irish Bank Public APIs Get Unsecured SME Loans
  x-api-slug: allied-irish-bank-public-apis
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple SME Unsecured Loan products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https://openapi.aibgb.co.uk/open-banking/v2.1//unsecured-sme-loans/
  tags: Unsecured, SME, Loans
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/unsecuredsmeloans-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/unsecuredsmeloans-get-openapi.md
- name: Allied Irish Bank Public APIs
  x-api-slug: allied-irish-bank-public-apis
  description: Allied Irish Banks (AIB) is one of the so-called Big Four commercial
    banks in Ireland. AIB offers a full range of personal and corporate banking services.
    AIB Capital Markets is the division of the company that offers international banking
    and treasury operations. The bank also offers a range of general insurance products
    such as home, travel, and health insurance. It offers life assurance and pensions
    through its tied agency with Irish Life Assurance plc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/allied-irish-bank.jpeg
  humanURL: https://aibgb.co.uk/
  baseURL: https://openapi.aibgb.co.uk/open-banking/v2.1/
  tags: Allied Irish Bank
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/allied-irish-bank/master/_listings/allied-irish-bank/openapi.md
x-common:
- type: x-developer
  url: http://openbankingapis.io/Allied-Irish-Bank
- type: x-documentation
  url: https://openbanking.atlassian.net/wiki/spaces/DZ/pages/54919225/Open+Data+API+Dashboard#
- type: x-twitter
  url: https://twitter.com/AIBGB
- type: x-website
  url: https://aibgb.co.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---