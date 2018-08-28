swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /conversations/{id}/remove_messages:
    post:
      summary: Delete a message
      description: Delete a message.
      operationId: delete-a-message
      x-api-path-slug: conversationsidremove-messages-post
      parameters:
      - in: query
        name: remove[]
        description: Array of message ids to be deleted
      responses:
        200:
          description: OK
      tags:
      - Conversations
      - Id
      - Remove
      - Messages
  /conversations/{id}/add_message:
    post:
      summary: Add a message
      description: Add a message.
      operationId: add-a-message
      x-api-path-slug: conversationsidadd-message-post
      parameters:
      - in: query
        name: attachment_ids[]
        description: An array of attachments ids
      - in: query
        name: body
        description: The message to be sent
      - in: query
        name: included_messages[]
        description: no description
      - in: query
        name: media_comment_id
        description: Media comment id of an audio of video file to be associated with
          thisnmessage
      - in: query
        name: media_comment_type
        description: Type of the associated media file
      - in: query
        name: recipients[]
        description: no description
      - in: query
        name: user_note
        description: Will add a faculty journal entry for each recipient as long as
          the usernmaking the api call has permission, the recipient is a student
          and facultynjournals are enabled in the account
      responses:
        200:
          description: OK
      tags:
      - Conversations
      - Id
      - Add
      - Message
  /courses/{course_id}/quizzes/id/submission_users/message:
    post:
      summary: Send a message to unsubmitted or submitted users for the quiz
      description: Send a message to unsubmitted or submitted users for the quiz.
      operationId: send-a-message-to-unsubmitted-or-submitted-users-for-the-quiz
      x-api-path-slug: coursescourse-idquizzesidsubmission-usersmessage-post
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Quizzes
      - Id
      - Submission
      - Users
      - Message
  /comm_messages:
    get:
      summary: List of CommMessages for a user
      description: List of commmessages for a user.
      operationId: list-of-commmessages-for-a-user
      x-api-path-slug: comm-messages-get
      parameters:
      - in: query
        name: end_time
        description: The end of the time range you want to retrieve messages for
      - in: query
        name: start_time
        description: The beginning of the time range you want to retrieve message
          from
      - in: query
        name: user_id
        description: The user id for whom you want to retrieve CommMessages
      responses:
        200:
          description: OK
      tags:
      - Comm
      - Messages