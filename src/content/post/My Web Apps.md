---
publishDate: 2024-02-07T00:00:00Z
title: The Web Apps That I Have Built
author: Michael Fitzgerald
excerpt: Get introduced to all the web apps that I've built to improve my teaching experience and my students' learning experiences.
image: ~/assets/images/blog/my-web-apps/The Web Apps That I Have Built.png
category: Capstone
tags:
  - teaching
  - technology
  - classroom
  - web app
  - bespoke
---

# Bespoke Web Apps

My programming journey began when I was back in the States in 2020. It
all started when I wanted to play Dungeons and Dragons (D&D) online with
my friends whom I met in Korea; they were all over the world now, so we
needed a virtual tabletop (VTT). I picked
[FoundryVTT](https://foundryvtt.com/) because of its
customizability. Little did I know at the time that it required
programming knowledge to gain the full benefits of its customizability.
So it began.

Since then, I've built several small local-only web apps. Local-only
because I'm still a novice web developer and programmer, so service-side
'magic' scares me 😂. I did not start creating any of the below
teaching-related web apps until I started teaching at Maple Bear in
March of 2022 because I was not sure what kinds of tools I would need.
Once I started teaching though, a deluge of ideas rushed down the
mountain of my creative brain and boy have they helped me as a teacher
and been a huge hit with my students!

## Class Daily

You know how you usually write your class schedule on the board before
class starts? Well, I got tired of doing that because I thought of a
better way. As I was planning for one of my lessons, the thought
occurred to me to use the plan for the display on the board. "How could
I do that?" I asked myself. How could I both plan and use that plan at
the same time with very little extra work from me in order for the
students to see our agenda for the day?

I always do my basic lesson plan in Google Sheets, like below:

![Target](~/assets/images/blog/my-web-apps/image2.jpg)

The daily agenda does not need a lot of information as we go over each
one as part of the introduction, or the students already know what it
means.

"AH HA! I can use the very same Google Sheet and upload it to a site to
display on the computer in class!" I thought.

That's exactly what I did. It looks like the below on the computer
screen in my classroom. You'll notice a clock on the left side; that's
Class Timers, which we will talk about next.

![Target](~/assets/images/blog/my-web-apps/image3.jpg)

Now, sadly, because I use GitHub and a CSV, that means that no one but
me can use this site. Sorry 🙁. I do hope to have the time to create an
online platform that combines Class Daily, Class Timers, and Random
Student Tools into one site at some point.

## Class Timers

One of my teacher friends said, "\...externalizing the frontal lobe\..."
when we were talking about how he handles the kids he is responsible for
at his school. He is in charge of creating the IEPs for dozens of
students. I had asked him what's the best thing I can do for them in my
classroom and he said that great phrase above about externalizing their
frontal lobes. So, I thought about a timer app that I would want and
went looking for one that could satisfy the following requirements:

1.  It must have nice colors

2.  It must display the timer very large to be visible from anywhere in the classroom

3.  It must use color and shape to identify each timer because I am color deficient, so I need the shapes

4.  It must allow for the creation of custom timers

5.  It must allow for the quick adjustment of active timers

6.  It must support rotations with a customizable transition duration

7.  It must allow for pausing and resuming of active timers

Maybe my Google-fu failed me, but I did not find one that met those
requirements, so I built my own. And guess what!? This site is usable by
you! Please go try it out and give me feedback so that I can make it
better 😀.

Do you remember the image above where Class Daily was on the right and
Class Timers was on the left? That's what it looks like in class for the
entire duration of the period. Every now and then, I'll start a timer
using Class Timers and the screen might change to be like one of the
below screenshots.

![Target](~/assets/images/blog/my-web-apps/image4.jpg)

![Target](~/assets/images/blog/my-web-apps/image5.jpg)

You'll notice the difference in color and shape. My students immediately
recognize that the turquoise diamond timer is a non-specific timer, just
one I set for whatever reason in class. They also recognize the purple
cloud timer to be Quick Game, as you can see from the name above the
timer. This is the timer that a student gets to run any vocab game of
their choice for review. This satisfies requirements 1, 2, 3, and 4.

You'll also notice the buttons that are below the timer. This allows for
quick adjustments of the active timer, which satisfies requirements 5
and 7.

One thing the timer now gets used for that I had not thought of was
during lunch time. At my current school, I supervise a kindergarten
class during lunch time on Mondays, Wednesdays, and Fridays. One day,
one of the students asked if they could change the shape and color of
the timer, for I had always used the non-specific timer above. I did not
think that they would want to do that, so we created a custom timer
called Orange Bear Lunch Time. Each day, I let a different student pick
the color and shape pair and rotate through the students. This is a huge
hit! Nearly every day, I get multiple, "It's so pretty!" or "WOW! It's
beautiful!" Kindergartners are so easy to please 🤣.

## MagniText

Have you heard of the Irrelevant Speech Effect? Well, any noise,
especially speech, is incredibly distracting during silent work time and
it impairs recall (<a href="https://doi.org/10.3758/bf03194948">Gisselgård et al., 2004</a>) and it's worse for children.
(<a href="https://doi.org/10.1016/j.neuroimage.2004.02.031">Elliott, 2002</a>) I use sign language to communicate simple things with
students during this time, but what about more complex messages?

Let's imagine a scenario where a student used the sign language for the
bathroom to signal they need to use the restroom, but you do not want to
let them go until their classmate has returned from the bathroom. You
could go over and whisper this to them, potentially causing a
distraction to nearby students, you could write it down on scratch
paper, or you could use MagniText, just like the below images. On your
phone, pull up the website, type the message in, then hit the checkmark
to see the text get larger, large enough for a student to see from far
away. If they cannot see it, simply walk a little closer or increase the
font size.

<div class="flex flex-row items-center justify-center gap-3 flex-wrap">
  <img src="/images/image7.jpg" class="max-w-[300px]" alt="MagniText with no text" />
  <img src="/images/image6.jpg" class="max-w-[300px]" alt="MagniText with text magnified" />
</div>

<!-- ![Target](~/assets/images/blog/my-web-apps/image6.jpg)
![Target](~/assets/images/blog/my-web-apps/image7.jpg) -->

No distractions at all. You did not have to move from where you were,
which could cause noise, and no one had to speak.

### MagniText's Limitations

One thing that I dislike is that this is only really usable for single
messages, ones that do not necessitate a complex reply, anything more
than a single sign language symbol can convey. But, what about actual
conversations? I want to create an app called TangibleTalks that is
entirely local, and part of the suite that I mentioned before. It would
be the 4th tool, in addition to Class Daily, Class Timers, and Random
Classroom Tools.

TangibleTalks would just be a chat app for talking with another person
on the same device. The teacher would type in a message, then pass the
phone to the student they're talking with, the student would type in
their message, and so on. It would have the same interface we're all
used to when chatting on a phone to ensure familiarity and a low
learning curve. Do you know of any web apps that can do this? I haven't
found any 🙁

## Random Classroom Tools

I had a very specific problem at my current school. My students argued
all the time about who was which position in line and it was always
causing overblown conflict. So, like the budding programmer I am,
instead of using a simple solution, like a chart in class, I made a web
app!

Currently, Random Classroom Tools has two tools: (1) randomly select a
student, and (2) randomly order all students in the class. Tool 1
selects a random student without replacement, meaning that one student
cannot be picked again until all other students have been selected. I
never use this. Tool 2 orders all the students in class in a random
order while ensuring that each student goes first and last at least once
before allowing any student to be first or last a second time. This can
be overridden by selecting the small F and L buttons next to a student's
name.

In the below image, you can see that several students have already
been first and last, as denoted by the red and blue badges. The number
within the badge indicates how many times they have been first or last
this cycle. There is one student who was last twice! I manually set this
student to last by clicking the square L button to the right of the
badges because she was absent one day.

<div class="flex flex-row items-center justify-center gap-3 flex-wrap">
  <img src="/images/image1.jpg" class="max-w-[300px]" alt="MagniText with no text" />
</div>

The students LOVE this so much. I never thought it would be as great of
a hit as it was. I always let the student who was last the previous time
hit the Sort button and they LOVE IT! They actually want to be last so
that they can hit the button and announce the order for the day. It has
completely resolved the issues I had with lining up at the end of the
day. It has also solved the issues my colleague had,

> This app was very
> easy to use and really helped me with classroom management because
> students responded well to the randomization aspect. They also enjoyed
> customizing their names by adding nicknames.

Having my colleague use it made me realize I could let my students pick
their nicknames, whereas before, I would just input their Korean name as
their nickname.

You can use this site! If you use it, please provide feedback so that I
can make it better! Got a random tool idea that I should add? Send it my
way!

## Conclusion

All of the websites that I\'ve made have enhanced my experience as a
teacher and without a doubt improved the experience of my students. They
are very engaged with Class Timers Requesting for a timer to be set and
they love to set the timers themselves. They also have become experts in
using Class Daily, and look forward to being last for the end of day
queue because of Random Classroom Tools. I cannot wait to merge all of
these local-only web apps into an actual online platform. Stay in
contact if you want to be alerted when I release it!

All of the websites can be found in Appendix A and I hope you are able
to get a lot of use out of these websites if you choose to do so and if
you have any feedback, whether it be positive or negative, please reach
out at michael (dot) fitzgerald (dot) 1406 at gmail.com. If you are also
a programmer and want to contribute to any of the projects, please see
the open source code in Appendix A and issue a pull request.

## References

<div class="hanging-indent">
Elliott, E. M. (2002). The irrelevant-speech effect and children:
theoretical implications of developmental change. Memory &amp;
Cognition, 3, 478--487. <a href="https://doi.org/10.3758/bf03194948">https://doi.org/10.3758/bf03194948</a>
</div>
<br>
<div class="hanging-indent">
Gisselgård, J., Petersson, K. M., & Ingvar, M. (2004). The irrelevant
speech effect and working memory load. NeuroImage, 3, 1107--1116. <a href="https://doi.org/10.1016/j.neuroimage.2004.02.031">https://doi.org/10.1016/j.neuroimage.2004.02.031</a>
</div>

## Appendix

### Appendix A

The table of the web apps I have built for teaching

<table border="1">
  <tr>
    <th>Website</th>
    <th>Open Source Code</th>
  </tr>
  <tr>
    <td><a href="https://mjf1406.github.io/class-daily/">Class Daily</a></td>
    <td><a href="https://github.com/mjf1406/class-daily">https://github.com/mjf1406/class-daily</a></td>
  </tr>
  <tr>
    <td><a href="https://mjf1406.github.io/class-timers/">Class Timers</a></td>
    <td><a href="https://github.com/mjf1406/class-timers">https://github.com/mjf1406/class-timers</a></td>
  </tr>
  <tr>
    <td><a href="https://mjf1406.github.io/magni-text/">MagniText</a></td>
    <td><a href="https://github.com/mjf1406/magni-text">https://github.com/mjf1406/magni-text</a></td>
  </tr>
  <tr>
    <td><a href="https://mjf1406.github.io/various-classroom-tools/">Random Classroom Tools</a></td>
    <td><a href="https://github.com/mjf1406/various-classroom-tools">https://github.com/mjf1406/various-classroom-tools</a></td>
  </tr>
</table>
