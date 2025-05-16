### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Нам нужно открыть дверь, сыграв правильную песню. В блоках кода "нота" выбери такой же порядок нот, которые сейчас играют.

#### ~ tutorialhint
Поменяй блоки "нота" для добавления нот в таком порядке: "la" "re" "so" "do".


```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Do) 
    hoc.note(Note.Do)
    hoc.note(Note.Do)     
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/music#v0.0.4
```