---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Messages
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Messages
  x-api-slug: memailfoldersidmessages-get
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-get-openapi.md
- name: Microsoft Graph API - List Messages
  x-api-slug: usersid--userprincipalnamemailfoldersidmessages-get
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-get-openapi.md
- name: Microsoft Graph API - List Messages
  x-api-slug: usersid--userprincipalnamemessages-get
  description: List messages Get the messages in the signed-in user's mailbox (including
    the Deleted Items and Clutter folders).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessages-get-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: memailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersmemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: memailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: memessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: usersid--userprincipalnamemessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: memailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: memailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersmemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersmemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: memailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: memailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: memessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: memessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: usersid--userprincipalnamemessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: usersid--userprincipalnamemessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: usersid--userprincipalnamemessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Send
  x-api-slug: memessagesidsend-post
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: memailfoldersidmessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersid--userprincipalnamemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply All
  x-api-slug: usersmemessagesidreplyall-post
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memailfoldersidmessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: usersid--userprincipalnamemessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Reply
  x-api-slug: memessagesidreply-post
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memailfoldersidmessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: usersid--userprincipalnamemessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Move
  x-api-slug: memessagesidmove-post
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memailfoldersidmessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: usersid--userprincipalnamemessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Forward
  x-api-slug: memessagesidforward-post
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memailfoldersidmessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply All
  x-api-slug: memessagesidcreatereplyall-post
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memailfoldersidmessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: usersid--userprincipalnamemessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Reply
  x-api-slug: memessagesidcreatereply-post
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memailfoldersidmessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: usersid--userprincipalnamemessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Create Forward
  x-api-slug: memessagesidcreateforward-post
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memailfoldersidmessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: usersid--userprincipalnamemessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Message Copy
  x-api-slug: memessagesidcopy-post
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Create Message
  x-api-slug: memailfoldersidmessages-post
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memailfoldersidmessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: usersid--userprincipalnamemessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API - Update Message
  x-api-slug: memessagesid-patch
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memailfoldersidmessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: usersid--userprincipalnamemessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API - Get Message
  x-api-slug: memessagesid-get
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memailfoldersidmessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: usersid--userprincipalnamemessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph API - Delete Message
  x-api-slug: memessagesid-delete
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---