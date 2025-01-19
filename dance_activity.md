### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Сопоставь стойку для брони с соответствующим постером на стене. Используй блок "танец стойки для брони", чтобы выбрать, какая стойка должна выполнять какой танец. Нажми "играть", чтобы узнать танцы.

#### ~ tutorialhint
Синий танец — это "Иссушающая волна".

```ghost
    hoc._dance_activity()
```
```template
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.GolemGallop)
    hoc._dance_activity(ArmorStand.Two, _Dances_Actvity.DolphinDisco)
    hoc._dance_activity(ArmorStand.Three, _Dances_Actvity.WitherWave)
    hoc._dance_activity(ArmorStand.Four, _Dances_Actvity.MushroomMarch)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/dance#v0.0.4
```