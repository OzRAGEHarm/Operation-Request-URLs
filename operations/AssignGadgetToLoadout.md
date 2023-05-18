# AssignGadgetToLoadout
Assign a gadget to a loadout by ID.

## URL
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/AssignGadgetToLoadout?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "gadgetId": "",
    "loadoutId": "",
    "slotIndex": 0
}
```

## Parameters
- `gadgetId`: ID of gadget
- `loadoutId`: ID of loadout to assign gadget to
- `slotIndex`: ID of gadget slot to assign gadget to
