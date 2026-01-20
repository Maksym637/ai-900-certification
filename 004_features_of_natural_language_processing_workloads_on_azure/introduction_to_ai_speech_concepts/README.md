## Introduction to AI speech concepts

---

### Speech recognition

Speech recognition, also called speech-to-text, enables applications to convert spoken language into written text.

The coordinated stages:

1. **Audio capture** provides the raw signal;
2. **Pre-processing** extracts MFCC features that highlight speech patterns;
3. **Acoustic modeling** predicts phoneme probabilities using transformer networks;
4. **Language modeling** applies vocabulary and grammar knowledge;
5. **Decoding** searches for the best word sequence;
6. **Post-processing** formats the text for human readers;

---

### Speech synthesis

Speech synthesis—also called text-to-speech (TTS)—converts written text into spoken audio.

The coordinated stages:

When you request speech synthesis for "Dr. Chen's appointment is at 3:00 PM":

1. **Text normalization** expands it to "Doctor Chen's appointment is at three o'clock P M";
2. **Linguistic analysis** converts it to phonemes: /ˈdɑktər ˈtʃɛnz əˈpɔɪntmənt ɪz æt θri əˈklɑk pi ɛm/;
3. **Prosody generation** predicts pitch rising slightly on "appointment", a pause after "is", and emphasis on "three";
4. **Speech synthesis** generates an audio waveform matching those specifications

---
