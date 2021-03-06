---
name: US Digital Registry
x-slug: us-digital-registry
description: Whether for access to emergency, financial or education public services,
  users need to trust they are engaging with official U.S. government digital accounts.
  The U.S. Digital Registry serves as the authoritative resource for agencies, citizens
  and developers to confirm the official status of social media and public-facing
  collaboration accounts, mobile apps and mobile websites, and help prevent exploitation
  from unofficial sources, phishing scams or malicious entities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
x-kinRank: "9"
x-alexaRank: "0"
tags: Agencies
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/apis.md
specificationVersion: "0.14"
apis:
- name: U.S. Digital Registry Agency API - Agencies
  x-api-slug: agencies-json-get
  description: This lists all active agencies in the system. These agencies can be
    used to query for social media accounts, mobile products, and galleries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1
  tags: Federal Government   GSA, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agencies-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agencies-json-get-openapi.md
- name: U.S. Digital Registry Agency API - Agency
  x-api-slug: agenciesid-json-get
  description: This returns an agency based on an ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1
  tags: Federal Government   GSA, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agenciesid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agenciesid-json-get-openapi.md
- name: U.S. Digital Registry Agency API - Agency
  x-api-slug: agenciesid-json-get
  description: This returns an agency based on an ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1
  tags: Federal Government   GSA, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agenciesid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/agencies/master/_listings/us-digital-registry/agenciesid-json-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://tyk.api.gallery.streamdata.io
- type: x-api-stack
  url: http://u.s..digital.registry.stack.network
- type: x-website
  url: https://usdigitalregistry.digitalgov.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---