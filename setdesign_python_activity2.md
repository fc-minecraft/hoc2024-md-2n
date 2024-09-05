### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Design the sets

```python-template
hoc.set(Biome.Taiga, Time.Day, Climate.Clear)
hoc.set(Biome.Taiga, Time.Day, Climate.Clear)
hoc.set(Biome.Taiga, Time.Day, Climate.Clear)
```

## Complete the Challenge 
Search the room to find the 3 scripts that describe the scenes and then use the ``||hoc:hoc.set()||`` function to sequence the 3 sets. It takes three separate paramters that define the set's ``||hoc:biome, time, and climate||``. See the hint for all available parameters.

#### ~ tutorialhint
**hoc:hoc.set()**
Available Biome parameters:
Biome.Taiga, Biome.Desert, Biome.Jungle

Available Time parameters:
Time.Day, Time.Sunset, Time.Night

Available Climate parameters
Climate.Clear, Climate.Snow, Climate.Rain


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set#v0.0.105
```