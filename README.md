A collection of patches and machines for Pure Data.

Following machines are currently implemented:<br>
**ponyoMixer** - extensible 4-channel audio-mixer.

They have been created using <i>pd-0.43-extended</i> which can be downloaded here: [puredata.info] (http://puredata.info/).

ponyoMixer
----------

Extensible 4-channel audio-mixer.

![ponyoMixer GUI](http://files.callistix.net/puredata/ponyomixer_gui.png)

### Features

- 4 channels by default, easily expandable to any amount of channels needed
- a volume slider with overdrive and panning knob for each channel
- preset values for volume and panning
- global reset button for getting "factory" settings quickly
- VU meters, switchable between pre and post metering
- mute and solo buttons for each channel

### Instructions

**connect to the mixer**:<br>
Just connect your audio outputs to the inlets of the [pd mixer] block in following order (ch = channel, l = left, r = right):<br>
ch1l ch1r ch2l ch2r ch3l ch3r ch4l ch4r
