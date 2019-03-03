# Week 4

[Home](./README.md)
[Week 1](./week1.md)
[Week 2](./week2.md)
[Week 3](./week3.md)
[Week 4](./week4.md)
[Group Reflection](./group_reflection.md)

## Monday 25/02/2019

Today people came in to teach us about reverse engineering. They talked about what reverse engineering is and gave us a little CTF to complete. Personally, I am interested in reverse engineering, I find it interesting as 

![Picture](/images/reverseeng1.PNG)

#### Abradolf Lincler

This was a very straight forward challenge. There is a program that runs and outputs an image of Abradolf Lincler, from the show Rick and Morty.

![Picture](/images/reverseeng2.PNG)

From function2, there were 4 statements where the program was moving (mov) some strings. I know this because of the tag mov and DWord. So to find the flag, we just need to investigate the DWord fields.

From changing the hexadecimal to ASCII text, we see the flag. So the program has been sending these strings through the program, without outputting the data.

![Picture](/images/reverseeng3.PNG)

The flag is ``` FLAG{B4bysR1rst} ```

I haven't had much time to play with the reverse engineering challenges as I was thinking about what I could present for our presentation on Friday. I discussed with Frank and Corey. We decided that we should start to meet up on Wednesday and work on our presentation and what we can show and explain to our audience who are coming in on Friday. Mainly today has been getting things ready for our presentation. 

But I do want to pursue reverse engineering as like stated above, it is an interesting field to get into, and a very hard field as well. Personally, topics that are hard draw me in a lot more as I like to perfect my skills and constantly pushes further to get as good as I can. I find it very fun when things are very challenging. Hence why I like cryptography as well :)


## Wednesday 27/02/2019

Wednesday, was mainly planning what Frank and Corey would like to do. After some ideas to grab their attention like comparing what cyber security really is from the movies, we just decide that we will do a presentation of our journey in this unit. 

We decided to put emphasis on the fact that all of us have learnt to go from boot to root in the boxes we attempted for the first time. Frank and I first box were Mr Robot. While Corey got a box from HTB (Hack the Box), just talking about our experiences and what we learnt from beating those boxes is a good point to talk about. As we can talk about our highlights, lowlights and insights. 

![Picture](/images/midas.PNG)

## Friday 1/03/2019

Today was our presentation. Very intrested in what the other studios have produced. We presented to people, talking about our thoughts of our units and what we learnt, as discussed in our presentation. We also did a live demo of us actually breaking into a box, teaching people what we do and hopefully get them intrested into cyber security and might be able to learn more about it.

![Picture](/images/friday1.JPG)

We also presented infront of academics, explaing why we loved doing this unit and what we got out of the unit. Beata Francis also wanted to record our thoughts on the unit, and what we got out of it. Not only individually but as a group and what industry experince this unit gave for us.  

The link to the presentation: [MIDAS 2019 Presentation](https://docs.google.com/presentation/d/15R4CfAy6mqTa8u99pGQ1XdQnMTgk63jD6Y0Bcu0OMU8/edit?usp=sharing)

## SLO's

**SLO 1**

*Engage with stakeholders to identify a problem or scope a defined problem.*

This SLO I've done quite often, as presenting infront of Rob in week 1, discussing the problems of certain attakcs and how they affect a business. And this Friday speaking in front of academics. But also me engaging with the industry by attending SecTalks at the PWC office in Banagraoo, and talking to the people from Deloitte about what they do, and what I can do to build myself up and learn off them.  

**SLO 2**

*Apply design and systems thinking to respond to a defined or newly identified problem*

**SLO 3**

*Apply technical skills to develop, model and/or evaluate designs*

**SLO 4**

*Demonstrate effective collaboration and communication skills.*

**SLO 5**
*Conduct critical self, peer, and group review and performance evaluation.*

## Conclusion

Overall this unit pushed me futher that I've ever gone. I learnt so much from this unit, like privlage esculation, web application penertration testing and much more. This unit also allowed me to beat my first box, which was an achievement I never thought I can complete. 

Now did I complete the things I wanted to get out of this unit, from Week 1? I believe so, the things I wanted to get out of the summer studio I have completed or started creating the foundation to build upon it in my spare time. Things like enurmation and technical knowledge I have created the foundation just by practicing and playing the hack the box challanges. 

**Now where do I go from here?**

I believe that if I play the hack the box challanges reguarly and write reports on them when they've been retired, will be a good steping point for me. As it will teach me how to properly write reports and writeups, but also teachs me how to get better and privlage esculation. Attempting more CTF's escpecially do the fields that I find intresting (Cryptography and Reverse Enginerering). Since this unit gave me a good framework to build my skills up to hopefully get into the industry.

![Picture](/images/midas2.png)
