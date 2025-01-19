### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Now that you found all the costume pieces, use the ``||hoc:head, body, and legs||`` block to create the 3 costumes the NPC is looking for. The order of the customes doesn't matter as long as they are 3 full sets.

#### ~ tutorialhint
The 3 sets of costumes the NPC is looking for are: ``||hoc:Cowboy||``, ``||hoc:Astronaut||``, and ``||hoc:Knight||``.


```ghost
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)
```
```template
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)        
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/costume#v0.0.4
```