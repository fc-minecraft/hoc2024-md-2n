### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Время выбрать костюмы! Соедини разные костюмы, в которые ты хочешь, чтобы Агент переоделся в них на шоу.

#### ~ tutorialhint
Ты можешь использовать цикл (повторения) вместо нескольких блоков, чтобы дольше оставить один и тот же костюм.


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
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/costume
```