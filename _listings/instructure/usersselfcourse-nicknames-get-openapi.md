---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API List course nicknames
  description: List course nicknames.
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
  /users/self/course_nicknames:
    delete:
      summary: Clear course nicknames
      description: Clear course nicknames.
      operationId: clear-course-nicknames
      x-api-path-slug: usersselfcourse-nicknames-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - Self
      - Course
      - Nicknames
    get:
      summary: List course nicknames
      description: List course nicknames.
      operationId: list-course-nicknames
      x-api-path-slug: usersselfcourse-nicknames-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Self
      - Course
      - Nicknames
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