### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Нам нужно открыть дверь, сыграв правильную песню. Используй блок "добавить инструмент" для добавления инструмента и блок "нота" для добавления нот.

#### ~ tutorialhint
Сначала добавь "гитара" с помощью блока "добавить инструмент", затем используй блок "нота" для добавления нот "la" "re" "so" "do".


```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Bells)
    hoc.note(Note.Do)
    hoc.note(Note.Do) 
    hoc.note(Note.Do)
    hoc.note(Note.Do)     
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/music#v0.0.4
```