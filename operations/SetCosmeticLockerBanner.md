# SetCosmeticLockerBanner
Equip an banner in the Battle Royale locker.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/SetCosmeticLockerBanner?profileId=athena&rvn=-1**

## Attributes
Compatible Profiles: `athena`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "bannerColorTemplateName": "",
    "bannerIconTemplateName": "",
    "lockerItem": "6ecfc0af-53ae-464f-aa68-238ecfc0502f"
}
```

## Parameters
- `bannerColorTemplateName`: ID of banner color (e.g. `DefaultColor22`)
- `bannerIconTemplateName`: ID of banner Icon (e.g. `BRS12_Cowboy`)
- `lockerItem`: GUID of item in inventory (e.g. `2099ae21-e941-44b6-aecd-bcf67abd442a`)
