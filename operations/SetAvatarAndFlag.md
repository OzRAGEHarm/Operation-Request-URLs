# SetAvatarAndFlag
Updates the current avatar and flag.

## URL(s)
**https://ut-public-service-prod11.ol.epicgames.com/ut/api/game/v2/profile/{accountID}/client/SetAvatarAndFlag?profileId=profile0&rvn=-1**

## Attributes
Compatible Profiles: `profile0`  
Supported MCPs: `ut`

## Payload
```json
{
    "newAvatar": "",
    "newFlag": ""
}
```

## Parameters
- `newAvatar`: ID of avatar (e.g. `UT.Avatar.0`)
- `newFlag`: ID of flag (e.g. `Unreal`)
