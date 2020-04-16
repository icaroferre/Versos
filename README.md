# Versos

![Versos](/Images/Versos-Screenshot.jpg)

## About

Versos is a multi-track looper / sampler designed to work with Monome Grid (more specifically the 64). It contains 6 standard tracks that can be used for recording external signals, a resampling track (#7) and a global track (#8).

All tracks use Monome's softcut engine ([the MaxMSP port by Andew Shike](https://github.com/AndrewShike/softcut-msp)) for recording and playback. 

Each track has a 32-second buffer (which can be exported as a wave file) and independent controls for transport, playback level, overdub level, loop state, rate and quantizer state.

Track #7 ("♺") can be used for resampling the output of tracks 1-6.  
Track #8 ("ALL") can be used for controling tracks 1-7 simultaniouly.  

Recording and playback messages can be quantized to a BPM (on quarter notes) to make it easy to sync multiple tracks. 

## Controls

![Controls](/Images/Versos-Controls.png)

Additional information:

Input level: -18dB / -12dB / -9dB / -6dB / -3dB / 0dB / +3dB / +6dB
Rate: -2x / -1x / -0.5x / 0.5x / 1x / 1.5x / 2x / 4x
Playback level: -18dB / -12dB / -9dB / -6dB / -3dB / 0dB / +3dB / +6dB

## How to Use

1 - Select the appropriate audio input / output devices, input channel and click on the speaker icon to enable audio processing.

2 - Select the track you'd like to record to.

3 - Check the Input Gain meter and the meter of the selected track to make sure that signal is getting to the track.

4 - Press the bottom-left button on the Grid to start recording, press it again to stop recording (do not press play or stop while its recording). 

5 - After you've recorded the base loop of the selected track, the Clear button will light up. You can press record again to start overdubbing or press clear to delete the base loop.

6 - Clicking on a different position button will jump the playback position to the selected section


