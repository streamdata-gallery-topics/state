---
name: Healthcare.gov
x-slug: healthcaregov
description: HealthCare.gov is a health insurance exchange website operated under
  the United States federal government under the provisions of the Patient Protection
  and Affordable Care Act (ACA, often known as Obamacare), designed to serve the residents
  of the thirty-six U.S. states that opted not to create their own state exchanges.
  The exchange facilitates the sale of private health insurance plans to residents
  of the United States[2] and offers subsidies to those who earn less than four times
  the federal poverty line. The website also assists those persons who are eligible
  to sign up for Medicaid, and has a separate marketplace for small businesses.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Healthcare.gov_logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: State
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/apis.md
specificationVersion: "0.14"
apis:
- name: Healthcare.gov Get API States Media Type Extension
  x-api-slug: healthcaregov
  description: Returns pages content.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Healthcare.gov_logo.png
  humanURL: http://www.healthcare.gov
  baseURL: https://www.healthcare.gov////api/states{mediaTypeExtension}
  tags: Insurance,States, Media, Type, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/apistatesmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/apistatesmediatypeextension-get-openapi.md
- name: Healthcare.gov Get State Name Media Type Extension
  x-api-slug: healthcaregov
  description: Returns pages content.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Healthcare.gov_logo.png
  humanURL: http://www.healthcare.gov
  baseURL: https://www.healthcare.gov////es/{stateName}{mediaTypeExtension}/
  tags: Insurance,State, Name, Media, Type, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/esstatenamemediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/esstatenamemediatypeextension-get-openapi.md
- name: Healthcare.gov Get State Name Media Type Extension
  x-api-slug: healthcaregov
  description: Returns pages content.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Healthcare.gov_logo.png
  humanURL: http://www.healthcare.gov
  baseURL: https://www.healthcare.gov////{stateName}{mediaTypeExtension}/
  tags: Insurance,State, Name, Media, Type, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/statenamemediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/statenamemediatypeextension-get-openapi.md
- name: Healthcare.gov
  x-api-slug: healthcaregov
  description: HealthCare.gov is a health insurance exchange website operated under
    the United States federal government under the provisions of the Patient Protection
    and Affordable Care Act (ACA, often known as Obamacare), designed to serve the
    residents of the thirty-six U.S. states that opted not to create their own state
    exchanges. The exchange facilitates the sale of private health insurance plans
    to residents of the United States[2] and offers subsidies to those who earn less
    than four times the federal poverty line. The website also assists those persons
    who are eligible to sign up for Medicaid, and has a separate marketplace for small
    businesses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Healthcare.gov_logo.png
  humanURL: http://www.healthcare.gov
  baseURL: https://www.healthcare.gov//
  tags: State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/healthcaregov/openapi.md
x-common:
- type: x-developer
  url: http://www.healthcare.gov/developers
- type: x-website
  url: http://www.healthcare.gov
- type: x-wikipedia
  url: http://en.wikipedia.org/wiki/Healthcare.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---