### @flyoutOnly true
### @hideIteration false
### @explicitHints true


# Design the sets

```python-template
hoc.set(Biome.Taiga, Time.Day, Climate.Clear)
```

## Design the sets
Piece together the three sets that Designer Ayomide requested by using the ``||hoc:hoc.set()||`` function. It takes three separate paramters that define the set's ``||hoc:biome, time, and climate||``. Try running the following code.

```python
hoc.set(Biome.Taiga, Time.Day, Climate.Clear)
```

## Complete the Challenge 
Now that you know how to use the ``||hoc:hoc.set()||`` function, help Ayomide put together the three sets and he will give you the key. See the hint for all available set piece paramters.

#### ~ tutorialhint
**hoc:hoc.set()**
Available Biome parameters:
Biome.Taiga, Biome.Desert, Biome.Jungle

Available Time parameters:
Time.Day, Time.Sunset, Time.Night

Available Climate parameters
Climate.Clear, Climate.Snow, Climate.Rain


```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/set#v0.0.4
```