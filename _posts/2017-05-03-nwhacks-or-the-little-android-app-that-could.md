---
id: 247
title: nwHacks and the little Android app that could
date: 2017-05-03T13:56:12+00:00
author: Caleigh
layout: post
guid: http://caleighm.com/?p=247
permalink: /2017/05/03/nwhacks-or-the-little-android-app-that-could/
categories:
  - Computer science
  - Programming how-to
tags:
  - Android
  - CockroachDB
  - frustration
  - git
  - Google Maps
  - JSON
  - nwHacks
  - success
  - version control
  - Yelp
---
I attended a second major hackathon this past term called [nwHacks](https://www.nwhacks.io/) in March. nwHacks is western Canada&#8217;s largest hackathon, 24 hours of coding, and it really showed. Unlike the [Vancouver Game Jam](https://www.ggjvancouver.com/), where you just had to buy a ticket, nwHacks was a free event _but_ it required an application something like two months in advance. I formed a team with 4 other students in my program back in January, but two weeks before the hackathon, nwHacks alerted us that only two of us were actually accepted to the event &#8212; the rest of my team was rejected.

The grading rubric for how applicants were accepted or rejected isn&#8217;t publicly available, although I think that the teammate and I who were accepted probably did have the most coding experience out of the five of us on the original team. Later I met several people who weren&#8217;t accepted &#8212; people that I thought were much more experienced and skilled than me. If you are applying to nwHacks, take the application seriously! We all thought it was just a formality so didn&#8217;t spend very much time on the application &#8212; boy, were we wrong. Go over your resume and your responses to their questions very carefully, especially if you&#8217;re a new programmer without a lot of experience or GitHub projects yet.

Fortunately, my teammate and I had other friends in the BCS program in the same boat &#8212; that is, their original team was broken up by a mix of acceptances and rejections. We formed a new team at the last minute with some other BCS students, and two days before the hackathon we decided to make an Android app that would display a list of available, personalized walking tours to the user based on the user&#8217;s location, and then guide them through the destination points on the selected tour and play the audio as the user approached.

&#8230; Yeah. We were _ambitious_.

When we arrived at nwHacks, the energy was already really high. It was a very different vibe from the game jam &#8212; you could tell some teams were really in it to win it, and the swag and sponsors at the event were on a whole new level. I got a t-shirt from [Hootsuite](http://www.hootsuite.com) that remains, to this day, my favourite pajama t-shirt (it&#8217;s so comfy), and I also got a great water bottle from [Microsoft](http://www.microsoft.com), annnnd of course tons of stickers for my laptop (yay!). On the one hand, that was pretty cool &#8212; we felt very important &#8212; but on the other hand, I definitely found it more intimidating!

Once we started coding, we quickly realized how out of depth we were. For one thing, we struggled a _lot _with version control. Using git came pretty easily to my team in the Game Jam, but this time around somehow we mangled up our file names and so every time one of us tried to commit, there were an endless number of merge conflicts. We didn&#8217;t fix this issue until the next morning.

We revised our plan to make it more manageable and decided to focus on getting a functional backend and frontend, so at least we could say we made an app (even if it didn&#8217;t do much). We used Google Maps and Yelp&#8217;s APIs to provide the data for three dummy walking tours (latitude/longitude, address, name of each destination point) and used one of the sponsors ([CockroachDB](https://www.cockroachlabs.com/) &#8212; so friendly and helpful!) to store all the data. Then we had an Express Node.js server to handle requests and a JSON parser that finally fed all of this data to the frontend so it could be nicely displayed in the app. All of these concepts and terms were new to me at the hackathon &#8212; only one of our teammates had any experience building an app, so it was a pretty big accomplishment (especially considering all the version control hiccups) that we got as far as we did!

Our team naturally split into three sub-teams, without any real discussion on our part. Two of us did UI, two of us did the Google Maps and Yelp APIs + CockroachDB, one of us did the JSON parser. We all ended up troubleshooting the server issues, although primarily the database guys set it up initially. I ended up doing most of the UI on Android Studio, but then realized that the Android emulator kept crashing my laptop (!) so I couldn&#8217;t actually test my code. Six hours into the hackathon, I started pair-programming with another teammate so we could use her computer instead. My poor little laptop went back into my bag and stayed there for most of the day.

We were understandably cranky and tired the next day (three of my teammates stayed overnight, but luckily I had a place to crash on campus). nwHacks was a higher-pressure environment, 24 hours is a lot less than the Game Jam&#8217;s 48 hours, and the version control issues holding us back were a definite source of frustration. I probably only spent about 5-10 hours actually coding, and the rest of my time was spent learning how Android Studio worked, troubleshooting our version control problems, trying to fix the Android emulator on my laptop, and discussing with my team what features we should cut so that we&#8217;d have something to demo at the end of the hackathon.

Like every hackathon I&#8217;ve attended so far, we were in the depth of despair in the last 4-6 hours. Nothing was working, we couldn&#8217;t figure out why, we felt like so much of our precious time had been wasted on silly problems &#8230; But (also like every hackathon I&#8217;ve attended so far) in the last thirty minutes of the hackathon, the original teammate and I finally figured out how to get our front and backends correctly communicating with each other, and we had a functional, non-crashing, beautiful little app! Just in time! That success was one of the highlights of my year, for sure.

At the end of the day, our WalkyTalky app displayed a list of available walking tours and, after selecting one of the walking tours, displayed a detailed list of its destination points as well as a Google Map path. &#8220;Talky&#8221; never really happened.

We ended the weekend watching all the award recipients demo their truly fabulous projects. Many of them had to do with accessibility (hardware that could read a person&#8217;s ASL signing and then translate it to text, for example), which was pretty cool to see. The winning project overall was a grocery cart that followed its owner around, scanned items placed into it, and then allowed the store manager to track and analyze shoppers&#8217; movements and purchases through the store.

I found the Game Jam more personally enjoyable, but nwHacks pushed me much further outside of my comfort zone. I would have liked to learn more about the backend stuff going on in our project; at this point, I&#8217;ve forked the repo on GitHub and I hope to do a bit of exploring on my own to see if I can piece together everything that happened. I think my biggest takeaway from nwHacks is that any hackathon team I&#8217;m on has to go to a GitHub workshop together before starting to code!