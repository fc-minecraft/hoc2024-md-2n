### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
That didn't quite work, lets make the song a bit stronger by adding the ``||hoc:Xylophone||`` instrument so both the Xylophone and Guitar plays the notes.

#### ~ tutorialhint
Add the ``||hoc:Xylophone||`` to the top of the code.

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
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```