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
x-alexaRank: ""
tags: Microsoft Graph
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}
  tags: List, Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}
  tags: List, Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Get Attachment
  x-api-slug: microsoft-graph-api
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachmentsid-get-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Delete calendar
    Delete a calendar other than the default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-delete-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendar-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendar-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendar-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendar-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendar-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendar-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-get-openapi.md
- name: Microsoft Graph API Get Calendar
  x-api-slug: microsoft-graph-api
  description: |-
    Get calendar
    Retrieve the properties and relationships of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: |-
    List calendarView
    Get the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,
    from the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of event objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsidevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsidevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsidevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsidevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsidevents-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of events in a calendar.  The list contains
    single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsidevents-get-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsidevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsidevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsidevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsidevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsidevents-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new Event in the default or the
    specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsidevents-post-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendar-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendar-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendar-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendar-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendar-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendar-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsid-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsid-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsid-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsid-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsid-patch-openapi.md
- name: Microsoft Graph API Update Calendar
  x-api-slug: microsoft-graph-api
  description: Update calendar Update the properties of calendar object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsid-patch-openapi.md
- name: Microsoft Graph API Delete Calendar Group
  x-api-slug: microsoft-graph-api
  description: Delete calendarGroup Delete a calendar group other than the default
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}
  tags: Calendar, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-delete-openapi.md
- name: Microsoft Graph API Delete Calendar Group
  x-api-slug: microsoft-graph-api
  description: Delete calendarGroup Delete a calendar group other than the default
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}
  tags: Calendar, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-delete-openapi.md
- name: Microsoft Graph API Get Calendar Group
  x-api-slug: microsoft-graph-api
  description: Get calendarGroup Retrieve the properties and relationships of a calendar
    group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}
  tags: Calendar, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-get-openapi.md
- name: Microsoft Graph API Get Calendar Group
  x-api-slug: microsoft-graph-api
  description: Get calendarGroup Retrieve the properties and relationships of a calendar
    group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}
  tags: Calendar, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendars-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendars-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendars-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendars-get-openapi.md
- name: Microsoft Graph API Create Calendar
  x-api-slug: microsoft-graph-api
  description: Create Calendar Use this API to create a new Calendar in a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendars-post-openapi.md
- name: Microsoft Graph API Create Calendar
  x-api-slug: microsoft-graph-api
  description: Create Calendar Use this API to create a new Calendar in a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendars-post-openapi.md
- name: Microsoft Graph API Create Calendar
  x-api-slug: microsoft-graph-api
  description: Create Calendar Use this API to create a new Calendar in a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendars-post-openapi.md
- name: Microsoft Graph API Create Calendar
  x-api-slug: microsoft-graph-api
  description: Create Calendar Use this API to create a new Calendar in a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendars-post-openapi.md
- name: Microsoft Graph API Update Calendargroup
  x-api-slug: microsoft-graph-api
  description: Update calendargroup Update the properties of calendargroup object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}
  tags: Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsid-patch-openapi.md
- name: Microsoft Graph API Update Calendargroup
  x-api-slug: microsoft-graph-api
  description: Update calendargroup Update the properties of calendargroup object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}
  tags: Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsid-patch-openapi.md
- name: Microsoft Graph API Chart Delete
  x-api-slug: microsoft-graph-api
  description: 'Chart: delete Deletes the chart object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///
  tags: Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/post-openapi.md
- name: Microsoft Graph API Get Chart
  x-api-slug: microsoft-graph-api
  description: Get Chart Retrieve the properties and relationships of chart object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///
  tags: Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/get-openapi.md
- name: Microsoft Graph API List Chart Collection
  x-api-slug: microsoft-graph-api
  description: List ChartCollection Retrieve a list of chart objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///List, , Collection
  tags: List, Chart, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/list--collection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/list--collection-get-openapi.md
- name: Microsoft Graph API List Chart Series Collection
  x-api-slug: microsoft-graph-api
  description: List ChartSeriesCollection Retrieve a list of chartseries objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///List, , Series, Collection
  tags: List, Chart, Series, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/list--series-collection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/list--series-collection-get-openapi.md
- name: Microsoft Graph API Create Chart Series
  x-api-slug: microsoft-graph-api
  description: Create ChartSeries Use this API to create a new ChartSeries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Series
  tags: Chart, Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-post-openapi.md
- name: Microsoft Graph API Chart Set Data
  x-api-slug: microsoft-graph-api
  description: 'Chart: setData Resets the source data for the chart.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Set, Data
  tags: Chart, Set, Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/set-data-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/set-data-post-openapi.md
- name: Microsoft Graph API Chart Set Position
  x-api-slug: microsoft-graph-api
  description: 'Chart: setPosition Positions the chart relative to cells on the worksheet.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Set, Position
  tags: Chart, Set, Position
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/set-position-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/set-position-post-openapi.md
- name: Microsoft Graph API Update Chart
  x-api-slug: microsoft-graph-api
  description: Update chart Update the properties of chart object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///
  tags: Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/patch-openapi.md
- name: Microsoft Graph API Get Chart Axis
  x-api-slug: microsoft-graph-api
  description: Get ChartAxis Retrieve the properties and relationships of chartaxis
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis
  tags: Chart, Axis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-openapi.md
- name: Microsoft Graph API Get Chart Axis
  x-api-slug: microsoft-graph-api
  description: Get ChartAxis Retrieve the properties and relationships of chartaxis
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis
  tags: Chart, Axis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-openapi.md
- name: Microsoft Graph API Get Chart Axis
  x-api-slug: microsoft-graph-api
  description: Get ChartAxis Retrieve the properties and relationships of chartaxis
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis
  tags: Chart, Axis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-get-openapi.md
- name: Microsoft Graph API Update Chartaxis
  x-api-slug: microsoft-graph-api
  description: Update chartaxis Update the properties of chartaxis object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axis
  tags: Chartaxis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-openapi.md
- name: Microsoft Graph API Update Chartaxis
  x-api-slug: microsoft-graph-api
  description: Update chartaxis Update the properties of chartaxis object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axis
  tags: Chartaxis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-openapi.md
- name: Microsoft Graph API Update Chartaxis
  x-api-slug: microsoft-graph-api
  description: Update chartaxis Update the properties of chartaxis object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axis
  tags: Chartaxis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-patch-openapi.md
- name: Microsoft Graph API Get Chart Axis Title
  x-api-slug: microsoft-graph-api
  description: Get ChartAxisTitle Retrieve the properties and relationships of chartaxistitle
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis, Title
  tags: Chart, Axis, Title
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-openapi.md
- name: Microsoft Graph API Get Chart Axis Title
  x-api-slug: microsoft-graph-api
  description: Get ChartAxisTitle Retrieve the properties and relationships of chartaxistitle
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis, Title
  tags: Chart, Axis, Title
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-openapi.md
- name: Microsoft Graph API Get Chart Axis Title
  x-api-slug: microsoft-graph-api
  description: Get ChartAxisTitle Retrieve the properties and relationships of chartaxistitle
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Axis, Title
  tags: Chart, Axis, Title
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axis-title-get-openapi.md
- name: Microsoft Graph API Update Chartaxistitle
  x-api-slug: microsoft-graph-api
  description: Update chartaxistitle Update the properties of chartaxistitle object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axistitle
  tags: Chartaxistitle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-openapi.md
- name: Microsoft Graph API Update Chartaxistitle
  x-api-slug: microsoft-graph-api
  description: Update chartaxistitle Update the properties of chartaxistitle object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axistitle
  tags: Chartaxistitle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-openapi.md
- name: Microsoft Graph API Update Chartaxistitle
  x-api-slug: microsoft-graph-api
  description: Update chartaxistitle Update the properties of chartaxistitle object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///axistitle
  tags: Chartaxistitle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/axistitle-patch-openapi.md
- name: Microsoft Graph API Chart Collection Add
  x-api-slug: microsoft-graph-api
  description: 'ChartCollection: add Creates a new chart.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Collection
  tags: Chart, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/collection-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/collection-post-openapi.md
- name: Microsoft Graph API Chart Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'ChartCollection: ItemAt Gets a chart based on its position in the
    collection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Collection, Item, At
  tags: Chart, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/collection-item-at-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/collection-item-at-post-openapi.md
- name: Microsoft Graph API Get Chart Data Labels
  x-api-slug: microsoft-graph-api
  description: Get ChartDataLabels Retrieve the properties and relationships of chartdatalabels
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Data, Labels
  tags: Chart, Data, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/data-labels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/data-labels-get-openapi.md
- name: Microsoft Graph API Update Chartdatalabels
  x-api-slug: microsoft-graph-api
  description: Update chartdatalabels Update the properties of chartdatalabels object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///datalabels
  tags: Chartdatalabels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/datalabels-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/datalabels-patch-openapi.md
- name: Microsoft Graph API Chart Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: clear Clear the fill color of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Clear
  tags: Chart, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-openapi.md
- name: Microsoft Graph API Chart Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: clear Clear the fill color of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Clear
  tags: Chart, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-openapi.md
- name: Microsoft Graph API Chart Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: clear Clear the fill color of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Clear
  tags: Chart, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-clear-post-openapi.md
- name: Microsoft Graph API Chart Fill Set Solid Color
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: setSolidColor Sets the fill formatting of a chart element
    to a uniform color.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Set, Solid, Color
  tags: Chart, Fill, Set, Solid, Color
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-openapi.md
- name: Microsoft Graph API Chart Fill Set Solid Color
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: setSolidColor Sets the fill formatting of a chart element
    to a uniform color.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Set, Solid, Color
  tags: Chart, Fill, Set, Solid, Color
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-openapi.md
- name: Microsoft Graph API Chart Fill Set Solid Color
  x-api-slug: microsoft-graph-api
  description: 'ChartFill: setSolidColor Sets the fill formatting of a chart element
    to a uniform color.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Fill, Set, Solid, Color
  tags: Chart, Fill, Set, Solid, Color
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/fill-set-solid-color-post-openapi.md
- name: Microsoft Graph API Get Chart Font
  x-api-slug: microsoft-graph-api
  description: Get ChartFont Retrieve the properties and relationships of chartfont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Font
  tags: Chart, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-openapi.md
- name: Microsoft Graph API Get Chart Font
  x-api-slug: microsoft-graph-api
  description: Get ChartFont Retrieve the properties and relationships of chartfont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Font
  tags: Chart, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-openapi.md
- name: Microsoft Graph API Get Chart Font
  x-api-slug: microsoft-graph-api
  description: Get ChartFont Retrieve the properties and relationships of chartfont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Font
  tags: Chart, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-get-openapi.md
- name: Microsoft Graph API Update Chartfont
  x-api-slug: microsoft-graph-api
  description: Update chartfont Update the properties of chartfont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///font
  tags: Chartfont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-openapi.md
- name: Microsoft Graph API Update Chartfont
  x-api-slug: microsoft-graph-api
  description: Update chartfont Update the properties of chartfont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///font
  tags: Chartfont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-openapi.md
- name: Microsoft Graph API Update Chartfont
  x-api-slug: microsoft-graph-api
  description: Update chartfont Update the properties of chartfont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///font
  tags: Chartfont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/font-patch-openapi.md
- name: Microsoft Graph API Get Chart Gridlines
  x-api-slug: microsoft-graph-api
  description: Get ChartGridlines Retrieve the properties and relationships of chartgridlines
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Gridlines
  tags: Chart, Gridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-openapi.md
- name: Microsoft Graph API Get Chart Gridlines
  x-api-slug: microsoft-graph-api
  description: Get ChartGridlines Retrieve the properties and relationships of chartgridlines
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Gridlines
  tags: Chart, Gridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-openapi.md
- name: Microsoft Graph API Get Chart Gridlines
  x-api-slug: microsoft-graph-api
  description: Get ChartGridlines Retrieve the properties and relationships of chartgridlines
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Gridlines
  tags: Chart, Gridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-get-openapi.md
- name: Microsoft Graph API Update Chartgridlines
  x-api-slug: microsoft-graph-api
  description: Update chartgridlines Update the properties of chartgridlines object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///gridlines
  tags: Chartgridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-openapi.md
- name: Microsoft Graph API Update Chartgridlines
  x-api-slug: microsoft-graph-api
  description: Update chartgridlines Update the properties of chartgridlines object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///gridlines
  tags: Chartgridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-openapi.md
- name: Microsoft Graph API Update Chartgridlines
  x-api-slug: microsoft-graph-api
  description: Update chartgridlines Update the properties of chartgridlines object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///gridlines
  tags: Chartgridlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/gridlines-patch-openapi.md
- name: Microsoft Graph API Get Chart Legend
  x-api-slug: microsoft-graph-api
  description: Get ChartLegend Retrieve the properties and relationships of chartlegend
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Legend
  tags: Chart, Legend
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/legend-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/legend-get-openapi.md
- name: Microsoft Graph API Update Chartlegend
  x-api-slug: microsoft-graph-api
  description: Update chartlegend Update the properties of chartlegend object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///legend
  tags: Chartlegend
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/legend-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/legend-patch-openapi.md
- name: Microsoft Graph API Chart Line Format Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartLineFormat: clear Clear the line format of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format, Clear
  tags: Chart, Line, Format, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-openapi.md
- name: Microsoft Graph API Chart Line Format Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartLineFormat: clear Clear the line format of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format, Clear
  tags: Chart, Line, Format, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-openapi.md
- name: Microsoft Graph API Chart Line Format Clear
  x-api-slug: microsoft-graph-api
  description: 'ChartLineFormat: clear Clear the line format of a chart element.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format, Clear
  tags: Chart, Line, Format, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-clear-post-openapi.md
- name: Microsoft Graph API Get Chart Line Format
  x-api-slug: microsoft-graph-api
  description: Get ChartLineFormat Retrieve the properties and relationships of chartlineformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format
  tags: Chart, Line, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-openapi.md
- name: Microsoft Graph API Get Chart Line Format
  x-api-slug: microsoft-graph-api
  description: Get ChartLineFormat Retrieve the properties and relationships of chartlineformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format
  tags: Chart, Line, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-openapi.md
- name: Microsoft Graph API Get Chart Line Format
  x-api-slug: microsoft-graph-api
  description: Get ChartLineFormat Retrieve the properties and relationships of chartlineformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Line, Format
  tags: Chart, Line, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/line-format-get-openapi.md
- name: Microsoft Graph API Update Chartlineformat
  x-api-slug: microsoft-graph-api
  description: Update chartlineformat Update the properties of chartlineformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///lineformat
  tags: Chartlineformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-openapi.md
- name: Microsoft Graph API Update Chartlineformat
  x-api-slug: microsoft-graph-api
  description: Update chartlineformat Update the properties of chartlineformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///lineformat
  tags: Chartlineformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-openapi.md
- name: Microsoft Graph API Update Chartlineformat
  x-api-slug: microsoft-graph-api
  description: Update chartlineformat Update the properties of chartlineformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///lineformat
  tags: Chartlineformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/lineformat-patch-openapi.md
- name: Microsoft Graph API Get Chart Point
  x-api-slug: microsoft-graph-api
  description: Get ChartPoint Retrieve the properties and relationships of chartpoint
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Point
  tags: Chart, Point
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/point-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/point-get-openapi.md
- name: Microsoft Graph API List Points
  x-api-slug: microsoft-graph-api
  description: List points Retrieve a list of chartpoints objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/charts(&lt;name&gt;)/series(&lt;undefined&gt;)/points
  tags: List, Points
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtchartsltnamegtseriesltundefinedgtpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtchartsltnamegtseriesltundefinedgtpoints-get-openapi.md
- name: Microsoft Graph API Chart Points Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'ChartPointsCollection: ItemAt Retrieve a point based on its position
    within the series.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Points, Collection, Item, At
  tags: Chart, Points, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/points-collection-item-at-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/points-collection-item-at-post-openapi.md
- name: Microsoft Graph API Get Chart Series
  x-api-slug: microsoft-graph-api
  description: Get ChartSeries Retrieve the properties and relationships of chartseries
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Series
  tags: Chart, Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-get-openapi.md
- name: Microsoft Graph API Create Chart Points
  x-api-slug: microsoft-graph-api
  description: Create ChartPoints Use this API to create a new ChartPoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Points
  tags: Chart, Points
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/points-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/points-post-openapi.md
- name: Microsoft Graph API Update Chartseries
  x-api-slug: microsoft-graph-api
  description: Update chartseries Update the properties of chartseries object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///series
  tags: Chartseries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-patch-openapi.md
- name: Microsoft Graph API Chart Series Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'ChartSeriesCollection: ItemAt Retrieves a series based on its position
    in the collection'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Series, Collection, Item, At
  tags: Chart, Series, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-collection-item-at-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/series-collection-item-at-post-openapi.md
- name: Microsoft Graph API Get Chart Title
  x-api-slug: microsoft-graph-api
  description: Get ChartTitle Retrieve the properties and relationships of charttitle
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///, Title
  tags: Chart, Title
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/title-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/title-get-openapi.md
- name: Microsoft Graph API Update Charttitle
  x-api-slug: microsoft-graph-api
  description: Update charttitle Update the properties of charttitle object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///title
  tags: Charttitle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/title-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/title-patch-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-delete-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolder/{id}/childFolders/{id}/.../contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API Delete Contact
  x-api-slug: microsoft-graph-api
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-get-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactfolders/{Id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactfolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolder/{id}/childFolders/{id}/.../contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API Get Contact
  x-api-slug: microsoft-graph-api
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactsid-patch-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolder/{id}/childFolders/{id}/.../contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API Update Contact
  x-api-slug: microsoft-graph-api
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts/{id}
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API Delete Contact Folder
  x-api-slug: microsoft-graph-api
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API Delete Contact Folder
  x-api-slug: microsoft-graph-api
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API Get Contact Folder
  x-api-slug: microsoft-graph-api
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API Get Contact Folder
  x-api-slug: microsoft-graph-api
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API List Child Folders
  x-api-slug: microsoft-graph-api
  description: List childFolders Get a collection of child folders under the specified
    contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/childFolders
  tags: List, Child, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API List Child Folders
  x-api-slug: microsoft-graph-api
  description: List childFolders Get a collection of child folders under the specified
    contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders
  tags: List, Child, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontacts-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API Create Contact Folder
  x-api-slug: microsoft-graph-api
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/childFolders
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API Create Contact Folder
  x-api-slug: microsoft-graph-api
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontacts-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API Delete Device
  x-api-slug: microsoft-graph-api
  description: Delete device Delete a registered device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-delete-openapi.md
- name: Microsoft Graph API Get Device
  x-api-slug: microsoft-graph-api
  description: Get device Get the properties and relationships of a device object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-get-openapi.md
- name: Microsoft Graph API List Devices
  x-api-slug: microsoft-graph-api
  description: List devices Retrieve a list of device objects registered in the organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices
  tags: List, Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devices-get-openapi.md
- name: Microsoft Graph API List Registered Owners
  x-api-slug: microsoft-graph-api
  description: List registeredOwners Retrieve a list of users that are registered
    owners of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}/registeredOwners
  tags: List, Registered, Owners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredowners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredowners-get-openapi.md
- name: Microsoft Graph API List Registered Users
  x-api-slug: microsoft-graph-api
  description: List registeredUsers Retrieve a list of users that are registered users
    of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}/registeredUsers
  tags: List, Registered, Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredusers-get-openapi.md
- name: Microsoft Graph API Create Device
  x-api-slug: microsoft-graph-api
  description: Create device Create and register a new device in the organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devices-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devices-post-openapi.md
- name: Microsoft Graph API Create Registered Owner
  x-api-slug: microsoft-graph-api
  description: Create registeredOwner Add a user as a registered owner of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}/registeredOwners
  tags: Registered, Owner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredowners-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredowners-post-openapi.md
- name: Microsoft Graph API Create Registered User
  x-api-slug: microsoft-graph-api
  description: Create registeredUser Add a registered user for the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}/registeredUsers
  tags: Registered, User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredusers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesidregisteredusers-post-openapi.md
- name: Microsoft Graph API Update Device
  x-api-slug: microsoft-graph-api
  description: Update device Update the properties of a registered device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////devices/{id}
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/devicesid-patch-openapi.md
- name: Microsoft Graph API Check Member Groups
  x-api-slug: microsoft-graph-api
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecheckmembergroups-post-openapi.md
- name: Microsoft Graph API Check Member Groups
  x-api-slug: microsoft-graph-api
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecheckmembergroups-post-openapi.md
- name: Microsoft Graph API Group Check Member Groups
  x-api-slug: microsoft-graph-api
  description: 'group: checkMemberGroups Check for membership in the specified list
    of groups. Returns from the list those groups of which the specified group has
    a direct or transitive membership.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/checkMemberGroups
  tags: Group, Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcheckmembergroups-post-openapi.md
- name: Microsoft Graph API Check Member Groups
  x-api-slug: microsoft-graph-api
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidcheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidcheckmembergroups-post-openapi.md
- name: Microsoft Graph API Delete Directory Object
  x-api-slug: microsoft-graph-api
  description: Delete directoryObject Deletes a directoryObject.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}
  tags: Directory, Object
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsid-delete-openapi.md
- name: Microsoft Graph API Get Directory Object
  x-api-slug: microsoft-graph-api
  description: Get directoryObject Retrieve the properties and relationships of directoryObject
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}
  tags: Directory, Object
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsid-get-openapi.md
- name: Microsoft Graph API Get Member Groups
  x-api-slug: microsoft-graph-api
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/megetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/megetmembergroups-post-openapi.md
- name: Microsoft Graph API Get Member Groups
  x-api-slug: microsoft-graph-api
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamegetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamegetmembergroups-post-openapi.md
- name: Microsoft Graph API Group Get Member Groups
  x-api-slug: microsoft-graph-api
  description: 'group: getMemberGroups Return all the groups that the specified group
    is a member of. The check is transitive, unlike reading the memberOf navigation
    property, which returns only the groups that the group is a direct member of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/getMemberGroups
  tags: Group, , Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidgetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidgetmembergroups-post-openapi.md
- name: Microsoft Graph API Get Member Groups
  x-api-slug: microsoft-graph-api
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidgetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidgetmembergroups-post-openapi.md
- name: Microsoft Graph API Get Member Objects
  x-api-slug: microsoft-graph-api
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/megetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/megetmemberobjects-post-openapi.md
- name: Microsoft Graph API Get Member Objects
  x-api-slug: microsoft-graph-api
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamegetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamegetmemberobjects-post-openapi.md
- name: Microsoft Graph API Get Member Objects
  x-api-slug: microsoft-graph-api
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidgetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryobjectsidgetmemberobjects-post-openapi.md
- name: Microsoft Graph API Get Directory Role
  x-api-slug: microsoft-graph-api
  description: Get directoryRole Retrieve the properties of a directoryRole object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles/{id}
  tags: Directory, Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesid-get-openapi.md
- name: Microsoft Graph API List Directory Roles
  x-api-slug: microsoft-graph-api
  description: List directoryRoles List the directory roles that are activated in
    the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles
  tags: List, Directory, Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroles-get-openapi.md
- name: Microsoft Graph API List Members
  x-api-slug: microsoft-graph-api
  description: List members Retrieve a list of the users that are assigned to the
    directory role.  Only users can be assigned to a directory role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles/{id}/members
  tags: List, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesidmembers-get-openapi.md
- name: Microsoft Graph API Activate Directory Role
  x-api-slug: microsoft-graph-api
  description: Activate directoryRole Activate a directory role. To read a directory
    role or update its members, it must first be activated in the tenant. Only the
    Company Administrators and the implicit Users directory roles are activated by
    default. To access and assign members to another directory role, you must first
    activate it with its corresponding directory role template (directoryRoleTemplate).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles
  tags: Activate, Directory, Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroles-post-openapi.md
- name: Microsoft Graph API Add Directory Role Member
  x-api-slug: microsoft-graph-api
  description: Add directory role member Use this API to create a new directory role
    member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles/{id}/members/$ref
  tags: Directory, Role, Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryrolesidmembersref-post-openapi.md
- name: Microsoft Graph API Get Directory Role Template
  x-api-slug: microsoft-graph-api
  description: Get directoryRoleTemplate Retrieve the properties and relationships
    of a directoryroletemplate object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoleTemplates/{id}
  tags: Directory, Role, Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroletemplatesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroletemplatesid-get-openapi.md
- name: Microsoft Graph API List Directory Role Templates
  x-api-slug: microsoft-graph-api
  description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
    objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoleTemplates
  tags: List, Directory, Role, Templates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroletemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/directoryroletemplates-get-openapi.md
- name: Microsoft Graph API List Available Drives
  x-api-slug: microsoft-graph-api
  description: List available drives Retrieve the list of Drive resources available
    for a target User or Group. Your app can also request the set of document libraries
    on the SharePoint root site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives
  tags: List, Available, Drives
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drives-get-openapi.md
- name: Microsoft Graph API List Available Drives
  x-api-slug: microsoft-graph-api
  description: List available drives Retrieve the list of Drive resources available
    for a target User or Group. Your app can also request the set of document libraries
    on the SharePoint root site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drives
  tags: List, Available, Drives
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medrives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medrives-get-openapi.md
- name: Microsoft Graph API List Available Drives
  x-api-slug: microsoft-graph-api
  description: List available drives Retrieve the list of Drive resources available
    for a target User or Group. Your app can also request the set of document libraries
    on the SharePoint root site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/drives
  tags: List, Available, Drives
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsiddrives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsiddrives-get-openapi.md
- name: Microsoft Graph API Get A Special Folder By Name
  x-api-slug: microsoft-graph-api
  description: Get a special folder by name Use the special collection to access a
    special folder by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/special/{name}
  tags: Special, FolderName
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medrivespecialname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medrivespecialname-get-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Accept
  x-api-slug: microsoft-graph-api
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Event Decline
  x-api-slug: microsoft-graph-api
  description: 'event: decline Decline invitation to the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/decline
  tags: Event, Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsiddecline-post-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Delete Event
  x-api-slug: microsoft-graph-api
  description: Delete event Delete event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-delete-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Event Dismiss Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder
  tags: Event, Dismiss, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsiddismissreminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsiddismissreminder-post-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-get-openapi.md
- name: Microsoft Graph API Get Event
  x-api-slug: microsoft-graph-api
  description: Get event Get the properties and relationships of the specified event
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API List Instances
  x-api-slug: microsoft-graph-api
  description: List instances Get the instances (occurrences) of an event for a specified
    time range. If the event is a SeriesMaster type, this returns the occurrences
    and exceptions of the event in the specified time range.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/instances
  tags: List, Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidinstances-get-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Snooze Reminder
  x-api-slug: microsoft-graph-api
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Event Tentatively Accept
  x-api-slug: microsoft-graph-api
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meeventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameeventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendareventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendareventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Update Event
  x-api-slug: microsoft-graph-api
  description: Update event Update the properties of event object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsid-patch-openapi.md
- name: Microsoft Graph API Delete Message
  x-api-slug: microsoft-graph-api
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
- name: Microsoft Graph API Delete Message
  x-api-slug: microsoft-graph-api
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph API Delete Message
  x-api-slug: microsoft-graph-api
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API Delete Message
  x-api-slug: microsoft-graph-api
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph API Get Message
  x-api-slug: microsoft-graph-api
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph API Get Message
  x-api-slug: microsoft-graph-api
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API Get Message
  x-api-slug: microsoft-graph-api
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API Get Message
  x-api-slug: microsoft-graph-api
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-get-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-post-openapi.md
- name: Microsoft Graph API Update Message
  x-api-slug: microsoft-graph-api
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph API Update Message
  x-api-slug: microsoft-graph-api
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API Update Message
  x-api-slug: microsoft-graph-api
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API Update Message
  x-api-slug: microsoft-graph-api
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph API Filter Apply
  x-api-slug: microsoft-graph-api
  description: 'Filter: apply Apply the given filter criteria on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply
  tags: Filter, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterapply-post-openapi.md
- name: Microsoft Graph API Filter Apply
  x-api-slug: microsoft-graph-api
  description: 'Filter: apply Apply the given filter criteria on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply
  tags: Filter, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterapply-post-openapi.md
- name: Microsoft Graph API Filter Clear
  x-api-slug: microsoft-graph-api
  description: 'Filter: clear Clear the filter on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear
  tags: Filter, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post-openapi.md
- name: Microsoft Graph API Filter Clear
  x-api-slug: microsoft-graph-api
  description: 'Filter: clear Clear the filter on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear
  tags: Filter, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post-openapi.md
- name: Microsoft Graph API Get Format Protection
  x-api-slug: microsoft-graph-api
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-get-openapi.md
- name: Microsoft Graph API Get Format Protection
  x-api-slug: microsoft-graph-api
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get-openapi.md
- name: Microsoft Graph API Get Format Protection
  x-api-slug: microsoft-graph-api
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get-openapi.md
- name: Microsoft Graph API Update Formatprotection
  x-api-slug: microsoft-graph-api
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-patch-openapi.md
- name: Microsoft Graph API Update Formatprotection
  x-api-slug: microsoft-graph-api
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-patch-openapi.md
- name: Microsoft Graph API Update Formatprotection
  x-api-slug: microsoft-graph-api
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-patch-openapi.md
- name: Microsoft Graph API Group Add Favorite
  x-api-slug: microsoft-graph-api
  description: 'group: addFavorite Add the group to the list of the current user''s
    favorite groups. Supported for only Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/addFavorite
  tags: Group, , Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidaddfavorite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidaddfavorite-post-openapi.md
- name: Microsoft Graph API Delete Group
  x-api-slug: microsoft-graph-api
  description: Delete group Delete group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}
  tags: Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-delete-openapi.md
- name: Microsoft Graph API Remove Accepted Sender
  x-api-slug: microsoft-graph-api
  description: Remove acceptedSender Remove a user or group from the acceptedSenders
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders/$ref
  tags: Remove, Accepted, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsendersref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsendersref-delete-openapi.md
- name: Microsoft Graph API Remove Member
  x-api-slug: microsoft-graph-api
  description: Remove member Use this API to remove a member from an Office 365 group,
    a security group or a mail-enabled security group through the members navigation
    property. You can remove users or other groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members/{id}/$ref
  tags: Remove, Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembersidref-delete-openapi.md
- name: Microsoft Graph API Remove Owner
  x-api-slug: microsoft-graph-api
  description: Remove owner Use this API to remove an owner from an Office 365 group,
    a security group or a mail-enabled security group through the owners navigation
    property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/owners/{id}/$ref
  tags: Remove, Owner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidownersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidownersidref-delete-openapi.md
- name: Microsoft Graph API Remove Rejected Sender
  x-api-slug: microsoft-graph-api
  description: Remove rejectedSender Remove a user or group from the rejectedSenders
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/rejectedSenders/$ref
  tags: Remove, Rejected, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsendersref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsendersref-delete-openapi.md
- name: Microsoft Graph API Get Group
  x-api-slug: microsoft-graph-api
  description: Get group Get the properties and relationships of a group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}
  tags: Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-get-openapi.md
- name: Microsoft Graph API Group Get Member Objects
  x-api-slug: microsoft-graph-api
  description: 'group: getMemberObjects Return all of the groups that this group is
    a member of. The check is transitive. Note: Groups cannot be members of directory
    roles, so no directory roles will be returned.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/getMemberObjects
  tags: Group, , Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidgetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidgetmemberobjects-post-openapi.md
- name: Microsoft Graph API List Groups
  x-api-slug: microsoft-graph-api
  description: List groups List all the groups available in an organization, including
    but not limited to Office 365 Groups. The default properties of each group are
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups
  tags: List, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groups-get-openapi.md
- name: Microsoft Graph API List Accepted Senders
  x-api-slug: microsoft-graph-api
  description: List acceptedSenders Get a list of users or groups that are in the
    acceptedSenders list for this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders
  tags: List, Accepted, Senders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsenders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsenders-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: List calendarView Get the occurrences, exceptions, and single instances
    of events in a calendar view defined by a time range, from the default calendar
    of a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidcalendarview-get-openapi.md
- name: Microsoft Graph API List Conversations
  x-api-slug: microsoft-graph-api
  description: List conversations Retrieve the list of conversations in this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations
  tags: List, Conversations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversations-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Retrieve a list of event objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events
  tags: List, Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidevents-get-openapi.md
- name: Microsoft Graph API List Member Of
  x-api-slug: microsoft-graph-api
  description: List memberOf Get groups that the group is a direct member of.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/memberOf
  tags: List, Member, Of
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmemberof-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmemberof-get-openapi.md
- name: Microsoft Graph API List Members
  x-api-slug: microsoft-graph-api
  description: List members Get a list of the group's direct members. A group can
    have users, contacts, and other groups as members. This operation is not transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members
  tags: List, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembers-get-openapi.md
- name: Microsoft Graph API List Owners
  x-api-slug: microsoft-graph-api
  description: List owners Retrieve a list of the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/owners
  tags: List, Owners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidowners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidowners-get-openapi.md
- name: Microsoft Graph API List Rejected Senders
  x-api-slug: microsoft-graph-api
  description: List rejectedSenders Get a list of users or groups that are in the
    rejectedSenders list for this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/rejectedSenders
  tags: List, Rejected, Senders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsenders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsenders-get-openapi.md
- name: Microsoft Graph API List Threads
  x-api-slug: microsoft-graph-api
  description: List threads Get all the threads of a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads
  tags: List, Threads
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreads-get-openapi.md
- name: Microsoft Graph API Create Accepted Sender
  x-api-slug: microsoft-graph-api
  description: Create acceptedSender Add a new user or group to the acceptedSender
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders/$ref
  tags: Accepted, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsendersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidacceptedsendersref-post-openapi.md
- name: Microsoft Graph API Create Conversation
  x-api-slug: microsoft-graph-api
  description: Create Conversation Create a new conversation by including a thread
    and a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations
  tags: Conversation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversations-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversations-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Use this API to create a new event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidevents-post-openapi.md
- name: Microsoft Graph API Create Group
  x-api-slug: microsoft-graph-api
  description: 'Create group Use this API to create a new group as specified in the
    request body. You can create one of 3 types of groups:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups
  tags: Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groups-post-openapi.md
- name: Microsoft Graph API Add Member
  x-api-slug: microsoft-graph-api
  description: 'Add member Use this API to add a member to an Office 365 group, a
    security group or a mail-enabled security group through the members navigation
    property. You can add users or other groups. Important: You can add only users
    to Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members/$ref
  tags: Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidmembersref-post-openapi.md
- name: Microsoft Graph API Add Group Owner
  x-api-slug: microsoft-graph-api
  description: Add group owner Add a user to the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/owners/$ref
  tags: Group, Owner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidownersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidownersref-post-openapi.md
- name: Microsoft Graph API Create Rejected Sender
  x-api-slug: microsoft-graph-api
  description: Create rejectedSender Add a new user or group to the rejectedSender
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/rejectedSenders/$ref
  tags: Rejected, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsendersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidrejectedsendersref-post-openapi.md
- name: Microsoft Graph API Create Thread
  x-api-slug: microsoft-graph-api
  description: Create thread Start a new conversation by first creating a thread.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads
  tags: Thread
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreads-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreads-post-openapi.md
- name: Microsoft Graph API Group Remove Favorite
  x-api-slug: microsoft-graph-api
  description: 'group: removeFavorite Remove the group from the list of the current
    user''s favorite groups. Supported for only Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/removeFavorite
  tags: Group, Remove, Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidremovefavorite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidremovefavorite-post-openapi.md
- name: Microsoft Graph API Group Reset Unseen Count
  x-api-slug: microsoft-graph-api
  description: 'group: resetUnseenCount Reset the unseenCount of all the posts that
    the current user has not seen since their last visit. Supported for only Office
    365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/resetUnseenCount
  tags: Group, Reset, Unseen, Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidresetunseencount-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidresetunseencount-post-openapi.md
- name: Microsoft Graph API Group Subscribe By Mail
  x-api-slug: microsoft-graph-api
  description: 'group: subscribeByMail Calling this method will enable the current
    user to receive email notifications for this group, about new posts, events, and
    files in that group. Supported for only Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/subscribeByMail
  tags: Group, SubscribeMail
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidsubscribebymail-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidsubscribebymail-post-openapi.md
- name: Microsoft Graph API Group Unsubscribe By Mail
  x-api-slug: microsoft-graph-api
  description: 'group: unsubscribeByMail Calling this method will prevent the current
    user from receiving email notifications for this group about new posts, events,
    and files in that group. Supported for only Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/unsubscribeByMail
  tags: Group, UnsubscribeMail
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidunsubscribebymail-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidunsubscribebymail-post-openapi.md
- name: Microsoft Graph API Update Group
  x-api-slug: microsoft-graph-api
  description: Update group Update the properties of a group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}
  tags: Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsid-patch-openapi.md
- name: Microsoft Graph API Get Icon
  x-api-slug: microsoft-graph-api
  description: Get Icon Retrieve the properties and relationships of icon object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/fields/icon
  tags: Icon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortfieldsicon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortfieldsicon-get-openapi.md
- name: Microsoft Graph API Get Icon
  x-api-slug: microsoft-graph-api
  description: Get Icon Retrieve the properties and relationships of icon object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon
  tags: Icon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-get-openapi.md
- name: Microsoft Graph API Update Icon
  x-api-slug: microsoft-graph-api
  description: Update icon Update the properties of icon object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/fields/icon
  tags: Icon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortfieldsicon-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortfieldsicon-patch-openapi.md
- name: Microsoft Graph API Update Icon
  x-api-slug: microsoft-graph-api
  description: Update icon Update the properties of icon object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon
  tags: Icon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-patch-openapi.md
- name: Microsoft Graph API List Overrides
  x-api-slug: microsoft-graph-api
  description: List overrides Get the overrides that a user has set up to always classify
    messages from certain senders in specific ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/inferenceClassification/overrides
  tags: List, Overrides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverrides-get-openapi.md
- name: Microsoft Graph API List Overrides
  x-api-slug: microsoft-graph-api
  description: List overrides Get the overrides that a user has set up to always classify
    messages from certain senders in specific ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id}/inferenceClassification/overrides
  tags: List, Overrides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-get-openapi.md
- name: Microsoft Graph API Create Inference Classification Override
  x-api-slug: microsoft-graph-api
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/inferenceClassification/overrides
  tags: Inference, Classification, Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API Create Inference Classification Override
  x-api-slug: microsoft-graph-api
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id}/inferenceClassification/overrides
  tags: Inference, Classification, Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API Delete Inference Classification Override
  x-api-slug: microsoft-graph-api
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/inferenceClassification/overrides/{id}
  tags: Inference, Classification, Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-openapi.md
- name: Microsoft Graph API Delete Inference Classification Override
  x-api-slug: microsoft-graph-api
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id}/inferenceClassification/overrides/{id}
  tags: Inference, Classification, Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-openapi.md
- name: Microsoft Graph API Update Inferenceclassificationoverride
  x-api-slug: microsoft-graph-api
  description: Update inferenceclassificationoverride Change the classifyAs field
    of an override as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/inferenceClassification/overrides/{id}
  tags: Inferenceclassificationoverride
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-patch-openapi.md
- name: Microsoft Graph API Update Inferenceclassificationoverride
  x-api-slug: microsoft-graph-api
  description: Update inferenceclassificationoverride Change the classifyAs field
    of an override as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id}/inferenceClassification/overrides/{id}
  tags: Inferenceclassificationoverride
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-patch-openapi.md
- name: Microsoft Graph API Create A Sharing Link For A Drive Item
  x-api-slug: microsoft-graph-api
  description: Create a sharing link for a DriveItem You can use createLink action
    to share a DriveItem via a sharing link.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/createLink
  tags: CreateSharing, LinkA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidcreatelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidcreatelink-post-openapi.md
- name: Microsoft Graph API Create A Sharing Link For A Drive Item
  x-api-slug: microsoft-graph-api
  description: Create a sharing link for a DriveItem You can use createLink action
    to share a DriveItem via a sharing link.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}:/createLink
  tags: CreateSharing, LinkA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempathcreatelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempathcreatelink-post-openapi.md
- name: Microsoft Graph API Create A Sharing Link For A Drive Item
  x-api-slug: microsoft-graph-api
  description: Create a sharing link for a DriveItem You can use createLink action
    to share a DriveItem via a sharing link.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/createLink
  tags: CreateSharing, LinkA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidcreatelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidcreatelink-post-openapi.md
- name: Microsoft Graph API Create A Sharing Link For A Drive Item
  x-api-slug: microsoft-graph-api
  description: Create a sharing link for a DriveItem You can use createLink action
    to share a DriveItem via a sharing link.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/createLink
  tags: CreateSharing, LinkA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidcreatelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidcreatelink-post-openapi.md
- name: Microsoft Graph API Track Changes For A Drive
  x-api-slug: microsoft-graph-api
  description: Track changes for a Drive This method allows your app to track changes
    to a drive and its children over time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root/delta
  tags: Track, Changes, Drive
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootdelta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootdelta-get-openapi.md
- name: Microsoft Graph API Track Changes For A Drive
  x-api-slug: microsoft-graph-api
  description: Track changes for a Drive This method allows your app to track changes
    to a drive and its children over time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/root/delta
  tags: Track, Changes, Drive
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveidrootdelta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveidrootdelta-get-openapi.md
- name: Microsoft Graph API Track Changes For A Drive
  x-api-slug: microsoft-graph-api
  description: Track changes for a Drive This method allows your app to track changes
    to a drive and its children over time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/root/delta
  tags: Track, Changes, Drive
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriverootdelta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriverootdelta-get-openapi.md
- name: Microsoft Graph API Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}:/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempathcontent-get-openapi.md
- name: Microsoft Graph API Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidcontent-get-openapi.md
- name: Microsoft Graph API Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesitemsitemidcontent-get-openapi.md
- name: Microsoft Graph API Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidcontent-get-openapi.md
- name: Microsoft Graph API Get A Drive Item Resource
  x-api-slug: microsoft-graph-api
  description: Get a DriveItem resource Retrieve the metadata for a DriveItem in a
    Drive by file system path or ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}
  tags: Drive, Item, Resource
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemid-get-openapi.md
- name: Microsoft Graph API Get A Drive Item Resource
  x-api-slug: microsoft-graph-api
  description: Get a DriveItem resource Retrieve the metadata for a DriveItem in a
    Drive by file system path or ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}
  tags: Drive, Item, Resource
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempath-get-openapi.md
- name: Microsoft Graph API Get A Drive Item Resource
  x-api-slug: microsoft-graph-api
  description: Get a DriveItem resource Retrieve the metadata for a DriveItem in a
    Drive by file system path or ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}
  tags: Drive, Item, Resource
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemid-get-openapi.md
- name: Microsoft Graph API List Children Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: List children of a driveItem Return a collection of DriveItems in the
    children relationship of a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}
  tags: List, Children, OfDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemid-get-openapi.md
- name: Microsoft Graph API Send A Sharing Invitation
  x-api-slug: microsoft-graph-api
  description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
    A sharing invitation provides permissions to the recipients and optionally sends
    an email to the recipients to notify them the item was shared.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/invite
  tags: SendSharing, Invitation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidinvite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidinvite-post-openapi.md
- name: Microsoft Graph API Send A Sharing Invitation
  x-api-slug: microsoft-graph-api
  description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
    A sharing invitation provides permissions to the recipients and optionally sends
    an email to the recipients to notify them the item was shared.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/items/{item-id}/invite
  tags: SendSharing, Invitation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driveitemsitemidinvite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driveitemsitemidinvite-post-openapi.md
- name: Microsoft Graph API Send A Sharing Invitation
  x-api-slug: microsoft-graph-api
  description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
    A sharing invitation provides permissions to the recipients and optionally sends
    an email to the recipients to notify them the item was shared.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/invite
  tags: SendSharing, Invitation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidinvite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidinvite-post-openapi.md
- name: Microsoft Graph API Send A Sharing Invitation
  x-api-slug: microsoft-graph-api
  description: Send a sharing invitation Sends a sharing invitation for a DriveItem.
    A sharing invitation provides permissions to the recipients and optionally sends
    an email to the recipients to notify them the item was shared.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/invite
  tags: SendSharing, Invitation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidinvite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidinvite-post-openapi.md
- name: Microsoft Graph API List Children Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: List children of a driveItem Return a collection of DriveItems in the
    children relationship of a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root/children
  tags: List, Children, OfDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootchildren-get-openapi.md
- name: Microsoft Graph API List Children Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: List children of a driveItem Return a collection of DriveItems in the
    children relationship of a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/children
  tags: List, Children, OfDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidchildren-get-openapi.md
- name: Microsoft Graph API List Children Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: List children of a driveItem Return a collection of DriveItems in the
    children relationship of a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}:/children
  tags: List, Children, OfDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempathchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempathchildren-get-openapi.md
- name: Microsoft Graph API List Children Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: List children of a driveItem Return a collection of DriveItems in the
    children relationship of a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/children
  tags: List, Children, OfDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidchildren-get-openapi.md
- name: Microsoft Graph API List Permissions On A Drive Item
  x-api-slug: microsoft-graph-api
  description: List permissions on a DriveItem List the effective permissions of on
    a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/permissions
  tags: List, Permissions, OnDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissions-get-openapi.md
- name: Microsoft Graph API List Permissions On A Drive Item
  x-api-slug: microsoft-graph-api
  description: List permissions on a DriveItem List the effective permissions of on
    a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{path}:/permissions
  tags: List, Permissions, OnDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissions-get-openapi.md
- name: Microsoft Graph API List Permissions On A Drive Item
  x-api-slug: microsoft-graph-api
  description: List permissions on a DriveItem List the effective permissions of on
    a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/permissions
  tags: List, Permissions, OnDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissions-get-openapi.md
- name: Microsoft Graph API List Permissions On A Drive Item
  x-api-slug: microsoft-graph-api
  description: List permissions on a DriveItem List the effective permissions of on
    a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/permissions
  tags: List, Permissions, OnDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissions-get-openapi.md
- name: Microsoft Graph API List Thumbnails For A Drive Item
  x-api-slug: microsoft-graph-api
  description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
    resources for a DriveItem resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}:/thumbnails
  tags: List, ThumbnailsA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempaththumbnails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempaththumbnails-get-openapi.md
- name: Microsoft Graph API List Thumbnails For A Drive Item
  x-api-slug: microsoft-graph-api
  description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
    resources for a DriveItem resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/thumbnails
  tags: List, ThumbnailsA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidthumbnails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidthumbnails-get-openapi.md
- name: Microsoft Graph API List Thumbnails For A Drive Item
  x-api-slug: microsoft-graph-api
  description: List thumbnails for a DriveItem Retrieve a collection of ThumbnailSet
    resources for a DriveItem resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/thumbnails
  tags: List, ThumbnailsA, Drive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidthumbnails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidthumbnails-get-openapi.md
- name: Microsoft Graph API Update Drive Item Properties
  x-api-slug: microsoft-graph-api
  description: Update DriveItem properties Update the metadata for a DriveItem by
    ID or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}
  tags: Drive, Item, Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemid-patch-openapi.md
- name: Microsoft Graph API Update Drive Item Properties
  x-api-slug: microsoft-graph-api
  description: Update DriveItem properties Update the metadata for a DriveItem by
    ID or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}
  tags: Drive, Item, Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempath-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootitempath-patch-openapi.md
- name: Microsoft Graph API Update Drive Item Properties
  x-api-slug: microsoft-graph-api
  description: Update DriveItem properties Update the metadata for a DriveItem by
    ID or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}
  tags: Drive, Item, Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemid-patch-openapi.md
- name: Microsoft Graph API Move A Drive Item
  x-api-slug: microsoft-graph-api
  description: Move a DriveItem To move a DriveItem to a new parent item, your app
    requests to update the parentReference of the DriveItem to move. This is a special
    case of the Update method. Your app can combine moving an item to a new container
    and updating other properties of the item into a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/{item-id}
  tags: MoveDrive, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemid-patch-openapi.md
- name: Microsoft Graph API Create A New Folder
  x-api-slug: microsoft-graph-api
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root/children
  tags: CreateNew, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootchildren-post-openapi.md
- name: Microsoft Graph API Create A New Folder
  x-api-slug: microsoft-graph-api
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{parent-item-id}/children
  tags: CreateNew, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API Create A New Folder
  x-api-slug: microsoft-graph-api
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{parent-item-id}/children
  tags: CreateNew, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API Create A New Folder
  x-api-slug: microsoft-graph-api
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{parent-item-id}/children
  tags: CreateNew, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API Update Drive Item Properties
  x-api-slug: microsoft-graph-api
  description: Update DriveItem properties Update the metadata for a DriveItem by
    ID or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}
  tags: Drive, Item, Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemid-patch-openapi.md
- name: Microsoft Graph API Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{parent-id}:/{filename}:/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsparentidfilenamecontent-put-openapi.md
- name: Microsoft Graph API Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{parent-path}/{filename}:/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootparentpathfilenamecontent-put-openapi.md
- name: Microsoft Graph API Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{parent-id}/children/{filename}/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsparentidchildrenfilenamecontent-put-openapi.md
- name: Microsoft Graph API Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph-api
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/drive/items/{parent-id}/children/{filename}/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsiddriveitemsparentidchildrenfilenamecontent-put-openapi.md
- name: Microsoft Graph API Mail Folder Copy
  x-api-slug: microsoft-graph-api
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/copy
  tags: Mail, Folder, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API Mail Folder Copy
  x-api-slug: microsoft-graph-api
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/copy
  tags: Mail, Folder, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API Delete Mail Folder
  x-api-slug: microsoft-graph-api
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-delete-openapi.md
- name: Microsoft Graph API Delete Mail Folder
  x-api-slug: microsoft-graph-api
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-openapi.md
- name: Microsoft Graph API Get Mail Folder
  x-api-slug: microsoft-graph-api
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-get-openapi.md
- name: Microsoft Graph API Get Mail Folder
  x-api-slug: microsoft-graph-api
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-openapi.md
- name: Microsoft Graph API List Child Folders
  x-api-slug: microsoft-graph-api
  description: List childFolders Get the folder collection under the specified folder.
    You can use the .../me/MailFolders shortcut to get the top-level folder collection
    and navigate to another folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders
  tags: List, Child, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API List Child Folders
  x-api-slug: microsoft-graph-api
  description: List childFolders Get the folder collection under the specified folder.
    You can use the .../me/MailFolders shortcut to get the top-level folder collection
    and navigate to another folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders
  tags: List, Child, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API List Messages
  x-api-slug: microsoft-graph-api
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessages-get-openapi.md
- name: Microsoft Graph API List Messages
  x-api-slug: microsoft-graph-api
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-get-openapi.md
- name: Microsoft Graph API Mail Folder Move
  x-api-slug: microsoft-graph-api
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/move
  tags: Mail, Folder, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmove-post-openapi.md
- name: Microsoft Graph API Mail Folder Move
  x-api-slug: microsoft-graph-api
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/move
  tags: Mail, Folder, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-openapi.md
- name: Microsoft Graph API Create Mail Folder
  x-api-slug: microsoft-graph-api
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API Create Mail Folder
  x-api-slug: microsoft-graph-api
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API Create Message
  x-api-slug: microsoft-graph-api
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API Create Message
  x-api-slug: microsoft-graph-api
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph API Update Mailfolder
  x-api-slug: microsoft-graph-api
  description: Update mailfolder Update the properties of mailfolder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}
  tags: Mailfolder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersid-patch-openapi.md
- name: Microsoft Graph API Update Mailfolder
  x-api-slug: microsoft-graph-api
  description: Update mailfolder Update the properties of mailfolder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}
  tags: Mailfolder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-patch-openapi.md
- name: Microsoft Graph API Message Copy
  x-api-slug: microsoft-graph-api
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph API Message Copy
  x-api-slug: microsoft-graph-api
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph API Message Copy
  x-api-slug: microsoft-graph-api
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API Message Copy
  x-api-slug: microsoft-graph-api
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph API Message Create Forward
  x-api-slug: microsoft-graph-api
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API Message Create Forward
  x-api-slug: microsoft-graph-api
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API Message Create Forward
  x-api-slug: microsoft-graph-api
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API Message Create Forward
  x-api-slug: microsoft-graph-api
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph API Message Create Reply
  x-api-slug: microsoft-graph-api
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API Message Create Reply
  x-api-slug: microsoft-graph-api
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API Message Create Reply
  x-api-slug: microsoft-graph-api
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API Message Create Reply
  x-api-slug: microsoft-graph-api
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph API Message Create Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API Message Create Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API Message Create Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API Message Create Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph API Message Forward
  x-api-slug: microsoft-graph-api
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph API Message Forward
  x-api-slug: microsoft-graph-api
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph API Message Forward
  x-api-slug: microsoft-graph-api
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API Message Forward
  x-api-slug: microsoft-graph-api
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-get-openapi.md
- name: Microsoft Graph API Message Move
  x-api-slug: microsoft-graph-api
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph API Message Move
  x-api-slug: microsoft-graph-api
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph API Message Move
  x-api-slug: microsoft-graph-api
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API Message Move
  x-api-slug: microsoft-graph-api
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfoldersidmessagesidattachmentsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidchildfoldersidmessagesidattachmentsid-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-post-openapi.md
- name: Microsoft Graph API Message Reply
  x-api-slug: microsoft-graph-api
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph API Message Reply
  x-api-slug: microsoft-graph-api
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph API Message Reply
  x-api-slug: microsoft-graph-api
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API Message Reply
  x-api-slug: microsoft-graph-api
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph API Message Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/me/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API Message Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph API Message Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API Message Reply All
  x-api-slug: microsoft-graph-api
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph API Message Send
  x-api-slug: microsoft-graph-api
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/send
  tags: Message, Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph API Message Send
  x-api-slug: microsoft-graph-api
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/send
  tags: Message, Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailFolders/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfoldersid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/calendars/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendarsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendarsid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders/{id}/contacts/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsid-get-openapi.md
- name: Microsoft Graph API Get Multi Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get multiValueLegacyExtendedProperty Get a resource instance that contains
    a multi-value extended property by using $expand.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}
  tags: Multi, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsid-get-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessages-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessages-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfolders-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailFolders
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfolders-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meevents-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameevents-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendars-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/calendars
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendars-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontacts-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolders-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/reply
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidreply-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/reply
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidreply-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/reply
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidreply-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/reply
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidreply-post-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailFolders/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfoldersid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfoldersid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/calendars/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendarsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendarsid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfoldersid-patch-openapi.md
- name: Microsoft Graph API Create Multi-value Extended Property
  x-api-slug: microsoft-graph-api
  description: Create multi-value extended property Create one or more multi-value
    extended properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders/{id}
  tags: Multi-value, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersid-patch-openapi.md
- name: Microsoft Graph API Add Named Item
  x-api-slug: microsoft-graph-api
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names/add
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesadd-post-openapi.md
- name: Microsoft Graph API Add Named Item
  x-api-slug: microsoft-graph-api
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets({id|name})/names/add
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-openapi.md
- name: Microsoft Graph API Get Named Item
  x-api-slug: microsoft-graph-api
  description: Get NamedItem Retrieve the properties and relationships of nameditem
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegt-get-openapi.md
- name: Microsoft Graph API List Named Item Collection
  x-api-slug: microsoft-graph-api
  description: List NamedItemCollection Retrieve a list of nameditem objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names
  tags: List, Named, Item, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknames-get-openapi.md
- name: Microsoft Graph API Named Item Range
  x-api-slug: microsoft-graph-api
  description: 'NamedItem: Range Returns the range object that is associated with
    the name. Throws an exception if the named item''s type is not a range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/Range
  tags: Named, Item, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-openapi.md
- name: Microsoft Graph API Update Nameditem
  x-api-slug: microsoft-graph-api
  description: Update nameditem Update the properties of nameditem object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)
  tags: Nameditem
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-openapi.md
- name: Microsoft Graph API Delete Open Extension
  x-api-slug: microsoft-graph-api
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-delete-openapi.md
- name: Microsoft Graph API Delete Open Extension
  x-api-slug: microsoft-graph-api
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-delete-openapi.md
- name: Microsoft Graph API Delete Open Extension
  x-api-slug: microsoft-graph-api
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-delete-openapi.md
- name: Microsoft Graph API Delete Open Extension
  x-api-slug: microsoft-graph-api
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-delete-openapi.md
- name: Microsoft Graph API Delete Open Extension
  x-api-slug: microsoft-graph-api
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-delete-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/messages/{Id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/events/{Id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/contacts/{Id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{Id}/events/{Id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{Id}/threads/{Id}/posts/{Id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/messages
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessages-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/events
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameevents-get-openapi.md
- name: Microsoft Graph API Get Open Extension
  x-api-slug: microsoft-graph-api
  description: Get open extension Get an open extension (openTypeExtension object)
    identified by name or fully qualified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{Id|userPrincipalName}/contacts
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontacts-get-openapi.md
- name: Microsoft Graph API Create Open Extension
  x-api-slug: microsoft-graph-api
  description: Create open extension Create an open extension (openTypeExtension object)
    and add custom properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts/{id}/extensions
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensions-post-openapi.md
- name: Microsoft Graph API Create Open Extension
  x-api-slug: microsoft-graph-api
  description: Create open extension Create an open extension (openTypeExtension object)
    and add custom properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events/{id}/extensions
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensions-post-openapi.md
- name: Microsoft Graph API Create Open Extension
  x-api-slug: microsoft-graph-api
  description: Create open extension Create an open extension (openTypeExtension object)
    and add custom properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages/{id}/extensions
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensions-post-openapi.md
- name: Microsoft Graph API Create Open Extension
  x-api-slug: microsoft-graph-api
  description: Create open extension Create an open extension (openTypeExtension object)
    and add custom properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/extensions
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensions-post-openapi.md
- name: Microsoft Graph API Create Open Extension
  x-api-slug: microsoft-graph-api
  description: Create open extension Create an open extension (openTypeExtension object)
    and add custom properties in a new or existing instance of a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/extensions
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensions-post-openapi.md
- name: Microsoft Graph API Update Open Extension
  x-api-slug: microsoft-graph-api
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/messages/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemessagesidextensionsextensionid-patch-openapi.md
- name: Microsoft Graph API Update Open Extension
  x-api-slug: microsoft-graph-api
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/events/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnameeventsidextensionsextensionid-patch-openapi.md
- name: Microsoft Graph API Update Open Extension
  x-api-slug: microsoft-graph-api
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contacts/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactsidextensionsextensionid-patch-openapi.md
- name: Microsoft Graph API Update Open Extension
  x-api-slug: microsoft-graph-api
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsideventsidextensionsextensionid-patch-openapi.md
- name: Microsoft Graph API Update Open Extension
  x-api-slug: microsoft-graph-api
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/extensions/{extensionId}
  tags: Open, Extension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidextensionsextensionid-patch-openapi.md
- name: Microsoft Graph API Get Organization
  x-api-slug: microsoft-graph-api
  description: Get organization Retrieve the properties and relationships of currently
    authenticated organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////organization
  tags: Organization
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/organization-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/organization-get-openapi.md
- name: Microsoft Graph API Update Organization
  x-api-slug: microsoft-graph-api
  description: Update organization Update the properties of the currently authenticated
    organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////organization
  tags: Organization
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/organization-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/organization-patch-openapi.md
- name: Microsoft Graph API Delete Permission
  x-api-slug: microsoft-graph-api
  description: Delete permission Remove access to a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-delete-openapi.md
- name: Microsoft Graph API Delete Permission
  x-api-slug: microsoft-graph-api
  description: Delete permission Remove access to a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{path}:/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-delete-openapi.md
- name: Microsoft Graph API Delete Permission
  x-api-slug: microsoft-graph-api
  description: Delete permission Remove access to a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-delete-openapi.md
- name: Microsoft Graph API Delete Permission
  x-api-slug: microsoft-graph-api
  description: Delete permission Remove access to a DriveItem.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-delete-openapi.md
- name: Microsoft Graph API Get Permission
  x-api-slug: microsoft-graph-api
  description: Get permission Retrieve the properties and relationships of permission
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-get-openapi.md
- name: Microsoft Graph API Get Permission
  x-api-slug: microsoft-graph-api
  description: Get permission Retrieve the properties and relationships of permission
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{path}:/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-get-openapi.md
- name: Microsoft Graph API Get Permission
  x-api-slug: microsoft-graph-api
  description: Get permission Retrieve the properties and relationships of permission
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-get-openapi.md
- name: Microsoft Graph API Get Permission
  x-api-slug: microsoft-graph-api
  description: Get permission Retrieve the properties and relationships of permission
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-get-openapi.md
- name: Microsoft Graph API Update Permission
  x-api-slug: microsoft-graph-api
  description: Update permission Update the properties of a permission by patching
    the resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriveitemsitemidpermissionspermid-patch-openapi.md
- name: Microsoft Graph API Update Permission
  x-api-slug: microsoft-graph-api
  description: Update permission Update the properties of a permission by patching
    the resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{path}:/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/medriverootpathpermissionspermid-patch-openapi.md
- name: Microsoft Graph API Update Permission
  x-api-slug: microsoft-graph-api
  description: Update permission Update the properties of a permission by patching
    the resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{drive-id}/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesdriveiditemsitemidpermissionspermid-patch-openapi.md
- name: Microsoft Graph API Update Permission
  x-api-slug: microsoft-graph-api
  description: Update permission Update the properties of a permission by patching
    the resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}
  tags: Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidpermissionspermid-patch-openapi.md
- name: Microsoft Graph API Delete Photo
  x-api-slug: microsoft-graph-api
  description: Delete photo Delete a photo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-delete-openapi.md
- name: Microsoft Graph API Delete Photo
  x-api-slug: microsoft-graph-api
  description: Delete photo Delete a photo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-delete-openapi.md
- name: Microsoft Graph API Delete Photo
  x-api-slug: microsoft-graph-api
  description: Delete photo Delete a photo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/root/createdByUser/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-delete-openapi.md
- name: Microsoft Graph API Get Photo
  x-api-slug: microsoft-graph-api
  description: Get photo Retrieve the properties and relationships of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-get-openapi.md
- name: Microsoft Graph API Get Photo
  x-api-slug: microsoft-graph-api
  description: Get photo Retrieve the properties and relationships of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-get-openapi.md
- name: Microsoft Graph API Get Photo
  x-api-slug: microsoft-graph-api
  description: Get photo Retrieve the properties and relationships of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/root/createdByUser/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-get-openapi.md
- name: Microsoft Graph API Update Photo
  x-api-slug: microsoft-graph-api
  description: Update photo Update the properties of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamephoto-patch-openapi.md
- name: Microsoft Graph API Update Photo
  x-api-slug: microsoft-graph-api
  description: Update photo Update the properties of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidphoto-patch-openapi.md
- name: Microsoft Graph API Update Photo
  x-api-slug: microsoft-graph-api
  description: Update photo Update the properties of photo object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/root/createdByUser/photo
  tags: Photo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootcreatedbyuserphoto-patch-openapi.md
- name: Microsoft Graph API Post Forward
  x-api-slug: microsoft-graph-api
  description: 'post: forward Forward a post to a recipient. You can specify both
    the parent conversation and thread in the request, or, you can specify just the
    parent thread without the parent conversation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/forward
  tags: Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidforward-post-openapi.md
- name: Microsoft Graph API Post Forward
  x-api-slug: microsoft-graph-api
  description: 'post: forward Forward a post to a recipient. You can specify both
    the parent conversation and thread in the request, or, you can specify just the
    parent thread without the parent conversation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/forward
  tags: Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidforward-post-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-get-openapi.md
- name: Microsoft Graph API List Attachments
  x-api-slug: microsoft-graph-api
  description: List attachments Retrieve a list of attachment objects attached to
    a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-get-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a post. Since there
    is currently a limit of 4MB on the total size of each REST request, this limits
    the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-post-openapi.md
- name: Microsoft Graph API Add Attachment
  x-api-slug: microsoft-graph-api
  description: Add attachment Use this API to add an attachment to a post. Since there
    is currently a limit of 4MB on the total size of each REST request, this limits
    the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-post-openapi.md
- name: Microsoft Graph API Range Bounding Rect
  x-api-slug: microsoft-graph-api
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/BoundingRect
  tags: Range, Bounding, Rect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeboundingrect-post-openapi.md
- name: Microsoft Graph API Range Bounding Rect
  x-api-slug: microsoft-graph-api
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/BoundingRect
  tags: Range, Bounding, Rect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post-openapi.md
- name: Microsoft Graph API Range Bounding Rect
  x-api-slug: microsoft-graph-api
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/BoundingRect
  tags: Range, Bounding, Rect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post-openapi.md
- name: Microsoft Graph API Range Cell
  x-api-slug: microsoft-graph-api
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/Cell
  tags: Range, Cell
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangecell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangecell-post-openapi.md
- name: Microsoft Graph API Range Cell
  x-api-slug: microsoft-graph-api
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Cell
  tags: Range, Cell
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcell-post-openapi.md
- name: Microsoft Graph API Range Cell
  x-api-slug: microsoft-graph-api
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Cell
  tags: Range, Cell
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecell-post-openapi.md
- name: Microsoft Graph API Range Clear
  x-api-slug: microsoft-graph-api
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-openapi.md
- name: Microsoft Graph API Range Clear
  x-api-slug: microsoft-graph-api
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-openapi.md
- name: Microsoft Graph API Range Clear
  x-api-slug: microsoft-graph-api
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-openapi.md
- name: Microsoft Graph API Range Column
  x-api-slug: microsoft-graph-api
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/Column
  tags: Range, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangecolumn-post-openapi.md
- name: Microsoft Graph API Range Column
  x-api-slug: microsoft-graph-api
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Column
  tags: Range, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcolumn-post-openapi.md
- name: Microsoft Graph API Range Column
  x-api-slug: microsoft-graph-api
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Column
  tags: Range, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post-openapi.md
- name: Microsoft Graph API Range Delete
  x-api-slug: microsoft-graph-api
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/delete
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangedelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangedelete-post-openapi.md
- name: Microsoft Graph API Range Delete
  x-api-slug: microsoft-graph-api
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/delete
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtdelete-post-openapi.md
- name: Microsoft Graph API Range Delete
  x-api-slug: microsoft-graph-api
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/delete
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post-openapi.md
- name: Microsoft Graph API Range Entire Column
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/EntireColumn
  tags: Range, Entire, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirecolumn-post-openapi.md
- name: Microsoft Graph API Range Entire Column
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireColumn
  tags: Range, Entire, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post-openapi.md
- name: Microsoft Graph API Range Entire Column
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireColumn
  tags: Range, Entire, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post-openapi.md
- name: Microsoft Graph API Range Entire Row
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/EntireRow
  tags: Range, Entire, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirerow-post-openapi.md
- name: Microsoft Graph API Range Entire Row
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireRow
  tags: Range, Entire, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirerow-post-openapi.md
- name: Microsoft Graph API Range Entire Row
  x-api-slug: microsoft-graph-api
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireRow
  tags: Range, Entire, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post-openapi.md
- name: Microsoft Graph API Range Offset Range
  x-api-slug: microsoft-graph-api
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/OffsetRange
  tags: Range, Offset, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeoffsetrange-post-openapi.md
- name: Microsoft Graph API Range Offset Range
  x-api-slug: microsoft-graph-api
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/OffsetRange
  tags: Range, Offset, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post-openapi.md
- name: Microsoft Graph API Range Offset Range
  x-api-slug: microsoft-graph-api
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/OffsetRange
  tags: Range, Offset, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post-openapi.md
- name: Microsoft Graph API Range Row
  x-api-slug: microsoft-graph-api
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/Row
  tags: Range, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangerow-post-openapi.md
- name: Microsoft Graph API Range Row
  x-api-slug: microsoft-graph-api
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Row
  tags: Range, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtrow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtrow-post-openapi.md
- name: Microsoft Graph API Range Row
  x-api-slug: microsoft-graph-api
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Row
  tags: Range, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangerow-post-openapi.md
- name: Microsoft Graph API Range Unmerge
  x-api-slug: microsoft-graph-api
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph API Range Unmerge
  x-api-slug: microsoft-graph-api
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-openapi.md
- name: Microsoft Graph API Range Unmerge
  x-api-slug: microsoft-graph-api
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph API Update Range
  x-api-slug: microsoft-graph-api
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrange-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrange-patch-openapi.md
- name: Microsoft Graph API Update Range
  x-api-slug: microsoft-graph-api
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(address=&lt;range-address&gt;)
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch-openapi.md
- name: Microsoft Graph API Update Range
  x-api-slug: microsoft-graph-api
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range
  tags: Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-patch-openapi.md
- name: Microsoft Graph API Range Used Range
  x-api-slug: microsoft-graph-api
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/UsedRange
  tags: Range, Used, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeusedrange-post-openapi.md
- name: Microsoft Graph API Range Used Range
  x-api-slug: microsoft-graph-api
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/UsedRange
  tags: Range, Used, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtusedrange-post-openapi.md
- name: Microsoft Graph API Range Used Range
  x-api-slug: microsoft-graph-api
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/UsedRange
  tags: Range, Used, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post-openapi.md
- name: Microsoft Graph API Get Range Border
  x-api-slug: microsoft-graph-api
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API Get Range Border
  x-api-slug: microsoft-graph-api
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API Get Range Border
  x-api-slug: microsoft-graph-api
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API List Range Border Collection
  x-api-slug: microsoft-graph-api
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph API List Range Border Collection
  x-api-slug: microsoft-graph-api
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-openapi.md
- name: Microsoft Graph API List Range Border Collection
  x-api-slug: microsoft-graph-api
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph API Update Rangeborder
  x-api-slug: microsoft-graph-api
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph API Update Rangeborder
  x-api-slug: microsoft-graph-api
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph API Update Rangeborder
  x-api-slug: microsoft-graph-api
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph API Range Border Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph API Range Border Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-openapi.md
- name: Microsoft Graph API Range Border Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph API Range Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph API Range Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-openapi.md
- name: Microsoft Graph API Range Fill Clear
  x-api-slug: microsoft-graph-api
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph API Get Range Fill
  x-api-slug: microsoft-graph-api
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph API Get Range Fill
  x-api-slug: microsoft-graph-api
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-openapi.md
- name: Microsoft Graph API Get Range Fill
  x-api-slug: microsoft-graph-api
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph API Update Rangefill
  x-api-slug: microsoft-graph-api
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-patch-openapi.md
- name: Microsoft Graph API Update Rangefill
  x-api-slug: microsoft-graph-api
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-patch-openapi.md
- name: Microsoft Graph API Update Rangefill
  x-api-slug: microsoft-graph-api
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-patch-openapi.md
- name: Microsoft Graph API Get Range Font
  x-api-slug: microsoft-graph-api
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/font
  tags: Range, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-get-openapi.md
- name: Microsoft Graph API Get Range Font
  x-api-slug: microsoft-graph-api
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/font
  tags: Range, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-get-openapi.md
- name: Microsoft Graph API Get Range Font
  x-api-slug: microsoft-graph-api
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/font
  tags: Range, Font
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get-openapi.md
- name: Microsoft Graph API Update Rangefont
  x-api-slug: microsoft-graph-api
  description: Update rangefont Update the properties of rangefont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/font
  tags: Rangefont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-patch-openapi.md
- name: Microsoft Graph API Update Rangefont
  x-api-slug: microsoft-graph-api
  description: Update rangefont Update the properties of rangefont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/font
  tags: Rangefont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-patch-openapi.md
- name: Microsoft Graph API Update Rangefont
  x-api-slug: microsoft-graph-api
  description: Update rangefont Update the properties of rangefont object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/font
  tags: Rangefont
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-patch-openapi.md
- name: Microsoft Graph API Range Format Autofit Columns
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API Range Format Autofit Columns
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API Range Format Autofit Columns
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API Range Format Autofit Rows
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/autofitRows
  tags: Range, Format, Autofit, Rows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitrows-post-openapi.md
- name: Microsoft Graph API Range Format Autofit Rows
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitRows
  tags: Range, Format, Autofit, Rows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post-openapi.md
- name: Microsoft Graph API Range Format Autofit Rows
  x-api-slug: microsoft-graph-api
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitRows
  tags: Range, Format, Autofit, Rows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post-openapi.md
- name: Microsoft Graph API Get Range Format
  x-api-slug: microsoft-graph-api
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format
  tags: Range, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-get-openapi.md
- name: Microsoft Graph API Get Range Format
  x-api-slug: microsoft-graph-api
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format
  tags: Range, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-get-openapi.md
- name: Microsoft Graph API Get Range Format
  x-api-slug: microsoft-graph-api
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format
  tags: Range, Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get-openapi.md
- name: Microsoft Graph API Create Range Border
  x-api-slug: microsoft-graph-api
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph API Create Range Border
  x-api-slug: microsoft-graph-api
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-openapi.md
- name: Microsoft Graph API Create Range Border
  x-api-slug: microsoft-graph-api
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph API Update Rangeformat
  x-api-slug: microsoft-graph-api
  description: Update rangeformat Update the properties of rangeformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format
  tags: Rangeformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-patch-openapi.md
- name: Microsoft Graph API Update Rangeformat
  x-api-slug: microsoft-graph-api
  description: Update rangeformat Update the properties of rangeformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format
  tags: Rangeformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-patch-openapi.md
- name: Microsoft Graph API Update Rangeformat
  x-api-slug: microsoft-graph-api
  description: Update rangeformat Update the properties of rangeformat object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format
  tags: Rangeformat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-patch-openapi.md
- name: Microsoft Graph API Range Sort Apply
  x-api-slug: microsoft-graph-api
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph API Range Sort Apply
  x-api-slug: microsoft-graph-api
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-openapi.md
- name: Microsoft Graph API Range Sort Apply
  x-api-slug: microsoft-graph-api
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph API Accessing Shared Drive Items
  x-api-slug: microsoft-graph-api
  description: Accessing shared DriveItems Access a shared DriveItem or a collection
    of shared items by using a shareId or sharing URL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////shares/{sharingIdOrUrl}
  tags: Accessing, Shared, Drive, Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/sharessharingidorurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/sharessharingidorurl-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memessages-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailfolders-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailFolders
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailfolders-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/meevents-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendars-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/calendars
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecalendars-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders/{id}/contacts
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersidcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactfolders
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolders-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/contactFolders
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidposts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidthreadsidposts-get-openapi.md
- name: Microsoft Graph API Get Single Value Legacy Extended Property
  x-api-slug: microsoft-graph-api
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts
  tags: Single, Value, Legacy, Extended, Property
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidposts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/groupsidconversationsidthreadsidposts-get-openapi.md
- name: Microsoft Graph API Get Subscribed Sku
  x-api-slug: microsoft-graph-api
  description: Get subscribedSku Retrieve a specific commercial subscription that
    an organization has acquired.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscribedSkus/{id}
  tags: Subscribed, Sku
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscribedskusid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscribedskusid-get-openapi.md
- name: Microsoft Graph API List Subscribed Skus
  x-api-slug: microsoft-graph-api
  description: List subscribedSkus Retrieve the list of commercial subscriptions that
    an organization has acquired.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscribedSkus
  tags: List, Subscribed, Skus
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscribedskus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscribedskus-get-openapi.md
- name: Microsoft Graph API Delete Subscription
  x-api-slug: microsoft-graph-api
  description: Delete subscription Delete a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscriptions/{subscriptionId}
  tags: Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-delete-openapi.md
- name: Microsoft Graph API Get Subscription
  x-api-slug: microsoft-graph-api
  description: Get subscription Retrieve the properties and relationships of a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscriptions/{subscriptionId}
  tags: Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-get-openapi.md
- name: Microsoft Graph API Create Subscription
  x-api-slug: microsoft-graph-api
  description: Create subscription Subscribes a listener application to receive notifications
    when data on the Microsoft Graph changes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscriptions
  tags: Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptions-post-openapi.md
- name: Microsoft Graph API Update Subscription
  x-api-slug: microsoft-graph-api
  description: Update subscription Renew a subscription by extending its expiry time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////subscriptions/{subscriptionId}
  tags: Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/subscriptionssubscriptionid-patch-openapi.md
- name: Microsoft Graph API Table Clear Filters
  x-api-slug: microsoft-graph-api
  description: 'Table: clearFilters Clears all the filters currently applied on the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/clearFilters
  tags: Table, Clear, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtclearfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtclearfilters-post-openapi.md
- name: Microsoft Graph API Table Clear Filters
  x-api-slug: microsoft-graph-api
  description: 'Table: clearFilters Clears all the filters currently applied on the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/clearFilters
  tags: Table, Clear, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtclearfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtclearfilters-post-openapi.md
- name: Microsoft Graph API Table Convert To Range
  x-api-slug: microsoft-graph-api
  description: 'Table: convertToRange Converts the table into a normal range of cells.
    All data is preserved.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/convertToRange
  tags: Table, ConvertRange
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtconverttorange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtconverttorange-post-openapi.md
- name: Microsoft Graph API Table Convert To Range
  x-api-slug: microsoft-graph-api
  description: 'Table: convertToRange Converts the table into a normal range of cells.
    All data is preserved.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/convertToRange
  tags: Table, ConvertRange
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtconverttorange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtconverttorange-post-openapi.md
- name: Microsoft Graph API Table Data Body Range
  x-api-slug: microsoft-graph-api
  description: 'Table: DataBodyRange Gets the range object associated with the data
    body of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/DataBodyRange
  tags: Table, Data, Body, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API Table Data Body Range
  x-api-slug: microsoft-graph-api
  description: 'Table: DataBodyRange Gets the range object associated with the data
    body of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/DataBodyRange
  tags: Table, Data, Body, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API Table Delete
  x-api-slug: microsoft-graph-api
  description: 'Table: delete Deletes the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/delete
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtdelete-post-openapi.md
- name: Microsoft Graph API Table Delete
  x-api-slug: microsoft-graph-api
  description: 'Table: delete Deletes the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/delete
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdelete-post-openapi.md
- name: Microsoft Graph API Get Table
  x-api-slug: microsoft-graph-api
  description: Get Table Retrieve the properties and relationships of table object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegt-get-openapi.md
- name: Microsoft Graph API Get Table
  x-api-slug: microsoft-graph-api
  description: Get Table Retrieve the properties and relationships of table object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegt-get-openapi.md
- name: Microsoft Graph API Table Header Row Range
  x-api-slug: microsoft-graph-api
  description: 'Table: HeaderRowRange Gets the range object associated with header
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/HeaderRowRange
  tags: Table, Header, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API Table Header Row Range
  x-api-slug: microsoft-graph-api
  description: 'Table: HeaderRowRange Gets the range object associated with header
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/HeaderRowRange
  tags: Table, Header, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API List Table Collection
  x-api-slug: microsoft-graph-api
  description: List TableCollection Retrieve a list of table objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables
  tags: List, Table, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktables-get-openapi.md
- name: Microsoft Graph API List Table Collection
  x-api-slug: microsoft-graph-api
  description: List TableCollection Retrieve a list of table objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables
  tags: List, Table, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttables-get-openapi.md
- name: Microsoft Graph API List Columns
  x-api-slug: microsoft-graph-api
  description: List columns Retrieve a list of tablecolumn objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns
  tags: List, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-get-openapi.md
- name: Microsoft Graph API List Columns
  x-api-slug: microsoft-graph-api
  description: List columns Retrieve a list of tablecolumn objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns
  tags: List, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-get-openapi.md
- name: Microsoft Graph API List Rows
  x-api-slug: microsoft-graph-api
  description: List rows Retrieve a list of tablerow objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows
  tags: List, Rows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrows-get-openapi.md
- name: Microsoft Graph API List Rows
  x-api-slug: microsoft-graph-api
  description: List rows Retrieve a list of tablerow objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows
  tags: List, Rows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrows-get-openapi.md
- name: Microsoft Graph API Create Table Column
  x-api-slug: microsoft-graph-api
  description: Create TableColumn Use this API to create a new TableColumn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-post-openapi.md
- name: Microsoft Graph API Create Table Column
  x-api-slug: microsoft-graph-api
  description: Create TableColumn Use this API to create a new TableColumn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-post-openapi.md
- name: Microsoft Graph API Create Table Row
  x-api-slug: microsoft-graph-api
  description: Create TableRow Use this API to create a new TableRow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrows-post-openapi.md
- name: Microsoft Graph API Create Table Row
  x-api-slug: microsoft-graph-api
  description: Create TableRow Use this API to create a new TableRow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrows-post-openapi.md
- name: Microsoft Graph API Table Range
  x-api-slug: microsoft-graph-api
  description: 'Table: Range Gets the range object associated with the entire table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/Range
  tags: Table, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrange-post-openapi.md
- name: Microsoft Graph API Table Range
  x-api-slug: microsoft-graph-api
  description: 'Table: Range Gets the range object associated with the entire table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/Range
  tags: Table, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrange-post-openapi.md
- name: Microsoft Graph API Table Reapply Filters
  x-api-slug: microsoft-graph-api
  description: 'Table: reapplyFilters Reapplies all the filters currently on the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/reapplyFilters
  tags: Table, Reapply, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtreapplyfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtreapplyfilters-post-openapi.md
- name: Microsoft Graph API Table Reapply Filters
  x-api-slug: microsoft-graph-api
  description: 'Table: reapplyFilters Reapplies all the filters currently on the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/reapplyFilters
  tags: Table, Reapply, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtreapplyfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtreapplyfilters-post-openapi.md
- name: Microsoft Graph API Table Total Row Range
  x-api-slug: microsoft-graph-api
  description: 'Table: TotalRowRange Gets the range object associated with totals
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/TotalRowRange
  tags: Table, Total, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API Table Total Row Range
  x-api-slug: microsoft-graph-api
  description: 'Table: TotalRowRange Gets the range object associated with totals
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/TotalRowRange
  tags: Table, Total, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API Update Table
  x-api-slug: microsoft-graph-api
  description: Update table Update the properties of table object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegt-patch-openapi.md
- name: Microsoft Graph API Update Table
  x-api-slug: microsoft-graph-api
  description: Update table Update the properties of table object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegt-patch-openapi.md
- name: Microsoft Graph API Table Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableCollection: add Create a new table. The range source address
    determines the worksheet under which the table will be added. If the table cannot
    be added (e.g., because the address is invalid, or the table would overlap with
    another table), an error will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables/add
  tags: Table, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesadd-post-openapi.md
- name: Microsoft Graph API Table Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableCollection: add Create a new table. The range source address
    determines the worksheet under which the table will be added. If the table cannot
    be added (e.g., because the address is invalid, or the table would overlap with
    another table), an error will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables/add
  tags: Table, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesadd-post-openapi.md
- name: Microsoft Graph API Table Column Data Body Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: DataBodyRange Gets the range object associated with the
    data body of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange
  tags: Table, Column, Data, Body, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API Table Column Data Body Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: DataBodyRange Gets the range object associated with the
    data body of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange
  tags: Table, Column, Data, Body, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API Table Column Delete
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: delete Deletes the column from the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdelete-post-openapi.md
- name: Microsoft Graph API Table Column Delete
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: delete Deletes the column from the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdelete-post-openapi.md
- name: Microsoft Graph API Get Table Column
  x-api-slug: microsoft-graph-api
  description: Get TableColumn Retrieve the properties and relationships of tablecolumn
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegt-get-openapi.md
- name: Microsoft Graph API Get Table Column
  x-api-slug: microsoft-graph-api
  description: Get TableColumn Retrieve the properties and relationships of tablecolumn
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)
  tags: Table, Column
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-get-openapi.md
- name: Microsoft Graph API Table Column Header Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange
  tags: Table, Column, Header, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API Table Column Header Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange
  tags: Table, Column, Header, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API Table Column Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: Range Gets the range object associated with the entire
    column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range
  tags: Table, Column, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API Table Column Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: Range Gets the range object associated with the entire
    column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range
  tags: Table, Column, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API Table Column Total Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: TotalRowRange Gets the range object associated with the
    totals row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange
  tags: Table, Column, Total, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API Table Column Total Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableColumn: TotalRowRange Gets the range object associated with the
    totals row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange
  tags: Table, Column, Total, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API Update Tablecolumn
  x-api-slug: microsoft-graph-api
  description: Update tablecolumn Update the properties of tablecolumn object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)
  tags: Tablecolumn
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegt-patch-openapi.md
- name: Microsoft Graph API Update Tablecolumn
  x-api-slug: microsoft-graph-api
  description: Update tablecolumn Update the properties of tablecolumn object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)
  tags: Tablecolumn
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-patch-openapi.md
- name: Microsoft Graph API Table Column Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableColumnCollection: add Adds a new column to the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns/add
  tags: Table, Column, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsadd-post-openapi.md
- name: Microsoft Graph API Table Column Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableColumnCollection: add Adds a new column to the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/add
  tags: Table, Column, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsadd-post-openapi.md
- name: Microsoft Graph API Table Column Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'TableColumnCollection: ItemAt Gets a column based on its position
    in the collection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns/ItemAt
  tags: Table, Column, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsitemat-post-openapi.md
- name: Microsoft Graph API Table Column Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'TableColumnCollection: ItemAt Gets a column based on its position
    in the collection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/ItemAt
  tags: Table, Column, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsitemat-post-openapi.md
- name: Microsoft Graph API Table Row Delete
  x-api-slug: microsoft-graph-api
  description: 'TableRow: delete Deletes the row from the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtdelete-post-openapi.md
- name: Microsoft Graph API Table Row Delete
  x-api-slug: microsoft-graph-api
  description: 'TableRow: delete Deletes the row from the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtdelete-post-openapi.md
- name: Microsoft Graph API Get Table Row
  x-api-slug: microsoft-graph-api
  description: Get TableRow Retrieve the properties and relationships of tablerow
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgt-get-openapi.md
- name: Microsoft Graph API Get Table Row
  x-api-slug: microsoft-graph-api
  description: Get TableRow Retrieve the properties and relationships of tablerow
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)
  tags: Table, Row
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-get-openapi.md
- name: Microsoft Graph API Table Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableRow: Range Returns the range object associated with the entire
    row.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range
  tags: Table, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtrange-post-openapi.md
- name: Microsoft Graph API Table Row Range
  x-api-slug: microsoft-graph-api
  description: 'TableRow: Range Returns the range object associated with the entire
    row.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range
  tags: Table, Row, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post-openapi.md
- name: Microsoft Graph API Update Tablerow
  x-api-slug: microsoft-graph-api
  description: Update tablerow Update the properties of tablerow object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)
  tags: Tablerow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgt-patch-openapi.md
- name: Microsoft Graph API Update Tablerow
  x-api-slug: microsoft-graph-api
  description: Update tablerow Update the properties of tablerow object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)
  tags: Tablerow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-patch-openapi.md
- name: Microsoft Graph API Table Row Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableRowCollection: add Adds a new row to the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows/add
  tags: Table, Row, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsadd-post-openapi.md
- name: Microsoft Graph API Table Row Collection Add
  x-api-slug: microsoft-graph-api
  description: 'TableRowCollection: add Adds a new row to the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/add
  tags: Table, Row, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsadd-post-openapi.md
- name: Microsoft Graph API Table Row Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'TableRowCollection: ItemAt Gets a row based on its position in the
    collection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/rows/ItemAt
  tags: Table, Row, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsitemat-post-openapi.md
- name: Microsoft Graph API Table Row Collection Item At
  x-api-slug: microsoft-graph-api
  description: 'TableRowCollection: ItemAt Gets a row based on its position in the
    collection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/ItemAt
  tags: Table, Row, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsitemat-post-openapi.md
- name: Microsoft Graph API Table Sort Apply
  x-api-slug: microsoft-graph-api
  description: 'TableSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/apply
  tags: Table, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortapply-post-openapi.md
- name: Microsoft Graph API Table Sort Apply
  x-api-slug: microsoft-graph-api
  description: 'TableSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply
  tags: Table, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortapply-post-openapi.md
- name: Microsoft Graph API Table Sort Clear
  x-api-slug: microsoft-graph-api
  description: 'TableSort: clear Clears the sorting that is currently on the table.
    While this doesn''t modify the table''s ordering, it clears the state of the header
    buttons.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/clear
  tags: Table, Sort, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-openapi.md
- name: Microsoft Graph API Table Sort Clear
  x-api-slug: microsoft-graph-api
  description: 'TableSort: clear Clears the sorting that is currently on the table.
    While this doesn''t modify the table''s ordering, it clears the state of the header
    buttons.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/clear
  tags: Table, Sort, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-openapi.md
- name: Microsoft Graph API Get Table Sort
  x-api-slug: microsoft-graph-api
  description: Get TableSort Retrieve the properties and relationships of tablesort
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort
  tags: Table, Sort
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsort-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsort-get-openapi.md
- name: Microsoft Graph API Get Table Sort
  x-api-slug: microsoft-graph-api
  description: Get TableSort Retrieve the properties and relationships of tablesort
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort
  tags: Table, Sort
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsort-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsort-get-openapi.md
- name: Microsoft Graph API Table Sort Reapply
  x-api-slug: microsoft-graph-api
  description: 'TableSort: reapply Reapplies the current sorting parameters to the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/reapply
  tags: Table, Sort, Reapply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortreapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesltidnamegtsortreapply-post-openapi.md
- name: Microsoft Graph API Table Sort Reapply
  x-api-slug: microsoft-graph-api
  description: 'TableSort: reapply Reapplies the current sorting parameters to the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/reapply
  tags: Table, Sort, Reapply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortreapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortreapply-post-openapi.md
- name: Microsoft Graph API Get Thumbnail Set
  x-api-slug: microsoft-graph-api
  description: Get thumbnailSet Retrieve the properties and relationships of a thumbnailSet
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/root/thumbnails/{id}
  tags: Thumbnail, Set
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootthumbnailsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driverootthumbnailsid-get-openapi.md
- name: Microsoft Graph API Get Thumbnail Set
  x-api-slug: microsoft-graph-api
  description: Get thumbnailSet Retrieve the properties and relationships of a thumbnailSet
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drive/items/{id}/thumbnails/{id}
  tags: Thumbnail, Set
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driveitemsidthumbnailsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/driveitemsidthumbnailsid-get-openapi.md
- name: Microsoft Graph API Get Thumbnail Set
  x-api-slug: microsoft-graph-api
  description: Get thumbnailSet Retrieve the properties and relationships of a thumbnailSet
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/{id}/root/thumbnails/{id}
  tags: Thumbnail, Set
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesidrootthumbnailsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/drivesidrootthumbnailsid-get-openapi.md
- name: Microsoft Graph API Assign License
  x-api-slug: microsoft-graph-api
  description: assignLicense Add or remove subscriptions for the user. You can also
    enable and disable specific plans associated with a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/assignLicense
  tags: Assign, License
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameassignlicense-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameassignlicense-post-openapi.md
- name: Microsoft Graph API Delete A User
  x-api-slug: microsoft-graph-api
  description: Delete a user Delete user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-delete-openapi.md
- name: Microsoft Graph API User Find Meeting Times
  x-api-slug: microsoft-graph-api
  description: 'user: findMeetingTimes Find meeting time suggestions based on organizer
    and attendee availability, and time or location constraints specified as parameters.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/findMeetingTimes
  tags: User, Find, Meeting, Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mefindmeetingtimes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mefindmeetingtimes-post-openapi.md
- name: Microsoft Graph API User Find Meeting Times
  x-api-slug: microsoft-graph-api
  description: 'user: findMeetingTimes Find meeting time suggestions based on organizer
    and attendee availability, and time or location constraints specified as parameters.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/findMeetingTimes
  tags: User, Find, Meeting, Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamefindmeetingtimes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamefindmeetingtimes-post-openapi.md
- name: Microsoft Graph API Get A User
  x-api-slug: microsoft-graph-api
  description: Get a user Retrieve the properties and relationships of user object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettings-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/automaticRepliesSetting
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingsautomaticrepliessetting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingsautomaticrepliessetting-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/automaticRepliesSetting
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingsautomaticrepliessetting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingsautomaticrepliessetting-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/language
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingslanguage-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/language
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingslanguage-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/timeZone
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingstimezone-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettingstimezone-get-openapi.md
- name: Microsoft Graph API Get User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/timeZone
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingstimezone-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingstimezone-get-openapi.md
- name: Microsoft Graph API List Users
  x-api-slug: microsoft-graph-api
  description: List users Retrieve a list of user objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users
  tags: List, Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/users-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/users-get-openapi.md
- name: Microsoft Graph API List Calendar Groups
  x-api-slug: microsoft-graph-api
  description: List calendarGroups Get the user's calendar groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups
  tags: List, Calendar, Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroups-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendars-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{calendar_group_id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecalendargroupscalendar-group-idcalendars-get-openapi.md
- name: Microsoft Graph API List Calendars
  x-api-slug: microsoft-graph-api
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{calendar_group_id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupscalendar-group-idcalendars-get-openapi.md
- name: Microsoft Graph API List Calendar View
  x-api-slug: microsoft-graph-api
  description: List calendarView Get the occurrences, exceptions, and single instances
    of events in a calendar view defined by a time range, from the user's default
    calendar, or from some other calendar of the user's.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarView
  tags: List, Calendar, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarview-get-openapi.md
- name: Microsoft Graph API List Contact Folders
  x-api-slug: microsoft-graph-api
  description: List contactFolders Get the contact folder collection in the default
    Contacts folder of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders
  tags: List, Contact, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolder/{id}/childFolders/{id}/.../contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderidchildfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API List Contacts
  x-api-slug: microsoft-graph-api
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts
  tags: List, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API List Created Objects
  x-api-slug: microsoft-graph-api
  description: List createdObjects Get a list of directory objects that were created
    by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/createdObjects
  tags: List, Created, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecreatedobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecreatedobjects-get-openapi.md
- name: Microsoft Graph API List Direct Reports
  x-api-slug: microsoft-graph-api
  description: List directReports Get user's direct reports. Returns the users and
    contacts for whom this user is assigned as manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/directReports
  tags: List, Direct, Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamedirectreports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamedirectreports-get-openapi.md
- name: Microsoft Graph API List Events
  x-api-slug: microsoft-graph-api
  description: List events Get a list of event objects in the user's mailbox. The
    list contains single instance meetings and series masters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events
  tags: List, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameevents-get-openapi.md
- name: Microsoft Graph API List Mail Folders
  x-api-slug: microsoft-graph-api
  description: List mailFolders Get the mail folder collection under the root folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders
  tags: List, Mail, Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-get-openapi.md
- name: Microsoft Graph API List Manager
  x-api-slug: microsoft-graph-api
  description: List manager Get user's manager. Returns the user or contact assigned
    as the user's manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/manager
  tags: List, Manager
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemanager-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemanager-get-openapi.md
- name: Microsoft Graph API List Member Of
  x-api-slug: microsoft-graph-api
  description: List memberOf Get groups and directory roles that the user is a direct
    member of.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/memberOf
  tags: List, Member, Of
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamememberof-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamememberof-get-openapi.md
- name: Microsoft Graph API List Messages
  x-api-slug: microsoft-graph-api
  description: List messages Get the messages in the signed-in user's mailbox (including
    the Deleted Items and Clutter folders).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemessages-get-openapi.md
- name: Microsoft Graph API List Owned Devices
  x-api-slug: microsoft-graph-api
  description: List ownedDevices Get the list of devices that are owned by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/ownedDevices
  tags: List, Owned, Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-openapi.md
- name: Microsoft Graph API List Owned Objects
  x-api-slug: microsoft-graph-api
  description: List ownedObjects Get the list of directory objects that are owned
    by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/ownedObjects
  tags: List, Owned, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-openapi.md
- name: Microsoft Graph API List Registered Devices
  x-api-slug: microsoft-graph-api
  description: List registeredDevices Get the list of user's registered devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/registeredDevices
  tags: List, Registered, Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameregistereddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameregistereddevices-get-openapi.md
- name: Microsoft Graph API Create Calendar Group
  x-api-slug: microsoft-graph-api
  description: Create CalendarGroup Use this API to create a new CalendarGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups
  tags: Calendar, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroups-post-openapi.md
- name: Microsoft Graph API Create Calendar
  x-api-slug: microsoft-graph-api
  description: Create Calendar Use this API to create a new Calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendars-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecalendars-post-openapi.md
- name: Microsoft Graph API Create Contact Folder
  x-api-slug: microsoft-graph-api
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders
  tags: Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/contactFolders/{contactFolderId}/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API Create Contact
  x-api-slug: microsoft-graph-api
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/contactFolders/{contactFolderId}/contacts
  tags: Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API Create Event
  x-api-slug: microsoft-graph-api
  description: Create Event Create an event in the user's default calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events
  tags: Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnameevents-post-openapi.md
- name: Microsoft Graph API Create Mail Folder
  x-api-slug: microsoft-graph-api
  description: Create MailFolder Use this API to create a new mail folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders
  tags: Mail, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-openapi.md
- name: Microsoft Graph API Assign A Manager
  x-api-slug: microsoft-graph-api
  description: Assign a manager Use this API to assign a user's manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id}/manager/$ref
  tags: AssignManager
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidmanagerref-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersidmanagerref-put-openapi.md
- name: Microsoft Graph API Create User
  x-api-slug: microsoft-graph-api
  description: Create User Use this API to create a new User. The request body contains
    the user to create. At a minimum, you must specify the required properties for
    the user. You can optionally specify any other writable properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/users-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/users-post-openapi.md
- name: Microsoft Graph API User Reminder View
  x-api-slug: microsoft-graph-api
  description: 'user: reminderView Return a list of calendar reminders within the
    specified start and end times.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/reminderView(startDateTime=startDateTime-value,endDateTime=endDateTime-value)
  tags: User, Reminder, View
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamereminderviewstartdatetimestartdatetimevalueenddatetimeenddatetimevalue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamereminderviewstartdatetimestartdatetimevalueenddatetimeenddatetimevalue-get-openapi.md
- name: Microsoft Graph API Send Mail
  x-api-slug: microsoft-graph-api
  description: Send mail Send the message specified in the request body. The message
    is saved in the Sent Items folder by default.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/sendMail
  tags: Send, Mail
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamesendmail-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalnamesendmail-post-openapi.md
- name: Microsoft Graph API Update User
  x-api-slug: microsoft-graph-api
  description: Update user Update the properties of a user object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersid--userprincipalname-patch-openapi.md
- name: Microsoft Graph API Update User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Update user mailbox settings Update one or more settings for the user's
    mailbox. This includes settings for automatic replies (notify people automatically
    upon receipt of their email), locale, or time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettings-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/memailboxsettings-patch-openapi.md
- name: Microsoft Graph API Update User Mailbox Settings
  x-api-slug: microsoft-graph-api
  description: Update user mailbox settings Update one or more settings for the user's
    mailbox. This includes settings for automatic replies (notify people automatically
    upon receipt of their email), locale, or time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-patch-openapi.md
- name: Microsoft Graph API List Worksheets
  x-api-slug: microsoft-graph-api
  description: List worksheets Retrieve a list of worksheet objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets
  tags: List, Worksheets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheets-get-openapi.md
- name: Microsoft Graph API Create Table
  x-api-slug: microsoft-graph-api
  description: Create Table Use this API to create a new Table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables/$/add
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbooktablesadd-post-openapi.md
- name: Microsoft Graph API Worksheet Cell
  x-api-slug: microsoft-graph-api
  description: 'Worksheet: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/Cell(row=&lt;row&gt;,column=&lt;column&gt;)
  tags: Worksheet, Cell
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtcellrowltrowgtcolumnltcolumngt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtcellrowltrowgtcolumnltcolumngt-get-openapi.md
- name: Microsoft Graph API Worksheet Delete
  x-api-slug: microsoft-graph-api
  description: 'Worksheet: delete Deletes the worksheet from the workbook.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/delete
  tags: Worksheet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtdelete-post-openapi.md
- name: Microsoft Graph API Get Worksheet
  x-api-slug: microsoft-graph-api
  description: Get Worksheet Retrieve the properties and relationships of worksheet
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)
  tags: Worksheet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegt-get-openapi.md
- name: Microsoft Graph API List Names
  x-api-slug: microsoft-graph-api
  description: List names Retrieve a list of named item associated with the worksheet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets({id|name})/names
  tags: List, Names
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-openapi.md
- name: Microsoft Graph API Create Chart
  x-api-slug: microsoft-graph-api
  description: Create Chart Use this API to create a new Chart.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com///
  tags: Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/post-openapi.md
- name: Microsoft Graph API Create Table
  x-api-slug: microsoft-graph-api
  description: Create Table Use this API to create a new Table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables/$/add
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesadd-post-openapi.md
- name: Microsoft Graph API Worksheet Range
  x-api-slug: microsoft-graph-api
  description: 'Worksheet: Range Gets the range object specified by the address or
    name.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/Range
  tags: Worksheet, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API Update Worksheet
  x-api-slug: microsoft-graph-api
  description: Update worksheet Update the properties of worksheet object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)
  tags: Worksheet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegt-patch-openapi.md
- name: Microsoft Graph API Worksheet Used Range
  x-api-slug: microsoft-graph-api
  description: 'Worksheet: UsedRange The used range is the smallest range that encompasses
    any cells that have a value or formatting assigned to them. If the worksheet is
    blank, this function will return the top left cell.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/UsedRange
  tags: Worksheet, Used, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtusedrange-post-openapi.md
- name: Microsoft Graph API Worksheet Collection Add
  x-api-slug: microsoft-graph-api
  description: 'WorksheetCollection: add Adds a new worksheet to the workbook. The
    worksheet will be added at the end of existing worksheets. If you wish to activate
    the newly added worksheet, call ".activate() on it.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets/
  tags: Worksheet, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheets-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheets-post-openapi.md
- name: Microsoft Graph API Get Worksheet Protection
  x-api-slug: microsoft-graph-api
  description: Get WorksheetProtection Retrieve the properties and relationships of
    worksheetprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection
  tags: Worksheet, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotection-get-openapi.md
- name: Microsoft Graph API Worksheet Protection Protect
  x-api-slug: microsoft-graph-api
  description: 'WorksheetProtection: protect Protect a worksheet. It throws if the
    worksheet has been protected.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection/protect
  tags: Worksheet, Protection, Protect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionprotect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionprotect-post-openapi.md
- name: Microsoft Graph API Worksheet Protection Unprotect
  x-api-slug: microsoft-graph-api
  description: 'WorksheetProtection: unprotect Unprotect a worksheet'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection/unprotect
  tags: Worksheet, Protection, Unprotect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionunprotect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionunprotect-post-openapi.md
- name: Microsoft Graph API
  x-api-slug: microsoft-graph-api
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft Graph
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-graph/master/_listings/microsoft-graph/openapi.md
x-common:
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