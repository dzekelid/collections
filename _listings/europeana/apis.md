---
name: Europeana
x-slug: europeana
description: Europeana API allows you to build applications that use the wealth of
  cultural heritage objects stored in the Europeana repository. The API uses the standard
  technology of REST calls over HTTP. Responses are returned in the JSON format.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/europeana-logo.jpeg
x-kinRank: "9"
x-alexaRank: ""
tags: Collections
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/apis.md
specificationVersion: "0.14"
apis:
- name: Europeana get a single record in JSON format
  x-api-slug: europeana
  description: Get a single record in json format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/europeana-logo.jpeg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.json
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidjson-get-openapi.md
- name: Europeana get single record in JSON LD format
  x-api-slug: europeana
  description: Get single record in json ld format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/europeana-logo.jpeg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.jsonld
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidjsonld-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidjsonld-get-openapi.md
- name: Europeana get single record in RDF format)
  x-api-slug: europeana
  description: Get single record in rdf format).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/europeana-logo.jpeg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.rdf
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidrdf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordidrdf-get-openapi.md
- name: Europeana
  x-api-slug: europeana
  description: Europeana API allows you to build applications that use the wealth
    of cultural heritage objects stored in the Europeana repository. The API uses
    the standard technology of REST calls over HTTP. Responses are returned in the
    JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/europeana-logo.jpeg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2/
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/openapi.md
x-common:
- type: x-base
  url: http://www.europeana.eu/api/
- type: x-blog
  url: http://blog.europeana.eu/
- type: x-blog-rss
  url: http://blog.europeana.eu/feed/
- type: x-developer
  url: http://europeana.eu/portal/api-introduction.html
- type: x-github
  url: https://github.com/europeana
- type: x-twitter
  url: https://twitter.com/EuropeanaEU
- type: x-website
  url: http://europeana.eu/portal/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---