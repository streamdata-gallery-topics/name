---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 1
info:
  title: Reverse Name Server API
  description: list-of-domains-that-share-the-same-primary-name-server
  version: 1.0.0
host: api.domaintools.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{domain]/name-server-domains/:
    get:
      summary: Reverse Name Server
      description: List of domains that share the same primary name server
      operationId: reverseNameServer
      x-api-path-slug: domainnameserverdomains-get
      parameters:
      - in: query
        name: limit
        description: Limits the size of the domain list than can appear in a response
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Reverse Name Server
---