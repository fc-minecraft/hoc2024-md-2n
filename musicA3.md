### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
The song is still missing something. Let's start with a medium tempo ``||hoc:drum||`` beat, and end the song by removing the ``||bells||`` and playing the ``||do||`` ``||hoc:note||``.

#### ~ tutorialhint
Add a medium tempo drum beat by adding the ``||hoc:drum||`` block and setting it to ``||medium||``, then use the ``||hoc:remove instrument||`` block at the end to remove the ``||bells||`` and add a final ``||do||`` ``||hoc:note||``.

```ghost
    hoc._add_instrument_activity()
    hoc._remove_instrument_activity()
    hoc.note()
    hoc.drums()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
    hoc._add_instrument_activity(Instrument_Activity.Bells)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)    
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music#v0.0.104
```