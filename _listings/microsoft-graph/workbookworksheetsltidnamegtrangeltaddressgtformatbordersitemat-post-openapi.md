---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Border Collection Item At
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: memailfoldersidchildfoldersid---messagesidattachmentsid-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: mecalendarsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: mecalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: usersid--userprincipalnamecalendarsid-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: mecalendargroupcalendarsid-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: mecalendargroupcalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsid-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: mecalendargroupsidcalendarsid-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: mecalendargroupsidcalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}:
    delete:
      summary: Delete Calendar
      description: |-
        Delete calendar
        Delete a calendar other than the default calendar.
      operationId: DeleteCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsid-delete
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
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsid-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
  /me/calendar:
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: mecalendar-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: mecalendar-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendar:
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: usersid--userprincipalnamecalendar-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendar-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /groups/{id}/calendar:
    get:
      summary: Get Calendar
      description: |-
        Get calendar
        Retrieve the properties and relationships of calendar object.
      operationId: GetCalendar
      x-api-path-slug: groupsidcalendar-get
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
    patch:
      summary: Update Calendar
      description: Update calendar Update the properties of calendar object.
      operationId: UpdateCalendar
      x-api-path-slug: groupsidcalendar-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /me/calendar/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: mecalendarcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /users/{id | userPrincipalName}/calendar/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: usersid--userprincipalnamecalendarcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /groups/{id}/calendar/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: groupsidcalendarcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /me/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: mecalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /users/{id | userPrincipalName}/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: usersid--userprincipalnamecalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /me/calendarGroup/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: mecalendargroupcalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /users/{id | userPrincipalName}/calendarGroup/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /me/calendarGroups/{id}/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: mecalendargroupsidcalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/calendarView:
    get:
      summary: List Calendar View
      description: |-
        List calendarView
        Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
        from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
      operationId: ListCalendarView
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: application/json
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /me/calendar/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: mecalendarevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: mecalendarevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Event
  /users/{id | userPrincipalName}/calendar/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: usersid--userprincipalnamecalendarevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: usersid--userprincipalnamecalendarevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /groups/{id}/calendar/events:
    get:
      summary: List Events
      description: List events Retrieve a list of event objects.
      operationId: ListEvents
      x-api-path-slug: groupsidcalendarevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: outlook
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new event.
      operationId: CreateEvent
      x-api-path-slug: groupsidcalendarevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /me/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: mecalendarsidevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: mecalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /users/{id | userPrincipalName}/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: usersid--userprincipalnamecalendarsidevents-get
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
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: usersid--userprincipalnamecalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Event
  /me/calendarGroup/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: mecalendargroupcalendarsidevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: mecalendargroupcalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /users/{id | userPrincipalName}/calendarGroup/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsidevents-get
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
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Event
  /me/calendarGroups/{id}/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: mecalendargroupsidcalendarsidevents-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: mecalendargroupsidcalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of events in a calendar.  The list
        contains single instance meetings and series masters.
      operationId: ListEvents
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsidevents-get
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
      - in: header
        name: Prefer
        description: outlook
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new Event in the default
        or the specified calendar.
      operationId: CreateEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Event
  /me/calendarGroups/{id}:
    delete:
      summary: Delete Calendar Group
      description: Delete calendarGroup Delete a calendar group other than the default
        calendar group.
      operationId: DeleteCalendarGroup
      x-api-path-slug: mecalendargroupsid-delete
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
      - Group
    get:
      summary: Get Calendar Group
      description: Get calendarGroup Retrieve the properties and relationships of
        a calendar group object.
      operationId: GetCalendarGroup
      x-api-path-slug: mecalendargroupsid-get
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
      - Group
    patch:
      summary: Update Calendargroup
      description: Update calendargroup Update the properties of calendargroup object.
      operationId: UpdateCalendargroup
      x-api-path-slug: mecalendargroupsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendargroup
  /users/{id | userPrincipalName}/calendarGroups/{id}:
    delete:
      summary: Delete Calendar Group
      description: Delete calendarGroup Delete a calendar group other than the default
        calendar group.
      operationId: DeleteCalendarGroup
      x-api-path-slug: usersid--userprincipalnamecalendargroupsid-delete
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
      - Group
    get:
      summary: Get Calendar Group
      description: Get calendarGroup Retrieve the properties and relationships of
        a calendar group object.
      operationId: GetCalendarGroup
      x-api-path-slug: usersid--userprincipalnamecalendargroupsid-get
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
      - Group
    patch:
      summary: Update Calendargroup
      description: Update calendargroup Update the properties of calendargroup object.
      operationId: UpdateCalendargroup
      x-api-path-slug: usersid--userprincipalnamecalendargroupsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Calendargroup
  /me/calendarGroup/calendars:
    get:
      summary: List Calendars
      description: List calendars Retrieve a list of calendars belonging to a calendar
        group.
      operationId: ListCalendars
      x-api-path-slug: mecalendargroupcalendars-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendars
    post:
      summary: Create Calendar
      description: Create Calendar Use this API to create a new Calendar in a calendar
        group.
      operationId: CreateCalendar
      x-api-path-slug: mecalendargroupcalendars-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendarGroup/calendars:
    get:
      summary: List Calendars
      description: List calendars Retrieve a list of calendars belonging to a calendar
        group.
      operationId: ListCalendars
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendars-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendars
    post:
      summary: Create Calendar
      description: Create Calendar Use this API to create a new Calendar in a calendar
        group.
      operationId: CreateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendars-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /me/calendarGroups/{id}/calendars:
    get:
      summary: List Calendars
      description: List calendars Retrieve a list of calendars belonging to a calendar
        group.
      operationId: ListCalendars
      x-api-path-slug: mecalendargroupsidcalendars-get
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
      - Calendars
    post:
      summary: Create Calendar
      description: Create Calendar Use this API to create a new Calendar in a calendar
        group.
      operationId: CreateCalendar
      x-api-path-slug: mecalendargroupsidcalendars-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /users/{id | userPrincipalName}/calendarGroups/{id}/calendars:
    get:
      summary: List Calendars
      description: List calendars Retrieve a list of calendars belonging to a calendar
        group.
      operationId: ListCalendars
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendars-get
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
      - Calendars
    post:
      summary: Create Calendar
      description: Create Calendar Use this API to create a new Calendar in a calendar
        group.
      operationId: CreateCalendar
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendars-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
  /workbook/worksheets(&lt;id|name&gt;)/charts(&lt;name&gt;)/series(&lt;undefined&gt;)/points:
    get:
      summary: List Points
      description: List points Retrieve a list of chartpoints objects.
      operationId: ListPoints
      x-api-path-slug: workbookworksheetsltidnamegtchartsltnamegtseriesltundefinedgtpoints-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Points
  /me/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Contact
  /me/contactFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactfoldersidcontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Contact
  /me/contactFolder/{id}/childFolders/{id}/.../contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Contact
  /me/contactfolders/{Id}/contacts/{id}:
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactfoldersidcontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactfolders/{id}/contacts/{id}:
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
  /me/contactFolders/{id}:
    delete:
      summary: Delete Contact Folder
      description: Delete contactFolder Delete contactFolder other than the default
        contactFolder.
      operationId: DeleteContactFolder
      x-api-path-slug: mecontactfoldersid-delete
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
      - Contact
      - Folder
    get:
      summary: Get Contact Folder
      description: Get contactFolder Get a contact folder by using the contact folder
        ID.
      operationId: GetContactFolder
      x-api-path-slug: mecontactfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Folder
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: mecontactfoldersid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id | userPrincipalName}/contactFolders/{id}:
    delete:
      summary: Delete Contact Folder
      description: Delete contactFolder Delete contactFolder other than the default
        contactFolder.
      operationId: DeleteContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersid-delete
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
      - Contact
      - Folder
    get:
      summary: Get Contact Folder
      description: Get contactFolder Get a contact folder by using the contact folder
        ID.
      operationId: GetContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersid-get
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
      - Contact
      - Folder
  /me/contactFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get a collection of child folders under the specified
        contact folder.
      operationId: ListChildFolders
      x-api-path-slug: mecontactfoldersidchildfolders-get
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
      - Child
      - Folders
    post:
      summary: Create Contact Folder
      description: Create ContactFolder Create a new contactFolder as a child of a
        specified folder.
      operationId: CreateContactFolder
      x-api-path-slug: mecontactfoldersidchildfolders-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Folder
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get a collection of child folders under the specified
        contact folder.
      operationId: ListChildFolders
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfolders-get
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
      - Child
      - Folders
    post:
      summary: Create Contact Folder
      description: Create ContactFolder Create a new contactFolder as a child of a
        specified folder.
      operationId: CreateContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Contact
      - Folder
  /me/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: mecontacts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: mecontacts-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: usersid--userprincipalnamecontacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: usersid--userprincipalnamecontacts-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /me/contactFolders/{id}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: mecontactfoldersidcontacts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: mecontactfoldersidcontacts-post
      parameters:
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{id}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Contacts
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontacts-post
      parameters:
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
      - Contact
  /devices/{id}:
    delete:
      summary: Delete Device
      description: Delete device Delete a registered device.
      operationId: DeleteDevice
      x-api-path-slug: devicesid-delete
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
      - Device
    get:
      summary: Get Device
      description: Get device Get the properties and relationships of a device object.
      operationId: GetDevice
      x-api-path-slug: devicesid-get
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
      - Device
    patch:
      summary: Update Device
      description: Update device Update the properties of a registered device.
      operationId: UpdateDevice
      x-api-path-slug: devicesid-patch
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
      - Device
  /devices:
    get:
      summary: List Devices
      description: List devices Retrieve a list of device objects registered in the
        organization.
      operationId: ListDevices
      x-api-path-slug: devices-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Devices
    post:
      summary: Create Device
      description: Create device Create and register a new device in the organization.
      operationId: CreateDevice
      x-api-path-slug: devices-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-type
        description: application/json
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device
  /devices/{id}/registeredOwners:
    get:
      summary: List Registered Owners
      description: List registeredOwners Retrieve a list of users that are registered
        owners of the device.
      operationId: ListRegisteredOwners
      x-api-path-slug: devicesidregisteredowners-get
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
      - Registered
      - Owners
    post:
      summary: Create Registered Owner
      description: Create registeredOwner Add a user as a registered owner of the
        device.
      operationId: CreateRegisteredOwner
      x-api-path-slug: devicesidregisteredowners-post
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
      - Registered
      - Owner
  /devices/{id}/registeredUsers:
    get:
      summary: List Registered Users
      description: List registeredUsers Retrieve a list of users that are registered
        users of the device.
      operationId: ListRegisteredUsers
      x-api-path-slug: devicesidregisteredusers-get
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
      - Registered
      - Users
    post:
      summary: Create Registered User
      description: Create registeredUser Add a registered user for the device.
      operationId: CreateRegisteredUser
      x-api-path-slug: devicesidregisteredusers-post
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
      - Registered
      - User
  /me/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: mecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /users/{id | userPrincipalName}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: usersid--userprincipalnamecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /groups/{id}/checkMemberGroups:
    post:
      summary: Group Check Member Groups
      description: 'group: checkMemberGroups Check for membership in the specified
        list of groups. Returns from the list those groups of which the specified
        group has a direct or transitive membership.'
      operationId: Group:CheckMemberGroups
      x-api-path-slug: groupsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Checks
      - Member
      - Groups
  /directoryObjects/{id}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: directoryobjectsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /directoryObjects/{id}:
    delete:
      summary: Delete Directory Object
      description: Delete directoryObject Deletes a directoryObject.
      operationId: DeleteDirectoryObject
      x-api-path-slug: directoryobjectsid-delete
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
      - Directory
      - Object
    get:
      summary: Get Directory Object
      description: Get directoryObject Retrieve the properties and relationships of
        directoryObject object.
      operationId: GetDirectoryObject
      x-api-path-slug: directoryobjectsid-get
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
      - Directory
      - Object
  /me/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: megetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /users/{id | userPrincipalName}/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: usersid--userprincipalnamegetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /groups/{id}/getMemberGroups:
    post:
      summary: Group Get Member Groups
      description: 'group: getMemberGroups Return all the groups that the specified
        group is a member of. The check is transitive, unlike reading the memberOf
        navigation property, which returns only the groups that the group is a direct
        member of.'
      operationId: Group:GetMemberGroups
      x-api-path-slug: groupsidgetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - ""
      - Member
      - Groups
  /directoryObjects/{id}/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: directoryobjectsidgetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /me/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: megetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /users/{id | userPrincipalName}/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: usersid--userprincipalnamegetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /directoryObjects/{id}/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: directoryobjectsidgetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /directoryRoles/{id}:
    get:
      summary: Get Directory Role
      description: Get directoryRole Retrieve the properties of a directoryRole object.
      operationId: GetDirectoryRole
      x-api-path-slug: directoryrolesid-get
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
      - Directory
      - Role
  /directoryRoles:
    get:
      summary: List Directory Roles
      description: List directoryRoles List the directory roles that are activated
        in the tenant.
      operationId: ListDirectoryRoles
      x-api-path-slug: directoryroles-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Directory
      - Roles
    post:
      summary: Activate Directory Role
      description: Activate directoryRole Activate a directory role. To read a directory
        role or update its members, it must first be activated in the tenant. Only
        the Company Administrators and the implicit Users directory roles are activated
        by default. To access and assign members to another directory role, you must
        first activate it with its corresponding directory role template (directoryRoleTemplate).
      operationId: ActivateDirectoryRole
      x-api-path-slug: directoryroles-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Directory
      - Role
  /directoryRoles/{id}/members:
    get:
      summary: List Members
      description: List members Retrieve a list of the users that are assigned to
        the directory role.  Only users can be assigned to a directory role.
      operationId: ListMembers
      x-api-path-slug: directoryrolesidmembers-get
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
      - Members
  /directoryRoles/{id}/members/$ref:
    post:
      summary: Add Directory Role Member
      description: Add directory role member Use this API to create a new directory
        role member.
      operationId: AddDirectoryRoleMember
      x-api-path-slug: directoryrolesidmembersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Role
      - Member
  /directoryRoleTemplates/{id}:
    get:
      summary: Get Directory Role Template
      description: Get directoryRoleTemplate Retrieve the properties and relationships
        of a directoryroletemplate object.
      operationId: GetDirectoryRoleTemplate
      x-api-path-slug: directoryroletemplatesid-get
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
      - Directory
      - Role
      - Template
  /directoryRoleTemplates:
    get:
      summary: List Directory Role Templates
      description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
        objects.
      operationId: ListDirectoryRoleTemplates
      x-api-path-slug: directoryroletemplates-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Directory
      - Role
      - Templates
  /drives:
    get:
      summary: List Available Drives
      description: List available drives Retrieve the list of Drive resources available
        for a target User or Group. Your app can also request the set of document
        libraries on the SharePoint root site.
      operationId: ListAvailableDrives
      x-api-path-slug: drives-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Available
      - Drives
  /me/drives:
    get:
      summary: List Available Drives
      description: List available drives Retrieve the list of Drive resources available
        for a target User or Group. Your app can also request the set of document
        libraries on the SharePoint root site.
      operationId: ListAvailableDrives
      x-api-path-slug: medrives-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Available
      - Drives
  /groups/{id}/drives:
    get:
      summary: List Available Drives
      description: List available drives Retrieve the list of Drive resources available
        for a target User or Group. Your app can also request the set of document
        libraries on the SharePoint root site.
      operationId: ListAvailableDrives
      x-api-path-slug: groupsiddrives-get
      parameters:
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Available
      - Drives
  /me/drive/special/{name}:
    get:
      summary: Get A Special Folder By Name
      description: Get a special folder by name Use the special collection to access
        a special folder by name.
      operationId: GetASpecialFolderByName
      x-api-path-slug: medrivespecialname-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Special
      - FolderName
  /me/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: meeventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnameeventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Accept
  /groups/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: groupsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /me/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Accept
  /groups/{id}/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: groupsidcalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /me/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Accept
  /me/calendargroup/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendargroupcalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Accept
  /me/calendargroups/{id}/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendargroupsidcalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Accept
  /me/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: meeventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnameeventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Decline
  /groups/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: groupsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /me/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Decline
  /groups/{id}/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: groupsidcalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /me/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Decline
  /me/calendargroup/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendargroupcalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Decline
  /me/calendargroups/{id}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendargroupsidcalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Decline
  /me/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: meeventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: meeventsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: meeventsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /users/{id | userPrincipalName}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: usersid--userprincipalnameeventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: usersid--userprincipalnameeventsid-get
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
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: usersid--userprincipalnameeventsid-patch
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
      - Event
  /groups/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: groupsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: groupsideventsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: groupsideventsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /me/calendar/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: mecalendareventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: mecalendareventsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: mecalendareventsid-patch
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
      - Event
  /users/{id | userPrincipalName}/calendar/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: usersid--userprincipalnamecalendareventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: usersid--userprincipalnamecalendareventsid-get
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
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: usersid--userprincipalnamecalendareventsid-patch
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
      - Event
  /groups/{id}/calendar/events/{id}/:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: groupsidcalendareventsid-delete
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
      - Event
  /me/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: mecalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: mecalendarsideventsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: mecalendarsideventsid-patch
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
      - Event
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsid-get
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
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsid-patch
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
      - Event
  /me/calendargroup/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: mecalendargroupcalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: mecalendargroupcalendarsideventsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: mecalendargroupcalendarsideventsid-patch
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
      - Event
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsid-get
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
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsid-patch
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
      - Event
  /me/calendargroups/{id}/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: mecalendargroupsidcalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: mecalendargroupsidcalendarsideventsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: mecalendargroupsidcalendarsideventsid-patch
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
      - Event
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}:
    delete:
      summary: Delete Event
      description: Delete event Delete event.
      operationId: DeleteEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsid-delete
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
      - Event
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsid-get
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
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsid-patch
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
      - Event
  /me/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: meeventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnameeventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /me/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendareventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsidcalendareventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /me/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /me/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupcalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /me/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsiddismissreminder-post
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
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/calendar/events/{id}:
    get:
      summary: Get Event
      description: Get event Get the properties and relationships of the specified
        event object.
      operationId: GetEvent
      x-api-path-slug: groupsidcalendareventsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
    patch:
      summary: Update Event
      description: Update event Update the properties of event object.
      operationId: UpdateEvent
      x-api-path-slug: groupsidcalendareventsid-patch
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
      - Event
  /me/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: meeventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: meeventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnameeventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnameeventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /groups/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: groupsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: groupsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendar/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: mecalendareventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: mecalendareventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendar/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamecalendareventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamecalendareventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /groups/{id}/calendar/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: groupsidcalendareventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: groupsidcalendareventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: mecalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: mecalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /me/calendargroup/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: mecalendargroupcalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: mecalendargroupcalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /me/calendargroups/{id}/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: mecalendargroupsidcalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: mecalendargroupsidcalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to an event. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /me/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: meeventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /users/{id | userPrincipalName}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: usersid--userprincipalnameeventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /groups/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: groupsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /me/calendar/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: mecalendareventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /users/{id | userPrincipalName}/calendar/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: usersid--userprincipalnamecalendareventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /groups/{id}/calendar/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: groupsidcalendareventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /me/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: mecalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /me/calendargroup/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: mecalendargroupcalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /me/calendargroups/{id}/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: mecalendargroupsidcalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/instances:
    get:
      summary: List Instances
      description: List instances Get the instances (occurrences) of an event for
        a specified time range. If the event is a SeriesMaster type, this returns
        the occurrences and exceptions of the event in the specified time range.
      operationId: ListInstances
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidinstances-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
        type: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Instances
  /me/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: meeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnameeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Snooze
      - Reminder
  /groups/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Snooze
      - Reminder
  /groups/{id}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsidcalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Snooze
      - Reminder
  /me/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Snooze
      - Reminder
  /me/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Snooze
      - Reminder
  /me/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: meeventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnameeventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Tentatively
      - Accept
  /groups/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: groupsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /me/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Tentatively
      - Accept
  /groups/{id}/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: groupsidcalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /me/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Tentatively
      - Accept
  /me/calendargroup/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendargroupcalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Tentatively
      - Accept
  /me/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendargroupsidcalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Event
      - Tentatively
      - Accept
  /me/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: memessagesid-delete
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
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: memessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: memessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-delete
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
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-get
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
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
  /me/mailFolders/{id}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: memailfoldersidmessagesid-delete
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
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: memailfoldersidmessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: memailfoldersidmessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
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
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
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
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
  /me/messages/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: memessagesidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: memessagesidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/messages/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamemessagesidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamemessagesidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply:
    post:
      summary: Filter Apply
      description: 'Filter: apply Apply the given filter criteria on the given column.'
      operationId: Filter:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtfilterapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply:
    post:
      summary: Filter Apply
      description: 'Filter: apply Apply the given filter criteria on the given column.'
      operationId: Filter:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Apply
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear:
    post:
      summary: Filter Clear
      description: 'Filter: clear Clear the filter on the given column.'
      operationId: Filter:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear:
    post:
      summary: Filter Clear
      description: 'Filter: clear Clear the filter on the given column.'
      operationId: Filter:Clear
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Clear
  /workbook/names(&lt;name&gt;)/range/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbooknamesltnamegtrangeformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
    patch:
      summary: Update Formatprotection
      description: Update formatprotection Update the properties of formatprotection
        object.
      operationId: UpdateFormatprotection
      x-api-path-slug: workbooknamesltnamegtrangeformatprotection-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Formatprotection
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
    patch:
      summary: Update Formatprotection
      description: Update formatprotection Update the properties of formatprotection
        object.
      operationId: UpdateFormatprotection
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatprotection-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Formatprotection
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
    patch:
      summary: Update Formatprotection
      description: Update formatprotection Update the properties of formatprotection
        object.
      operationId: UpdateFormatprotection
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Formatprotection
  /groups/{id}/addFavorite:
    post:
      summary: Group Add Favorite
      description: 'group: addFavorite Add the group to the list of the current user''s
        favorite groups. Supported for only Office 365 groups.'
      operationId: Group:AddFavorite
      x-api-path-slug: groupsidaddfavorite-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - ""
      - Favorite
  /groups/{id}:
    delete:
      summary: Delete Group
      description: Delete group Delete group.
      operationId: DeleteGroup
      x-api-path-slug: groupsid-delete
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
      - Group
    get:
      summary: Get Group
      description: Get group Get the properties and relationships of a group object.
      operationId: GetGroup
      x-api-path-slug: groupsid-get
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
      - Group
    patch:
      summary: Update Group
      description: Update group Update the properties of a group object.
      operationId: UpdateGroup
      x-api-path-slug: groupsid-patch
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
      - Group
  /groups/{id}/acceptedSenders/$ref:
    delete:
      summary: Remove Accepted Sender
      description: Remove acceptedSender Remove a user or group from the acceptedSenders
        list.
      operationId: RemoveAcceptedSender
      x-api-path-slug: groupsidacceptedsendersref-delete
      parameters:
      - in: query
        name: $id
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: query
        name: gt;
        type: string
      - in: path
        name: id
        type: string
      - in: query
        name: lt;id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Accepted
      - Sender
    post:
      summary: Create Accepted Sender
      description: Create acceptedSender Add a new user or group to the acceptedSender
        list.
      operationId: CreateAcceptedSender
      x-api-path-slug: groupsidacceptedsendersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accepted
      - Sender
  /groups/{id}/members/{id}/$ref:
    delete:
      summary: Remove Member
      description: Remove member Use this API to remove a member from an Office 365
        group, a security group or a mail-enabled security group through the members
        navigation property. You can remove users or other groups.
      operationId: RemoveMember
      x-api-path-slug: groupsidmembersidref-delete
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
      - Remove
      - Member
  /groups/{id}/owners/{id}/$ref:
    delete:
      summary: Remove Owner
      description: Remove owner Use this API to remove an owner from an Office 365
        group, a security group or a mail-enabled security group through the owners
        navigation property.
      operationId: RemoveOwner
      x-api-path-slug: groupsidownersidref-delete
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
      - Remove
      - Owner
  /groups/{id}/rejectedSenders/$ref:
    delete:
      summary: Remove Rejected Sender
      description: Remove rejectedSender Remove a user or group from the rejectedSenders
        list.
      operationId: RemoveRejectedSender
      x-api-path-slug: groupsidrejectedsendersref-delete
      parameters:
      - in: query
        name: $id
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: query
        name: gt;
        type: string
      - in: path
        name: id
        type: string
      - in: query
        name: lt;id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Rejected
      - Sender
    post:
      summary: Create Rejected Sender
      description: Create rejectedSender Add a new user or group to the rejectedSender
        list.
      operationId: CreateRejectedSender
      x-api-path-slug: groupsidrejectedsendersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rejected
      - Sender
  /groups/{id}/getMemberObjects:
    post:
      summary: Group Get Member Objects
      description: 'group: getMemberObjects Return all of the groups that this group
        is a member of. The check is transitive. Note: Groups cannot be members of
        directory roles, so no directory roles will be returned.'
      operationId: Group:GetMemberObjects
      x-api-path-slug: groupsidgetmemberobjects-post
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
      - Group
      - ""
      - Member
      - Objects
  /groups:
    get:
      summary: List Groups
      description: List groups List all the groups available in an organization, including
        but not limited to Office 365 Groups. The default properties of each group
        are returned.
      operationId: ListGroups
      x-api-path-slug: groups-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Groups
    post:
      summary: Create Group
      description: 'Create group Use this API to create a new group as specified in
        the request body. You can create one of 3 types of groups:'
      operationId: CreateGroup
      x-api-path-slug: groups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
  /groups/{id}/acceptedSenders:
    get:
      summary: List Accepted Senders
      description: List acceptedSenders Get a list of users or groups that are in
        the acceptedSenders list for this group.
      operationId: ListAcceptedSenders
      x-api-path-slug: groupsidacceptedsenders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Accepted
      - Senders
  /groups/{id}/calendarView:
    get:
      summary: List Calendar View
      description: List calendarView Get the occurrences, exceptions, and single instances
        of events in a calendar view defined by a time range, from the default calendar
        of a group.
      operationId: ListCalendarView
      x-api-path-slug: groupsidcalendarview-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: query
        name: endDateTime
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: Prefer
        description: string
      - in: query
        name: startDateTime
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Calendar
      - View
  /groups/{id}/conversations:
    get:
      summary: List Conversations
      description: List conversations Retrieve the list of conversations in this group.
      operationId: ListConversations
      x-api-path-slug: groupsidconversations-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Conversations
    post:
      summary: Create Conversation
      description: Create Conversation Create a new conversation by including a thread
        and a post.
      operationId: CreateConversation
      x-api-path-slug: groupsidconversations-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Conversation
  /groups/{id}/events:
    get:
      summary: List Events
      description: List events Retrieve a list of event objects.
      operationId: ListEvents
      x-api-path-slug: groupsidevents-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Events
    post:
      summary: Create Event
      description: Create Event Use this API to create a new event.
      operationId: CreateEvent
      x-api-path-slug: groupsidevents-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
  /groups/{id}/memberOf:
    get:
      summary: List Member Of
      description: List memberOf Get groups that the group is a direct member of.
      operationId: ListMemberOf
      x-api-path-slug: groupsidmemberof-get
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
      - Member
      - Of
  /groups/{id}/members:
    get:
      summary: List Members
      description: List members Get a list of the group's direct members. A group
        can have users, contacts, and other groups as members. This operation is not
        transitive.
      operationId: ListMembers
      x-api-path-slug: groupsidmembers-get
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
      - Members
  /groups/{id}/owners:
    get:
      summary: List Owners
      description: List owners Retrieve a list of the group's owners. The owners are
        a set of non-admin users who are allowed to modify the group object.
      operationId: ListOwners
      x-api-path-slug: groupsidowners-get
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
      - Owners
  /groups/{id}/rejectedSenders:
    get:
      summary: List Rejected Senders
      description: List rejectedSenders Get a list of users or groups that are in
        the rejectedSenders list for this group.
      operationId: ListRejectedSenders
      x-api-path-slug: groupsidrejectedsenders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Rejected
      - Senders
  /groups/{id}/threads:
    get:
      summary: List Threads
      description: List threads Get all the threads of a group.
      operationId: ListThreads
      x-api-path-slug: groupsidthreads-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Threads
    post:
      summary: Create Thread
      description: Create thread Start a new conversation by first creating a thread.
      operationId: CreateThread
      x-api-path-slug: groupsidthreads-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thread
  /groups/{id}/members/$ref:
    post:
      summary: Add Member
      description: 'Add member Use this API to add a member to an Office 365 group,
        a security group or a mail-enabled security group through the members navigation
        property. You can add users or other groups. Important: You can add only users
        to Office 365 groups.'
      operationId: AddMember
      x-api-path-slug: groupsidmembersref-post
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
      - Member
  /groups/{id}/owners/$ref:
    post:
      summary: Add Group Owner
      description: Add group owner Add a user to the group's owners. The owners are
        a set of non-admin users who are allowed to modify the group object.
      operationId: AddGroupOwner
      x-api-path-slug: groupsidownersref-post
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
      - Group
      - Owner
  /groups/{id}/removeFavorite:
    post:
      summary: Group Remove Favorite
      description: 'group: removeFavorite Remove the group from the list of the current
        user''s favorite groups. Supported for only Office 365 groups.'
      operationId: Group:RemoveFavorite
      x-api-path-slug: groupsidremovefavorite-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Remove
      - Favorite
  /groups/{id}/resetUnseenCount:
    post:
      summary: Group Reset Unseen Count
      description: 'group: resetUnseenCount Reset the unseenCount of all the posts
        that the current user has not seen since their last visit. Supported for only
        Office 365 groups.'
      operationId: Group:ResetUnseenCount
      x-api-path-slug: groupsidresetunseencount-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Reset
      - Unseen
      - Count
  /groups/{id}/subscribeByMail:
    post:
      summary: Group Subscribe By Mail
      description: 'group: subscribeByMail Calling this method will enable the current
        user to receive email notifications for this group, about new posts, events,
        and files in that group. Supported for only Office 365 groups.'
      operationId: Group:SubscribeByMail
      x-api-path-slug: groupsidsubscribebymail-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - SubscribeMail
  /groups/{id}/unsubscribeByMail:
    post:
      summary: Group Unsubscribe By Mail
      description: 'group: unsubscribeByMail Calling this method will prevent the
        current user from receiving email notifications for this group about new posts,
        events, and files in that group. Supported for only Office 365 groups.'
      operationId: Group:UnsubscribeByMail
      x-api-path-slug: groupsidunsubscribebymail-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - UnsubscribeMail
  /workbook/tables(&lt;id|name&gt;)/sort/fields/icon:
    get:
      summary: Get Icon
      description: Get Icon Retrieve the properties and relationships of icon object.
      operationId: GetIcon
      x-api-path-slug: workbooktablesltidnamegtsortfieldsicon-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
    patch:
      summary: Update Icon
      description: Update icon Update the properties of icon object.
      operationId: UpdateIcon
      x-api-path-slug: workbooktablesltidnamegtsortfieldsicon-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon:
    get:
      summary: Get Icon
      description: Get Icon Retrieve the properties and relationships of icon object.
      operationId: GetIcon
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
    patch:
      summary: Update Icon
      description: Update icon Update the properties of icon object.
      operationId: UpdateIcon
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
  /me/inferenceClassification/overrides:
    get:
      summary: List Overrides
      description: List overrides Get the overrides that a user has set up to always
        classify messages from certain senders in specific ways.
      operationId: ListOverrides
      x-api-path-slug: meinferenceclassificationoverrides-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Overrides
    post:
      summary: Create Inference Classification Override
      description: Create inferenceClassificationOverride Create an override for a
        sender identified by an SMTP address. Future messages from that SMTP address
        will be consistently classified as specified in the override.
      operationId: CreateInferenceClassificationOverride
      x-api-path-slug: meinferenceclassificationoverrides-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      responses:
        200:
          description: OK
      tags:
      - Inference
      - Classification
      - Override
  /users/{id}/inferenceClassification/overrides:
    get:
      summary: List Overrides
      description: List overrides Get the overrides that a user has set up to always
        classify messages from certain senders in specific ways.
      operationId: ListOverrides
      x-api-path-slug: usersidinferenceclassificationoverrides-get
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
      - Overrides
    post:
      summary: Create Inference Classification Override
      description: Create inferenceClassificationOverride Create an override for a
        sender identified by an SMTP address. Future messages from that SMTP address
        will be consistently classified as specified in the override.
      operationId: CreateInferenceClassificationOverride
      x-api-path-slug: usersidinferenceclassificationoverrides-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Inference
      - Classification
      - Override
  /me/inferenceClassification/overrides/{id}:
    delete:
      summary: Delete Inference Classification Override
      description: Delete inferenceClassificationOverride Delete an override specified
        by its ID.
      operationId: DeleteInferenceClassificationOverride
      x-api-path-slug: meinferenceclassificationoverridesid-delete
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
      - Inference
      - Classification
      - Override
    patch:
      summary: Update Inferenceclassificationoverride
      description: Update inferenceclassificationoverride Change the classifyAs field
        of an override as specified.
      operationId: UpdateInferenceclassificationoverride
      x-api-path-slug: meinferenceclassificationoverridesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Inferenceclassificationoverride
  /users/{id}/inferenceClassification/overrides/{id}:
    delete:
      summary: Delete Inference Classification Override
      description: Delete inferenceClassificationOverride Delete an override specified
        by its ID.
      operationId: DeleteInferenceClassificationOverride
      x-api-path-slug: usersidinferenceclassificationoverridesid-delete
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
      - Inference
      - Classification
      - Override
    patch:
      summary: Update Inferenceclassificationoverride
      description: Update inferenceclassificationoverride Change the classifyAs field
        of an override as specified.
      operationId: UpdateInferenceclassificationoverride
      x-api-path-slug: usersidinferenceclassificationoverridesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Inferenceclassificationoverride
  /me/drive/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: medriveitemsitemidcreatelink-post
      parameters:
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
  /me/drive/root:/{item-path}:/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: medriverootitempathcreatelink-post
      parameters:
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
  /groups/{group-id}/drive/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemidcreatelink-post
      parameters:
      - in: path
        name: group-id
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
  /drives/{drive-id}/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: drivesdriveiditemsitemidcreatelink-post
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
  /me/drive/root/delta:
    get:
      summary: Track Changes For A Drive
      description: Track changes for a Drive This method allows your app to track
        changes to a drive and its children over time.
      operationId: TrackChangesForADrive
      x-api-path-slug: medriverootdelta-get
      responses:
        200:
          description: OK
      tags:
      - Track
      - Changes
      - Drive
  /drives/{drive-id}/root/delta:
    get:
      summary: Track Changes For A Drive
      description: Track changes for a Drive This method allows your app to track
        changes to a drive and its children over time.
      operationId: TrackChangesForADrive
      x-api-path-slug: drivesdriveidrootdelta-get
      parameters:
      - in: path
        name: drive-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Track
      - Changes
      - Drive
  /groups/{group-id}/drive/root/delta:
    get:
      summary: Track Changes For A Drive
      description: Track changes for a Drive This method allows your app to track
        changes to a drive and its children over time.
      operationId: TrackChangesForADrive
      x-api-path-slug: groupsgroupiddriverootdelta-get
      parameters:
      - in: path
        name: group-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Track
      - Changes
      - Drive
  /me/drive/root:/{item-path}:/content:
    get:
      summary: Download The Contents Of A Drive Item
      description: Download the contents of a DriveItem Download the contents for
        a driveItem. Only driveItem with the file property can be downloaded.
      operationId: DownloadTheContentsOfADriveItem
      x-api-path-slug: medriverootitempathcontent-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - DownloadContents
      - OfDrive
      - Item
  /me/drive/items/{item-id}/content:
    get:
      summary: Download The Contents Of A Drive Item
      description: Download the contents of a DriveItem Download the contents for
        a driveItem. Only driveItem with the file property can be downloaded.
      operationId: DownloadTheContentsOfADriveItem
      x-api-path-slug: medriveitemsitemidcontent-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - DownloadContents
      - OfDrive
      - Item
  /drives/items/{item-id}/content:
    get:
      summary: Download The Contents Of A Drive Item
      description: Download the contents of a DriveItem Download the contents for
        a driveItem. Only driveItem with the file property can be downloaded.
      operationId: DownloadTheContentsOfADriveItem
      x-api-path-slug: drivesitemsitemidcontent-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - DownloadContents
      - OfDrive
      - Item
  /groups/{group-id}/drive/items/{item-id}/content:
    get:
      summary: Download The Contents Of A Drive Item
      description: Download the contents of a DriveItem Download the contents for
        a driveItem. Only driveItem with the file property can be downloaded.
      operationId: DownloadTheContentsOfADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemidcontent-get
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - DownloadContents
      - OfDrive
      - Item
  /me/drive/items/{item-id}:
    get:
      summary: Get A Drive Item Resource
      description: Get a DriveItem resource Retrieve the metadata for a DriveItem
        in a Drive by file system path or ID.
      operationId: GetADriveItemResource
      x-api-path-slug: medriveitemsitemid-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Resource
    patch:
      summary: Update Drive Item Properties
      description: Update DriveItem properties Update the metadata for a DriveItem
        by ID or path.
      operationId: UpdateDriveItemProperties
      x-api-path-slug: medriveitemsitemid-patch
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current eTag on the folder, a 412 Precondition Failed
          response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Properties
  /me/drive/root:/{item-path}:
    get:
      summary: Get A Drive Item Resource
      description: Get a DriveItem resource Retrieve the metadata for a DriveItem
        in a Drive by file system path or ID.
      operationId: GetADriveItemResource
      x-api-path-slug: medriverootitempath-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Resource
    patch:
      summary: Update Drive Item Properties
      description: Update DriveItem properties Update the metadata for a DriveItem
        by ID or path.
      operationId: UpdateDriveItemProperties
      x-api-path-slug: medriverootitempath-patch
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current eTag on the folder, a 412 Precondition Failed
          response is returned
        type: string
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Properties
  /drives/{drive-id}/items/{item-id}:
    get:
      summary: Get A Drive Item Resource
      description: Get a DriveItem resource Retrieve the metadata for a DriveItem
        in a Drive by file system path or ID.
      operationId: GetADriveItemResource
      x-api-path-slug: drivesdriveiditemsitemid-get
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Resource
    patch:
      summary: Update Drive Item Properties
      description: Update DriveItem properties Update the metadata for a DriveItem
        by ID or path.
      operationId: UpdateDriveItemProperties
      x-api-path-slug: drivesdriveiditemsitemid-patch
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current eTag on the folder, a 412 Precondition Failed
          response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Properties
  /groups/{group-id}/drive/items/{item-id}:
    get:
      summary: List Children Of A Drive Item
      description: List children of a driveItem Return a collection of DriveItems
        in the children relationship of a DriveItem.
      operationId: ListChildrenOfADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemid-get
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Children
      - OfDrive
      - Item
    patch:
      summary: Update Drive Item Properties
      description: Update DriveItem properties Update the metadata for a DriveItem
        by ID or path.
      operationId: UpdateDriveItemProperties
      x-api-path-slug: groupsgroupiddriveitemsitemid-patch
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current eTag on the folder, a 412 Precondition Failed
          response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive
      - Item
      - Properties
  /me/drive/items/{item-id}/invite:
    post:
      summary: Send A Sharing Invitation
      description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
        A sharing invitation provides permissions to the recipients and optionally
        sends an email to the recipients to notify them the item was shared.
      operationId: SendASharingInvitation
      x-api-path-slug: medriveitemsitemidinvite-post
      parameters:
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - SendSharing
      - Invitation
  /drive/items/{item-id}/invite:
    post:
      summary: Send A Sharing Invitation
      description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
        A sharing invitation provides permissions to the recipients and optionally
        sends an email to the recipients to notify them the item was shared.
      operationId: SendASharingInvitation
      x-api-path-slug: driveitemsitemidinvite-post
      parameters:
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - SendSharing
      - Invitation
  /drives/{drive-id}/items/{item-id}/invite:
    post:
      summary: Send A Sharing Invitation
      description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
        A sharing invitation provides permissions to the recipients and optionally
        sends an email to the recipients to notify them the item was shared.
      operationId: SendASharingInvitation
      x-api-path-slug: drivesdriveiditemsitemidinvite-post
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - SendSharing
      - Invitation
  /groups/{group-id}/drive/items/{item-id}/invite:
    post:
      summary: Send A Sharing Invitation
      description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
        A sharing invitation provides permissions to the recipients and optionally
        sends an email to the recipients to notify them the item was shared.
      operationId: SendASharingInvitation
      x-api-path-slug: groupsgroupiddriveitemsitemidinvite-post
      parameters:
      - in: path
        name: group-id
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - SendSharing
      - Invitation
  /me/drive/root/children:
    get:
      summary: List Children Of A Drive Item
      description: List children of a driveItem Return a collection of DriveItems
        in the children relationship of a DriveItem.
      operationId: ListChildrenOfADriveItem
      x-api-path-slug: medriverootchildren-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Children
      - OfDrive
      - Item
    post:
      summary: Create A New Folder
      description: Create a new folder Create a new folder or DriveItem in a Drive
        with a specified parent item or path.
      operationId: CreateANewFolder
      x-api-path-slug: medriverootchildren-post
      responses:
        200:
          description: OK
      tags:
      - CreateNew
      - Folder
  /me/drive/items/{item-id}/children:
    get:
      summary: List Children Of A Drive Item
      description: List children of a driveItem Return a collection of DriveItems
        in the children relationship of a DriveItem.
      operationId: ListChildrenOfADriveItem
      x-api-path-slug: medriveitemsitemidchildren-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Children
      - OfDrive
      - Item
  /me/drive/root:/{item-path}:/children:
    get:
      summary: List Children Of A Drive Item
      description: List children of a driveItem Return a collection of DriveItems
        in the children relationship of a DriveItem.
      operationId: ListChildrenOfADriveItem
      x-api-path-slug: medriverootitempathchildren-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Children
      - OfDrive
      - Item
  /drives/{drive-id}/items/{item-id}/children:
    get:
      summary: List Children Of A Drive Item
      description: List children of a driveItem Return a collection of DriveItems
        in the children relationship of a DriveItem.
      operationId: ListChildrenOfADriveItem
      x-api-path-slug: drivesdriveiditemsitemidchildren-get
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the eTag (or cTag) provided
          matches the current tag on the file, an HTTP 304 Not Modified response is
          returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Children
      - OfDrive
      - Item
  /me/drive/items/{item-id}/permissions:
    get:
      summary: List Permissions On A Drive Item
      description: List permissions on a DriveItem List the effective permissions
        of on a DriveItem.
      operationId: ListPermissionsOnADriveItem
      x-api-path-slug: medriveitemsitemidpermissions-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the etag provided matches
          the current etag on the item, an HTTP 304 Not Modified response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Permissions
      - OnDrive
      - Item
  /me/drive/root:/{path}:/permissions:
    get:
      summary: List Permissions On A Drive Item
      description: List permissions on a DriveItem List the effective permissions
        of on a DriveItem.
      operationId: ListPermissionsOnADriveItem
      x-api-path-slug: medriverootpathpermissions-get
      parameters:
      - in: header
        name: if-none-match
        description: If this request header is included and the etag provided matches
          the current etag on the item, an HTTP 304 Not Modified response is returned
        type: string
      - in: path
        name: path
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Permissions
      - OnDrive
      - Item
  /drives/{drive-id}/items/{item-id}/permissions:
    get:
      summary: List Permissions On A Drive Item
      description: List permissions on a DriveItem List the effective permissions
        of on a DriveItem.
      operationId: ListPermissionsOnADriveItem
      x-api-path-slug: drivesdriveiditemsitemidpermissions-get
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the etag provided matches
          the current etag on the item, an HTTP 304 Not Modified response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Permissions
      - OnDrive
      - Item
  /groups/{group-id}/drive/items/{item-id}/permissions:
    get:
      summary: List Permissions On A Drive Item
      description: List permissions on a DriveItem List the effective permissions
        of on a DriveItem.
      operationId: ListPermissionsOnADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemidpermissions-get
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-none-match
        description: If this request header is included and the etag provided matches
          the current etag on the item, an HTTP 304 Not Modified response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Permissions
      - OnDrive
      - Item
  /me/drive/root:/{item-path}:/thumbnails:
    get:
      summary: List Thumbnails For A Drive Item
      description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
        resources for a DriveItem resource.
      operationId: ListThumbnailsForADriveItem
      x-api-path-slug: medriverootitempaththumbnails-get
      parameters:
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - ThumbnailsA
      - Drive
      - Item
  /me/drive/items/{item-id}/thumbnails:
    get:
      summary: List Thumbnails For A Drive Item
      description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
        resources for a DriveItem resource.
      operationId: ListThumbnailsForADriveItem
      x-api-path-slug: medriveitemsitemidthumbnails-get
      parameters:
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - ThumbnailsA
      - Drive
      - Item
  /groups/{group-id}/drive/items/{item-id}/thumbnails:
    get:
      summary: List Thumbnails For A Drive Item
      description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
        resources for a DriveItem resource.
      operationId: ListThumbnailsForADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemidthumbnails-get
      parameters:
      - in: path
        name: group-id
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - ThumbnailsA
      - Drive
      - Item
  /groups/{group-id}/drive/{item-id}:
    patch:
      summary: Move A Drive Item
      description: Move a DriveItem To move a DriveItem to a new parent item, your
        app requests to update the parentReference of the DriveItem to move. This
        is a special case of the Update method. Your app can combine moving an item
        to a new container and updating other properties of the item into a single
        request.
      operationId: MoveADriveItem
      x-api-path-slug: groupsgroupiddriveitemid-patch
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current eTag on the folder, a 412 Precondition Failed
          response is returned
        type: string
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - MoveDrive
      - Item
  /me/drive/items/{parent-item-id}/children:
    post:
      summary: Create A New Folder
      description: Create a new folder Create a new folder or DriveItem in a Drive
        with a specified parent item or path.
      operationId: CreateANewFolder
      x-api-path-slug: medriveitemsparentitemidchildren-post
      parameters:
      - in: path
        name: parent-item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateNew
      - Folder
  /drives/{drive-id}/items/{parent-item-id}/children:
    post:
      summary: Create A New Folder
      description: Create a new folder Create a new folder or DriveItem in a Drive
        with a specified parent item or path.
      operationId: CreateANewFolder
      x-api-path-slug: drivesdriveiditemsparentitemidchildren-post
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: path
        name: parent-item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateNew
      - Folder
  /groups/{group-id}/drive/items/{parent-item-id}/children:
    post:
      summary: Create A New Folder
      description: Create a new folder Create a new folder or DriveItem in a Drive
        with a specified parent item or path.
      operationId: CreateANewFolder
      x-api-path-slug: groupsgroupiddriveitemsparentitemidchildren-post
      parameters:
      - in: path
        name: group-id
        type: string
      - in: path
        name: parent-item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateNew
      - Folder
  /me/drive/items/{parent-id}:/{filename}:/content:
    put:
      summary: Upload Or Replace The Contents Of A Drive Item
      description: Upload or replace the contents of a driveItem The simple upload
        API allows you to provide the contents of a new file or update the contents
        of an existing file in a single API call. This method only supports files
        up to 4MB in size.
      operationId: UploadOrReplaceTheContentsOfADriveItem
      x-api-path-slug: medriveitemsparentidfilenamecontent-put
      parameters:
      - in: path
        name: filename
        type: string
      - in: path
        name: parent-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Or
      - ReplaceContents
      - OfDrive
      - Item
  /me/drive/root:/{parent-path}/{filename}:/content:
    put:
      summary: Upload Or Replace The Contents Of A Drive Item
      description: Upload or replace the contents of a driveItem The simple upload
        API allows you to provide the contents of a new file or update the contents
        of an existing file in a single API call. This method only supports files
        up to 4MB in size.
      operationId: UploadOrReplaceTheContentsOfADriveItem
      x-api-path-slug: medriverootparentpathfilenamecontent-put
      parameters:
      - in: path
        name: filename
        type: string
      - in: path
        name: parent-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Or
      - ReplaceContents
      - OfDrive
      - Item
  /me/drive/items/{parent-id}/children/{filename}/content:
    put:
      summary: Upload Or Replace The Contents Of A Drive Item
      description: Upload or replace the contents of a driveItem The simple upload
        API allows you to provide the contents of a new file or update the contents
        of an existing file in a single API call. This method only supports files
        up to 4MB in size.
      operationId: UploadOrReplaceTheContentsOfADriveItem
      x-api-path-slug: medriveitemsparentidchildrenfilenamecontent-put
      parameters:
      - in: path
        name: filename
        type: string
      - in: path
        name: parent-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Or
      - ReplaceContents
      - OfDrive
      - Item
  /groups/{id}/drive/items/{parent-id}/children/{filename}/content:
    put:
      summary: Upload Or Replace The Contents Of A Drive Item
      description: Upload or replace the contents of a driveItem The simple upload
        API allows you to provide the contents of a new file or update the contents
        of an existing file in a single API call. This method only supports files
        up to 4MB in size.
      operationId: UploadOrReplaceTheContentsOfADriveItem
      x-api-path-slug: groupsiddriveitemsparentidchildrenfilenamecontent-put
      parameters:
      - in: path
        name: filename
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: parent-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Or
      - ReplaceContents
      - OfDrive
      - Item
  /me/mailFolders/{id}/copy:
    post:
      summary: Mail Folder Copy
      description: 'mailFolder: copy Copy a mailfolder and its contents to another
        mailfolder.'
      operationId: MailFolder:Copy
      x-api-path-slug: memailfoldersidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mail
      - Folder
      - Copy
  /users/{id | userPrincipalName}/mailFolders/{id}/copy:
    post:
      summary: Mail Folder Copy
      description: 'mailFolder: copy Copy a mailfolder and its contents to another
        mailfolder.'
      operationId: MailFolder:Copy
      x-api-path-slug: usersid--userprincipalnamemailfoldersidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Mail
      - Folder
      - Copy
  /me/mailFolders/{id}:
    delete:
      summary: Delete Mail Folder
      description: Delete mailFolder Delete mailFolder.
      operationId: DeleteMailFolder
      x-api-path-slug: memailfoldersid-delete
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
      - Mail
      - Folder
    get:
      summary: Get Mail Folder
      description: Get mailFolder Retrieve the properties and relationships of mailfolder
        object.
      operationId: GetMailFolder
      x-api-path-slug: memailfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mail
      - Folder
    patch:
      summary: Update Mailfolder
      description: Update mailfolder Update the properties of mailfolder object.
      operationId: UpdateMailfolder
      x-api-path-slug: memailfoldersid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mailfolder
  /users/{id | userPrincipalName}/mailFolders/{id}:
    delete:
      summary: Delete Mail Folder
      description: Delete mailFolder Delete mailFolder.
      operationId: DeleteMailFolder
      x-api-path-slug: usersid--userprincipalnamemailfoldersid-delete
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
      - Mail
      - Folder
    get:
      summary: Get Mail Folder
      description: Get mailFolder Retrieve the properties and relationships of mailfolder
        object.
      operationId: GetMailFolder
      x-api-path-slug: usersid--userprincipalnamemailfoldersid-get
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
      - Mail
      - Folder
    patch:
      summary: Update Mailfolder
      description: Update mailfolder Update the properties of mailfolder object.
      operationId: UpdateMailfolder
      x-api-path-slug: usersid--userprincipalnamemailfoldersid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Mailfolder
  /me/mailFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get the folder collection under the specified
        folder. You can use the .../me/MailFolders shortcut to get the top-level folder
        collection and navigate to another folder.
      operationId: ListChildFolders
      x-api-path-slug: memailfoldersidchildfolders-get
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
      - Child
      - Folders
    post:
      summary: Create Mail Folder
      description: Create MailFolder Use this API to create a new child mailfolder.
      operationId: CreateMailFolder
      x-api-path-slug: memailfoldersidchildfolders-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mail
      - Folder
  /users/{id | userPrincipalName}/mailFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get the folder collection under the specified
        folder. You can use the .../me/MailFolders shortcut to get the top-level folder
        collection and navigate to another folder.
      operationId: ListChildFolders
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfolders-get
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
      - Child
      - Folders
    post:
      summary: Create Mail Folder
      description: Create MailFolder Use this API to create a new child mailfolder.
      operationId: CreateMailFolder
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfolders-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Mail
      - Folder
  /me/mailFolders/{id}/messages:
    get:
      summary: List Messages
      description: List messages Get all the messages in the signed-in user's mailbox,
        or those messages in a specified folder in the mailbox.
      operationId: ListMessages
      x-api-path-slug: memailfoldersidmessages-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Messages
    post:
      summary: Create Message
      description: Create Message Use this API to create a new Message in a mailfolder.
      operationId: CreateMessage
      x-api-path-slug: memailfoldersidmessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/mailFolders/{id}/messages:
    get:
      summary: List Messages
      description: List messages Get all the messages in the signed-in user's mailbox,
        or those messages in a specified folder in the mailbox.
      operationId: ListMessages
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessages-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Messages
    post:
      summary: Create Message
      description: Create Message Use this API to create a new Message in a mailfolder.
      operationId: CreateMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Message
  /me/mailFolders/{id}/move:
    post:
      summary: Mail Folder Move
      description: 'mailFolder: move Move a mailfolder and its contents to another
        mailfolder.'
      operationId: MailFolder:Move
      x-api-path-slug: memailfoldersidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mail
      - Folder
      - Move
  /users/{id | userPrincipalName}/mailFolders/{id}/move:
    post:
      summary: Mail Folder Move
      description: 'mailFolder: move Move a mailfolder and its contents to another
        mailfolder.'
      operationId: MailFolder:Move
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
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
      - Mail
      - Folder
      - Move
  /me/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: memessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /users/{id | userPrincipalName}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: usersid--userprincipalnamemessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Copy
  /me/mailFolders/{id}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: memailfoldersidmessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Copy
  /me/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Forward
  /me/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memailfoldersidmessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: memailfoldersidmessagesidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: memailfoldersidmessagesidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidattachments-get
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
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a message.
      operationId: AddAttachment
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
  /me/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: memessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /users/{id | userPrincipalName}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: usersid--userprincipalnamemessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Move
  /me/mailFolders/{id}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: memailfoldersidmessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Move
  /me/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /users/me/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersmemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: memailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
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
      - Message
      - Reply
  /me/messages/{id}/send:
    post:
      summary: Message Send
      description: 'message: send Send a message in the draft folder. The draft message
        can be a new message draft, reply draft, reply-all draft, or a forward draft.
        The message is then saved in the Sent Items folder.'
      operationId: Message:Send
      x-api-path-slug: memessagesidsend-post
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
      - Message
      - Send
  /users/{id | userPrincipalName}/messages/{id}/send:
    post:
      summary: Message Send
      description: 'message: send Send a message in the draft folder. The draft message
        can be a new message draft, reply draft, reply-all draft, or a forward draft.
        The message is then saved in the Sent Items folder.'
      operationId: Message:Send
      x-api-path-slug: usersid--userprincipalnamemessagesidsend-post
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
      - Message
      - Send
  /users/{id|userPrincipalName}/messages/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/mailFolders/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfoldersid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/events/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnameeventsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnameeventsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/calendars/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendarsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendarsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/contacts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}/contacts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersidcontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
    patch:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /groups/{id}/threads/{id}/posts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: groupsidthreadsidpostsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: groupsidconversationsidthreadsidpostsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /me/messages:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: memessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/messages:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /me/mailFolders:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: memailfolders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/mailFolders:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfolders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /me/events:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: meevents-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/events:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnameevents-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /me/calendars:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: mecalendars-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/calendars:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendars-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/contacts:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontacts-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /me/contactFolders:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: mecontactfolders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfolders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /groups/{id}/threads/{id}/posts/{id}/reply:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: groupsidthreadsidpostsidreply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/reply:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: groupsidconversationsidthreadsidpostsidreply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /groups/{id}/threads/{id}/reply:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: groupsidthreadsidreply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /groups/{id}/conversations/{id}/threads/{id}/reply:
    post:
      summary: Create Multi-value Extended Property
      description: Create multi-value extended property Create one or more multi-value
        extended properties in a new or existing instance of a resource.
      operationId: CreateMulti-valueExtendedProperty
      x-api-path-slug: groupsidconversationsidthreadsidreply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi-value
      - Extended
      - Property
  /workbook/names/add:
    post:
      summary: Add Named Item
      description: Add Named Item Adds a new name to the collection of the given scope
        using the user's locale for the formula.
      operationId: AddNamedItem
      x-api-path-slug: workbooknamesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer {code}
      responses:
        200:
          description: OK
      tags:
      - Named
      - Item
  /workbook/worksheets({id|name})/names/add:
    post:
      summary: Add Named Item
      description: Add Named Item Adds a new name to the collection of the given scope
        using the user's locale for the formula.
      operationId: AddNamedItem
      x-api-path-slug: workbookworksheetsidnamenamesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer {code}
      - in: path
        name: id|name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Named
      - Item
  /workbook/names(&lt;name&gt;):
    get:
      summary: Get Named Item
      description: Get NamedItem Retrieve the properties and relationships of nameditem
        object.
      operationId: GetNamedItem
      x-api-path-slug: workbooknamesltnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Named
      - Item
    patch:
      summary: Update Nameditem
      description: Update nameditem Update the properties of nameditem object.
      operationId: UpdateNameditem
      x-api-path-slug: workbooknamesltnamegt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer {code}
      responses:
        200:
          description: OK
      tags:
      - Nameditem
  /workbook/names:
    get:
      summary: List Named Item Collection
      description: List NamedItemCollection Retrieve a list of nameditem objects.
      operationId: ListNamedItemCollection
      x-api-path-slug: workbooknames-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Named
      - Item
      - Collection
  /workbook/names(&lt;name&gt;)/Range:
    post:
      summary: Named Item Range
      description: 'NamedItem: Range Returns the range object that is associated with
        the name. Throws an exception if the named item''s type is not a range.'
      operationId: NamedItem:Range
      x-api-path-slug: workbooknamesltnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Named
      - Item
      - Range
  /users/{id|userPrincipalName}/contacts/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/events/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/messages/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/events/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/threads/{id}/posts/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/messages/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/events/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/contacts/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{Id}/events/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{Id}/threads/{Id}/posts/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/messages:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessages-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/events:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnameevents-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/contacts:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontacts-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/contacts/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/events/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/messages/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/events/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: groupsideventsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/threads/{id}/posts/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /organization:
    get:
      summary: Get Organization
      description: Get organization Retrieve the properties and relationships of currently
        authenticated organization.
      operationId: GetOrganization
      x-api-path-slug: organization-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Organization
    patch:
      summary: Update Organization
      description: Update organization Update the properties of the currently authenticated
        organization.
      operationId: UpdateOrganization
      x-api-path-slug: organization-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Organization
  /me/drive/items/{item-id}/permissions/{perm-id}:
    delete:
      summary: Delete Permission
      description: Delete permission Remove access to a DriveItem.
      operationId: DeletePermission
      x-api-path-slug: medriveitemsitemidpermissionspermid-delete
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    get:
      summary: Get Permission
      description: Get permission Retrieve the properties and relationships of permission
        object.
      operationId: GetPermission
      x-api-path-slug: medriveitemsitemidpermissionspermid-get
      parameters:
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    patch:
      summary: Update Permission
      description: Update permission Update the properties of a permission by patching
        the resource.
      operationId: UpdatePermission
      x-api-path-slug: medriveitemsitemidpermissionspermid-patch
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
  /me/drive/root:/{path}:/permissions/{perm-id}:
    delete:
      summary: Delete Permission
      description: Delete permission Remove access to a DriveItem.
      operationId: DeletePermission
      x-api-path-slug: medriverootpathpermissionspermid-delete
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: path
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    get:
      summary: Get Permission
      description: Get permission Retrieve the properties and relationships of permission
        object.
      operationId: GetPermission
      x-api-path-slug: medriverootpathpermissionspermid-get
      parameters:
      - in: path
        name: path
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    patch:
      summary: Update Permission
      description: Update permission Update the properties of a permission by patching
        the resource.
      operationId: UpdatePermission
      x-api-path-slug: medriverootpathpermissionspermid-patch
      parameters:
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: path
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
  /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}:
    delete:
      summary: Delete Permission
      description: Delete permission Remove access to a DriveItem.
      operationId: DeletePermission
      x-api-path-slug: groupsgroupiddriveitemsitemidpermissionspermid-delete
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    get:
      summary: Get Permission
      description: Get permission Retrieve the properties and relationships of permission
        object.
      operationId: GetPermission
      x-api-path-slug: groupsgroupiddriveitemsitemidpermissionspermid-get
      parameters:
      - in: path
        name: group-id
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    patch:
      summary: Update Permission
      description: Update permission Update the properties of a permission by patching
        the resource.
      operationId: UpdatePermission
      x-api-path-slug: groupsgroupiddriveitemsitemidpermissionspermid-patch
      parameters:
      - in: path
        name: group-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
  /drives/{drive-id}/items/{item-id}/permissions/{perm-id}:
    delete:
      summary: Delete Permission
      description: Delete permission Remove access to a DriveItem.
      operationId: DeletePermission
      x-api-path-slug: drivesdriveiditemsitemidpermissionspermid-delete
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    get:
      summary: Get Permission
      description: Get permission Retrieve the properties and relationships of permission
        object.
      operationId: GetPermission
      x-api-path-slug: drivesdriveiditemsitemidpermissionspermid-get
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
    patch:
      summary: Update Permission
      description: Update permission Update the properties of a permission by patching
        the resource.
      operationId: UpdatePermission
      x-api-path-slug: drivesdriveiditemsitemidpermissionspermid-patch
      parameters:
      - in: path
        name: drive-id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      - in: path
        name: item-id
        type: string
      - in: path
        name: perm-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permission
  /users/{id | userPrincipalName}/photo:
    delete:
      summary: Delete Photo
      description: Delete photo Delete a photo.
      operationId: DeletePhoto
      x-api-path-slug: usersid--userprincipalnamephoto-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
    get:
      summary: Get Photo
      description: Get photo Retrieve the properties and relationships of photo object.
      operationId: GetPhoto
      x-api-path-slug: usersid--userprincipalnamephoto-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
    patch:
      summary: Update Photo
      description: Update photo Update the properties of photo object.
      operationId: UpdatePhoto
      x-api-path-slug: usersid--userprincipalnamephoto-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
  /groups/{id}/photo:
    delete:
      summary: Delete Photo
      description: Delete photo Delete a photo.
      operationId: DeletePhoto
      x-api-path-slug: groupsidphoto-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
    get:
      summary: Get Photo
      description: Get photo Retrieve the properties and relationships of photo object.
      operationId: GetPhoto
      x-api-path-slug: groupsidphoto-get
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
      - Photo
    patch:
      summary: Update Photo
      description: Update photo Update the properties of photo object.
      operationId: UpdatePhoto
      x-api-path-slug: groupsidphoto-patch
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
      - Photo
  /drive/root/createdByUser/photo:
    delete:
      summary: Delete Photo
      description: Delete photo Delete a photo.
      operationId: DeletePhoto
      x-api-path-slug: driverootcreatedbyuserphoto-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: if-match
        description: If this request header is included and the eTag (or cTag) provided
          does not match the current tag on the item, a 412 Precondition Failed response
          is returned and the item will not be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
    get:
      summary: Get Photo
      description: Get photo Retrieve the properties and relationships of photo object.
      operationId: GetPhoto
      x-api-path-slug: driverootcreatedbyuserphoto-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
    patch:
      summary: Update Photo
      description: Update photo Update the properties of photo object.
      operationId: UpdatePhoto
      x-api-path-slug: driverootcreatedbyuserphoto-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Photo
  /groups/{id}/threads/{id}/posts/{id}/forward:
    post:
      summary: Post Forward
      description: 'post: forward Forward a post to a recipient. You can specify both
        the parent conversation and thread in the request, or, you can specify just
        the parent thread without the parent conversation.'
      operationId: Post:Forward
      x-api-path-slug: groupsidthreadsidpostsidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Forward
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/forward:
    post:
      summary: Post Forward
      description: 'post: forward Forward a post to a recipient. You can specify both
        the parent conversation and thread in the request, or, you can specify just
        the parent thread without the parent conversation.'
      operationId: Post:Forward
      x-api-path-slug: groupsidconversationsidthreadsidpostsidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Forward
  /groups/{id}/threads/{id}/posts/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a post.
      operationId: ListAttachments
      x-api-path-slug: groupsidthreadsidpostsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a post. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: groupsidthreadsidpostsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a post.
      operationId: ListAttachments
      x-api-path-slug: groupsidconversationsidthreadsidpostsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
    post:
      summary: Add Attachment
      description: Add attachment Use this API to add an attachment to a post. Since
        there is currently a limit of 4MB on the total size of each REST request,
        this limits the size of the attachment you can add to under 4MB.
      operationId: AddAttachment
      x-api-path-slug: groupsidconversationsidthreadsidpostsidattachments-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /workbook/names(&lt;name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooknamesltnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/names(&lt;name&gt;)/range/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbooknamesltnamegtrangecell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/names(&lt;name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooknamesltnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/names(&lt;name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooknamesltnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/names(&lt;name&gt;)/range/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbooknamesltnamegtrangedelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/names(&lt;name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooknamesltnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/names(&lt;name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooknamesltnamegtrangeentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
  /workbook/names(&lt;name&gt;)/range/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbooknamesltnamegtrangeoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/names(&lt;name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooknamesltnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtrow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/names(&lt;name&gt;)/range/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbooknamesltnamegtrangeunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/names(&lt;name&gt;)/range:
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbooknamesltnamegtrange-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(address=&lt;range-address&gt;):
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range:
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/names(&lt;name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooknamesltnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
    patch:
      summary: Update Rangeborder
      description: Update rangeborder Update the properties of rangeborder object.
      operationId: UpdateRangeborder
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersltsideindexgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangeborder
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
    patch:
      summary: Update Rangeborder
      description: Update rangeborder Update the properties of rangeborder object.
      operationId: UpdateRangeborder
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangeborder
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
    patch:
      summary: Update Rangeborder
      description: Update rangeborder Update the properties of rangeborder object.
      operationId: UpdateRangeborder
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangeborder
  /workbook/names(&lt;name&gt;)/range/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbooknamesltnamegtrangeformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
  /workbook/names(&lt;name&gt;)/range/format/borders/ItemAt:
    post:
      summary: Range Border Collection Item At
      description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
      operationId: RangeBorderCollection:ItemAt
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders/ItemAt:
    post:
      summary: Range Border Collection Item At
      description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
      operationId: RangeBorderCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
      - Collection
      - Item
      - At
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