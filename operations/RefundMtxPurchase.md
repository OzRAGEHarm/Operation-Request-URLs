# RefundMtxPurchase
Refunds an in-game purchase by ID.

## URL(s)
**https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountID}/client/RefundMtxPurchase?profileId=common_core&rvn=-1**

## Attributes
Compatible Profiles: `common_core`  
Supported MCPs: `fortnite`

## Payload
```json
{
    "purchaseId": "",
    "quickReturn": true
}
```

## Parameters
- `purchaseId`: GUID of purchase in inventory (e.g. `60f19b18-6543-41c4-afa2-294a78125ef1`)
- `quickReturn`: determines which type of refund to perform - setting this to `true` will use the `Cancel Purchase` feature
