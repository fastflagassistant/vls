
my personal fast flag list, given to by trusted people
- content used to collect fast flags

### Mesh Noclip V1
```json

{
    "DFIntPhysicsDecompForceUpgradeVersion": "1500"
}
```
### Mesh Noclip V2

- Used for terrain noclip too
```json

{
   "DFIntBulletContactBreakOrthogonalThresholdActivatePercent": 2147483647,
   "DFIntBulletContactBreakThresholdPercent": -2147483648,
   "DFIntBulletContactBreakOrthogonalThresholdPercent": -2147483648
}
```
### Mesh Noclip V3 (Combined)
```json
{
   "DFIntPhysicsDecompForceUpgradeVersion": "1500",
   "DFIntBulletContactBreakOrthogonalThresholdActivatePercent": 2147483647,
   "DFIntBulletContactBreakThresholdPercent": -2147483648,
   "DFIntBulletContactBreakOrthogonalThresholdPercent": -2147483648
}
```
### No knockback in certain games
- In slap battles its bannable (USE AT YOUR OWN RISK)
```json
{
   "DFIntGameNetLocalSpaceMaxSendIndex": "100000",
   "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```
### ESP??
- You cant see through walls with it
```json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest4": "False",
    "FFlagEnableInGameMenuChrome": "False",
    "FFlagEnableInGameMenuSongbirdABTest": "False"
}
```
### What people call "Wall Glide"
- Change to higher negative values for more distance
```json
 {
     "DFIntMaximumUnstickForceInGs": "-10"
 }
```
### Fling parts
- Stand ontop of a part to fling it
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### No animations
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Max raycast distance
- breaks leg collision and some games under 3
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```
### Fling you or a part that is below you
```json
{
"DFIntSolidFloorMassMultTenth": "-2147483647"
"DFIntSolidFloorPercentForceApplication": "-450",
"DFIntNonSolidFloorPercentForceApplication": "-3200"
}
```
### Fling you or a part that is below you V2 (More stable)
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### Drive vehicles slow (Not verified)
```json
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```
### Drunk
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
}
```
### Even funnier drunk fflag
```json
{
  "DFIntMaxAltitudePDHipHeightPercent": "-10000",
  "DFIntNewPDAltitudeNoForceZonePercent": "14673",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999"
}
```
### You dont have animations for the server but you do for your client
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Well known speed fflag (Buggy)
```json
{
     "DFIntMaximumUnstickForceInGs": "-1"
     "DFIntRaycastMaxDistance": "0"
}
```
## Invisible 1 (Freezes you in place)
```json
{
    "DFIntGameNetOptimizeParallelPhysicsSendAssemblyBatch": "-1",
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "-1"
}
```
### Invisible 2 (restricts the client from moving through the server)
```json
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
- MORE UPDATES SOOOONNNNNNNNNNNNNNNNNNN
- join discord (its empty bc im lonely :( )


SKELETON ESP WHAT HOW WHEN WHY
```json
{
  "DFFlagDebugDrawEnable": "True",
  "DFFlagAnimatorDrawSkeletonAll": "True",
  "DFIntAnimatorDrawSkeletonScalePercent": "6",
  "DFFlagAnimatorDrawSkeletonAttachments": "False",
  "DFFlagAnimatorDrawSkeletonText": "False",
  "FFlagDataModelPatcherForceLocal": "True"
}
```

how it works:
```json
{
  "DFFlagDebugDrawEnable": "True", - enables?
  "DFFlagAnimatorDrawSkeletonAll": "True", draws the skeleton for all
  "DFIntAnimatorDrawSkeletonScalePercent": "6", scale for it idk
  "DFFlagAnimatorDrawSkeletonAttachments": "False", shows you the animation constraints
  "DFFlagAnimatorDrawSkeletonText": "False", self explanatory
  "FFlagDataModelPatcherForceLocal": "True" just keep this on
}
```
