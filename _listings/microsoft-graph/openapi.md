swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /users/{id|userPrincipalName}/messages/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/mailFolders/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/events/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnameeventsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/calendars/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendarsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contacts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}/contacts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersidcontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /groups/{id}/threads/{id}/posts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: groupsidthreadsidpostsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}:
    get:
      summary: Get Multi Value Legacy Extended Property
      description: Get multiValueLegacyExtendedProperty Get a resource instance that
        contains a multi-value extended property by using $expand.
      operationId: GetMultiValueLegacyExtendedProperty
      x-api-path-slug: groupsidconversationsidthreadsidpostsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Value
      - Legacy
      - Extended
      - Property
  /me/messages:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: memessages-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/mailFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: memailfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/mailFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/events:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: meevents-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/calendars:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: mecalendars-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/calendars:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendars-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}/contacts:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersidcontacts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/contactfolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: mecontactfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /groups/{id}/threads/{id}/posts:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: groupsidthreadsidposts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /groups/{id}/conversations/{id}/threads/{id}/posts:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: groupsidconversationsidthreadsidposts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property