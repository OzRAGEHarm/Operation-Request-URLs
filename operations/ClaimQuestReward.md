# ClaimQuestReward
Claim a reward from a completed quest by ID.

## URL(s)
*Profile: athena, MPC: fortnite* - **https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/ClaimQuestReward?profileId=athena&rvn=-1**
*Profile: campaign, MCP: fortnite* - **https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/ClaimQuestReward?profileId=campaign&rvn=-1**

## Attributes
Compatible Profiles: `athena`, `campaign`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "questId": ""
}
```

## Parameters
- `questId`: ID of completed quest
