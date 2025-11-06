# Felipe-s-Lib
Okay, here's my contribution: This library includes: PVZDB for Thymed Events (LTE) to work Worldmap Vertical Movement Everything included in the RenoJson library and the Blazey library (I give them credit for their contributions)

# PVZDB
Includes the offsets for current versions so that LTE works; do not modify anything.

# Worldmap Vertical Movement
If you want, you can remove it simply by deleting the code and the function.

# Build Instructions

Building this repo is the same as building Blazey example mod update. The instructions regarding that you can find here and here or in this old doc. This library requires some packages modifications in order to work. You can find example Plant/Zombie types jsons in the Packages directory. If you want to utilize Power Lily's custom fields, add these to her props:

CollectableType (string)
CollectableCount (integer)
CollectableOffsetY (float)
Arcade's new property is GridItemType (string). One important note: DO NOT use a grid item which class isn't GridItemEightiesArcadeCabinet, otherwise zombie won't be able to push it.

# Bull's and Veteran Bull's new property:

RiderType (string) (using this for bull props)
VetRiderType (string) (using this for veteran bull props)
RiderLayerToHide (string list) (this can use for both props)
LaunchDistance (float) (this can use for both props)
NOTE: The RiderType and VetRiderType must use ZombieImp class with BullRiderProps. If you want using any vanilla props of them, just not use them as the function will using the hardcode value instead.

# ZcorpRacer's (Chair Racer) new property:

RacerType (string)
NOTE: The RacerType must use ZcorpRacerZombie class. If you want using any vanilla props of them, just not use them as the function will using the hardcode value instead.




