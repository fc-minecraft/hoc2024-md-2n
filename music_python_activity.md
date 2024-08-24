### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Compose the Music

```python-template
hoc.add_instrument(Instrument.Xylophone)
```

## Using instruments
Musician Andi is challenging you to recreate the music they're playing. Let's first learn how to add instruments and play notes. All code needs to start with the ``||hoc:hoc.add_instrument()||`` function. This function sets what instrument will be playing. Then you could define what notes you want to play using the ``||hoc:hoc.note()||`` function. Try running the following code.

```python
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

## Removing instruments
You can also remove instruments using the ``||hoc:hoc.remove_instrument()||`` function or add new ones at any point in your song. The example code will begin by playing the Xylophone, then replace the Xylophone with a Guitar, and then add the Bells while the Guitar is still playing.

```python
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.add_instrument(Instrument.Guitar)
hoc.remove_instrument(Instrument.Xylophone)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.add_instrument(Instrument.Bells)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

## Adding drums
You can also add a drum beat to your song by using the ``||hoc:hoc.drums()||`` function. You can set the drums to be *Slow*, *Medium*, *Fast* or disable them with *Stop*.

```python
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.drums(Drums.Slow)
hoc.note(Note.Mi)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.note(Note.La)
hoc.note(Note.Ti)
```


## Complete the challenge
Now that you know how to use the different functions, see if you could recreate the song that Musician Andi is playing. See the hint for all available instruments.

#### ~ tutorialhint
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
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/music#v0.0.103
```