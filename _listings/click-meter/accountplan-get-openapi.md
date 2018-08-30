---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Retrieve current account plan
  description: Retrieve current account plan.
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
  /account/domainwhitelist/{whitelistId}:
    delete:
      summary: Delete an domain entry
      description: Delete an domain entry.
      operationId: deleteAccountDomainwhitelistWhitelist
      x-api-path-slug: accountdomainwhitelistwhitelistid-delete
      parameters:
      - in: path
        name: whitelistId
        description: The id of the domain to delete
      responses:
        200:
          description: OK
      tags:
      - Account
      - Domainwhitelist
      - WhitelistId
  /account/guests:
    get:
      summary: Retrieve list of a guest
      description: Retrieve list of a guest.
      operationId: getAccountGuests
      x-api-path-slug: accountguests-get
      parameters:
      - in: query
        name: limit
        description: Limit results to this number
      - in: query
        name: offset
        description: Offset where to start from
      - in: query
        name: sortBy
        description: Field to sort by
      - in: query
        name: sortDirection
        description: Direction of sort asc or desc
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
    post:
      summary: Create a guest
      description: Create a guest.
      operationId: postAccountGuests
      x-api-path-slug: accountguests-post
      parameters:
      - in: body
        name: value
        description: Guest object to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
  /account/guests/count:
    get:
      summary: Retrieve count of guests
      description: Retrieve count of guests.
      operationId: getAccountGuestsCount
      x-api-path-slug: accountguestscount-get
      parameters:
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - Count
  /account/guests/{guestId}:
    delete:
      summary: Delete a guest
      description: Delete a guest.
      operationId: deleteAccountGuestsGuest
      x-api-path-slug: accountguestsguestid-delete
      parameters:
      - in: path
        name: guestId
        description: Id of the guest
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
    get:
      summary: Retrieve a guest
      description: Retrieve a guest.
      operationId: getAccountGuestsGuest
      x-api-path-slug: accountguestsguestid-get
      parameters:
      - in: path
        name: guestId
        description: Id of the guest
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
    post:
      summary: Update a guest
      description: Update a guest.
      operationId: postAccountGuestsGuest
      x-api-path-slug: accountguestsguestid-post
      parameters:
      - in: path
        name: guestId
        description: Id of the guest
      - in: body
        name: value
        description: Guest object with field updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
  /account/guests/{guestId}/permissions:
    get:
      summary: Retrieve permissions for a guest
      description: Retrieve permissions for a guest.
      operationId: getAccountGuestsGuestPermissions
      x-api-path-slug: accountguestsguestidpermissions-get
      parameters:
      - in: query
        name: entityId
        description: Optional id of the datapoint/group entity to filter by
      - in: query
        name: entityType
        description: Can be datapoint or group
      - in: path
        name: guestId
        description: Id of the guest
      - in: query
        name: limit
        description: Limit results to this number
      - in: query
        name: offset
        description: Offset where to start from
      - in: query
        name: type
        description: Can be w or r
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Permissions
  /account/guests/{guestId}/permissions/count:
    get:
      summary: Retrieve count of the permissions for a guest
      description: Retrieve count of the permissions for a guest.
      operationId: getAccountGuestsGuestPermissionsCount
      x-api-path-slug: accountguestsguestidpermissionscount-get
      parameters:
      - in: query
        name: entityId
        description: Optional id of the datapoint/group entity to filter by
      - in: query
        name: entityType
        description: Can be datapoint or group
      - in: path
        name: guestId
        description: Id of the guest
      - in: query
        name: type
        description: Can be w or r
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Permissions
      - Count
  /account/guests/{guestId}/{type}/permissions/patch:
    post:
      summary: Change the permission on a shared object
      description: Change the permission on a shared object.
      operationId: postAccountGuestsGuestTypePermissionsPatch
      x-api-path-slug: accountguestsguestidtypepermissionspatch-post
      parameters:
      - in: body
        name: body
        description: The patch permission request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: guestId
        description: Id of the guest
      - in: path
        name: type
        description: Can be datapoint or group
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Type
      - Permissions
      - Patch
    put:
      summary: Change the permission on a shared object
      description: Change the permission on a shared object.
      operationId: putAccountGuestsGuestTypePermissionsPatch
      x-api-path-slug: accountguestsguestidtypepermissionspatch-put
      parameters:
      - in: body
        name: body
        description: The patch permission request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: guestId
        description: Id of the guest
      - in: path
        name: type
        description: Can be datapoint or group
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Type
      - Permissions
      - Patch
  /account/ipblacklist:
    get:
      summary: Retrieve list of a ip to exclude from event tracking
      description: Retrieve list of a ip to exclude from event tracking.
      operationId: getAccountIpblacklist
      x-api-path-slug: accountipblacklist-get
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
      - Ipblacklist
    post:
      summary: Create an ip blacklist entry
      description: Create an ip blacklist entry.
      operationId: postAccountIpblacklist
      x-api-path-slug: accountipblacklist-post
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
      - Ipblacklist
  /account/ipblacklist/{blacklistId}:
    delete:
      summary: Delete an ip blacklist entry
      description: Delete an ip blacklist entry.
      operationId: deleteAccountIpblacklistBlacklist
      x-api-path-slug: accountipblacklistblacklistid-delete
      parameters:
      - in: path
        name: blacklistId
        description: The id of the ip to delete
      responses:
        200:
          description: OK
      tags:
      - Account
      - Ipblacklist
      - BlacklistId
  /account/plan:
    get:
      summary: Retrieve current account plan
      description: Retrieve current account plan.
      operationId: getAccountPlan
      x-api-path-slug: accountplan-get
      responses:
        200:
          description: OK
      tags:
      - Account
      - Plan
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