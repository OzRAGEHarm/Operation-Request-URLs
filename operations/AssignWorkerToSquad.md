# AssignWorkerToSquad
Assign a worker to a squad by ID.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/AssignWorkerToSquad?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "squadId": "",
    "characterId": ""
}
```

## Parameters
- `squadId`: ID of a squad
- `characterId`: ID of a character
