# AssignHeroToLoadout
Assign a hero to a loadout by ID.

## URL
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/AssignHeroToLoadout?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "slotName": "",
    "loadoutId": "",
    "heroId": ""
}
```

## Parameters
- `slotName`: name of slot
- `loadoutId`: ID of loadout to assign hero to
- `heroId`: ID of hero
