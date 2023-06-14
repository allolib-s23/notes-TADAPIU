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
- I developed a better way to organize the code. The frequencies for each note are declared, and a function for playing a particular instrument is defined. Therefore, composers can directly enter the note that they want to play and the note's start time, attack, duration, amplitude, etc. Also, the notes for a particular part of the song are included in one function to increase the readability of the code. In this demo, I tried to emulate the sound of accordion by adding two sin waves and one saw wave. I also implemented simple graphics, in which the position of Dodecahedron is based on frequency.

## Demo 3
- Finzalized Pachelbel's Canon
- A transcription of Canon by Johann Pachelbel with my own edition of arrangement
- [Link to repo](https://github.com/allolib-s23/demo1-TADAPIU)
- To run it: ```./run.sh sirui_demo/canon.cpp```
- I extended the piece for demo 2 with lots of new notes from my creativity added. I also added more instrument in the song. I included a plucked string and tried to make it sounds like a lyre. I focused more on the volume control and the progressive feature of the song by changing some of the melodies and adding broken chords. I picked D major and 140 BPM.

## Demo 4
- Loonboon
- A transcription of Loonboon by Laura Shigihara from Plants vs Zombies
- [Link to repo](https://github.com/allolib-s23/demo1-TADAPIU)
- To run it: ```./run.sh sirui_demo/loonboon.cpp```
- I was inspired by this video (https://www.youtube.com/watch?v=lr4vi_XAjQQ). I listened to the song several times and extrated the main melody and bassline. Apart from using a sin wave instrument and a plunked string, I used additive synthesis to create an instrument that has 8-bit quality because this is the background music from a video game. Also, I changed the timbre of the drum to make it sounds like a bowling sound because in the game, the player is using Wall-nut bowling to defeat zombies. For the graphics, I used a Dodecahedron along with a circle for the bassline, and the shape is quickly rolling down to create a visualization of the rolling bassline.
