---
layout: twitch-app
title:  "Twitch Desktop App"
date:   2016-11-19 06:53:57 -0800
categories: project
tags: snippet
featured_image: "/img/twitch/splash/twitch_splash.jpg"
post_images: true
---
## Designing A Twitch Desktop App

I love to watch Twitch streams.  Hell, I was watching live streams before there was a Twitch.  When Twitch was called Justin.tv, and all it had was people streaming themselves pouring chocolate syrup all over their bodies and singing karaoke.  My enjoyment for watching people stream video games actually started when I stumbled on Nico Nico Douga's live channels.  There I was able to watch Japanese gamers streaming obscure video games that we never saw over here in America, or watching Japanese speed runners play games like Dragon Quests III, or Demon's Souls with precision speed.  What I'm trying to say is, is that watching people play video games online brings me back to when I was a kid, and I watched my older brother and his friends play video games.  I always enjoyed that, and so with Twitch being as huge and great as it is, I thought that maybe I could take a stab at designing some mockups for a desktop application that wraps the whole Twitch experience into a nice little package.  Over the course of a week and a half, the following screenshot mockups are what I came up with for a Twitch desktop application.

The actual idea of designing a Twitch desktop app stemmed from my use of another program called [Discord](https://discordapp.com/).  Discord is a free desktop application that allows users to voice chat and chat in channels without having to use older programs like Ventrilo or Teamspeak.  It's a really awesome service, and I just love the simplicity of it all.  It even has Twitch functionality built into it so that streamers can create Discord channels for their users to talk and chat in.  One day while in one of the channels that I frequent, I noticed a quick conversation that was happening between two individuals.

![Discord Screenshot](/img/twitch/splash/twitch_messaging.jpg "Discord Screenshot")
_Disgruntled Twitch user_

One user was trying to message another user about something important, but because of the way Twitch handles messages, the user receiving said message never knew he had a message to begin with.  So this got me thinking about my Twitch desktop app design.  One that had better messaging functionality, while also keeping the same aesthetic appeal of the browser based Twitch site.  

When a user logs into the Twitch desktop app, they're taken to the **Following** screen.  This is no different to what happens when you log into the Twitch web app, or the iPad app.  By logging a user into their following screen, they're able to easily see if someone that they're following is online and streaming.  To be honest, there wasn't a whole lot that I wanted to change with the following screen, because I think that it works quite well as is right now on Twitch.  I did remove the video game cards that would fill the lower right hand portion of the app to show what game a streamer was streaming.  I found that many times that the viewer wasn't streaming the game that was being displayed in their thumbnail.  Also, I just don't like the way the card fits into the thumbnail and takes up that extra space.

![Following Screen](/img/twitch/splash/following_screen.jpg "Following Screen")
_New following layout_

What I did add in my prototype, however, was the ability to hover over a streamers thumbnail and you would get a quick five-second glimpse at what they're streaming.  I think that feature would be a neat little addition to Twitch, and would probably only work well in a desktop application instead of the web version of Twitch.  Plus, by removing the little game picture from the thumbnail, a user can gain a more reliable understanding of what a streamer is playing, instead of relying on the thumbnail / card combo alone.
<div class="twitch_video">
<video controls>
  <source src="/video/twitch/follow_video.mp4" type="video/mp4">
  <source src="/video/twitch/follow_video.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

When a user clicks on a stream that they want to watch, they're taken to that streamers channel.  I've actually gone ahead and modified the iPad versions view of a streamers channel a bit in my design mockup.  I think that the Twitch designers have done a great job of giving everything a nice amount of vertical spacing. By moving the about section, which is located underneath a stream in the web version of Twitch, and moved it into a tab controller with the chat section.  This way, a user is able to click and read the about section if they want, but aren't required to see it every time they open up someone's stream and have to view this huge section underneath the live broadcast.  

![Channel Screen](/img/twitch/splash/channel_screen.jpg "Channel Screen")
_New channel layout_

In my prototype video below, I wanted to show off the transition between thumbnail view, and channel transition.  It's not great, but with more work I could easily make it a lot smoother.  I just wanted to get the point across that a user could easily notice what video game a user was playing by hovering over the thumbnail, and then hopefully, converting that hover to a click and viewing that persons stream.

<div class="twitch_video">
<video controls>
  <source src="/video/twitch/channel_video.mp4" type="video/mp4">
  <source src="/video/twitch/channel_video.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

So I'm going to be honest with ya'll.  I just straight don't like the way Twitch handles messages.  In fact, that's one of the main reasons that I went and started this design mockup.  I saw how Discord designed their messaging system, and I think that they just hit it out of the park.  Now don't get me wrong, Twitch's messaging system works, but I feel like they've taken a core system of Twitch and completely tucked it away into another section, away from the main attraction of Twitch, aka, watching someone's stream.  Not only that, but to find the messages section, they've hidden it inside a bottom bar that you have to click to reveal.

![Twitch Web Message Screen](/img/twitch/artboard/twitch_messaging_web.png "Twitch Web Message Screen")
_Twitch has their messaging function hidden_

What I wanted to do in my design was to take the majority of features that Twitch has hidden in their toggle bar, and place it in the upper right hand corner of the app so that these core functions are more easily accessible and wont remove a user from engaging in the stream that they're watching.  The added benefit of placing the settings and messaging buttons in the upper right hand corner is that instead of having to make two clicks to get to the settings options or messages screen, you only need to make one click.  

![Message Screen](/img/twitch/splash/message_screen.jpg "Message Screen")
_New messages button_

In my prototype, I gave the modal a little spring effect to give it a more welcoming appearance, and therefore making it a more enjoyable experience to click and view your messages.
<div class="twitch_video">
<video controls>
  <source src="/video/twitch/messages_video.mp4" type="video/mp4">
  <source src="/video/twitch/messages_video.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

Just like with the messages button, I wanted the settings functionality to be much more accessible, and not take a user away from the stream that they may have been watching.  Instead, have a modal pop up and all the settings that a user can set would be much more easily configured.  I think this works a lot better than having all the settings hidden away like it is right now on Twitch, and I believe that this system works a lot better and would be more doable in a desktop app, than in a web app.  

![Settings Screen](/img/twitch/splash/settings_screen.jpg "Settings Screen")
_New settings button modal_

In my prototype, you can see that I've actually taken all of the settings that you would find inside the toggle button on Twitch, and have moved them all into their own tabs inside the settings modal.  I really like this design concept more than what's available right now on Twitch.  By separating them into individual tabs, a user can more easily configure different settings, and once they're done, they can just close the modal and continue watching their stream.  I added the turbo tab inside the settings modal, but I could easily envision it as its own button in the navigation bar.
<div class="twitch_video">
<video controls>
  <source src="/video/twitch/settings_video.mp4" type="video/mp4">
  <source src="/video/twitch/settings_video.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

All in all, I think that I was fairly successful in my attempts in designing a Twitch desktop app.  Obviously there's a lot missing, and I never designed for the five different states, just the ideal states of the app.  Like a stated at the beginning of this post, I love to watch streams on Twitch.  Getting to interact with like minded folks, never mind the chaotic chat spams of the more popular streams, is an awesome experience that I love being a part of.  I think that a desktop app that provided a more robust chat system, messaging system, and neat little added features like hover states would give the more dedicated Twitch viewer a more engrossing streaming experience.

For anyone interested, I've made my [Principle file available for download](http://www.mrkitsune.com/files/Twitch_App_Prototype.prd).  As well as my [Sketch](http://www.mrkitsune.com/files/Twitch.sketch) file, and a full walkthrough of my prototype can be viewed below.  

<div class="twitch_video">
<video controls>
  <source src="/video/twitch/Twitch_App_Prototype.mp4" type="video/mp4">
  <source src="/video/twitch/Twitch_App_Prototype.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>
