# **George Tharpe** - *Software Developer*

## My Projects 

### OmegaApp

<a href="https://i.imgur.com/ZWotZZQ.mp4" title="OmegaApp"><img src="https://i.imgur.com/ceJpDF6.png" width="500" height="500" alt="OmegaApp" /></a>

Click the image to see a video

Description
```
The OmegaApp incorporates the lyrics.ovh and the Dandelion Sentiment
Analysis API's. The lyrics api takes in an atrist name and song title
to return the song lyrics. OmegaApp then sends the lyrics to the
Dandelion api, which takes in strings and returns a number from -1 to
1. Numbers that range from -1 to 0 represent a negative sentiment and
numbers 0 to 1 represent positive sentiment. OmegaApp uses this number
to determine a color based on RGB values. It works such that songs with
more negative sentiment are blue-ish and songs with more positve
sentiment are yellow-ish. It should be noted that the sentiment analysis
is not the best at finding the sentiment of song lyrics. This could
be due to the length of the string being too large for accurate analysis.
Alternativly, the AI might just struggle with the convoluted nature of
song lyrics. Whatever the reason, OmegaApp adjusts for this by shifting
the sentiment score. If the score is from -1.0 to -0.35 we call the
sentiment negative and blue shift the color. If the socre is from
-0.349 to 1 we call the sentiment positve and yellow shift the color.
Note that nutral scores (scores near 0) will be green-ish. This
adjustment helps compensate for the fact that the score of many happy
songs is a negative value. OmegaApp is a frame work, which could easily
incorporate better sentiment analysis in future versions. OmegaApp uses
the Dandelion api because it is free and easy to use. Of course, the
software is always going to be a work in progress. Please feel free to let
us know ways we can improve by emailing the developer George Tharpe.
```

### GalleryApp

<a href="https://i.imgur.com/1h61Ppk.mp4" title="GalleryApp"><img src="https://i.imgur.com/0ONL9jm.png" width="500" height="500" alt="GalleryApp" /></a>

Click the image to see a video

Description
```
The Gallery app uses the Itunes API to download images based on the users search. 
It then displays the first 20 results and cycles through the other results randomly.
The Gallery app includes a pause play feature and a progress bar, which both run on
seprate threads. Additionally it has threads for pop up error messages, which are 
designed to be user friendly. Overall, the Gallery app was an interesting project 
that got my feet wet in the world of GUI's and API's.
```

## About Me
![About Me Photo](https://i.imgur.com/5rPPSe7.jpeg)

This is a short description about me intended to be read by a potential employer.
```
My name is George Tharpe, I am a 20 year old undergraduate student at UGA. My major is Computer Systems Engineering, 
which is a small major at the University of Georgia's College of Engineering. The major is essentially
half electrical engineering and half computer science; to learn more about my major check out 
https://engineering.uga.edu/bs-computer-systems-engineering . I grew up in Snellville Georgia with my mom, brother,
and dog. My brother, Henry, is 22 and in law school at Emory Law. Henry is the hardest working person I know, and I 
have learned a lot from him. My mom is a middle school math teacher who always pushed me to do well in school. 
Constantly dealing with students not doing homework in her classes, my mom made it a point that I completed every 
assignment. She pushed me to do well in every class, but math and science was clearly what I was ment to do. 
Math based sciences were always my favorite classes because I understood them and they were interesting. I was 
first introduced to coding in AP Computer Science, which I took my senior year of high school. My teacher was 
really cool and would always stay after class to talk to me about math and science concepts. AP ComSci. was the
first time that I worked on problems that weren’t assigned; I did them purely for fun! 

While I do find coding interesting enough to do for fun, I spend most of my free time on my skateboard. 
Every since I started skateboarding at the start of 2020, it has quickly become an obsession for me.
Over quarantine it was the only thing I had to do, and I picked it up really quickly. In case you were
curious, I can do kick flips, jump down stairs, and ride on rails. I am not exaggerating when I say 
skateboarding changed my life. I have met dozens of friends, improved my health, and learned new ways of 
thinking. More specifically, skateboarding taught me confidence, creativity, and the perseverance to keep
trying even when you fail. In a way learning a new trick is similar to working on code. They’re both about 
trial and error. The first time you try you’re not even close, but you keep trying and slowly make progress. 
Once you finally land the trick or get the code working, you’re far from finished. You have to keep working 
on it until it’s perfect. Thats just one example of how skating makes good developers.


```
