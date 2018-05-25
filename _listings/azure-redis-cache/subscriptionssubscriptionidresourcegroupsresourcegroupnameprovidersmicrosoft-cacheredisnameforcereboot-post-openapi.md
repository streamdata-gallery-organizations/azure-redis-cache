---
swagger: "2.0"
x-collection-name: Azure Redis Cache
x-complete: 0
info:
  title: Azure Redis Cache API Redis Force Reboot
  description: Reboot specified Redis node(s). This operation requires write permission
    to the cache resource. There can be potential data loss.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.Cache/operations:
    get:
      summary: Operations List
      description: Lists all of the available REST API operations of the Microsoft.Cache
        provider.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-cacheoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}:
    put:
      summary: Redis Create
      description: Create or replace (overwrite/recreate, with potential downtime)
        an existing Redis cache.
      operationId: Redis_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-put
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Create Redis operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis
    patch:
      summary: Redis Update
      description: Update an existing Redis cache.
      operationId: Redis_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-patch
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Update Redis operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis
    delete:
      summary: Redis Delete
      description: Deletes a Redis cache.
      operationId: Redis_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-delete
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis
    get:
      summary: Redis Get
      description: Gets a Redis cache (resource description).
      operationId: Redis_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-get
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/:
    get:
      summary: Redis List By Resource Group
      description: Lists all Redis caches in a resource group.
      operationId: Redis_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredis-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Resource Group
  /subscriptions/{subscriptionId}/providers/Microsoft.Cache/Redis/:
    get:
      summary: Redis List
      description: Gets all Redis caches in the specified subscription.
      operationId: Redis_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-cacheredis-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Redis
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/listKeys:
    post:
      summary: Redis List Keys
      description: Retrieve a Redis cache's access keys. This operation requires write
        permission to the cache resource.
      operationId: Redis_ListKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamelistkeys-post
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Keys
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/regenerateKey:
    post:
      summary: Redis Regenerate Key
      description: Regenerate Redis cache's access keys. This operation requires write
        permission to the cache resource.
      operationId: Redis_RegenerateKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameregeneratekey-post
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Specifies which key to regenerate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Regenerate Key
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/forceReboot:
    post:
      summary: Redis Force Reboot
      description: Reboot specified Redis node(s). This operation requires write permission
        to the cache resource. There can be potential data loss.
      operationId: Redis_ForceReboot
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameforcereboot-post
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Specifies which Redis node(s) to reboot
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Force Reboot
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