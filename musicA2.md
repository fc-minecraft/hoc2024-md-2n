### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
That didn't quite work, lets make the song a bit more complex by adding the ``||bell||`` instrument and then replaying the four notes.

#### ~ tutorialhint
Add the ``||bell||`` after the guitar plays it's four notes using the ``||hoc:add instrument||`` block and then use the ``||hoc:note||`` block to replay the notes ``||do||`` ``||so||`` ``||la||`` ``||fa||``

```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music#v0.0.104
```