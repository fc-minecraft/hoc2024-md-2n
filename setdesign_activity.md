### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Step 1
Обследуй комнату, чтобы найти 3 скрипта, которые описывают сцены, а затем используй блок "биом, время и погода" для их последовательного расположения в правильном порядке.

#### ~ tutorialhint
Биом тайги должен быть "день" с погодой "снег", биом пустыни должен быть "закат" с ясной погодой "ясно", а биом джунглей должен быть "ночь" с погодой "дождь".

```ghost
    hoc._set_activity()
```
```template
    hoc._set_activity(Biome_Activity.Taiga, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Desert, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Jungle, Time_Activity.Day, Weather_Activity.Clear)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/set
```