---
description: >-
  Below you will find a listing of the recent changes we have made to our
  Platform API. This includes details of both breaking and non-breaking changes.
  The current version of our APIs is 2020-01-31.
---

# Platform change log

### 2020-03-03

* [\#504](https://github.com/reapit/foundations/issues/504) - It is now possible to request that related property information is included with `GET /propertyImages` and `GET /propertyImages/{id}` responses by using the `embed` parameter 

### 2020-03-02

* [\#495](https://github.com/reapit/foundations/issues/495) - It is now possible to request that related negotiator information is included with `GET /offices` and `GET /offices/{id}` responses by using the `embed` parameter 
* [\#483](https://github.com/reapit/foundations/issues/483) - It is now possible to request that related office information is included with `GET /negotiators` and `GET /negotiators/{id}` responses by using the `embed` parameter

### 2020-02-24

* [\#327](https://github.com/reapit/foundations/issues/327) - Added endpoints to present the available types of journal entry that have been configured a customer environment

### 2020-02-20

* [\#383](https://github.com/reapit/foundations/issues/383) - Fixed issue where requests missing the required authorization header would return malformed error response


