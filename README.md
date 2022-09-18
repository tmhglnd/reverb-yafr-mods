# reverb-yafr-mods

**Please consider to download and donate via http://gumroad.com/tmhglnd**

**or become a patron on http://patreon.com/timohoogland**

---

## About

The yafr2 reverb may be the most used reverb in Max. It is great and I have used it for many projects in the past. But sometimes it just misses a bit more control and ease-of-use. The original yafr2 reverb credit goes to Randy Jones. Modifications made to the reverbs are listed in the Features.

## Contains

- **th.yafr~** - *Plate reverb in the style of Griesinger, positive feedback with softclipping*

- **th.yafr.gliss~** - *Plate reverb in the style of Griesinger with a time-domain pitchshifter in the feedback*

- **th.yafr.freeze~** - *Plate reverb in the style of Griesinger with fft-freeze effect*

- **th.yafr.inf~** - *Plate reverb in the style of Griesinger with self-regulating feedback loop for infinite decay*

## Features

Ported to a complete signal chain (so modulation on all parameters can be done in the signal-domain)
Added presets for quick access of settings

- Wet-dry functionality and stereo input

- Parameters scaled to range of 0 - 1 for easy modulation with signals

- Positive feedback posibility with softclipping in the feedback loop

- Bigger roomsize possibility (will eventually sound like delay, maximum of 10 seconds)

- Glissando effect reverb with a time-domain pitchshifter in the feedback

- FFT-freeze effect reverb with smoothing between frames

- Self-regulating feedback loop for infinite decay

## Sources

- https://cycling74.com/tools/charles-spectral-tutorials - *fft freezer loosly inspired by spectral proccesing tutorials from Jean Francois Charles*

## Install

```
1. download zip
2. unzip and place in Max Searchpath (eg. MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max Searchpath
3. $ cd ~/Documents/Max\ 8/Library
4. $ git clone https://github.com/tmhglnd/reverb-yafr-mods.git
5. restart Max8
```
