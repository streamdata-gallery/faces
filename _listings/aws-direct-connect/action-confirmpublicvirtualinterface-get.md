---
swagger: "2.0"
info:
  title: AWS Direct Connect API Confirm Public Virtual Interface
  version: 1.0.0
  description: Accept ownership of a public virtual interface created by another customer.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ConfirmPublicVirtualInterface:
    get:
      summary: ' Confirm Public Virtual Interface '
      description: Accept ownership of a public virtual interface created by another
        customer
      operationId: confirmPublicVirtualInterface
      parameters:
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - private virtual interfaces
definitions: []
x-collection-name: AWS Direct Connect
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