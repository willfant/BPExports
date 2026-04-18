# StartScareCooldown

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- ScareCooldownTime
- DebugEnabled

## Writes
- bScareCooldownActive 
- ScareCooldownTimerHandle

## Calls
- Set Timer by Function Name
- Debug Message
- To String (Text)

## Called By
- EventGraph

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
