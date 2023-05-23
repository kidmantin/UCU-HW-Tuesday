# Alignment Decoding
My task was to decode an audio, from LibriSpeech dec-clean, to text using [provided LSTM acoustic model](https://gist.github.com/proger/a7e820fbfa0181273fdbf2351901d0d8) and check decoding in [praat software](https://www.fon.hum.uva.nl/praat/)

Code I used to do it is in vivtorok.ipynb

## Results:

I created 2703 textgrids files that store information about phonems and their timings in audio file, some of them were causing problems with intervals, their last phonem were starting when the audio already ended, I fixed this mistake by deleting last added interval so that timing of last decoded phonem syncs with the end of an audio file


