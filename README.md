A collection of patches and machines for Pure Data.

Following machines are currently implemented:

*PONYOMIXER:9000* - extensible 4-channel audio-mixer.

They have been created using <i>pd-0.43-extended</i> which can be downloaded here: [puredata.info] (http://puredata.info/).

PONYOMIXER:9000
---------------

Extensible 4-channel audio-mixer for Pure Data.

![ponyomixer9000 GUI](http://files.callistix.net/puredata/ponyomixer9000_gui.png)

### Features

- 4 channels by default, easily expandable to any amount of channels needed
- a volume slider with overdrive and panning knob for each channel
- preset values for volume and panning
- global reset button for getting "factory" settings quickly
- VU meters, switchable between pre and post metering
- mute and solo buttons for each channel

Instructions
------------
### connect to the mixer

Just connect your audio outputs to the inlets of the [pd mixer] block in following order (ch = channel, l = left, r = right):

ch1l ch1r ch2l ch2r ch3l ch3r ch4l ch4r
