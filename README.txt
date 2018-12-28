This package contains a small coding file, for use with Sonic Pi. I have created aa simple solo generator, which allows the user to use live coding, to cue in two backing drum beats, and some piano background chords. Then, there is an “improvisor” live loop, which will choose random notes and spacing, in order to create an “improvised solo”, similar to in jazz. 

I have written the code in the key of C. The piano backgrounds alternate between the perfect fifths of the key of C, C and G, followed by a short chromatic run at the end. This allows the background to be simple, but dynamic. Also, since prefect fits sound so nice, this because a great sound for the improviser to solo over. The improvisor can only pick notes in the key of C, and has the 1st, 3rd, and 5th weighted twice as heavily, as a real soloist would also play these notes more. I also randomized the sleep to only be multiples of 0.125, so that even with random sleep times, the soloist will stay in beat with the rest of the band. 

The code is split into 4 buffers, so that each part can be queued individually. Buffer 0 is the bass drums, buffer 1 is the snares, buffer 2 is the background, and buffer 3 is the soloist.

The key and notes the soloist plays can easily be adjusted manually, as well as the sleep intervals. This will allow you to fully customize the sound of the song for your purposes! Enjoy!
