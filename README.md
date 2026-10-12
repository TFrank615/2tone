# TwoTone

A small browser app for identifying Motorola Quick Call II two-tone sequences in an audio recording.

## Use it

Open `index.html` in a current desktop browser, choose or drop in an audio file, and select **Analyze recording**. The sample button loads a synthetic A-to-B sequence so you can see the result layout.

Audio is decoded and analyzed in the browser; it is not sent to a server. Audio formats depend on browser support. WAV and MP3 are good formats to try first.

## What it reports

- Tone A and tone B frequencies in hertz, in sequence order
- Approximate duration of each tone
- Every detected pair and its location in the recording

This is an initial detector tuned for steady tones in Quick Call II recordings. Noise, clipping, speech over the tones, or very short recordings can affect its readings.
