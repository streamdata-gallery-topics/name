---
swagger: "2.0"
x-collection-name: Healthcare.gov
x-complete: 0
info:
  title: Healthcare.gov Get State Name Media Type Extension
  version: 1.0.0
  description: Returns pages content.
host: www.healthcare.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /blog/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Blog Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: blogpagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Blog
      - Page
      - Name
      - Media
      - Type
      - Extension
  /es/blog/{pageName}{mediaTypeExtension}:
    get:
      summary: GetBlog Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: esblogpagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Blog
      - Page
      - Name
      - Media
      - Type
      - Extension
  /es/glossary/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Glossary Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: esglossarypagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Glossary
      - Page
      - Name
      - Media
      - Type
      - Extension
  /es/question/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Question Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: esquestionpagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Question
      - Page
      - Name
      - Media
      - Type
      - Extension
  /es/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: espagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Page
      - Name
      - Media
      - Type
      - Extension
  /es/{stateName}{mediaTypeExtension}/:
    get:
      summary: Get State Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: esstatenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: stateName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - State
      - Name
      - Media
      - Type
      - Extension
  /glossary/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Glossary Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: glossarypagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Glossary
      - Page
      - Name
      - Media
      - Type
      - Extension
  /question/{pageName}{mediaTypeExtension}:
    get:
      summary: Get Question Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: questionpagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Question
      - Page
      - Name
      - Media
      - Type
      - Extension
  /{pageName}{mediaTypeExtension}:
    get:
      summary: Get Page Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: pagenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: pageName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Page
      - Name
      - Media
      - Type
      - Extension
  /{stateName}{mediaTypeExtension}/:
    get:
      summary: Get State Name Media Type Extension
      description: Returns pages content.
      operationId: returns-pages-content
      x-api-path-slug: statenamemediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      - in: path
        name: stateName
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - State
      - Name
      - Media
      - Type
      - Extension
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