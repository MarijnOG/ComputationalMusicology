# ComputationalMusicology
Repo for the UvA course Computational Musicology

## On my corpus of music
The goal of this corpus of music and the analysis thereof is to find out whether Spotify makes distinctions between different kinds of alternative 'emo' music. The styles that I am interested in include math rock, post rock and Midwest (emo). To those uninitiated in the cult, I will give a brief introduction, as well as give an example of what I consider a typical track for these styles. 

### 1. Math rock
Math rock is characterized by harmonically rich chords, often involving major sixth, all kinds of seven and nine, eleven and thirteen chords. Rhythmically, the music rarely follows a 4/4 structure, often changing time signatures throughout songs. The style of playing that is most notable in the often very present and highly technical electric guitars can be described as 'angular' with big intervals and high contrasts in syncopation, as well as accenting off-beats frequently. 

A typical track could be: Bubble Dream by Chon

### 2. Post rock
Post rock is harmonically similar to math rock, hence why the two are often grouped together. Post rock, however, conveys a much different emotion, which I would personally describe as “positive solitude”, like being very alone and being okay with that. The style is much calmer and less ‘angular’ than math rock, and thrives on winding repetitions of somewhat meditative leitmotifs, often preceded by sonically big crescendos.

Your hand in mine by Explosions in the Sky is very post rock indeed.

### 3. Midwest emo
This style is a bit harder to describe, as it features much of the same characteristics of the previous two styles, but in varying degrees. Midwest can be very peaceful or feature metal-esque screaming, depending on the song and artist. A common trait, one that is shared in most emo music, is yelling vocals. The previous two styles are typically instrumental, whereas this style usually offers emotional or downright depressing lyrics for the listener to enjoy or wallow in. It still features the same harmonic ideas.

Never meant by American Football is the most famous and ubiquitous example.


Exploring the distinctions between math rock, post rock, and Midwest emo using the characteristics provided by the Spotify API presents an intriguing challenge. There is much debate among fans about the boundaries and overlap of these genres, hence why such an analysis could be meaningful. 
An example of an outlier could be Polyphia, which is traditionally a math rock/metal band that turned more to an electronic and hip hop influenced instrumental boy band. Where would they land on the spectrum? Through the use of the toolset provided by Spotify, new insights in this subset of emo-genres can be gained.

## Week 7: A first plot
Since all my three selected styles of music feature some challenges for (party-esque) dancing, namely being slow and winding or irregular in rhythm, I opted to plot this metric against the tempo of the song. The arbitrary 'energy' feature of the Spotify API is also visible as a color in the plot. For comparison, a part of the Beatles discography is also shown, as these are historically quite danceable.
