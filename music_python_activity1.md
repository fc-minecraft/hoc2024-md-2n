### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

```python-template
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Do) 
hoc.note(Note.Do)
hoc.note(Note.Do)     
```

## Using instruments
We need to unlock the door by playing the correct song. First, your code should start with the instrument that's currently playing. Use the ``||hoc:hoc.add_instrument()||`` function to set what instrument will play. Then define the notes you want to play using the ``||hoc:hoc.note()||`` function.

#### ~ tutorialhint
First add the ``||hoc:Instrument.Guitar||`` by using the ``||hoc:hoc.add_instrument()||`` function, then play the ``||hoc:Note.La||`` ``||hoc:Note.Re||`` ``||hoc:Note.So||`` ``||hoc:Note.Do||`` notes by using the ``||hoc:hoc.note()||`` function.


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```