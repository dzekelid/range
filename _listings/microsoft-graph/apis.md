---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Range
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - Named Item Range
  x-api-slug: workbooknamesltnamegtrange-post
  description: 'NamedItem: Range Returns the range object that is associated with
    the name. Throws an exception if the named item''s type is not a range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-openapi.md
- name: Microsoft Graph API - Range Bounding Rect
  x-api-slug: workbooknamesltnamegtrangeboundingrect-post
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeboundingrect-post-openapi.md
- name: Microsoft Graph API - Range Bounding Rect
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post-openapi.md
- name: Microsoft Graph API - Range Bounding Rect
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post-openapi.md
- name: Microsoft Graph API - Range Cell
  x-api-slug: workbooknamesltnamegtrangecell-post
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangecell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangecell-post-openapi.md
- name: Microsoft Graph API - Range Cell
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtcell-post
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcell-post-openapi.md
- name: Microsoft Graph API - Range Cell
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecell-post
  description: 'Range: Cell Gets the range object containing the single cell based
    on row and column numbers. The cell can be outside the bounds of its parent range,
    so long as it''s stays within the worksheet grid. The returned cell is located
    relative to the top left cell of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecell-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecell-post-openapi.md
- name: Microsoft Graph API - Range Clear
  x-api-slug: workbooknamesltnamegtrangeclear-post
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-openapi.md
- name: Microsoft Graph API - Range Clear
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtclear-post
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-openapi.md
- name: Microsoft Graph API - Range Clear
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-openapi.md
- name: Microsoft Graph API - Range Column
  x-api-slug: workbooknamesltnamegtrangecolumn-post
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangecolumn-post-openapi.md
- name: Microsoft Graph API - Range Column
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtcolumn-post
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtcolumn-post-openapi.md
- name: Microsoft Graph API - Range Column
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post
  description: 'Range: Column Gets a column contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post-openapi.md
- name: Microsoft Graph API - Range Delete
  x-api-slug: workbooknamesltnamegtrangedelete-post
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangedelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangedelete-post-openapi.md
- name: Microsoft Graph API - Range Delete
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtdelete-post
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtdelete-post-openapi.md
- name: Microsoft Graph API - Range Delete
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post
  description: 'Range: delete Deletes the cells associated with the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangedelete-post-openapi.md
- name: Microsoft Graph API - Range Entire Column
  x-api-slug: workbooknamesltnamegtrangeentirecolumn-post
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirecolumn-post-openapi.md
- name: Microsoft Graph API - Range Entire Column
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post-openapi.md
- name: Microsoft Graph API - Range Entire Column
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post
  description: 'Range: EntireColumn Gets an object that represents the entire column
    of the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post-openapi.md
- name: Microsoft Graph API - Range Entire Row
  x-api-slug: workbooknamesltnamegtrangeentirerow-post
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeentirerow-post-openapi.md
- name: Microsoft Graph API - Range Entire Row
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtentirerow-post
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtentirerow-post-openapi.md
- name: Microsoft Graph API - Range Entire Row
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post-openapi.md
- name: Microsoft Graph API - Range Offset Range
  x-api-slug: workbooknamesltnamegtrangeoffsetrange-post
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeoffsetrange-post-openapi.md
- name: Microsoft Graph API - Range Offset Range
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtoffsetrange-post-openapi.md
- name: Microsoft Graph API - Range Offset Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post
  description: 'Range: OffsetRange Gets an object which represents a range that''s
    offset from the specified range. The dimension of the returned range will match
    this range. If the resulting range is forced outside the bounds of the worksheet
    grid, an exception will be thrown.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeoffsetrange-post-openapi.md
- name: Microsoft Graph API - Range Row
  x-api-slug: workbooknamesltnamegtrangerow-post
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangerow-post-openapi.md
- name: Microsoft Graph API - Range Row
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtrow-post
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtrow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtrow-post-openapi.md
- name: Microsoft Graph API - Range Row
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangerow-post
  description: 'Range: Row Gets a row contained in the range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangerow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangerow-post-openapi.md
- name: Microsoft Graph API - Range Unmerge
  x-api-slug: workbooknamesltnamegtrangeunmerge-post
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph API - Range Unmerge
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtunmerge-post
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-openapi.md
- name: Microsoft Graph API - Range Unmerge
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph API - Update Range
  x-api-slug: workbooknamesltnamegtrange-patch
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrange-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrange-patch-openapi.md
- name: Microsoft Graph API - Update Range
  x-api-slug: workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeaddressltrangeaddressgt-patch-openapi.md
- name: Microsoft Graph API - Update Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-patch
  description: Update range Update the properties of range object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-patch-openapi.md
- name: Microsoft Graph API - Range Used Range
  x-api-slug: workbooknamesltnamegtrangeusedrange-post
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeusedrange-post-openapi.md
- name: Microsoft Graph API - Range Used Range
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtusedrange-post
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtusedrange-post-openapi.md
- name: Microsoft Graph API - Range Used Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post
  description: 'Range: UsedRange Returns the used range of the given range object.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeusedrange-post-openapi.md
- name: Microsoft Graph API - Get Range Border
  x-api-slug: workbooknamesltnamegtrangeformatbordersltsideindexgt-get
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API - Get Range Border
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API - Get Range Border
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph API - List Range Border Collection
  x-api-slug: workbooknamesltnamegtrangeformatborders-get
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph API - List Range Border Collection
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatborders-get
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-openapi.md
- name: Microsoft Graph API - List Range Border Collection
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph API - Range Border Collection Item At
  x-api-slug: workbooknamesltnamegtrangeformatbordersitemat-post
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph API - Range Border Collection Item At
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-openapi.md
- name: Microsoft Graph API - Range Border Collection Item At
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph API - Range Fill Clear
  x-api-slug: workbooknamesltnamegtrangeformatfillclear-post
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph API - Range Fill Clear
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-openapi.md
- name: Microsoft Graph API - Range Fill Clear
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph API - Get Range Fill
  x-api-slug: workbooknamesltnamegtrangeformatfill-get
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph API - Get Range Fill
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfill-get
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-openapi.md
- name: Microsoft Graph API - Get Range Fill
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph API - Get Range Font
  x-api-slug: workbooknamesltnamegtrangeformatfont-get
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfont-get-openapi.md
- name: Microsoft Graph API - Get Range Font
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfont-get
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfont-get-openapi.md
- name: Microsoft Graph API - Get Range Font
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get
  description: Get RangeFont Retrieve the properties and relationships of rangefont
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get-openapi.md
- name: Microsoft Graph API - Range Format Autofit Columns
  x-api-slug: workbooknamesltnamegtrangeformatautofitcolumns-post
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API - Range Format Autofit Columns
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API - Range Format Autofit Columns
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph API - Range Format Autofit Rows
  x-api-slug: workbooknamesltnamegtrangeformatautofitrows-post
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitrows-post-openapi.md
- name: Microsoft Graph API - Range Format Autofit Rows
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post-openapi.md
- name: Microsoft Graph API - Range Format Autofit Rows
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post
  description: 'RangeFormat: autofitRows Changes the height of the rows of the current
    range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post-openapi.md
- name: Microsoft Graph API - Get Range Format
  x-api-slug: workbooknamesltnamegtrangeformat-get
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformat-get-openapi.md
- name: Microsoft Graph API - Get Range Format
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformat-get
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformat-get-openapi.md
- name: Microsoft Graph API - Get Range Format
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get
  description: Get RangeFormat Retrieve the properties and relationships of rangeformat
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformat-get-openapi.md
- name: Microsoft Graph API - Create Range Border
  x-api-slug: workbooknamesltnamegtrangeformatborders-post
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph API - Create Range Border
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtformatborders-post
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-openapi.md
- name: Microsoft Graph API - Create Range Border
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph API - Range Sort Apply
  x-api-slug: workbooknamesltnamegtrangesortapply-post
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph API - Range Sort Apply
  x-api-slug: workbookworksheetsltidnamegtrangeltaddressgtsortapply-post
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-openapi.md
- name: Microsoft Graph API - Range Sort Apply
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph API - Table Data Body Range
  x-api-slug: workbooktablesltidnamegtdatabodyrange-post
  description: 'Table: DataBodyRange Gets the range object associated with the data
    body of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API - Table Data Body Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post
  description: 'Table: DataBodyRange Gets the range object associated with the data
    body of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API - Table Header Row Range
  x-api-slug: workbooktablesltidnamegtheaderrowrange-post
  description: 'Table: HeaderRowRange Gets the range object associated with header
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API - Table Header Row Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post
  description: 'Table: HeaderRowRange Gets the range object associated with header
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API - Table Range
  x-api-slug: workbooktablesltidnamegtrange-post
  description: 'Table: Range Gets the range object associated with the entire table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtrange-post-openapi.md
- name: Microsoft Graph API - Table Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtrange-post
  description: 'Table: Range Gets the range object associated with the entire table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrange-post-openapi.md
- name: Microsoft Graph API - Table Total Row Range
  x-api-slug: workbooktablesltidnamegttotalrowrange-post
  description: 'Table: TotalRowRange Gets the range object associated with totals
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API - Table Total Row Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post
  description: 'Table: TotalRowRange Gets the range object associated with totals
    row of the table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API - Table Column Data Body Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post
  description: 'TableColumn: DataBodyRange Gets the range object associated with the
    data body of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API - Table Column Data Body Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post
  description: 'TableColumn: DataBodyRange Gets the range object associated with the
    data body of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post-openapi.md
- name: Microsoft Graph API - Table Column Header Row Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API - Table Column Header Row Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post-openapi.md
- name: Microsoft Graph API - Table Column Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-post
  description: 'TableColumn: Range Gets the range object associated with the entire
    column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API - Table Column Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post
  description: 'TableColumn: Range Gets the range object associated with the entire
    column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API - Table Column Total Row Range
  x-api-slug: workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post
  description: 'TableColumn: TotalRowRange Gets the range object associated with the
    totals row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API - Table Column Total Row Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post
  description: 'TableColumn: TotalRowRange Gets the range object associated with the
    totals row of the column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post-openapi.md
- name: Microsoft Graph API - Table Row Range
  x-api-slug: workbooktablesltidnamegtrowsltindexgtrange-post
  description: 'TableRow: Range Returns the range object associated with the entire
    row.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbooktablesltidnamegtrowsltindexgtrange-post-openapi.md
- name: Microsoft Graph API - Table Row Range
  x-api-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post
  description: 'TableRow: Range Returns the range object associated with the entire
    row.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post-openapi.md
- name: Microsoft Graph API - Worksheet Range
  x-api-slug: workbookworksheetsltidnamegtrange-post
  description: 'Worksheet: Range Gets the range object specified by the address or
    name.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrange-post-openapi.md
- name: Microsoft Graph API - Worksheet Used Range
  x-api-slug: workbookworksheetsltidnamegtusedrange-post
  description: 'Worksheet: UsedRange The used range is the smallest range that encompasses
    any cells that have a value or formatting assigned to them. If the worksheet is
    blank, this function will return the top left cell.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtusedrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/range/master/_listings/microsoft-graph/workbookworksheetsltidnamegtusedrange-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---