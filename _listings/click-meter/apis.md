---
name: Click Meter
x-slug: click-meter
description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
  agency. The ClickMeter System was initially a web tool created to address the needs
  of our agency to precisely count and track the web-marketing actions we performed
  for our customers.The system evolved rapidly, and emerged as one of the most widely
  used software solutions in our agency to collect, analyze, and share data for and
  with our customers. After few years after the development of the first ClickMeter
  system, we decided to go live with a service that can be useful to everyone involved
  in web-marketing activities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Click Meter
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/apis.md
specificationVersion: "0.14"
apis:
- name: Click Meter Retrieve current account data
  x-api-slug: click-meter
  description: Retrieve current account data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/account-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/account-get-openapi.md
- name: Click Meter Update current account data
  x-api-slug: click-meter
  description: Update current account data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/account-post-openapi.md
- name: Click Meter Retrieve list of a domains allowed to redirect in DDU mode
  x-api-slug: click-meter
  description: Retrieve list of a domains allowed to redirect in ddu mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist
  tags: Account,Domainwhitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountdomainwhitelist-get-openapi.md
- name: Click Meter Create an domain entry
  x-api-slug: click-meter
  description: Create an domain entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist
  tags: Account,Domainwhitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountdomainwhitelist-post-openapi.md
- name: Click Meter Delete an domain entry
  x-api-slug: click-meter
  description: Delete an domain entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist/{whitelistId}
  tags: Account,Domainwhitelist,WhitelistId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountdomainwhitelistwhitelistid-delete-openapi.md
- name: Click Meter Retrieve list of a guest
  x-api-slug: click-meter
  description: Retrieve list of a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests
  tags: Account,Guests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguests-get-openapi.md
- name: Click Meter Create a guest
  x-api-slug: click-meter
  description: Create a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests
  tags: Account,Guests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguests-post-openapi.md
- name: Click Meter Retrieve count of guests
  x-api-slug: click-meter
  description: Retrieve count of guests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/count
  tags: Account,Guests,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestscount-get-openapi.md
- name: Click Meter Delete a guest
  x-api-slug: click-meter
  description: Delete a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestid-delete-openapi.md
- name: Click Meter Retrieve a guest
  x-api-slug: click-meter
  description: Retrieve a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestid-get-openapi.md
- name: Click Meter Update a guest
  x-api-slug: click-meter
  description: Update a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestid-post-openapi.md
- name: Click Meter Retrieve permissions for a guest
  x-api-slug: click-meter
  description: Retrieve permissions for a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/permissions
  tags: Account,Guests,GuestId,Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestidpermissions-get-openapi.md
- name: Click Meter Retrieve count of the permissions for a guest
  x-api-slug: click-meter
  description: Retrieve count of the permissions for a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/permissions/count
  tags: Account,Guests,GuestId,Permissions,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestidpermissionscount-get-openapi.md
- name: Click Meter Change the permission on a shared object
  x-api-slug: click-meter
  description: Change the permission on a shared object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/{type}/permissions/patch
  tags: Account,Guests,GuestId,Type,Permissions,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestidtypepermissionspatch-post-openapi.md
- name: Click Meter Change the permission on a shared object
  x-api-slug: click-meter
  description: Change the permission on a shared object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/{type}/permissions/patch
  tags: Account,Guests,GuestId,Type,Permissions,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountguestsguestidtypepermissionspatch-put-openapi.md
- name: Click Meter Retrieve list of a ip to exclude from event tracking
  x-api-slug: click-meter
  description: Retrieve list of a ip to exclude from event tracking.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist
  tags: Account,Ipblacklist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountipblacklist-get-openapi.md
- name: Click Meter Create an ip blacklist entry
  x-api-slug: click-meter
  description: Create an ip blacklist entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist
  tags: Account,Ipblacklist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountipblacklist-post-openapi.md
- name: Click Meter Delete an ip blacklist entry
  x-api-slug: click-meter
  description: Delete an ip blacklist entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist/{blacklistId}
  tags: Account,Ipblacklist,BlacklistId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountipblacklistblacklistid-delete-openapi.md
- name: Click Meter Retrieve current account plan
  x-api-slug: click-meter
  description: Retrieve current account plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/plan
  tags: Account,Plan
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/accountplan-get-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated
  tags: Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregated-get-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe grouped
    by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe grouped by
    some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated/list
  tags: Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedlist-get-openapi.md
- name: Click Meter Retrieve statistics about a subset of conversions for a timeframe
    with conversions data
  x-api-slug: click-meter
  description: Retrieve statistics about a subset of conversions for a timeframe with
    conversions data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated/summary/conversions
  tags: Aggregated,Summary,Conversions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummaryconversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummaryconversions-get-openapi.md
- name: Click Meter Retrieve statistics about a subset of datapoints for a timeframe
    with datapoints data
  x-api-slug: click-meter
  description: Retrieve statistics about a subset of datapoints for a timeframe with
    datapoints data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated/summary/datapoints
  tags: Aggregated,Summary,Datapoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummarydatapoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummarydatapoints-get-openapi.md
- name: Click Meter Retrieve statistics about a subset of groups for a timeframe with
    groups data
  x-api-slug: click-meter
  description: Retrieve statistics about a subset of groups for a timeframe with groups
    data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated/summary/groups
  tags: Aggregated,Summary,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummarygroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/aggregatedsummarygroups-get-openapi.md
- name: Click Meter Retrieve the latest list of events of this account. Limited to
    last 100.
  x-api-slug: click-meter
  description: Retrieve the latest list of events of this account. limited to last
    100..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////clickstream
  tags: Clickstream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/clickstream-get-openapi.md
- name: Click Meter Retrieve a list of conversions
  x-api-slug: click-meter
  description: Retrieve a list of conversions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions
  tags: Conversions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversions-get-openapi.md
- name: Click Meter Create a conversion
  x-api-slug: click-meter
  description: Create a conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions
  tags: Conversions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversions-post-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe related
    to a subset of conversions grouped by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe related to
    a subset of conversions grouped by some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/aggregated/list
  tags: Conversions,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsaggregatedlist-get-openapi.md
- name: Click Meter Retrieve a count of conversions
  x-api-slug: click-meter
  description: Retrieve a count of conversions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/count
  tags: Conversions,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionscount-get-openapi.md
- name: Click Meter Delete conversion specified by id
  x-api-slug: click-meter
  description: Delete conversion specified by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}
  tags: Conversions,ConversionId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionid-delete-openapi.md
- name: Click Meter Retrieve conversion specified by id
  x-api-slug: click-meter
  description: Retrieve conversion specified by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}
  tags: Conversions,ConversionId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionid-get-openapi.md
- name: Click Meter Update conversion specified by id
  x-api-slug: click-meter
  description: Update conversion specified by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}
  tags: Conversions,ConversionId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionid-post-openapi.md
- name: Click Meter Retrieve statistics about this conversion for a timeframe
  x-api-slug: click-meter
  description: Retrieve statistics about this conversion for a timeframe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/aggregated
  tags: Conversions,ConversionId,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionidaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about this conversion for a timeframe grouped
    by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this conversion for a timeframe grouped by
    some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/aggregated/list
  tags: Conversions,ConversionId,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionidaggregatedlist-get-openapi.md
- name: Click Meter Retrieve a list of datapoints connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a list of datapoints connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints
  tags: Conversions,ConversionId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversioniddatapoints-get-openapi.md
- name: Click Meter Modify the association between a conversion and multiple datapoints
  x-api-slug: click-meter
  description: Modify the association between a conversion and multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/batch/patch
  tags: Conversions,ConversionId,Datapoints,Batch,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversioniddatapointsbatchpatch-put-openapi.md
- name: Click Meter Retrieve a count of datapoints connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a count of datapoints connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/count
  tags: Conversions,ConversionId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversioniddatapointscount-get-openapi.md
- name: Click Meter Modify the association between a conversion and a datapoint
  x-api-slug: click-meter
  description: Modify the association between a conversion and a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/patch
  tags: Conversions,ConversionId,Datapoints,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversioniddatapointspatch-put-openapi.md
- name: Click Meter Retrieve the list of events related to this conversion.
  x-api-slug: click-meter
  description: Retrieve the list of events related to this conversion..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/hits
  tags: Conversions,ConversionId,Hits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionidhits-get-openapi.md
- name: Click Meter Fast patch the "notes" field of a conversion
  x-api-slug: click-meter
  description: Fast patch the "notes" field of a conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/notes
  tags: Conversions,ConversionId,Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionidnotes-put-openapi.md
- name: Click Meter Retrieve a top report connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a top report connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/reports
  tags: Conversions,ConversionId,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/conversionsconversionidreports-get-openapi.md
- name: Click Meter List of all the datapoints associated to the user
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints
  tags: Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapoints-get-openapi.md
- name: Click Meter Create a datapoint
  x-api-slug: click-meter
  description: Create a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints
  tags: Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapoints-post-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe by groups
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe by groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/aggregated
  tags: Datapoints,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about all datapoints of this customer for
    a timeframe grouped by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about all datapoints of this customer for a timeframe
    grouped by some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/aggregated/list
  tags: Datapoints,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsaggregatedlist-get-openapi.md
- name: Click Meter Delete multiple datapoints
  x-api-slug: click-meter
  description: Delete multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsbatch-delete-openapi.md
- name: Click Meter Update multiple datapoints
  x-api-slug: click-meter
  description: Update multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsbatch-post-openapi.md
- name: Click Meter Create multiple datapoints
  x-api-slug: click-meter
  description: Create multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsbatch-put-openapi.md
- name: Click Meter Count the datapoints associated to the user
  x-api-slug: click-meter
  description: Count the datapoints associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/count
  tags: Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointscount-get-openapi.md
- name: Click Meter Delete a datapoint
  x-api-slug: click-meter
  description: Delete a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsid-delete-openapi.md
- name: Click Meter Get a datapoint
  x-api-slug: click-meter
  description: Get a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsid-get-openapi.md
- name: Click Meter Update a datapoint
  x-api-slug: click-meter
  description: Update a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsid-post-openapi.md
- name: Click Meter Retrieve statistics about this datapoint for a timeframe
  x-api-slug: click-meter
  description: Retrieve statistics about this datapoint for a timeframe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/aggregated
  tags: Datapoints,Id,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about this datapoint for a timeframe grouped
    by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this datapoint for a timeframe grouped by
    some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/aggregated/list
  tags: Datapoints,Id,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidaggregatedlist-get-openapi.md
- name: Click Meter Fast switch the "favourite" field of a datapoint
  x-api-slug: click-meter
  description: Fast switch the "favourite" field of a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/favourite
  tags: Datapoints,Id,Favourite
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidfavourite-put-openapi.md
- name: Click Meter Retrieve the list of events related to this datapoint.
  x-api-slug: click-meter
  description: Retrieve the list of events related to this datapoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/hits
  tags: Datapoints,Id,Hits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidhits-get-openapi.md
- name: Click Meter Fast patch the "notes" field of a datapoint
  x-api-slug: click-meter
  description: Fast patch the "notes" field of a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/notes
  tags: Datapoints,Id,Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidnotes-put-openapi.md
- name: Click Meter Retrieve a top report connected to this datapoint
  x-api-slug: click-meter
  description: Retrieve a top report connected to this datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/reports
  tags: Datapoints,Id,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/datapointsidreports-get-openapi.md
- name: Click Meter Retrieve a list of domains
  x-api-slug: click-meter
  description: Retrieve a list of domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domains-get-openapi.md
- name: Click Meter Create a domain
  x-api-slug: click-meter
  description: Create a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domains-post-openapi.md
- name: Click Meter Retrieve count of domains
  x-api-slug: click-meter
  description: Retrieve count of domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains/count
  tags: Domains,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domainscount-get-openapi.md
- name: Click Meter Delete a domain
  x-api-slug: click-meter
  description: Delete a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains/{id}
  tags: Domains,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domainsid-delete-openapi.md
- name: Click Meter Get a domain
  x-api-slug: click-meter
  description: Get a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains/{id}
  tags: Domains,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domainsid-get-openapi.md
- name: Click Meter Update a domain
  x-api-slug: click-meter
  description: Update a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains/{id}
  tags: Domains,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/domainsid-post-openapi.md
- name: Click Meter List of all the groups associated to the user.
  x-api-slug: click-meter
  description: List of all the groups associated to the user..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groups-get-openapi.md
- name: Click Meter Create a group
  x-api-slug: click-meter
  description: Create a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groups-post-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe by groups
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe by groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/aggregated
  tags: Groups,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about all groups of this customer for a timeframe
    grouped by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about all groups of this customer for a timeframe
    grouped by some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/aggregated/list
  tags: Groups,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsaggregatedlist-get-openapi.md
- name: Click Meter Count the groups associated to the user.
  x-api-slug: click-meter
  description: Count the groups associated to the user..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/count
  tags: Groups,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupscount-get-openapi.md
- name: Click Meter Delete group specified by id
  x-api-slug: click-meter
  description: Delete group specified by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}
  tags: Groups,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsid-delete-openapi.md
- name: Click Meter Get a group
  x-api-slug: click-meter
  description: Get a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}
  tags: Groups,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsid-get-openapi.md
- name: Click Meter Update a group
  x-api-slug: click-meter
  description: Update a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}
  tags: Groups,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsid-post-openapi.md
- name: Click Meter Retrieve statistics about this group for a timeframe
  x-api-slug: click-meter
  description: Retrieve statistics about this group for a timeframe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/aggregated
  tags: Groups,Id,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about this group for a timeframe grouped by
    some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this group for a timeframe grouped by some
    temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/aggregated/list
  tags: Groups,Id,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidaggregatedlist-get-openapi.md
- name: Click Meter Retrieve statistics about a subset of datapoints for a timeframe
    with datapoints data
  x-api-slug: click-meter
  description: Retrieve statistics about a subset of datapoints for a timeframe with
    datapoints data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/aggregated/summary
  tags: Groups,Id,Aggregated,Summary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidaggregatedsummary-get-openapi.md
- name: Click Meter List of all the datapoints associated to the user in this group.
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user in this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints
  tags: Groups,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsiddatapoints-get-openapi.md
- name: Click Meter Create a datapoint in this group
  x-api-slug: click-meter
  description: Create a datapoint in this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints
  tags: Groups,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsiddatapoints-post-openapi.md
- name: Click Meter Count the datapoints associated to the user in this group.
  x-api-slug: click-meter
  description: Count the datapoints associated to the user in this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints/count
  tags: Groups,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsiddatapointscount-get-openapi.md
- name: Click Meter Fast switch the "favourite" field of a group
  x-api-slug: click-meter
  description: Fast switch the "favourite" field of a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/favourite
  tags: Groups,Id,Favourite
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidfavourite-put-openapi.md
- name: Click Meter Retrieve the list of events related to this group.
  x-api-slug: click-meter
  description: Retrieve the list of events related to this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/hits
  tags: Groups,Id,Hits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidhits-get-openapi.md
- name: Click Meter Fast patch the "notes" field of a group
  x-api-slug: click-meter
  description: Fast patch the "notes" field of a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/notes
  tags: Groups,Id,Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidnotes-put-openapi.md
- name: Click Meter Retrieve a top report connected to this group
  x-api-slug: click-meter
  description: Retrieve a top report connected to this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/reports
  tags: Groups,Id,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/groupsidreports-get-openapi.md
- name: Click Meter Retrieve the list of events related to this account.
  x-api-slug: click-meter
  description: Retrieve the list of events related to this account..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////hits
  tags: Hits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/hits-get-openapi.md
- name: Click Meter Retrieve current account data
  x-api-slug: click-meter
  description: Retrieve current account data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////me
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/me-get-openapi.md
- name: Click Meter Retrieve current account plan
  x-api-slug: click-meter
  description: Retrieve current account plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////me/plan
  tags: Me,Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/meplan-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/meplan-get-openapi.md
- name: Click Meter Retrieve a top report
  x-api-slug: click-meter
  description: Retrieve a top report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////reports
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/reports-get-openapi.md
- name: Click Meter List of all the retargeting scripts associated to the user
  x-api-slug: click-meter
  description: List of all the retargeting scripts associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting
  tags: Retargeting
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargeting-get-openapi.md
- name: Click Meter Creates a retargeting script
  x-api-slug: click-meter
  description: Creates a retargeting script.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting
  tags: Retargeting
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargeting-post-openapi.md
- name: Click Meter Retrieve count of retargeting scripts
  x-api-slug: click-meter
  description: Retrieve count of retargeting scripts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/count
  tags: Retargeting,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingcount-get-openapi.md
- name: Click Meter Deletes a retargeting script (and remove associations)
  x-api-slug: click-meter
  description: Deletes a retargeting script (and remove associations).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}
  tags: Retargeting,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingid-delete-openapi.md
- name: Click Meter Get a retargeting script object
  x-api-slug: click-meter
  description: Get a retargeting script object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}
  tags: Retargeting,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingid-get-openapi.md
- name: Click Meter Updates a retargeting script
  x-api-slug: click-meter
  description: Updates a retargeting script.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}
  tags: Retargeting,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingid-post-openapi.md
- name: Click Meter List of all the datapoints associated to the retargeting script.
  x-api-slug: click-meter
  description: List of all the datapoints associated to the retargeting script..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}/datapoints
  tags: Retargeting,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingiddatapoints-get-openapi.md
- name: Click Meter Count the datapoints associated to the retargeting script.
  x-api-slug: click-meter
  description: Count the datapoints associated to the retargeting script..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}/datapoints/count
  tags: Retargeting,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/retargetingiddatapointscount-get-openapi.md
- name: Click Meter List of all the groups associated to the user filtered by this
    tag.
  x-api-slug: click-meter
  description: List of all the groups associated to the user filtered by this tag..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tags-get-openapi.md
- name: Click Meter Create a tag
  x-api-slug: click-meter
  description: Create a tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tags-post-openapi.md
- name: Click Meter List of all the groups associated to the user filtered by this
    tag.
  x-api-slug: click-meter
  description: List of all the groups associated to the user filtered by this tag..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/count
  tags: Tags,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagscount-get-openapi.md
- name: Click Meter Delete a tag
  x-api-slug: click-meter
  description: Delete a tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}
  tags: Tags,TagId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagid-delete-openapi.md
- name: Click Meter Retrieve a tag
  x-api-slug: click-meter
  description: Retrieve a tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}
  tags: Tags,TagId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagid-get-openapi.md
- name: Click Meter Delete the association of this tag with all datapoints
  x-api-slug: click-meter
  description: Delete the association of this tag with all datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints
  tags: Tags,TagId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagiddatapoints-delete-openapi.md
- name: Click Meter List of all the datapoints associated to the user filtered by
    this tag
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user filtered by this
    tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints
  tags: Tags,TagId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagiddatapoints-get-openapi.md
- name: Click Meter Count the datapoints associated to the user filtered by this tag
  x-api-slug: click-meter
  description: Count the datapoints associated to the user filtered by this tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints/count
  tags: Tags,TagId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagiddatapointscount-get-openapi.md
- name: Click Meter Associate/Deassociate a tag with a datapoint
  x-api-slug: click-meter
  description: Associate/deassociate a tag with a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints/patch
  tags: Tags,TagId,Datapoints,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagiddatapointspatch-put-openapi.md
- name: Click Meter Delete the association of this tag with all groups
  x-api-slug: click-meter
  description: Delete the association of this tag with all groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/groups
  tags: Tags,TagId,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagidgroups-delete-openapi.md
- name: Click Meter List of all the groups associated to the user filtered by this
    tag.
  x-api-slug: click-meter
  description: List of all the groups associated to the user filtered by this tag..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/groups
  tags: Tags,TagId,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagidgroups-get-openapi.md
- name: Click Meter Count the groups associated to the user filtered by this tag
  x-api-slug: click-meter
  description: Count the groups associated to the user filtered by this tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/groups/count
  tags: Tags,TagId,Groups,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagidgroupscount-get-openapi.md
- name: Click Meter Associate/Deassociate a tag with a group
  x-api-slug: click-meter
  description: Associate/deassociate a tag with a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/groups/patch
  tags: Tags,TagId,Groups,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagidgroupspatch-put-openapi.md
- name: Click Meter Fast patch a tag name
  x-api-slug: click-meter
  description: Fast patch a tag name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/name
  tags: Tags,TagId,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/tagstagidname-put-openapi.md
- name: Click Meter
  x-api-slug: click-meter
  description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
    agency. The ClickMeter System was initially a web tool created to address the
    needs of our agency to precisely count and track the web-marketing actions we
    performed for our customers.The system evolved rapidly, and emerged as one of
    the most widely used software solutions in our agency to collect, analyze, and
    share data for and with our customers. After few years after the development of
    the first ClickMeter system, we decided to go live with a service that can be
    useful to everyone involved in web-marketing activities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80//
  tags: Click Meter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/click-meter/master/_listings/click-meter/openapi.md
x-common:
- type: x-blog
  url: https://blog.clickmeter.com/
- type: x-pricing
  url: http://clickmeter.com/pricing-signup
- type: x-support
  url: https://support.clickmeter.com/hc/en-us
- type: x-terms-of-service
  url: http://clickmeter.com/terms-conditions
- type: x-twitter
  url: https://twitter.com/clickmeter
- type: x-website
  url: http://clickmeter.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---