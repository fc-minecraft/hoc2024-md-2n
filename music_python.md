### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

## Create your own Music
The Agent needs help composing music for its show. Use the following functions to create music for the Agent.

```python
*hoc.add_instrument()* and *hoc.remove_instrument()* parameters:
Instrument.Synth, Instrument.Xylophone, Instrument.Guitar, Instrument.Flute, Instrument.Bells, Instrument.Bass, Instrument.Piano, Instrument.Villager

*hoc.note()* parameters
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti

*hoc.drums()* parameters
Drums.Fast, Drums.Medium, Drums.Slow, Drums.None.
```

```python-template
hoc.add_instrument(Instrument.Piano)
hoc.drums(Drums.Fast)
for i in range(3):
    hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.drums(Drums.Medium)
hoc.note(Note.Mi)
hoc.add_instrument(Instrument.Guitar)
hoc.remove_instrument(Instrument.Piano)
hoc.note(Note.Fa)
hoc.drums(Drums.Slow)
hoc.note(Note.So)
hoc.add_instrument(Instrument.Synth)
hoc.note(Note.La)
hoc.drums(Drums.Stop)
hoc.note(Note.Ti)
```


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.67
```