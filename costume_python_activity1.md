### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

```python-template
hoc.costume(HeadWear.Knight_Helmet, MidWear.Cowboy_Shirt, LowerWear.Ballerina_Tutu)
```

## Choosing the costumes
Look at the lock to see what numbers it's displaying and then use the closet to find which costume pieces matche that number. Once you've matched them up, use the ``||hoc:hoc.costume()||`` function to open the lock. Set the ``||agent:HeadWear, MidWear, and LowerWear||`` of the costumes. See the hint for all available parameters.

#### ~ tutorialhint
The lock needs the ``||agent:Knight||`` costume to open. Set the head, body and legs to use the ``||agent:Knight||`` items.

**hoc.costume()**  
Available HeadWear parameters:  
HeadWear.Astronaut_Helmet, HeadWear.Cowboy_Hat, HeadWear.Knight_Helmet, HeadWear.Ballerina_Crown, HeadWear.Construction_Helmet

Available MidWear parameters:  
MidWear.Astronaut_Top, MidWear.Cowboy_Shirt, MidWear.Knight_Top, MidWear.Ballerina_Shirt, MidWear.Construction_Shirt

Available LowerWear parameters:  
LowerWear.Astronaut_Legs, LowerWear.Cowboy_Pants, LowerWear.Knight_Legs, LowerWear.Ballerina_Tutu, LowerWear.Construction_Pants




```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume#v0.0.112
```