# RemoveGiftBox
Removes a list of gift boxes from a player's inventory.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/athena/api/game/v2/profile/{accountID}/client/RemoveGiftBox?profileId=common_core&rvn=-1**

## Attributes
Compatible Profiles: `common_core`  
Supported MCPs: `athena`

## Payload
```json
{
    "giftBoxItemIds": []
}
```

## Parameters
- `giftBoxItemIds`: list of gift box GUIDs in inventory (e.g. `ea74a9cc-a0d5-4625-adcb-9e8c5ff9c256`)
