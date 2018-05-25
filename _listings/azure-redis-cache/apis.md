---
name: Azure Redis Cache
x-slug: azure-redis-cache
description: Azure Redis Cache is based on the popular open source Redis cache. It
  gives you access to a secure, dedicated Redis cache, managed by Microsoft and accessible
  from any application within Azure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Redis Cache
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Redis Cache API Operations List
  x-api-slug: azure-redis-cache-api
  description: Lists all of the available REST API operations of the Microsoft.Cache
    provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////providers/Microsoft.Cache/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/providersmicrosoft-cacheoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/providersmicrosoft-cacheoperations-get-openapi.md
- name: Azure Redis Cache API Redis Create
  x-api-slug: azure-redis-cache-api
  description: Create or replace (overwrite/recreate, with potential downtime) an
    existing Redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}
  tags: Redis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-put-openapi.md
- name: Azure Redis Cache API Redis Update
  x-api-slug: azure-redis-cache-api
  description: Update an existing Redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}
  tags: Redis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-patch-openapi.md
- name: Azure Redis Cache API Redis Delete
  x-api-slug: azure-redis-cache-api
  description: Deletes a Redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}
  tags: Redis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-delete-openapi.md
- name: Azure Redis Cache API Redis Get
  x-api-slug: azure-redis-cache-api
  description: Gets a Redis cache (resource description).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}
  tags: Redis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisname-get-openapi.md
- name: Azure Redis Cache API Redis List By Resource Group
  x-api-slug: azure-redis-cache-api
  description: Lists all Redis caches in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/
  tags: Redis Resource Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredis-get-openapi.md
- name: Azure Redis Cache API Redis List
  x-api-slug: azure-redis-cache-api
  description: Gets all Redis caches in the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Cache/Redis/
  tags: Redis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidprovidersmicrosoft-cacheredis-get-openapi.md
- name: Azure Redis Cache API Redis List Keys
  x-api-slug: azure-redis-cache-api
  description: Retrieve a Redis cache's access keys. This operation requires write
    permission to the cache resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/listKeys
  tags: Redis Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamelistkeys-post-openapi.md
- name: Azure Redis Cache API Redis Regenerate Key
  x-api-slug: azure-redis-cache-api
  description: Regenerate Redis cache's access keys. This operation requires write
    permission to the cache resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/regenerateKey
  tags: Redis Regenerate Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameregeneratekey-post-openapi.md
- name: Azure Redis Cache API Redis Force Reboot
  x-api-slug: azure-redis-cache-api
  description: Reboot specified Redis node(s). This operation requires write permission
    to the cache resource. There can be potential data loss.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/forceReboot
  tags: Redis Force Reboot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameforcereboot-post-openapi.md
- name: Azure Redis Cache API Redis Import Data
  x-api-slug: azure-redis-cache-api
  description: Import data into Redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/import
  tags: Redis Import Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameimport-post-openapi.md
- name: Azure Redis Cache API Redis Export Data
  x-api-slug: azure-redis-cache-api
  description: Export data from the redis cache to blobs in a container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/export
  tags: Redis Export Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameexport-post-openapi.md
- name: Azure Redis Cache API Firewall Rules List
  x-api-slug: azure-redis-cache-api
  description: Gets all firewall rules in the specified redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{cacheName}/firewallRules
  tags: Firewall Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacherediscachenamefirewallrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacherediscachenamefirewallrules-get-openapi.md
- name: Azure Redis Cache API Redis Firewall Rule Create Or Update
  x-api-slug: azure-redis-cache-api
  description: Create or update a redis cache firewall rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{cacheName}/firewallRules/{ruleName}
  tags: Redis Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacherediscachenamefirewallrulesrulename-put-openapi.md
- name: Azure Redis Cache API Redis Firewall Rule Get
  x-api-slug: azure-redis-cache-api
  description: Gets a single firewall rule in a specified redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{cacheName}/firewallRules/{ruleName}
  tags: Redis Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacherediscachenamefirewallrulesrulename-get-openapi.md
- name: Azure Redis Cache API Redis Firewall Rule Delete
  x-api-slug: azure-redis-cache-api
  description: Deletes a single firewall rule in a specified redis cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{cacheName}/firewallRules/{ruleName}
  tags: Redis Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacherediscachenamefirewallrulesrulename-delete-openapi.md
- name: Azure Redis Cache API Patch Schedules Create Or Update
  x-api-slug: azure-redis-cache-api
  description: Create or replace the patching schedule for Redis cache (requires Premium
    SKU).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/patchSchedules/default
  tags: Schedules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamepatchschedulesdefault-put-openapi.md
- name: Azure Redis Cache API Patch Schedules Delete
  x-api-slug: azure-redis-cache-api
  description: Deletes the patching schedule of a redis cache (requires Premium SKU).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/patchSchedules/default
  tags: Schedules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamepatchschedulesdefault-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamepatchschedulesdefault-delete-openapi.md
- name: Azure Redis Cache API Patch Schedules Get
  x-api-slug: azure-redis-cache-api
  description: Gets the patching schedule of a redis cache (requires Premium SKU).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/patchSchedules/default
  tags: Schedules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamepatchschedulesdefault-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnamepatchschedulesdefault-get-openapi.md
- name: Azure Redis Cache API
  x-api-slug: azure-redis-cache-api
  description: Azure Redis Cache is based on the popular open source Redis cache.
    It gives you access to a secure, dedicated Redis cache, managed by Microsoft and
    accessible from any application within Azure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com//
  tags: Azure Redis Cache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-redis-cache/master/_listings/azure-redis-cache/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/redis-cache/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cache/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/cache/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cache/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---