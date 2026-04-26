# SaveArrivalStateAfterTransition

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- CachedSaveManager
- CachedGI
- SaveManagerRef

## Writes
- CachedSaveManager
- ArrivalSaveRetryHandle

## Calls
- Is Valid
- Write Save to Disk
- Get Game Instance
- Set Timer by Function Name

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
