---
swagger: "2.0"
x-collection-name: Codefresh
x-complete: 0
info:
  title: Codefresh Get Pipelines Name
  description: Get pipelines name.
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pipelines/{name}:
    get:
      summary: Get Pipelines Name
      description: Get pipelines name.
      operationId: getPipelinesName
      x-api-path-slug: pipelinesname-get
      parameters:
      - in: path
        name: name
        description: Name of pipeline
      responses:
        200:
          description: OK
      tags:
      - Pipelines
      - Name
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