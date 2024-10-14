### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Let's dance! Sequence together your ``||hoc:dance steps||`` to create a dance for the Agent to do.

#### ~ tutorialhint
You can use a ``||loops:repeat loop||`` instead of multiple blocks to repeat the same dance move.


```ghost
    hoc.dances()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.dance(Dance.DolphinDisco)
    hoc.dance(Dance.MushroomMarch)
    hoc.dance(Dance.WitherWave)
    hoc.dance(Dance.GolemGallop)
    hoc.dance(Dance.BlazeBounce)
    for (let i = 0; i < 3; i++) {
        hoc.dance(Dance.MushroomMarch)
    }
    hoc.dance(Dance.HoglinHandJive)
    hoc.dance(Dance.DungeonDig)
    hoc.dance(Dance.AlexAxle)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/dance
```