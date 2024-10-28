### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Step 1
Search the room to find the 3 scripts that describe the scenes and then use the  ``||hoc:biome, time, and weather||`` block to sequence them in the correct order. 

#### ~ tutorialhint
The taiga biome should be ``||hoc:day||`` with ``||hoc:snow||``, the desert biome should be ``||hoc:sunset||`` with ``||hoc:clear||`` weather, and the jungle biome should be ``||hoc:night||`` with ``||hoc:rain||``.

```ghost
    hoc._set_activity()
```
```template
    hoc._set_activity(Biome_Activity.Taiga, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Desert, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Jungle, Time_Activity.Day, Weather_Activity.Clear)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set
```