# danceA
### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Search the room to find what 4 dances are needed to open the door and the sequence they need to be in. Then use the ``||hoc:dance steps||`` block to sequence the 4 dances into the correct oder.

#### ~ tutorialhint
There are 4 posters on the wall with numbers. Those posters will tell you the sequence the 4 ``||hoc:dance steps||`` need to be placed.


```ghost
    hoc._dance_activity()
```
```template
    hoc._dance_activity(_Dances_Actvity.Move1)
    hoc._dance_activity(_Dances_Actvity.Move1)
    hoc._dance_activity(_Dances_Actvity.Move1)
    hoc._dance_activity(_Dances_Actvity.Move1)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/dance#v0.0.1
```