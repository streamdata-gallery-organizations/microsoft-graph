---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Permissions On A Drive Item
  description: List permissions on a DriveItem List the effective permissions of on
    a DriveItem.
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