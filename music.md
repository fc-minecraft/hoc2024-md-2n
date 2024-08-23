### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Let's compose some music! You can add and remove instruments using the ``||hoc:add_instrument||`` and ``||hoc:remove_instrument||`` blocks and start a drum beat using the ``||hoc:drum||`` block. Then use the ``||hoc:note||`` block to create the song. 

#### ~ tutorialhint
You can add or remove an instrument at any time throughout your music. If you define multiple instruments, they will all play the same note at the same time.

```ghost
    hoc.add_instrument()
    hoc.remove_instrument()
    hoc.note()
    hoc.drums()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.add_instrument(Instrument.Piano)
    hoc.add_instrument(Instrument.Guitar)
    hoc.drums(Drums.Medium)    
    hoc.note(Note.Do)
    hoc.note(Note.Re)
    hoc.note(Note.Mi)
    hoc.remove_instrument(Instrument.Guitar)
    hoc.add_instrument(Instrument.Synth)
    hoc.drums(Drums.Fast)  
    for (let i = 0; i < 5; i++) {
        hoc.note(Note.Fa)
    }  
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Ti)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.67
```