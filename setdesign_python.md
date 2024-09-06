### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

```python-template
hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Day, Climate.Snow)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Sunset, Climate.Rain)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Night, Climate.Thunderstorm)
```

## Design the sets
Let's design the sets! Choose which ``||hoc:biome, time, and climate||`` should be displayed for each portion of the show by using the ``||hoc:hoc.set()||`` function. See the hint for all available set parameters.

#### ~ tutorialhint
**hoc:hoc.set()**
Available Biome parameters:
Biome.Savannah, Biome.Taiga, Biome.Desert, Biome.Jungle, Biome.Forest
Biome.Ocean, Biome.Nether, Biome.End, Biome.City, Biome.Space

Available Time parameters:
Time.Sunrise, Time.Day, Time.Sunset, Time.Night

Available Climate parameters
Climate.Clear, Climate.Snow, Climate.Rain, Climate.Thunderstorm

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set#v0.0.105
```