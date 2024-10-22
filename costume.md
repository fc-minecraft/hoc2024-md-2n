### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Time to pick out some costumes! Sequence together the different ``||hoc:head, body, and legs||`` costumes you want the Agent to change into during the show.

#### ~ tutorialhint
You can use a ``||loops:repeat loop||`` instead of multiple blocks to keep a specific costume on for longer.


```ghost
    hoc.costume()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Cowboy_Shirt, LowerWear.Swim_Shorts)
    hoc.costume(HeadWear.Superstar_Hat, MidWear.Ballerina_Shirt, LowerWear.Astronaut_Legs)
    hoc.costume(HeadWear.Cowboy_Hat, MidWear.Green_TShirt, LowerWear.Khaki_Shorts)
    hoc.costume(HeadWear.Construction_Helmet, MidWear.Varsity_Jacket, LowerWear.Black_Boots)
    for (let i = 0; i < 3; i++) {
        hoc.costume(HeadWear.Sun_Glasses, MidWear.Basketball_Jersey, LowerWear.Cowboy_Pants)
    }
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume
```