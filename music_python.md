### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

## Create your own Music
The Agent needs help composing music for its show. Use the following functions to create music for the Agent.

```python
# available parameters:
# Instrument.Synth, Instrument.Xylophone, Instrument.Guitar, Instrument.Flute, Instrument.Bells, Instrument.Bass, Instrument.Piano, Instrument.Villager
hoc.add_instrument(Instrument.Synth)
hoc.remove_instrument(Instrument.Synth)

# available parameters:
# Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti
hoc.note(Note.Do)

# available parameters:
# Drums.Slow, Drums.Medium, or Drums.Fast, Drums.None
hoc.drums(Drums.Slow)
```

```python-template
hoc.add_instrument(Instrument.Piano)
hoc.drums(Drums.Fast)
for i in range(3):
    hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.70
```