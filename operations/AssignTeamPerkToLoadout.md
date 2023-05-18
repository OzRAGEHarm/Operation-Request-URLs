# AssignTeamPerkToLoadout
Assign a team perk to a loadout by ID.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/AssignTeamPerkToLoadout?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "teamPerkId": "",
    "loadoutId": ""
}
```

## Parameters
- `teamPerkId`: ID of team perk
- `loadoutId`: ID of loadout to assign team perk to
