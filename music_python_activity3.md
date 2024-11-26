### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
hoc.add_instrument(Instrument.Xylophone)
hoc.add_instrument(Instrument.Guitar)
hoc.note(Note.La)
hoc.note(Note.Re)
hoc.note(Note.So)
hoc.note(Note.Do)
```

## Using instruments
The song is still missing something. Let's add a ``||hoc:Medium||`` (medium) tempo using the ``||hoc:hoc.drums()||`` function.

#### ~ tutorialhint
Add the ``||hoc:hoc.drums()||`` function to the beginning of the code and set it to ``||hoc:Medium||`` so it plays along with the Guitar and Xylophone.


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```