### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the Music

## Musician Andi's Challenge @unplugged

Let's create music using coding! Musician Andi is challenging you to recreate the music they're playing. Let's learn how to add and remove instruments, play notes, and run drum beats.

[SOME KIND OF GIF]

## Using Instruments

Let's first learn how to add instruments and play notes. All code needs to start with the *hoc.add_instrument()* function. This function sets what instrument will be playing. Then you could define what notes you want to play using the *hoc.note()* function.

Try running the following code:

```python
hoc.add_instrument(Instrument.Piano)
hoc.note(Note.Do)
hoc.note(Note.Re)
hoc.note(Note.Mi)
hoc.note(Note.Fa)
hoc.note(Note.So)
hoc.note(Note.La)
hoc.note(Note.Ti)
```

## Available Instruments @unplugged
You can use any of the following 8 instruments:

Instrument.Synth, Instrument.Xylophone, Instrument.Guitar, Instrument.Flute, Instrument.Bells, Instrument.Bass, Instrument.Piano, Instrument.Villager

## Removing Instruments
You can also remove instruments using the *hoc.remove_instrument()* function or add new ones at any point in your song. The following example will begin by playing the Piano, then replace the Piano with a Guitar, and then add the Synth while the Guitar is still playing.

```python
hoc.add_instrument(Instrument.Piano)
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

## Adding Drums
You can also add a drum beat to your song by using the *hoc.drums()* function. You can set the drums to be Drums.Slow, Drums.Medium, or Drums.Fast. You can also disable the drums using Drums.None. 

```python
hoc.add_instrument(Instrument.Piano)
hoc.drums(Drums.Fast)
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
hoc.drums(Drums.None)
hoc.note(Note.Ti)
```

## Complete the Challenge
Now that you know how to use the different functions, see if you could recreate the song that Musician Andi is playing.

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