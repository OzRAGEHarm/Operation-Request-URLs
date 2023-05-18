# CraftWorldItem
Crafts a world item. Used in Fortnite's campaign.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/CraftWorldItem?profileId=theater0&rvn=-1**

## Attributes
Compatible Profiles: `theater0`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "targetSchematicItemId": "",
    "numTimesToCraft": 0,
    "targetSchematicTier": ""
}
```

## Parameters
- `targetSchematicItemId`: ID of schematic used to craft the item
- `numTimesToCraft`: number of times to craft the item
- `targetSchematicTier`: tier of the item in craft, in roman numerals (in lowercase):
   - i
   - ii
   - iii
   - iv
   - v
   - vi
   - no_tier
