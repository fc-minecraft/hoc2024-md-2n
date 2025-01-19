### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Это не совсем сработало, давай сделаем песню немного сильнее, добавив инструмент "ксилофон", чтобы как ксилофон, так и гитара играли ноты.

#### ~ tutorialhint
Добавь "ксилофон" в начало кода.

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