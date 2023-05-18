# SetMtxPlatform
Set the current MTX platform used for purchases in the item shop.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/SetMtxPlatform?profileId=common_core&rvn=-1**

## Attributes
Compatible Profiles: `common_core`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "newPlatform": ""
}
```

## Parameters
- `newPlatform`: the platform that will be used for purchases
   - Epic
   - PSN
   - Live
   - Shared
   - EpicPC
   - EpicPCKorea
   - IOSAppStore
   - EpicAndroid
   - Nintendo
   - WeGame
   - Samsung
