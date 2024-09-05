### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
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
```

## Using instruments
The song is still missing something. Let's start with a ``||agent:Drums.Medium||`` tempo using the ``||hoc:hoc.drums()||`` function, and end the song by removing the ``||agent:Instrument.Bells||`` instrument and playing the ``||agent:Note.Do||`` ``||hoc:hoc.note()||``. See the hint for all available parameters.

#### ~ tutorialhint
Add the ``||hoc:hoc.drums()||`` function to the beginning of the code and set it to ``||agent:Drums.Medium||`` then remove the ``||agent:Instrument.Bells||`` at the end using the ``||hoc:hoc.remove_instrument()||`` function and add a final ``||agent:Note.Do||`` ``||hoc:hoc.note()||``

**hoc.add_instrument()** | **hoc.remove_instrument()**  
Available instruments:  
Instrument.Xylophone, Instrument.Guitar, Instrument.Bells

**hoc.note()**  
Available notes:  
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti

**hoc.drums()**  
Available drums:  
Drums.Slow, Drums.Medium, or Drums.Fast, Drums.None


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.105
```