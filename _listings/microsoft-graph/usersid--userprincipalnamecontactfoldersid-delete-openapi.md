---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Delete Contact Folder
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
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