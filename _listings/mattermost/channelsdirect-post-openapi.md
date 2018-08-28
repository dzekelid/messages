---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Create a direct message channel
  description: |-
    Create a new direct message channel between two users.
    ##### Permissions
    Must be one of the two users and have `create_direct_channel` permission. Having the `manage_system` permission voids the previous requirements.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/channels/{channel_id}/unread:
    get:
      summary: Get unread messages
      description: |-
        Get the total unread messages and mentions for a channel for a user.
        ##### Permissions
        Must be logged in as user and have the `read_channel` permission, or have `edit_other_usrs` permission.
      operationId: get-the-total-unread-messages-and-mentions-for-a-channel-for-a-user-permissionsmust-be-logged-in-as-
      x-api-path-slug: usersuser-idchannelschannel-idunread-get
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Unread
      - Messages
  /channels/direct:
    post:
      summary: Create a direct message channel
      description: |-
        Create a new direct message channel between two users.
        ##### Permissions
        Must be one of the two users and have `create_direct_channel` permission. Having the `manage_system` permission voids the previous requirements.
      operationId: create-a-new-direct-message-channel-between-two-users-permissionsmust-be-one-of-the-two-users-and-ha
      x-api-path-slug: channelsdirect-post
      parameters:
      - in: body
        name: body
        description: The two user ids to be in the direct message
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Direct
      - Message
      - Channel
  /channels/group:
    post:
      summary: Create a group message channel
      description: |-
        Create a new group message channel to group of users. If the logged in user's id is not included in the list, it will be appended to the end.
        ##### Permissions
        Must have `create_group_channel` permission.
      operationId: create-a-new-group-message-channel-to-group-of-users-if-the-logged-in-users-id-is-not-included-in-th
      x-api-path-slug: channelsgroup-post
      parameters:
      - in: body
        name: body
        description: User ids to be in the group message channel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Group
      - Message
      - Channel
  /logs:
    post:
      summary: Add log message
      description: |-
        Add log messages to the server logs.
        ##### Permissions
        Users with `manage_system` permission can log ERROR or DEBUG messages.
        Logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` or just DEBUG messages when `false`.
        Non-logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` and cannot log when `false`.
      operationId: add-log-messages-to-the-server-logs-permissionsusers-with-manage-system-permission-can-log-error-or-
      x-api-path-slug: logs-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Log
      - Message
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---