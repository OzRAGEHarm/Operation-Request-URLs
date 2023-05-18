# RefundItem
Refunds an item by ID. This is only for Fortnite's campaign mode.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/athena/api/game/v2/profile/{accountID}/client/RefundItem?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `athena`

## Payload
```json
{
    "targetItemId": ""
}
```

## Parameters
- `targetItemId`: ID of item to refund
