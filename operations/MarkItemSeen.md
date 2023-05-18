# MarkItemSeen
Marks an item as seen by ID.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/MarkItemSeen?profileId=athena&rvn=-1**

## Attributes
Compatible Profiles: `athena`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "itemIds": []
}
```

## Parameters
- `itemIds`: a list of item GUIDs in inventory (e.g. `2099ae21-e941-44b6-aecd-bcf67abd442a`)
