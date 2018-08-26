---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Header Row Range
  description: 'Table: HeaderRowRange Gets the range object associated with header
    row of the table.'
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post
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
  /workbook/names(&lt;name&gt;)/range/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbooknamesltnamegtrangeoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/OffsetRange:
    post:
      summary: Range Offset Range
      description: 'Range: OffsetRange Gets an object which represents a range that''s
        offset from the specified range. The dimension of the returned range will
        match this range. If the resulting range is forced outside the bounds of the
        worksheet grid, an exception will be thrown.'
      operationId: Range:OffsetRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Offset
      - Range
  /workbook/names(&lt;name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooknamesltnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtrow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/names(&lt;name&gt;)/range/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbooknamesltnamegtrangeunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/unmerge:
    post:
      summary: Range Unmerge
      description: 'Range: unmerge Unmerge the range cells into separate cells.'
      operationId: Range:Unmerge
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Unmerge
  /workbook/names(&lt;name&gt;)/range:
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbooknamesltnamegtrange-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(address=&lt;range-address&gt;):
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range:
    patch:
      summary: Update Range
      description: Update range Update the properties of range object.
      operationId: UpdateRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
  /workbook/names(&lt;name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooknamesltnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/UsedRange:
    post:
      summary: Range Used Range
      description: 'Range: UsedRange Returns the used range of the given range object.'
      operationId: Range:UsedRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Used
      - Range
  /workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/names(&lt;name&gt;)/range/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbooknamesltnamegtrangeformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
    post:
      summary: Create Range Border
      description: Create RangeBorder Use this API to create a new RangeBorder.
      operationId: CreateRangeBorder
      x-api-path-slug: workbooknamesltnamegtrangeformatborders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
    post:
      summary: Create Range Border
      description: Create RangeBorder Use this API to create a new RangeBorder.
      operationId: CreateRangeBorder
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatborders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders:
    get:
      summary: List Range Border Collection
      description: List RangeBorderCollection Retrieve a list of rangeborder objects.
      operationId: ListRangeBorderCollection
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Range
      - Border
      - Collection
    post:
      summary: Create Range Border
      description: Create RangeBorder Use this API to create a new RangeBorder.
      operationId: CreateRangeBorder
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/names(&lt;name&gt;)/range/format/borders/ItemAt:
    post:
      summary: Range Border Collection Item At
      description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
      operationId: RangeBorderCollection:ItemAt
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders/ItemAt:
    post:
      summary: Range Border Collection Item At
      description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
      operationId: RangeBorderCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
      - Collection
      - Item
      - At
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders/ItemAt:
    post:
      summary: Range Border Collection Item At
      description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
      operationId: RangeBorderCollection:ItemAt
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
      - Collection
      - Item
      - At
  /workbook/names(&lt;name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooknamesltnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/names(&lt;name&gt;)/range/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbooknamesltnamegtrangeformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
  /workbook/names(&lt;name&gt;)/range/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbooknamesltnamegtrangeformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font
  /workbook/names(&lt;name&gt;)/range/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbooknamesltnamegtrangeformatautofitcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Columns
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Columns
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Columns
  /workbook/names(&lt;name&gt;)/range/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbooknamesltnamegtrangeformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/names(&lt;name&gt;)/range/format:
    get:
      summary: Get Range Format
      description: Get RangeFormat Retrieve the properties and relationships of rangeformat
        object.
      operationId: GetRangeFormat
      x-api-path-slug: workbooknamesltnamegtrangeformat-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format:
    get:
      summary: Get Range Format
      description: Get RangeFormat Retrieve the properties and relationships of rangeformat
        object.
      operationId: GetRangeFormat
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformat-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format:
    get:
      summary: Get Range Format
      description: Get RangeFormat Retrieve the properties and relationships of rangeformat
        object.
      operationId: GetRangeFormat
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
  /workbook/names(&lt;name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooknamesltnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
  /workbook/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
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