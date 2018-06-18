---
name: eMuseum API docs
x-slug: emuseum-api-docs
description: Developed in partnership with museums, The Museum System makes capturing,
  managing and accessing collection information quick and easy. eMuseum is a web-based
  software program that integrates seamlessly with TMS and other collection management
  systems to dynamically publish information to your website, Intranet, and kiosks.
  This API delivers search information and images from TMS &amp; eMuseum to GSA.gov.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Collections
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/emuseum-api-docs/apis.md
specificationVersion: "0.14"
apis:
- name: eMuseum API Collections
  x-api-slug: emuseum-api
  description: Get Collections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//collections/all
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/emuseum-api-docs/collectionsall-get-openapi.md
- name: eMuseum API Collections
  x-api-slug: emuseum-api
  description: Get Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//collections/{id}
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/emuseum-api-docs/collectionsid-get-openapi.md
- name: eMuseum API
  x-api-slug: emuseum-api
  description: Developed in partnership with museums, The Museum System makes capturing,
    managing and accessing collection information quick and easy. eMuseum is a web-based
    software program that integrates seamlessly with TMS and other collection management
    systems to dynamically publish information to your website, Intranet, and kiosks.
    This API delivers search information and images from TMS &amp; eMuseum to GSA.gov.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/emuseum-api-docs/openapi.md
x-common:
- type: x-issues-page
  url: https://github.com/GSA/eMuseum-API/issues
- type: x-website
  url: http://gsa.github.io/eMuseum-API/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---