---
layout: post
title: BlocJams
thumbnail-path: "img/blocflix.png"
short-description: BlocJams is a Spotify replica for finding the best music and listening to it online, on any device.

---

{:.center}
![]({{ site.baseurl }}/img/blocflix.png)

## Explanation

There is so much music in this world. The user experience for listening to music has changed hugely since the discovery of CDs, then then portable music players like iPOD. BlocJams wants to change it and give developer the tools to integrate music into the world wide web.

## Problem

BlocJams was my personal project. I decided to work on BlocJams because I have always wanted to build a music player on the web for my religion group. All the technology aspects of the group, event management, and teaching kids is all managed by the youth. Due to lack of finances and a will to learn, we can't hire experts do build this project. Thus, I decided to take on this approach myself as I will learn HTML, CSS, DOM Tree, Javascript, and other technologies. I wanted a music player that lists albums and the songs that they contain. The music player should have a player bar that allows for easier playing/pausing the song and skipping/rewinding.

## Solution

Using the HTML5 and CSS3, I was able to create a basic website with different pages. So far I had basic website with different pages for album, songs, and even the main landing page. The album's page had a cover-art for the album, dummy songs, and even dummy length of the song, and a dummy player bar. Using Javascript helper library, jQuery, I was able to add more functionality to the collection/album view, add a working play/pause button on the album page, and even create a working play/pause button on the player bar. Additionally, I used jQuery to add next song and previous song to the player bar, and fully functioning seek bar. Majority of the features were straight forward to create. The only exception was the play/pause button on the seek bar. The issue was the variables that handled play/pause button were declared in local scope. Using the Google Chrome's Inspect tool, I tracked down the values passed between each call of every methods and variables. Thereafter, I discovered that the variables handling the play/pause button on the player bar needed to be declared in global scope.  

## Results

Although the expected time for building the fully functional music player website was 60 hours of work. However, I ended up using about 70 hours of total work. The extra 10 hours, I used to conduct external research I needed to comprehend new technologies. As an amateur with this field, I wanted to fully understand my work and the reasoning behind it and not just its completion. There were times when I added, committed, and even published incorrect code. However, since I understood it while writing it, I was able to rewrite the code.

## Conclusion
It was AMAZING! Yes, there was time when I pulled my hair out because a thing or two didn't work. It was merely a result of spending more than enough time on concepts and sometimes technical issues such as not restarting my mac for a while. The new skills I gained including HTML5, CSS3, Vanilla Javascript, and jQuery are well-worth the time and dedication I put into it. As of now, I still consider the project incomplete because there are a lot more features I want to add to it, while keeping the user experience simple and the site easily maneuverable. 


Bacon ipsum dolor amet filet mignon meatball spare ribs fatback bacon shankle. Kielbasa andouille fatback salami, boudin bresaola pig alcatra turkey spare ribs jerky. Corned beef bresaola leberkas salami alcatra beef landjaeger venison shank bacon meatloaf beef ribs picanha. Leberkas sausage brisket porchetta shankle prosciutto chicken picanha kielbasa pig kevin t-bone turducken filet mignon jowl.
