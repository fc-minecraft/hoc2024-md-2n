### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

## Using instruments
We need to unlock the door by playing the correct song. All code needs to start with the ``||hoc:hoc.add_instrument()||`` function. This function sets what instrument will be playing. Then you could define what notes you want to play using the ``||hoc:hoc.note()||`` function. See the hint for all available parameters.

#### ~ tutorialhint
First add the ``||agent:Instrument.Guitar||`` by using the ``||hoc:hoc.add_instrument()||`` function, then play the ``||agent:Note.Do||`` ``||agent:Note.So||`` ``||agent:Note.La||`` ``||agent:Note.Fa||`` notes by using the ``||hoc:hoc.note()||`` function.

**hoc.add_instrument()**
Available instruments:  
Instrument.Xylophone, Instrument.Guitar, Instrument.Bells

**hoc.note()**
Available notes:  
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.104
```