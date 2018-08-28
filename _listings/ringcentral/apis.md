---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Messages
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Create SMS Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidsms-post
  description: "Creates and sends new SMS message. Sending SMS messages simultaneously
    to different recipients is limited up to 50 requests per minute; relevant for
    all client applications.\nApp Permission\nSMS\nUser Permission\nOutboundSMS\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [] value is invalid\n\n\n400\nCMN-406\nDuplicate
    value for parameter to: +13476733173 found in request\n\n\n400\nMSG-243\nParameter
    [to] value [18882049692] is invalid [Phone number is blocked]\n\n\n400\nMSG-245\nParameter
    [from] value [88121002330] is invalid [Cannot find the phone number which belongs
    to user]\n\n\n400\nMSG-246\nSending SMS from/to extension numbers is not available\n\n\n400\nMSG-247\nSending
    SMS to short numbers is not available\n\n\n400\nMSG-365\nParameters [country.id]
    and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-376\nAttachment
    size limit exceeded\n\n\n400\nMSG-379\nToo many attachments\n\n\n400\nMSG-381\nExceeded
    maximum number of recipients for a Group MMS: [10]\n\n\n403\nBIL-103\nFeature
    [MMS] is not available for current account\n\n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [SMS] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [OutboundSMS] permission for
    requested resource.\n\n\n403\nMSG-240\nInternational SMS is not available for
    account.\n\n\n403\nMSG-241\nCannot send SMS from Fax number\n\n\n403\nMSG-242\nThe
    requested feature is not available\n\n\n403\nMSG-314\nExtension is of inappropriate
    type\n\n\n403\nMSG-367\n\"from\" phone number does not support SMS\n\n\n403\nMSG-383\nInternational
    MMS feature is not available\n\n\n403\nMSG-384\nAccount limits exceeded. Cannot
    send the message.\n\n\n403\nMSG-388\nThe destination is prohibited\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n415\nMSG-348\nUnsupported attachment
    media type, attachment [3]: [stuff.smil]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidsms-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Sync
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagesync-get
  description: "Synchronizes messages.\nApp Permission\nReadMessages\nUser Permission\nReadMessages\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [messageType] value is invalid\n\n\n400\nMSG-333\nParameter
    [syncToken] is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [ReadMessages] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagesync-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-get
  description: "Returns individual message record(s) by the given message ID(s). The
    length of inbound messages is unlimited. Batch request is supported.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessages] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Message(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-put
  description: "Updates message(s) by ID(s). Batch request is supported, see Batch
    Requests for details. Currently, only the message read status updating is supported.\nApp
    Permission\nEditMessages\nUser Permission\nEditMessages\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [] value is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [EditMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [EditMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Message(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-delete
  description: "Deletes message(s) by the given message ID(s). The first call of this
    method transfers the message to the &#39;Delete&#39; status. The second call transfers
    the deleted message to the &#39;Purged&#39; status. If it is required to make
    the message &#39;Purged&#39; immediately (from the first call), then set the query
    parameter purge to &#39;True&#39;.\nApp Permission\nEditMessages\nUser Permission\nEditMessages\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [purge] value is invalid\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditMessages] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Create SMS Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidsms-post
  description: "Creates and sends new SMS message. Sending SMS messages simultaneously
    to different recipients is limited up to 50 requests per minute; relevant for
    all client applications.\nApp Permission\nSMS\nUser Permission\nOutboundSMS\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [] value is invalid\n\n\n400\nCMN-406\nDuplicate
    value for parameter to: +13476733173 found in request\n\n\n400\nMSG-243\nParameter
    [to] value [18882049692] is invalid [Phone number is blocked]\n\n\n400\nMSG-245\nParameter
    [from] value [88121002330] is invalid [Cannot find the phone number which belongs
    to user]\n\n\n400\nMSG-246\nSending SMS from/to extension numbers is not available\n\n\n400\nMSG-247\nSending
    SMS to short numbers is not available\n\n\n400\nMSG-365\nParameters [country.id]
    and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-376\nAttachment
    size limit exceeded\n\n\n400\nMSG-379\nToo many attachments\n\n\n400\nMSG-381\nExceeded
    maximum number of recipients for a Group MMS: [10]\n\n\n403\nBIL-103\nFeature
    [MMS] is not available for current account\n\n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [SMS] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [OutboundSMS] permission for
    requested resource.\n\n\n403\nMSG-240\nInternational SMS is not available for
    account.\n\n\n403\nMSG-241\nCannot send SMS from Fax number\n\n\n403\nMSG-242\nThe
    requested feature is not available\n\n\n403\nMSG-314\nExtension is of inappropriate
    type\n\n\n403\nMSG-367\n\"from\" phone number does not support SMS\n\n\n403\nMSG-383\nInternational
    MMS feature is not available\n\n\n403\nMSG-384\nAccount limits exceeded. Cannot
    send the message.\n\n\n403\nMSG-388\nThe destination is prohibited\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n415\nMSG-348\nUnsupported attachment
    media type, attachment [3]: [stuff.smil]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidsms-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create SMS Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidsms-post
  description: "Creates and sends new SMS message. Sending SMS messages simultaneously
    to different recipients is limited up to 50 requests per minute; relevant for
    all client applications.\nApp Permission\nSMS\nUser Permission\nOutboundSMS\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [] value is invalid\n\n\n400\nCMN-406\nDuplicate
    value for parameter to: +13476733173 found in request\n\n\n400\nMSG-243\nParameter
    [to] value [18882049692] is invalid [Phone number is blocked]\n\n\n400\nMSG-245\nParameter
    [from] value [88121002330] is invalid [Cannot find the phone number which belongs
    to user]\n\n\n400\nMSG-246\nSending SMS from/to extension numbers is not available\n\n\n400\nMSG-247\nSending
    SMS to short numbers is not available\n\n\n400\nMSG-365\nParameters [country.id]
    and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-376\nAttachment
    size limit exceeded\n\n\n400\nMSG-379\nToo many attachments\n\n\n400\nMSG-381\nExceeded
    maximum number of recipients for a Group MMS: [10]\n\n\n403\nBIL-103\nFeature
    [MMS] is not available for current account\n\n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [SMS] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [OutboundSMS] permission for
    requested resource.\n\n\n403\nMSG-240\nInternational SMS is not available for
    account.\n\n\n403\nMSG-241\nCannot send SMS from Fax number\n\n\n403\nMSG-242\nThe
    requested feature is not available\n\n\n403\nMSG-314\nExtension is of inappropriate
    type\n\n\n403\nMSG-367\n\"from\" phone number does not support SMS\n\n\n403\nMSG-383\nInternational
    MMS feature is not available\n\n\n403\nMSG-384\nAccount limits exceeded. Cannot
    send the message.\n\n\n403\nMSG-388\nThe destination is prohibited\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n415\nMSG-348\nUnsupported attachment
    media type, attachment [3]: [stuff.smil]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidsms-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Sync
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagesync-get
  description: "Synchronizes messages.\nApp Permission\nReadMessages\nUser Permission\nReadMessages\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [messageType] value is invalid\n\n\n400\nMSG-333\nParameter
    [syncToken] is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [ReadMessages] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagesync-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Sync
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagesync-get
  description: "Synchronizes messages.\nApp Permission\nReadMessages\nUser Permission\nReadMessages\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [messageType] value is invalid\n\n\n400\nMSG-333\nParameter
    [syncToken] is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [ReadMessages] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagesync-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Sync
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagesync-get
  description: "Synchronizes messages.\nApp Permission\nReadMessages\nUser Permission\nReadMessages\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [messageType] value is invalid\n\n\n400\nMSG-333\nParameter
    [syncToken] is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [ReadMessages] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagesync-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Sync
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagesync-get
  description: "Synchronizes messages.\nApp Permission\nReadMessages\nUser Permission\nReadMessages\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [messageType] value is invalid\n\n\n400\nMSG-333\nParameter
    [syncToken] is invalid\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [ReadMessages] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagesync-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message Attachment
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get
  description: "Returns a specific message attachment data as a media stream.\nApp
    Permission\nReadMessages\nUser Permission\nReadMessageContent\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessageContent] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found\n\n\n416\nCMN-107\nRequested range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestoremessageidcontentattachmentid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Message List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidmessagestore-get
  description: "Returns the list of messages from an extension mailbox.\nApp Permission\nReadMessages\nUser
    Permission\nReadMessages\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [readStatus]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadMessages] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadMessages] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidmessagestore-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Fax Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfax-post
  description: "Creates and sends/resends new fax message. Resend can be done if sending
    failed.\nApp Permission\nFaxes\nUser Permission\nOutboundFaxes\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [to] value is invalid\n\n\n400\nMSG-344\nSending fax to extension numbers is not
    available\n\n\n400\nMSG-347\nAttachment [t.txt] body is empty\n\n\n400\nMSG-355\nFor
    binary data filename with extension should be specified, attachment [1]: []\n\n\n400\nMSG-356\nEither
    filename or content type should be specified, attachment [1]: []\n\n\n400\nMSG-365\nParameters
    [country.id] and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-370\nfilename
    is too long, 256 characters allowed\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Faxes] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OutboundFaxes] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n415\nMSG-348\nUnsupported
    attachment media type, attachment [1]: [.jfif]\n\n\n415\nMSG-353\nNo file extension
    or content type specified, attachment [1]: [filename,txt]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfax-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Pager Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcompanypager-post
  description: "Creates and sends a pager message.\nApp Permission\nInternalMessages\nUser
    Permission\nInternalSMS\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [to.phoneNumber]
    value is invalid\n\n\n400\nCMN-102\nResource for parameter [to] is not found\n\n\n400\nMSG-316\nParameter
    [to] value [102] is invalid [Target extension not found]\n\n\n400\nMSG-324\nExtension
    is of unappropriate state\n\n\n400\nMSG-331\nParameter [from] value [11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111]
    is invalid [Sender extension number does not correspond to logged in extension]\n\n\n400\nMSG-332\nParameter
    [from] value [404544780008] is invalid [Sender extension id does not correspond
    to logged in extension]\n\n\n400\nMSG-335\nRecipient extension number does not
    correspond to ID\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [InternalMessages] permission\n\n\n403\nCMN-408\nIn order to call
    this API endpoint, user needs to have [InternalSMS] permission for requested resource.\n\n\n403\nMSG-325\nReply
    is forbidden for old message threads\n\n\n403\nMSG-326\nReply is denied for user,
    who is no longer a thread participant\n\n\n403\nMSG-330\nSender extension is of
    unappropriate type\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcompanypager-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create SMS Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidsms-post
  description: "Creates and sends new SMS message. Sending SMS messages simultaneously
    to different recipients is limited up to 50 requests per minute; relevant for
    all client applications.\nApp Permission\nSMS\nUser Permission\nOutboundSMS\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [] value is invalid\n\n\n400\nCMN-406\nDuplicate
    value for parameter to: +13476733173 found in request\n\n\n400\nMSG-243\nParameter
    [to] value [18882049692] is invalid [Phone number is blocked]\n\n\n400\nMSG-245\nParameter
    [from] value [88121002330] is invalid [Cannot find the phone number which belongs
    to user]\n\n\n400\nMSG-246\nSending SMS from/to extension numbers is not available\n\n\n400\nMSG-247\nSending
    SMS to short numbers is not available\n\n\n400\nMSG-365\nParameters [country.id]
    and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-376\nAttachment
    size limit exceeded\n\n\n400\nMSG-379\nToo many attachments\n\n\n400\nMSG-381\nExceeded
    maximum number of recipients for a Group MMS: [10]\n\n\n403\nBIL-103\nFeature
    [MMS] is not available for current account\n\n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [SMS] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [OutboundSMS] permission for
    requested resource.\n\n\n403\nMSG-240\nInternational SMS is not available for
    account.\n\n\n403\nMSG-241\nCannot send SMS from Fax number\n\n\n403\nMSG-242\nThe
    requested feature is not available\n\n\n403\nMSG-314\nExtension is of inappropriate
    type\n\n\n403\nMSG-367\n\"from\" phone number does not support SMS\n\n\n403\nMSG-383\nInternational
    MMS feature is not available\n\n\n403\nMSG-384\nAccount limits exceeded. Cannot
    send the message.\n\n\n403\nMSG-388\nThe destination is prohibited\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n415\nMSG-348\nUnsupported attachment
    media type, attachment [3]: [stuff.smil]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidsms-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create SMS Message
  x-api-slug: restapiv1-0accountaccountidextensionextensionidsms-post
  description: "Creates and sends new SMS message. Sending SMS messages simultaneously
    to different recipients is limited up to 50 requests per minute; relevant for
    all client applications.\nApp Permission\nSMS\nUser Permission\nOutboundSMS\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [] value is invalid\n\n\n400\nCMN-406\nDuplicate
    value for parameter to: +13476733173 found in request\n\n\n400\nMSG-243\nParameter
    [to] value [18882049692] is invalid [Phone number is blocked]\n\n\n400\nMSG-245\nParameter
    [from] value [88121002330] is invalid [Cannot find the phone number which belongs
    to user]\n\n\n400\nMSG-246\nSending SMS from/to extension numbers is not available\n\n\n400\nMSG-247\nSending
    SMS to short numbers is not available\n\n\n400\nMSG-365\nParameters [country.id]
    and [country.isoCode] can not be specified simultaneously\n\n\n400\nMSG-376\nAttachment
    size limit exceeded\n\n\n400\nMSG-379\nToo many attachments\n\n\n400\nMSG-381\nExceeded
    maximum number of recipients for a Group MMS: [10]\n\n\n403\nBIL-103\nFeature
    [MMS] is not available for current account\n\n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [SMS] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [OutboundSMS] permission for
    requested resource.\n\n\n403\nMSG-240\nInternational SMS is not available for
    account.\n\n\n403\nMSG-241\nCannot send SMS from Fax number\n\n\n403\nMSG-242\nThe
    requested feature is not available\n\n\n403\nMSG-314\nExtension is of inappropriate
    type\n\n\n403\nMSG-367\n\"from\" phone number does not support SMS\n\n\n403\nMSG-383\nInternational
    MMS feature is not available\n\n\n403\nMSG-384\nAccount limits exceeded. Cannot
    send the message.\n\n\n403\nMSG-388\nThe destination is prohibited\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n415\nMSG-348\nUnsupported attachment
    media type, attachment [3]: [stuff.smil]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidsms-post-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---