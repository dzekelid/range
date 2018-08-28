swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 1
info:
  title: GoToWebinar API
  description: todo-add-description
  version: 1.0.0
host: api.getgo.com
basePath: /G2W/rest/organizers
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/reports/organizers/{organizerKey}/sessions ':
    post:
      summary: Get Sessions by Date Range
      description: Get sessions by date range.
      operationId: ReportsOrganizersSessionsByOrganizerKeyPost
      x-api-path-slug: reportsorganizersorganizerkeysessions-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      responses:
        200:
          description: OK
      tags:
      - Sessions
      - By
      - Date
      - Range