# ClaimMfaEnabled
Claim a reward as a result of enabling 2FA.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/ClaimMfaEnabled?profileId=common_core&rvn=-1**

## Attributes
Compatible Profiles: `common_core`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "bClaimForStw": false
}
```

## Parameters
- `bClaimForStw`: determines if the reward should be claimed for STW
