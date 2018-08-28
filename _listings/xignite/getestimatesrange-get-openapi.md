---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Fact Set Estimates Get Estimates Range
  description: Get Estimates Range
  version: 1.0.0
host: factsetestimates.xignite.com
basePath: xFactSetEstimates.json/XigniteFactSetEstimates
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetEventsForRange:
    get:
      summary: Get Events For Range
      description: Get events for the specified range.
      operationId: postGeteventsforrange
      x-api-path-slug: geteventsforrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Events
      - Range
  /GetEventsForRangeLength:
    get:
      summary: Get Events For Range Length
      description: Get events for the date specified and next number of days past
        it.
      operationId: postGeteventsforrangelength
      x-api-path-slug: geteventsforrangelength-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Events
      - Range
      - Length
  /GetEventsReleasedForRange:
    get:
      summary: Get Events Released For Range
      description: Get events released for the specified range.
      operationId: postGeteventsreleasedforrange
      x-api-path-slug: geteventsreleasedforrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Events
      - Released
      - Range
  /GetEventsReleasedForRangeLength:
    get:
      summary: Get Events Released For Range Length
      description: Get events released for the date specified and next number of days
        past it.
      operationId: postGeteventsreleasedforrangelength
      x-api-path-slug: geteventsreleasedforrangelength-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Events
      - Released
      - Range
      - Length
  /GetHistoricalCrossRatesRange:
    get:
      summary: Get Historical Cross Rates Range
      description: This operation returns a range of cross-rates for a currency pair.
      operationId: postGethistoricalcrossratesrange
      x-api-path-slug: gethistoricalcrossratesrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Cross
      - Rates
      - Range
  /GetHistoricalCrossRatesBidAskRange:
    get:
      summary: Get Historical Cross Rates Bid Ask Range
      description: This operation returns a range of cross-rates for a currency pair.
      operationId: postGethistoricalcrossratesbaskrange
      x-api-path-slug: gethistoricalcrossratesbidaskrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Cross
      - Rates
      - Bid
      - Ask
      - Range
  /GetHistoricalMonthlyCrossRatesRange:
    get:
      summary: Get Historical Monthly Cross Rates Range
      description: This operation returns a complete range of stock quotes for a currency
        pair.
      operationId: postGethistoricalmonthlycrossratesrange
      x-api-path-slug: gethistoricalmonthlycrossratesrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Monthly
      - Cross
      - Rates
      - Range
  /GetEstimatesRange:
    get:
      summary: Get Estimates Range
      description: Get Estimates Range
      operationId: GetEstimatesRange
      x-api-path-slug: getestimatesrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Estimates
      - Range
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