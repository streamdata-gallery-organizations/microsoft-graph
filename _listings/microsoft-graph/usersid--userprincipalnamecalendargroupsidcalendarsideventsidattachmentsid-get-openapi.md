---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get Attachment
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
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