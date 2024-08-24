### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

## Create your own Music
The Agent needs help composing music for its show. Use the following functions to create music for the Agent. See the hint for all available parameters.

``||hoc:hoc.add_instrument()||``
``||hoc:hoc.remove_instrument()||``
``||hoc:hoc.note()||``
``||hoc:hoc.drums()||``

#### ~ tutorialhint
**hoc.add_instrument()** | **hoc.remove_instrument()**
Available instruments:  
Instrument.Bass, Instrument.Bells, Instrument.Flute, Instrument.Guitar, Instrument.Piano, Instrument.Synth, Instrument.Villager, Instrument.Xylophone

**hoc.note()**
Available notes:  
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti

**hoc.drums()**
Available drums:  
Drums.Slow, Drums.Medium, or Drums.Fast, Drums.None

```python-template
hoc.add_instrument(Instrument.Piano)
hoc.drums(Drums.Slow)
for i in range(3):
    hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.add_instrument(Instrument.Guitar)
hoc.remove_instrument(Instrument.Piano)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.add_instrument(Instrument.Synth)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.98
```