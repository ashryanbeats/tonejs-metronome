#Tone JS Metronome
This is a super basic example of how to set up a metronome with Tone JS and vanilla JavaScript.

##Getting a sound for the metronome
You'll need to make a directory called `sounds` and add a file to it to hear any sound.

This line shows you where the script is looking for the sound:
```
var player = new Tone.Player("./sounds/woodblock.wav").toMaster();
```

So, in directory `sounds`, we are looking for a file called `woodblock.wav`.

If you don't have a sound on-hand, I recommend [this woodblock by kwahmah_02](https://www.freesound.org/people/kwahmah_02/sounds/268822/) on Freesound.org.