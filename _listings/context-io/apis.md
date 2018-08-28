---
name: Context.IO
x-slug: context-io
description: Create simple email webhooks and code against a free, RESTful, IMAP API.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
x-kinRank: "9"
x-alexaRank: "569975"
tags: Messages
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/apis.md
specificationVersion: "0.14"
apis:
- name: Context.IO - Get Accounts Contacts Email Messages
  x-api-slug: accountsidcontactsemailmessages-get
  description: Lists messages where a contact is present. Returns the latest email
    messages exchanged with one or more email addresses. By "exchanged with Mr. X"
    we mean any email received from Mr. X, sent to Mr. X or sent by anyone to both
    Mr. X and the mailbox owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-openapi.md
- name: Context.IO - Get Accounts Messages
  x-api-slug: accountsidmessages-get
  description: 'Lists email messages for an account. List filters: each of the email,
    to, from, cc and bcc parameters can be set to a comma-separated list of email
    addresses. These multiple addresses are treated as an OR combination. You can
    set more than one parameter when doing this call. Multiple parameters are treated
    as an AND combination.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-openapi.md
- name: Context.IO - Get Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-get
  description: Gets the file, contact and other information about a given email message.
    As specified in the RFC822, the < and > at the beginning and end of the Message-ID
    are part of the value and should be included if you're putting an email_message_id
    in the url.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-openapi.md
- name: Context.IO - Post Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-post
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Body
  x-api-slug: accountsidmessagesmessage-idbody-get
  description: 'Fetches the message body of a given email. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message. One thing to point out is
    we do fetch messages in such a way that large files attached to a message won''t
    make any difference in the response time. This call only returns text portions
    of messages, attachments aren''t included. To get a list of attachments on the
    message, look for the files property in the response of a message instance. To
    download the content of these attachments, use the files/content call.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Source
  x-api-slug: accountsidmessagesmessage-idsource-get
  description: 'Fetches the message source. Returns the raw RFC-822 message source
    for the message (including attachments) with no parsing or decoding to any portions
    of the message. On-demand data retrieval: since we do not keep full copies of
    emails on our servers, this call triggers a connection to the IMAP server to fetch
    the message. Attachments are part of the message source so they will impact how
    fast this call responds.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-get
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-openapi.md
- name: Context.IO - Post Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-post
  description: Sets message flags for a given email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Headers
  x-api-slug: accountsidmessagesmessage-idheaders-get
  description: 'Lists complete headers of a given email message. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message headers.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Thread
  x-api-slug: accountsidmessagesmessage-idthread-get
  description: Gets information about all messages of the thread a given message is
    in. This returns an array with the same structure as getting information on a
    single message for every message in the thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-openapi.md
- name: Context.IO - Get Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-get
  description: Gets the file, contact and other information about a given email message.
    As specified in the RFC822, the < and > at the beginning and end of the Message-ID
    are part of the value and should be included if you're putting an email_message_id
    in the url.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-openapi.md
- name: Context.IO - Post Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-post
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Body
  x-api-slug: accountsidmessagesmessage-idbody-get
  description: 'Fetches the message body of a given email. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message. One thing to point out is
    we do fetch messages in such a way that large files attached to a message won''t
    make any difference in the response time. This call only returns text portions
    of messages, attachments aren''t included. To get a list of attachments on the
    message, look for the files property in the response of a message instance. To
    download the content of these attachments, use the files/content call.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Source
  x-api-slug: accountsidmessagesmessage-idsource-get
  description: 'Fetches the message source. Returns the raw RFC-822 message source
    for the message (including attachments) with no parsing or decoding to any portions
    of the message. On-demand data retrieval: since we do not keep full copies of
    emails on our servers, this call triggers a connection to the IMAP server to fetch
    the message. Attachments are part of the message source so they will impact how
    fast this call responds.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-get
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-openapi.md
- name: Context.IO - Post Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-post
  description: Sets message flags for a given email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Headers
  x-api-slug: accountsidmessagesmessage-idheaders-get
  description: 'Lists complete headers of a given email message. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message headers.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Thread
  x-api-slug: accountsidmessagesmessage-idthread-get
  description: Gets information about all messages of the thread a given message is
    in. This returns an array with the same structure as getting information on a
    single message for every message in the thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-openapi.md
- name: Context.IO - Get Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-get
  description: Gets the file, contact and other information about a given email message.
    As specified in the RFC822, the < and > at the beginning and end of the Message-ID
    are part of the value and should be included if you're putting an email_message_id
    in the url.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-openapi.md
- name: Context.IO - Get Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-get
  description: Gets the file, contact and other information about a given email message.
    As specified in the RFC822, the < and > at the beginning and end of the Message-ID
    are part of the value and should be included if you're putting an email_message_id
    in the url.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-openapi.md
- name: Context.IO - Post Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-post
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-openapi.md
- name: Context.IO - Post Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-post
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Body
  x-api-slug: accountsidmessagesmessage-idbody-get
  description: 'Fetches the message body of a given email. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message. One thing to point out is
    we do fetch messages in such a way that large files attached to a message won''t
    make any difference in the response time. This call only returns text portions
    of messages, attachments aren''t included. To get a list of attachments on the
    message, look for the files property in the response of a message instance. To
    download the content of these attachments, use the files/content call.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Body
  x-api-slug: accountsidmessagesmessage-idbody-get
  description: 'Fetches the message body of a given email. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message. One thing to point out is
    we do fetch messages in such a way that large files attached to a message won''t
    make any difference in the response time. This call only returns text portions
    of messages, attachments aren''t included. To get a list of attachments on the
    message, look for the files property in the response of a message instance. To
    download the content of these attachments, use the files/content call.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Source
  x-api-slug: accountsidmessagesmessage-idsource-get
  description: 'Fetches the message source. Returns the raw RFC-822 message source
    for the message (including attachments) with no parsing or decoding to any portions
    of the message. On-demand data retrieval: since we do not keep full copies of
    emails on our servers, this call triggers a connection to the IMAP server to fetch
    the message. Attachments are part of the message source so they will impact how
    fast this call responds.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Source
  x-api-slug: accountsidmessagesmessage-idsource-get
  description: 'Fetches the message source. Returns the raw RFC-822 message source
    for the message (including attachments) with no parsing or decoding to any portions
    of the message. On-demand data retrieval: since we do not keep full copies of
    emails on our servers, this call triggers a connection to the IMAP server to fetch
    the message. Attachments are part of the message source so they will impact how
    fast this call responds.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-get
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-get
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-openapi.md
- name: Context.IO - Post Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-post
  description: Sets message flags for a given email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-openapi.md
- name: Context.IO - Post Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-post
  description: Sets message flags for a given email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Headers
  x-api-slug: accountsidmessagesmessage-idheaders-get
  description: 'Lists complete headers of a given email message. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message headers.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Headers
  x-api-slug: accountsidmessagesmessage-idheaders-get
  description: 'Lists complete headers of a given email message. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message headers.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Thread
  x-api-slug: accountsidmessagesmessage-idthread-get
  description: Gets information about all messages of the thread a given message is
    in. This returns an array with the same structure as getting information on a
    single message for every message in the thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Thread
  x-api-slug: accountsidmessagesmessage-idthread-get
  description: Gets information about all messages of the thread a given message is
    in. This returns an array with the same structure as getting information on a
    single message for every message in the thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-openapi.md
- name: Context.IO - Get Accounts Contacts Email Messages
  x-api-slug: accountsidcontactsemailmessages-get
  description: Lists messages where a contact is present. Returns the latest email
    messages exchanged with one or more email addresses. By "exchanged with Mr. X"
    we mean any email received from Mr. X, sent to Mr. X or sent by anyone to both
    Mr. X and the mailbox owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-openapi.md
- name: Context.IO - Get Accounts Contacts Email Messages
  x-api-slug: accountsidcontactsemailmessages-get
  description: Lists messages where a contact is present. Returns the latest email
    messages exchanged with one or more email addresses. By "exchanged with Mr. X"
    we mean any email received from Mr. X, sent to Mr. X or sent by anyone to both
    Mr. X and the mailbox owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidcontactsemailmessages-get-openapi.md
- name: Context.IO - Get Accounts Messages
  x-api-slug: accountsidmessages-get
  description: 'Lists email messages for an account. List filters: each of the email,
    to, from, cc and bcc parameters can be set to a comma-separated list of email
    addresses. These multiple addresses are treated as an OR combination. You can
    set more than one parameter when doing this call. Multiple parameters are treated
    as an AND combination.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-openapi.md
- name: Context.IO - Get Accounts Messages
  x-api-slug: accountsidmessages-get
  description: 'Lists email messages for an account. List filters: each of the email,
    to, from, cc and bcc parameters can be set to a comma-separated list of email
    addresses. These multiple addresses are treated as an OR combination. You can
    set more than one parameter when doing this call. Multiple parameters are treated
    as an AND combination.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessages-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Thread
  x-api-slug: accountsidmessagesmessage-idthread-get
  description: Gets information about all messages of the thread a given message is
    in. This returns an array with the same structure as getting information on a
    single message for every message in the thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idthread-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Headers
  x-api-slug: accountsidmessagesmessage-idheaders-get
  description: 'Lists complete headers of a given email message. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message headers.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idheaders-get-openapi.md
- name: Context.IO - Post Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-post
  description: Sets message flags for a given email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-post-openapi.md
- name: Context.IO - Get Accounts Messages Message Flags
  x-api-slug: accountsidmessagesmessage-idflags-get
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idflags-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Source
  x-api-slug: accountsidmessagesmessage-idsource-get
  description: 'Fetches the message source. Returns the raw RFC-822 message source
    for the message (including attachments) with no parsing or decoding to any portions
    of the message. On-demand data retrieval: since we do not keep full copies of
    emails on our servers, this call triggers a connection to the IMAP server to fetch
    the message. Attachments are part of the message source so they will impact how
    fast this call responds.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idsource-get-openapi.md
- name: Context.IO - Get Accounts Messages Message Body
  x-api-slug: accountsidmessagesmessage-idbody-get
  description: 'Fetches the message body of a given email. On-demand data retrieval:
    since we do not keep full copies of emails on our servers, this call triggers
    a connection to the IMAP server to fetch the message. One thing to point out is
    we do fetch messages in such a way that large files attached to a message won''t
    make any difference in the response time. This call only returns text portions
    of messages, attachments aren''t included. To get a list of attachments on the
    message, look for the files property in the response of a message instance. To
    download the content of these attachments, use the files/content call.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-idbody-get-openapi.md
- name: Context.IO - Post Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-post
  description: Copies or moves a message. Allows you to copy or move a message between
    folders. If there are more than one sources on the account, you can use this call
    to copy/move the message between these sources. In this case, the dst_label parameter
    must identify the source you want to message to be copied/moved to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-post-openapi.md
- name: Context.IO - Get Accounts Messages Message
  x-api-slug: accountsidmessagesmessage-id-get
  description: Gets the file, contact and other information about a given email message.
    As specified in the RFC822, the < and > at the beginning and end of the Message-ID
    are part of the value and should be included if you're putting an email_message_id
    in the url.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/context-io/accountsidmessagesmessage-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://constant.contact.api.gallery.streamdata.io
- type: x-api-stack
  url: http://context.io.stack.network
- type: x-base
  url: https://api.context.io/
- type: x-blog
  url: http://blog.context.io/
- type: x-blog-rss
  url: http://blog.context.io/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/product/context-io
- type: x-crunchbase
  url: https://crunchbase.com/organization/context-io
- type: x-documentation
  url: http://context.io/docs/2.0
- type: x-email
  url: hello@context.io
- type: x-email
  url: support@context.io
- type: x-email
  url: business@context.io
- type: x-faq
  url: http://context.io/privacy-faq
- type: x-github
  url: https://github.com/contextio
- type: x-ios-library
  url: https://github.com/contextio/contextio-ios
- type: x-node-js-library
  url: https://github.com/contextio/ContextIO-node
- type: x-php-library
  url: https://github.com/contextio/PHP-ContextIO
- type: x-pricing
  url: http://context.io/pricing
- type: x-privacy
  url: http://www.returnpath.com/privacy-policy-data
- type: x-python-library
  url: https://github.com/contextio/Python-ContextIO
- type: x-ruby-library
  url: https://github.com/contextio/contextio-ruby
- type: x-selfservice-registration
  url: http://context.io/#signup
- type: x-terms-of-service
  url: http://context.io/terms-of-service
- type: x-twitter
  url: https://twitter.com/contextio
- type: x-website
  url: http://context.io/
- type: x-website
  url: http://context.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---