---
swagger: "2.0"
x-collection-name: CircleCI
x-complete: 0
info:
  title: CircleCI Parameters Project Username Project
  description: Parameters project username project.
  version: 1.0.0
host: circleci.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /project/{username}/{project}:
    get:
      summary: Get Project Username Project
      description: Build summary for each of the last 30 builds for a single git repo.
      operationId: getProjectUsernameProject
      x-api-path-slug: projectusernameproject-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
    parameters:
      summary: Parameters Project Username Project
      description: Parameters project username project.
      operationId: parametersProjectUsernameProject
      x-api-path-slug: projectusernameproject-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
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