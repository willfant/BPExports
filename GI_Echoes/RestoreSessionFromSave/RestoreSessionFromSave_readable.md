# RestoreSessionFromSave

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Reads
- SaveManagerRef
- SavedLevelRef
- TransitionManagerRef
- Out World Mode
- bIsDebug

## Writes
- TransitionManagerRef
- SavedLevelRef
- Out World Mode

## Calls
- Get Actor Of Class
- Is Valid
- Get Current World Mode
- Is Valid Soft Object Reference
- Travel to Level Ref
- Debug
- Get Current Level Name

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
