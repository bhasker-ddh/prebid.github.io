---
layout: bidder
title: Colossus
description: Prebid Colossus Bidder Adapter
biddercode: colossus
usp_supported: true
schain_supported: true
coppa_supported: true
media_types: banner, video, native
userIds: all
gdpr: true
pbjs: true
pbs: true
pbs_app_supported: true
floors_supported: true
sidebarType: 1
---

### Prebid.Server Bid Params

{: .table .table-bordered .table-striped }
| Name           | Scope    | Description                                              | Example    | Type      |
|----------------|----------|----------------------------------------------------------|------------|-----------|
| `TagID` | optional | Placement Id will be generated on Colossus SSP Platform. | `'0'`        | `string` |
| `groupId` | optional | Group Id will be generated on Colossus SSP Platform. | `'0'`        | `string` |

You only need to use one parameter: either TagID or groupId

*For prebidJS parametres, look into colossusssp.md*
