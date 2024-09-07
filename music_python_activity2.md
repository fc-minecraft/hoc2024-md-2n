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
That didn't quite work, lets make the song a bit more complex by adding the ``||agent:Instrument.Bell||`` instrument and then replaying the four notes. See the hint for all available parameters.

#### ~ tutorialhint
Now add the ``||agent:Instrument.Bell||`` instrument to the end of the code using the ``||hoc:hoc.add_instrument()||`` function, then play the ``||agent:Note.Do||`` ``||agent:Note.So||`` ``||agent:Note.La||`` ``||agent:Note.Fa||`` notes again by using the ``||hoc:hoc.note()||`` function.

**hoc.add_instrument()**  
Available instruments:  
Instrument.Xylophone, Instrument.Guitar, Instrument.Bells

**hoc.note()**  
Available notes:  
Note.Do, Note.Re, Note.Mi, Note.Fa, Note.So, Note.La, Note.Ti


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music#v0.0.110
```