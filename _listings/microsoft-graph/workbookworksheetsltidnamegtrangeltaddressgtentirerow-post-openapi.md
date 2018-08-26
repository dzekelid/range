---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Entire Row
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/Range:
    post:
      summary: Named Item Range
      description: 'NamedItem: Range Returns the range object that is associated with
        the name. Throws an exception if the named item''s type is not a range.'
      operationId: NamedItem:Range
      x-api-path-slug: workbooknamesltnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Named
      - Item
      - Range
  /workbook/names(&lt;name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooknamesltnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/names(&lt;name&gt;)/range/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbooknamesltnamegtrangecell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Cell:
    post:
      summary: Range Cell
      description: 'Range: Cell Gets the range object containing the single cell based
        on row and column numbers. The cell can be outside the bounds of its parent
        range, so long as it''s stays within the worksheet grid. The returned cell
        is located relative to the top left cell of the range.'
      operationId: Range:Cell
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecell-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Cell
  /workbook/names(&lt;name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooknamesltnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/names(&lt;name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooknamesltnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/names(&lt;name&gt;)/range/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbooknamesltnamegtrangedelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/delete:
    post:
      summary: Range Delete
      description: 'Range: delete Deletes the cells associated with the range.'
      operationId: Range:Delete
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/names(&lt;name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooknamesltnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/names(&lt;name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooknamesltnamegtrangeentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
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