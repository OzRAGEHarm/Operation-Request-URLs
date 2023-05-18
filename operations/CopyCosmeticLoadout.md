# CopyCosmeticLoadout
Copies or saves a cosmetic loadout.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/?profileId=athena&rvn=-1**

## Attributes
Compatible Profiles: `athena`
Supported MCPs: `fortnite`

## Payload
```json
{
    "optNewNameForTarget": "",
    "sourceIndex": "",
    "targetIndex": ""
}
```

- `optNewNameForTarget`: If you save a cosmetic loadout you can change this to the new name of the loadout, leaving the string empty will not change the loadout's name.
- `sourceIndex`: Index of the loadout you want to copy (e.g. 1). `targetIndex` has to be `0` if you want to copy a loadout.
- `targetIndex`: Index of the loadout you want to save (e.g. 1). `sourceIndex` has to be `0` if you want to save a loadout.

