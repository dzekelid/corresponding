---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Return list of tasks, corresponding to task ids passed in.
  version: 1.0.0
  description: Return list of tasks, corresponding to task ids passed in..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/chat/unreadsummary:
    get:
      summary: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread.
      description: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread..
      operationId: Chat_UnreadSummary
      x-api-path-slug: apichatunreadsummary-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - Unread
      - Chat
      - Messagesthe
      - Negotiator
      - Plus
      - List
      - Of
      - Corresponding
      - Message
      - Ids
      - Which
      - Are
      - Unread
  /api/todo/gettodosbyid:
    get:
      summary: Return list of tasks, corresponding to task ids passed in.
      description: Return list of tasks, corresponding to task ids passed in..
      operationId: DefaultToDo_GetTodosByIdByids
      x-api-path-slug: apitodogettodosbyid-get
      parameters:
      - in: query
        name: ids
        description: List of task ids
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - List
      - Of
      - Tasks
      - ""
      - Corresponding
      - To
      - Task
      - Ids
      - Passed
      - In
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