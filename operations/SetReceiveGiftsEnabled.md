# SetReceiveGiftsEnabled
Sets whether a user can receive gifts.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/SetReceiveGiftsEnabled?profileId=common_core&rvn=-1**

## Attributes
Compatible Profiles: `common_core`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "bReceiveGifts": true
}
```

## Parameters
- `bReceiveGifts`: determines whether a user can receive gifts
