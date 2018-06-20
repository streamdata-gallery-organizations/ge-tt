---
name: Ge.tt
x-slug: ge-tt
description: Extremely simple realtime filesharing. No signup required. Share any
  number of photos, videos, music, anything - in seconds - no matter how large.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
x-kinRank: "8"
x-alexaRank: "36546"
tags: Ge.tt
created: "2018-06-19"
modified: "2018-06-19"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/apis.md
specificationVersion: "0.14"
apis:
- name: Ge.tt  REST API Files Create
  x-api-slug: ge-tt--rest-api
  description: 'To upload files to Ge.tt you must first create the file under a given
    share. You do that by posting the filename:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/create
  tags: Files,Sharename,Create
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamecreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamecreate-post-openapi.md
- name: Ge.tt  REST API Files
  x-api-slug: ge-tt--rest-api
  description: 'Get the state of a file. This returns the following data:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/{fileid}
  tags: Files,Sharename,Fileid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileid-get-openapi.md
- name: Ge.tt  REST API Files  Blob
  x-api-slug: ge-tt--rest-api
  description: Will redirect to the binary content of the file
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/{fileid}/blob
  tags: Files,Sharename,Fileid,Blob
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblob-get-openapi.md
- name: Ge.tt  REST API Files  Blob Thumb
  x-api-slug: ge-tt--rest-api
  description: Will redirect to a thumbnail of the binary file. Currently only available
    for images.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/{fileid}/blob/thumb
  tags: Files,Sharename,Fileid,Blob,Thumb
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblobthumb-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidblobthumb-get-openapi.md
- name: Ge.tt  REST API Files  Destroy
  x-api-slug: ge-tt--rest-api
  description: Delete a file and the binary contents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/{fileid}/destroy
  tags: Files,Sharename,Fileid,Destroy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileiddestroy-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileiddestroy-post-openapi.md
- name: Ge.tt  REST API Files  Upload
  x-api-slug: ge-tt--rest-api
  description: Get upload urls to the file. This returns a new PUT and POST url for
    you to upload the file to.nOBS You can also choose to use the put- or posturl
    that you were previously given to override the file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/files/{sharename}/{fileid}/upload
  tags: Files,Sharename,Fileid,Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1filessharenamefileidupload-get-openapi.md
- name: Ge.tt  REST API Shares
  x-api-slug: ge-tt--rest-api
  description: 'Returns all your shares and the containing files:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/shares
  tags: Shares
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1shares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1shares-get-openapi.md
- name: Ge.tt  REST API Shares Create
  x-api-slug: ge-tt--rest-api
  description: 'Creates a new share. The request body is optional but can look like:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/shares/create
  tags: Shares,Create
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharescreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharescreate-post-openapi.md
- name: Ge.tt  REST API Shares
  x-api-slug: ge-tt--rest-api
  description: Lists a share.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/shares/{sharename}
  tags: Shares,Sharename
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharename-get-openapi.md
- name: Ge.tt  REST API Shares Destroy
  x-api-slug: ge-tt--rest-api
  description: Delete a share and all of its files.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/shares/{sharename}/destroy
  tags: Shares,Sharename,Destroy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenamedestroy-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenamedestroy-post-openapi.md
- name: Ge.tt  REST API Shares Update
  x-api-slug: ge-tt--rest-api
  description: Updates a share. Currently you can only update the title
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/shares/{sharename}/update
  tags: Shares,Sharename,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenameupdate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1sharessharenameupdate-post-openapi.md
- name: Ge.tt  REST API Users Login
  x-api-slug: ge-tt--rest-api
  description: 'The API is based on oauth with an xauth handshake. The request body
    looks like this:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/users/login
  tags: Users,Login
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1userslogin-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1userslogin-post-openapi.md
- name: Ge.tt  REST API Users Me
  x-api-slug: ge-tt--rest-api
  description: 'Returns your user information:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1//1/users/me
  tags: Users,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1usersme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/1usersme-get-openapi.md
- name: Ge.tt  REST API
  x-api-slug: ge-tt--rest-api
  description: The Ge.tt API allows you to use Ge.tt in your own applications. We
    believe that our users should be able to access their files and share their content
    in their platform of choice. By using the API, developers are able to easily put
    their own content, or the content of their users online. At the same time they
    are able to use Ge.tts unique real-time file sharing technology where files are
    available before they are even uploaded.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1012-ge-tt.jpg
  humanURL: http://ge.tt
  baseURL: https://open.ge.tt//1
  tags: Ge.tt
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/ge-tt/master/_listings/ge-tt/openapi.md
x-common:
- type: x--net-library
  url: http://ge.tt/developers/csharp
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