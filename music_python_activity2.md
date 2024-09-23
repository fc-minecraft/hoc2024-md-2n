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
```

## Using instruments
That didn't quite work, lets make the song a bit more stronger by adding the ``||agent:Instrument.Xylophone||`` instrument to the top of the code to play along with the guitar.

#### ~ tutorialhint
Now add the ``||agent:Instrument.Xylophone||`` instrument to the start of the code by using the ``||hoc:hoc.add_instrument()||`` function.

**hoc.add_instrument()**  
Available instruments:  
Instrument.Xylophone, Instrument.Guitar, Instrument.Bells

**hoc.note()**  
Available notes:  
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music#v0.0.110
```