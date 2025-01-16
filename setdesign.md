### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Design the sets
Давай создадим наборы! Выбери, какой "биом, время и погода" должны быть показаны для каждой части шоу.

#### ~ tutorialhint
Ты можешь использовать цикл (повторения) вместо нескольких блоков, чтобы отображать определенный набор дольше.

```ghost
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Day, Climate.Snow)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Sunset, Climate.Rain)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Night, Climate.Thunderstorm)
    }
    
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/set
```