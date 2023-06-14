# Notes from Sirui Chen

## Demo 1
- Untitled
- Original piece
- [Link to repo](https://github.com/allolib-s23/demo1-TADAPIU)
- To run it: ```./run.sh sirui_demo/0417.cpp```
- This is my first piece and I tried to write a simple canon. I mainly explored the synthSequencer and wrote notes by hard coding the frequencies, start time, attack, duration, release parameters. I also explored additive synthesis and used a combination of sin wave and saw waves. I picked D major and 120 BPM.

## Demo 2
- Pachelbel's Canon
- A transcription of Canon by Johann Pachelbel
- [Link to repo](https://github.com/allolib-s23/demo1-TADAPIU)
- To run it: ```./run.sh sirui_demo/0503.cpp```
- I developed a better way to organize the code. The frequencies for each note are declared, and a function for playing a particular instrument is defined. Therefore, composers can directly enter the note that they want to play and the note's start time, attack, duration, amplitude, etc. Also, the notes for a particular part of the song are included in one function to increase the readability of the code. In this demo, I tried to emulate the sound of accordion by 
