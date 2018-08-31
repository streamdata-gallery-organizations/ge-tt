---
name: Ge.tt
x-slug: ge-tt
description: Extremely simple realtime filesharing. No signup required. Share any
  number of photos, videos, music, anything - in seconds - no matter how large.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
x-kinRank: "8"
x-alexaRank: "36546"
tags: Ge.tt
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/apis.md
specificationVersion: "0.14"
apis:
- name: Ge.tt  REST API - Files Create
  x-api-slug: 1filessharenamecreate-post
  description: 'To upload files to Ge.tt you must first create the file under a given
    share. You do that by posting the filename:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamecreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamecreate-post-openapi.md
- name: Ge.tt  REST API - Files
  x-api-slug: 1filessharenamefileid-get
  description: 'Get the state of a file. This returns the following data:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileid-get-openapi.md
- name: Ge.tt  REST API - Files  Blob
  x-api-slug: 1filessharenamefileidblob-get
  description: Will redirect to the binary content of the file
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblob-get-openapi.md
- name: Ge.tt  REST API - Files  Blob Thumb
  x-api-slug: 1filessharenamefileidblobthumb-get
  description: Will redirect to a thumbnail of the binary file. Currently only available
    for images.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblobthumb-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblobthumb-get-openapi.md
- name: Ge.tt  REST API - Files  Destroy
  x-api-slug: 1filessharenamefileiddestroy-post
  description: Delete a file and the binary contents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileiddestroy-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileiddestroy-post-openapi.md
- name: Ge.tt  REST API - Files  Upload
  x-api-slug: 1filessharenamefileidupload-get
  description: Get upload urls to the file. This returns a new PUT and POST url for
    you to upload the file to.nOBS You can also choose to use the put- or posturl
    that you were previously given to override the file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidupload-get-openapi.md
- name: Ge.tt  REST API - Shares
  x-api-slug: 1shares-get
  description: 'Returns all your shares and the containing files:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1shares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1shares-get-openapi.md
- name: Ge.tt  REST API - Shares Create
  x-api-slug: 1sharescreate-post
  description: 'Creates a new share. The request body is optional but can look like:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharescreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharescreate-post-openapi.md
- name: Ge.tt  REST API - Shares
  x-api-slug: 1sharessharename-get
  description: Lists a share.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharename-get-openapi.md
- name: Ge.tt  REST API - Shares Destroy
  x-api-slug: 1sharessharenamedestroy-post
  description: Delete a share and all of its files.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenamedestroy-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenamedestroy-post-openapi.md
- name: Ge.tt  REST API - Shares Update
  x-api-slug: 1sharessharenameupdate-post
  description: Updates a share. Currently you can only update the title
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenameupdate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenameupdate-post-openapi.md
- name: Ge.tt  REST API - Users Login
  x-api-slug: 1userslogin-post
  description: 'The API is based on oauth with an xauth handshake. The request body
    looks like this:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1userslogin-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1userslogin-post-openapi.md
- name: Ge.tt  REST API - Users Me
  x-api-slug: 1usersme-get
  description: 'Returns your user information:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Files, Storage, File Transfer, File Sharing, File, Stack Network, Getting
    Started Example, Mobile, Technology, internet, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1usersme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1usersme-get-openapi.md
x-common:
- type: x--net-library
  url: http://ge.tt/developers/csharp
- type: x-api-gallery
  url: http://fullcontact.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ge.tt.stack.network
- type: x-base
  url: http://open.ge.tt
- type: x-blog
  url: http://ge.tt/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/ge-tt
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ge-tt
- type: x-developer
  url: http://ge.tt/developers
- type: x-email
  url: hello@ge.tt
- type: x-facebook
  url: https://www.facebook.com/gettsharing
- type: x-faq
  url: http://ge.tt/faq
- type: x-getting-started
  url: http://ge.tt/developers/start
- type: x-github
  url: https://github.com/gett
- type: x-java-library
  url: http://ge.tt/developers/java
- type: x-perl-library
  url: http://ge.tt/developers/perl
- type: x-python-library
  url: http://ge.tt/developers/python
- type: x-terms-of-service
  url: http://ge.tt/terms
- type: x-twitter
  url: https://twitter.com/gettsharing
- type: x-website
  url: http://ge.tt
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---