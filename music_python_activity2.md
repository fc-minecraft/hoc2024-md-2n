### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
hoc.add_instrument(Instrument.Guitar)
hoc.note(Note.La)
hoc.note(Note.Re)
hoc.note(Note.So)
hoc.note(Note.Do)
```

## Using instruments
That didn't quite work, lets make the song a bit more stronger by adding the ``||hoc:Instrument.Xylophone||`` instrument to the top of the code to play along with the guitar.

#### ~ tutorialhint
Now add the ``||hoc:Instrument.Xylophone||`` instrument to the start of the code by using the ``||hoc:hoc.add_instrument()||`` function.


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```