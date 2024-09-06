### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Design the sets
Let's design the sets! Choose which ``||hoc:biome, time, and weather||`` should be displayed for each portion of the show.

#### ~ tutorialhint
You can use a ``||loops:for loop||`` instead of multiple blocks to keep a specific set up for longer.

```ghost
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Day, Climate.Snow)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Sunset, Climate.Rain)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Night, Climate.Thunderstorm)
    }
    
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set#v0.0.105
```