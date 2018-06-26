---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Create an domain entry
  description: Create an domain entry.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account:
    get:
      summary: Retrieve current account data
      description: Retrieve current account data.
      operationId: getAccount
      x-api-path-slug: account-get
      responses:
        200:
          description: OK
      tags:
      - Account
    post:
      summary: Update current account data
      description: Update current account data.
      operationId: postAccount
      x-api-path-slug: account-post
      parameters:
      - in: body
        name: value
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
  /account/domainwhitelist:
    get:
      summary: Retrieve list of a domains allowed to redirect in DDU mode
      description: Retrieve list of a domains allowed to redirect in ddu mode.
      operationId: getAccountDomainwhitelist
      x-api-path-slug: accountdomainwhitelist-get
      parameters:
      - in: query
        name: limit
        description: Limit results to this number
      - in: query
        name: offset
        description: Offset where to start from
      responses:
        200:
          description: OK
      tags:
      - Account
      - Domainwhitelist
    post:
      summary: Create an domain entry
      description: Create an domain entry.
      operationId: postAccountDomainwhitelist
      x-api-path-slug: accountdomainwhitelist-post
      parameters:
      - in: body
        name: value
        description: The entry to add
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Domainwhitelist
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