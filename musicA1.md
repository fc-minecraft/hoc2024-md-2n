### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
We need to unlock the door by playing the correct song. Use the ``||hoc:add instrument||`` block to add an instrument and the ``||hoc:note||`` block to add notes.

#### ~ tutorialhint
First add the ``||guitar||`` using the ``||hoc:add instrument||`` block then use the ``||hoc:note||`` block to add the notes ``||la||`` ``||re||`` ``||so||`` ``||do||``


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
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music#v0.0.113
```