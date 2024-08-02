### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Step 1
Now that you found all the pieces needed to build the sets, use the ``||hoc2024:biome, time, and weather||`` block to sequence the set changes. The starter code's biomes are already in the correct order, set the time and weather of each block to the appropriate option. 

#### ~ tutorialhint
The tagia biome should be ``||hoc2024:day||`` with ``||hoc2024:snow``, the desert biome should be ``||hoc2024:sunset||`` with ``||hoc2024:clear||`` weather, and the jungle biome should be ``||hoc2024:night||`` with ``||hoc2024:rain||``.

```ghost
    hoc202a.seta()
```
```template
    hoc2024.seta(BiomeA.Biome2, TimeA.Time2, WeatherA.Weather1)
    hoc2024.seta(BiomeA.Biome3, TimeA.Time2, WeatherA.Weather1)
    hoc2024.seta(BiomeA.Biome4, TimeA.Time2, WeatherA.Weather1)
    
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.50
```