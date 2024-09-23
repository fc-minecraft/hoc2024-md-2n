### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Time to pick out some costumes! Sequence together the different ``||hoc:head, body, and legs||`` costumes you want the Agent to change into during the show.

#### ~ tutorialhint
You can use a ``||loops:for loop||`` instead of multiple blocks to keep a specific costume on for longer.


```ghost
    hoc.costume()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
    for (let i = 0; i < 3; i++) {
        hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
    }
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume#v0.0.113
```