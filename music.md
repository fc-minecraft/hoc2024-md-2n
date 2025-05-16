### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Давай сочиним музыку! Ты можешь менять здесь что угодно или просто запусти код.

#### ~ tutorialhint
Ты можешь добавлять или удалять инструмент в любое время во время создания музыки. Если ты выберешь несколько инструментов, они все будут играть одну и ту же ноту одновременно.

```ghost
    hoc.add_instrument()
    hoc.remove_instrument()
    hoc.note()
    hoc.drums()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.drums(Drums.Medium)
    hoc.add_instrument(Instrument.Xylophone)
    hoc.add_instrument(Instrument.Guitar)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
    hoc.add_instrument(Instrument.Bells)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
    hoc.remove_instrument(Instrument.Bells)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts-1/n/music#v0.0.4
```