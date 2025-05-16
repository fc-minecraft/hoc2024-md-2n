### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Давай танцевать! Соедини блоки, чтобы создать танец для Агента. Можно все оставить как есть и просто запустить код.

#### ~ tutorialhint
Ты можешь использовать цикл (повторения) вместо нескольких блоков, чтобы повторять один и тот же танцевальный элемент.


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
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/dance#v0.0.4
```