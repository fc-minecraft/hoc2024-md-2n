### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Match the armor stand with the corresponding poster on the wall. Use the ``||hoc:armor stand dance||`` block to choose which armor stand should do which dance.


```ghost
    hoc._dance_activity()
```
```template
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.Move1)
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.Move1)
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.Move1)
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.Move1)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/dance#v0.0.107
```