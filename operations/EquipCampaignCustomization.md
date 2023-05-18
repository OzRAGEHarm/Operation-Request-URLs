# EquipCampaignCustomization
Equips a customization in Fortnite: Save the World.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/EquipCampaignCustomization?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "slotName": "",
    "itemToSlot": ""
}
```

## Parameters
- `slotName`: enum `PersonalVehicle`
- `itemToSlot`: ID of item in slot
