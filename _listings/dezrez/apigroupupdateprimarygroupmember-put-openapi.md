---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Return the Groups with appointments between a given date range, ordered
    by appointments Count
  version: 1.0.0
  description: Return the groups with appointments between a given date range, ordered
    by appointments count.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/group/updateprimarygroupmember:
    put:
      summary: Return the Groups with appointments between a given date range, ordered
        by appointments Count
      description: Return the groups with appointments between a given date range,
        ordered by appointments count.
      operationId: Group_UpdatePrimaryGroupMemberByfilter
      x-api-path-slug: apigroupupdateprimarygroupmember-put
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - Groups
      - Appointments
      - Between
      - Given
      - Date
      - Range
      - ""
      - Ordered
      - By
      - Appointments
      - Count
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