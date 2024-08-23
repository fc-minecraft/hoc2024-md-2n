### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Let's dance! Sequence together your ``||hoc2024:dance steps||`` to create a dance for the Agent to do.

#### ~ tutorialhint
You can use a ``||loops:for loop||`` instead of multiple blocks to repeat the same dance move.


```ghost
    hoc.dances()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.dance(Dance.Move2)
    hoc.dance(Dance.Move4)
    hoc.dance(Dance.Move3)
    hoc.dance(Dance.Move1)
    hoc.dance(Dance.Move5)
    for (let i = 0; i < 7; i++) {
        hoc.dance(Dance.Move4)
    }
    hoc.dance(Dance.Move8)
    hoc.dance(Dance.Move9)
    hoc.dance(Dance.Move10)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/dance#v0.0.63
```