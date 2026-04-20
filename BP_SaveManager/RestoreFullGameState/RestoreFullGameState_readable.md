# RestoreFullGameState

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Reads
- CurrentSaveObject

## Calls
- Is Save System Ready
- Debug Critical
- Get Sender Name
- Debug Info
- Is Valid
- Apply Snapshot to Managers
- Load Save
- Resolve Owner Manager Refs
- Apply Resolved Audio State from Context
- Restart Scare Loop for Current State
- Handle Pending Arrival Transition

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
