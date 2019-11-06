Fragmatic
=========

_Now powered by GLSL!_

Litt til λ
----------

- [Wierd science](https://youtu.be/gmMPvUwyMxA?t=689)
- [Veldig live shading](https://youtu.be/u517aj_JzVg?t=610)
- [Bonzomatic](https://github.com/Gargaj/Bonzomatic)
- [Book of shaders](https://thebookofshaders.com/11/)
- [Actors](https://github.com/heidisu/actor-invaders)
- [Hydra](https://github.com/ojack/hydra-synth)


How to set up an audio loopback
-------------------------------
Fragmatic records audio from the computer audio input, so in order to drive the vizualisations from the audio playing on your computer,
you'll need to set up an audio loopback from your sound output to the input. This can be done in a number of different ways, depending on your OS.

### Ubuntu
* Install pavucontrol (PulseAudio Volume Control) using apt-get or the Ubuntu Software Center.

```shell
$> sudo apt-get install pavucontrol
```

* Open PulseAudio Volume Control. It should be in the applications menu under Sound and Video.

```shell
$> pavucontrol
```

* Open Sound Recorder and start recording. Playing any sound at this point would be helpful, as your level indicator should react once you have finished.

* Go to the "Recording" tab in the PulseAudio Volume Control window.
* Make sure that "Applications" is selected in the drop down menu on the "Recording" tab.
* Choose "Monitor of Internal Audio Analog Atereo" from the "Record Stream from" menu in the Sound Recorder entry of the application list.
