---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Delete Calendar
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: meeventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnameeventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendar/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendarideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendar/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendareventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/calendar/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidcalendareventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendargroup/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendargroupcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendargroupsidcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: memessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamemessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/mailFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: memailfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: memailfoldersidchildfoldersid---messagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /groups/{id}/threads/{id}/posts/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidthreadsidpostsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidconversationsidthreadsidpostsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: mecalendarsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: usersid--userprincipalnamecalendarsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /me/calendarGroup/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: mecalendargroupcalendarsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendarGroup/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /me/calendarGroups/{id}/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: mecalendargroupsidcalendarsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
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