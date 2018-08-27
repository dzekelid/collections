---
name: Flickr
x-slug: flickr
description: Flickr (pronounced flicker) is an image hosting and video hosting website,
  and web services suite that was created by Ludicorp in 2004 and acquired by Yahoo
  in 2005. In addition to being a popular website for users to share and embed personal
  photographs, and effectively an online community, the service is widely used by
  photo researchers and by bloggers to host images that they embed in blogs and social
  media.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Collections
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/flickr/apis.md
specificationVersion: "0.14"
apis:
- name: Flickr - Collections Get Info
  x-api-slug: restmethodflickr-collections-getinfo-get
  description: Returns information for a single collection. Currently can only be
    called by the collection owner, this may change.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/flickr/restmethodflickr-collections-getinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/flickr/restmethodflickr-collections-getinfo-get-openapi.md
- name: Flickr - Collections Get Tree
  x-api-slug: restmethodflickr-collections-gettree-get
  description: Returns a tree (or sub tree) of collections belonging to a given user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Images, My API Stack, Imports, Stack Network, Stack, Media, Photos, Getting
    Started Example, API Provider, Photos, Photos, Profiles, General Data, Relative
    Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/flickr/restmethodflickr-collections-gettree-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/flickr/restmethodflickr-collections-gettree-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://flat.api.gallery.streamdata.io
- type: x-api-stack
  url: http://flickr.stack.network
- type: x-authentication
  url: https://www.flickr.com/services/api/auth.oauth.html
- type: x-base
  url: https://api.flickr.com/services/
- type: x-developer
  url: https://www.flickr.com/services/api/
- type: x-getting-started
  url: https://www.flickr.com/services/developer/
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/flickr/details.html
- type: x-support
  url: https://help.yahoo.com/kb/flickr-for-desktop
- type: x-terms-of-service
  url: https://www.flickr.com/services/api/tos/
- type: x-twitter
  url: https://twitter.com/flickr
- type: x-website
  url: http://www.flickr.com/
- type: x-website
  url: http://flickr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---