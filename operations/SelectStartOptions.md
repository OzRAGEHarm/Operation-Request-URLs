# SelectStartOptions
Selects options to start the game with.

## URL(s)
**https://wex-public-service-prod11.ol.epicgames.com/wex/api/game/v2/profile/{accountID}/client/SelectStartOptions?profileId=profile0&rvn=-1**

## Attributes
Compatible Profiles: `profile0`  
Supported MCPs: `wex`

## Payload
```json
{
    "characterTemplateId": "",
    "displayName": "",
    "affiliateId": ""
}
```

## Parameters
- `characterTemplateId`: ID of the character to start with (e.g. `Character:Mage_Starter_Fire_Fireball_T03`)
- `displayName`: the current display name of the account
- `affiliateId`: ID of creator to support
