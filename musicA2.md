### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Давай теперь добавим инструмент "ксилофон"! Перетащи его из блоков слева в начало кода.

#### ~ tutorialhint
Добавь "ксилофон" в начало кода.
```blocks
    hoc._add_instrument_activity(Instrument_Activity.Xylophone)
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re) 
    hoc.note(Note.So)
    hoc.note(Note.Do) 
```

```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/music#v0.0.4
```