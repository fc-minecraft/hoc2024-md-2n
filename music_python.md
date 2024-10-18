### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
hoc.drums(Drums.Medium)
hoc.add_instrument(Instrument.Xylophone)
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
hoc.remove_instrument(Instrument.Bells)
hoc.note(Note.Do)
```

## Create your own Music
The Agent needs help composing music for its show. Use the following functions to create music for the Agent.

``||hoc:hoc.add_instrument()||``
``||hoc:hoc.remove_instrument()||``
``||hoc:hoc.note()||``
``||hoc:hoc.drums()||``



```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```