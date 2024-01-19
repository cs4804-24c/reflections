![image](https://github.com/cehrensperger/reflections/assets/19954402/1c6b1411-a659-49a0-930e-fe7c43f6e5a9)</br>
Source: https://eagereyes.org/blog/2021/when-the-wrong-chart-is-the-right-choice </br></br>
This data visualation is from an eagereyes.org article that talks about some edge cases of when otherwise unacceptable methods for data visualization actually do 
make sense. This one in particular is about audio data visualization for an audio software called "iZotope RX" which can be used for audio recording, mixing, 
broadcast, sound design, and mastering. The interesting part of this data visualtion is in the way the vertical dB scale is made. The "zero-point" or center line 
represents infinite dB while above and below the center line go from infinity to -20 to 0 dB. This is because the -20 to 0 dB range is the most important for the 
audio professionals that use this software and it is useful for that range to take up as much physical space on the visualization as possible. This gives all other 
dB ranges the small range between -20 (both above and below the center line) to -infinity. This to me seems like a prime example of top-down design methodology because 
of how it is built specifically for how the users are going to use it. I can imagine that the people working on this audio software might have actually talked to their 
potential customers and asked them what is most useful to see when working with audio. I would also think that the idea to use this kind of vertical scale would be 
awfully hard to think of if not deeply involved in the audio community. One thing I might change about this representation of data is the colors of the scales. The 
colors of the audio itself and the orange line telling the user where they are within the audio file have a nice contrast with the background but it is somewhat 
difficult to see the numbers on the vertical and horizontal scales.
