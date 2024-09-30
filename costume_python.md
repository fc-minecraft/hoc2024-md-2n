### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

```python-template
hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
for i in range(3):
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Construction_Shirt, LowerWear.Swim_Shorts)
```

## Choosing the costumes
Time to pick out some costumes! Sequence together the different ``||hoc:head, body, and legs||`` of the costumes using the ``||hoc:hoc.costume()||`` function. See the hint for all available costumes parameters.


#### ~ tutorialhint
**hoc.costume()**  
Available HeadWear parameters:  
Astronaut_Helmet, Ballerina_Crown, Baseball_Hat, Construction_Helmet, Cowboy_Hat, Knight_Helmet, Reading_Glasses, Sun_Glasses, Superstar_Hat

Available MidWear parameters:  
Astronaut_Top, Ballerina_Shirt, Basketball_Jersey, Construction_Shirt, Cowboy_Shirt, Green_TShirt, Knight_Top, Superstar_Shirt, Varsity_Jacket

Available LowerWear parameters:  
Astronaut_Legs, Ballerina_Tutu, Black_Boots, Construction_Pants, Cowboy_Pants, Khaki_Shorts, Knight_Legs, Superstar_Pants, Swim_Shorts


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume#v0.0.115
```