### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Choose the costumes

```python-template
hoc.costume(HeadWear.Knight_Helmet, MidWear.Cowboy_Shirt, LowerWear.Ballerina_Tutu)
```

## Choosing the costumes
It looks like there's a second lock made of iron. You'll need to figure out which costume pieces it requires. Use the ``||hoc:hoc.costume()||`` function to open the lock. Set the ``||agent:HeadWear, MidWear, and LowerWear||`` of the costumes. See the hint for all available parameters.

#### ~ tutorialhint
**hoc.costume()**  
Available HeadWear parameters:  
HeadWear.Astronaut_Helmet, HeadWear.Cowboy_Hat, HeadWear.Knight_Helmet

Available MidWear parameters:  
MidWear.Astronaut_Top, MidWear.Cowboy_Shirt, MidWear.Knight_Top

Available LowerWear parameters:  
LowerWear.Astronaut_Legs, LowerWear.Cowboy_Pants, LowerWear.Knight_Legs




```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/costume#v0.0.105
```