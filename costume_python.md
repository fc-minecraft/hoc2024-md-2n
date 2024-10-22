### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

```python-template
hoc.costume(HeadWear.Knight_Helmet, MidWear.Cowboy_Shirt, LowerWear.Swim_Shorts)
hoc.costume(HeadWear.Superstar_Hat, MidWear.Ballerina_Shirt, LowerWear.Astronaut_Legs)
hoc.costume(HeadWear.Cowboy_Hat, MidWear.Green_TShirt, LowerWear.Khaki_Shorts)
hoc.costume(HeadWear.Construction_Helmet, MidWear.Varsity_Jacket, LowerWear.Black_Boots)
for i in range(3):
    hoc.costume(HeadWear.Sun_Glasses, MidWear.Basketball_Jersey, LowerWear.Cowboy_Pants)
```

## Choosing the costumes
Time to pick out some costumes! Sequence together the different ``||hoc:head, body, and legs||`` of the costumes using the ``||hoc:hoc.costume()||`` function.


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume
```