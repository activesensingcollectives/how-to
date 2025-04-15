# How to: calibrate the GRAS 40BF with a Sound Level Calibrator 

The GRAS 40BF is a wide-frequency calibration mic with a very flat
frequency response. The advantage of having this flatness is that 
the sensitivity (rms/Pa, mV/Pa) is going to be the same at any other recorded frequency. 

## You'll need
Microphone model: GRAS 40BF with a Type 26AC pre-amp (the metal rod).

![](IMAGE HERE)

You will also need:
* GRAS power-module (e.g. GRAS 12AA)
* BNC cables
* BNC-audio jack adapters
* An audio interface to record the sound. You may need to use the same audio interface for another target microphone - so check that you have all the accessories for the other mic too.

Sound level calibrator: B & K Type 4231

![](IMAGE HERE)

## Steps
Step 1: Check that your GRAS microphone is getting a signal. 
Step 2: Turn on the calibrator. It should produce a faint tone that is at 1kH at an intensity of 1 Pascal rms (94 dB SPL re 20muPa). 
Step 3: Keep the metal grid on the GRAS40BF *on*. Insert the microphone into the calibrator - it should fit rather snugly. 
Step 4: Record the 1 Pascal sound. 
Step 5: Check that the recorded audio is not clipping and note the gain values used (on the power module and the audio interface)
Step 6: Press the 'volume' button. You should hear the tone get a bit louder. This is the 10 Pascal tone (114 dB SPL re 20muPa). 
Step 7: Record the 10 Pascal tone. 
Step 8: Check that the recorded audio is not clipping and note the gain values used (on the power module and the audio interface)
Step 9: Export/save the audio. 

## Calculations/output
To get measure the 1/10 Pa equivalent in your recording chaing - go back to the recorded audio and compensate for the gain you had while recording.

Then calculate the dB rms of the 1 kHz tone and 94 and 114 dB SPL. This will give e.g. X,Y dB rms for the two sound pressure levels. The sound-pressure levell of any sound you record with the GRAS (e.g. a playback, bat call) can then be easily calculated knowing these reference tone RMS values. 

## Example
Let's say the recorded audio had a -40 and -20 dB rms for the two reference tone-levels. 
Here we know then that the microphone has a sensitivity of 0.01 rms/Pa. 

For example, if you record a playback and it has a -34 dB rms, then we can calculate that the recorded sound has a 88 dB rms SPL!