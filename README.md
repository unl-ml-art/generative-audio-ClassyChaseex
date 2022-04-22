# Project 2 Generative Audio

Karston Chase, kchase4@huskers.unl.edu

## Abstract

In my project I would want to have an AI assist me in remixing a song. The AI could either generate new texts for lyrics on an existing song or a background beat for existing lyrics. Getting the track to line up and work together with the lyrics would be difficult and wouldn't happen on the first try. What I would do is cherry pick the best tracks or lyrics that I feel work best together and then edit them to sound somewhat believeable. Any awkward sounding beats or weird drop offs could be manually fixed by me and then I could pick out lyrics from an existing band like AC/DC or Nirvana and make a somewhat remix out of their existing song with generated backing tracks.

## Model/Data

Briefly describe the files that are included with your repository:
- Nirvana
- Grunge Music
- (Both of these were trained through OpenAI Jukebox)

## Code

Your code for generating your project:
- Jupyter notebooks: Interacting_with_Jukebox.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- nirvana_background_generation4.wav (This is the fully generated AI track for the chosen song.)
- nirvana_isolated_local.wav (This file is not present in the repository because it is too large, but I will try to add it to the Canvas post if possible. It is the isolated audio I edited out of Nirvana's song "In Bloom". If you listen to that song, just imagine it being all vocals with no music in the background and that is basically what this file is.)
- Nirvana_Remix_3.wav (This is fully edited final product. There are actually two backing tracks put together here and blended to give a little more variety between the tracks. The isolated lyrics from "In Bloom" are edited onto the backing track and edited in a way that best matches up with the audio sample.)

## Technical Notes

- I messed with the temperature a bit to 1.0 on the second backing track.
- If you try to run the Jupyter Notebook yourself with the previously used settings, you might get a similar sounding track to mine. However, the final product is an edited combination of multiple tracks put together. While you might notice some similarities, the final track won't be exactly the same as the track submitted here.

## Reference

References to any papers, techniques, repositories you used:
- OpenAI Jukebox
- Jupyter Lab
- Google Magenta Interpolation (Not used much in the final product but helped inspire some blending techniques for the tracks.)
