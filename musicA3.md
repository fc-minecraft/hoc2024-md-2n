### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
В песне все еще чего-то не хватает. Давай добавим ударный ритм с умеренным темпом "барабан".

#### ~ tutorialhint
Добавь ударный ритм с умеренным темпом, вставив блок "барабан" в начало кода.

```ghost
    hoc._add_instrument_activity()
    hoc.note()
    hoc.drums()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Xylophone)
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/music
```