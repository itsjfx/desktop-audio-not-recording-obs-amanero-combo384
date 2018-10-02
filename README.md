# desktop-audio-not-recording-obs-amanero-combo384
This issue is caused by any DAC, such as the Klein DAC, that uses the Amanero Combo384 sound card or a non default sample rate
I couldn't find any help online but saw people with similar issues, but here's the fix.

## What the issue looks like
https://i.imgur.com/fVO9F44.png
* On our end it doesn't look like there are any problems however when listening to the stream or recording it is obvious it's not being captured.

## How to fix
1. Check what sample rates your DAC or device supports : https://i.imgur.com/CY2QpMW.png
* These are the defaults for mine so I haven't changed them but according to Amanero's website the DAC supports a variety of sample rates, including 44.1 Khz.
2. Open OBS and change the sample rate: https://i.imgur.com/03OnARK.png
3. Profit
