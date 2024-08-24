### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Step 1
Now that you found all the pieces needed to build the sets, use the ``||hoc:biome, time, and weather||`` block to sequence the set changes. The starter code's biomes are already in the correct order, set the time and weather of each block to the appropriate option. 

#### ~ tutorialhint
The tagia biome should be ``||hoc:day||`` with ``||hoc:snow``, the desert biome should be ``||hoc:sunset||`` with ``||hoc:clear||`` weather, and the jungle biome should be ``||hoc:night||`` with ``||hoc:rain||``.

```ghost
    hoc._set_activity()
```
```template
    hoc._set_activity(Biome_Activity.Taiga, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Desert, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Jungle, Time_Activity.Day, Weather_Activity.Clear)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/set#v0.0.103
```