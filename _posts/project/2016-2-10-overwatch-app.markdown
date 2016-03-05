---
layout: post
title:  "Overwatch App"
date:   2016-2-10 08:09:51 -0800
categories: project
tags: snippet
featured_image: "/img/overwatch_app/dva1x.jpg"
post_images: false
---
## I Play To Win!

I'm super pumped for [Overwatch](http://us.battle.net/overwatch/en/game/)!  So much so that I decided to think of what an app for the game would look like if it were to be developed by Blizzard.  I wanted the design of my app to encompass the feel of the Overwatch universe, with images, icons, and colors that seemingly go hand in hand with the [iOS Human Interface Guidelines](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/).   

So like a good little UI designer, I didn't just go and open up Sketch and begin designing the app.  The first thing that I did was write down and answer a bunch of common interview questions that I think Blizzard would use to gauge interest in an Overwatch app.  More importantly though, these questions helped me figure out who the target audience for this app would be.
{% responsive_image path: img/overwatch_app/interviewquestions.png alt: "Questions" title: "Questions"%}
**_Click to read rest of the questions_**

After figuring out who my target audience was, I went ahead and made a persona board mockup with four different personas.  The persona board really helped me out a lot in making sure that the focus of the Overwatch app wasn't just for the hardcore FPS playerbase. I had to also focus on gamers who maybe only play WoW or Hearthstone and not First Person Shooters, or folks who would like to try out Overwatch, but have never played a FPS before.
{% responsive_image path: img/overwatch_app/persona.png alt: "Persona Board" title: "Persona Board"%}
**_Click to view persona board_**

Once I finished up both my interview questions and persona board, I went ahead and started to make my wireframes for the app.  My idea for the Overwatch app was for the user to log in using their [battlenet](http://us.battle.net/en/) account, because I know Blizzard has talked about selling skins for heroes, and so if a player wanted to buy a skin for a hero they liked, they could do so through the app using their battlenet account.  I wanted the Overwatch app to have a rankings section, a forums section, a heroes section, and a live section.  These sections will be explained in better detail with my high fidelity screens.
{% responsive_image path: img/overwatch_app/wireframes.png alt: "Interview wireframes" title: "Interview wireframes"%}
**_Click to view wireframes_**

## Home Section

I wanted the home screen for the Overwatch app to feel dynamic with direct links to tournament streams at the top, and showing off the latest news in the Overwatch universe.  Be it patches, developer videos, cosplay pictures, all configurable by the user to show what is important to them.  
[![Home Screen](/img/overwatch_app/overwatchHome1x.jpg "Home Screen")](/img/overwatch_app/overWatchHomescreen1x.jpg)
**_Click to view home screen_**

## Rankings Section

When a user clicks on the rankings button, they're taken to the rankings screen.  Here a user can search for players, teams, and upcoming Overwatch tournaments.  Right off the bat, I wanted players who were more interested in E-Sports to be able to see the top teams from around the world, and their standings.  If I were to actually create an Overwatch app, I would allow users the option to switch off the team rankings section, and instead show off their profile, with their personal stats showing.
[![Rankings Screen](/img/overwatch_app/Rankings1x.jpg "Rankings Screen")](/img/overwatch_app/Rankings1x.jpg)
**_Click to view rankings screen_**

When a user clicks on a particular teams name, they're then taken to that particular teams section.  From there, they're able to view news related to that team, a media section for videos or social media posts from that team. The roster screen would show who's on that team and the teams recent matches. I also put a live button there so that if a member from that team streams on twitch, it would be viewable from the team section part of the app.
[![Team Screen](/img/overwatch_app/teamMembersScreen1x.jpg "Team Screen")](/img/overwatch_app/teamMemberScreenLong1x.jpg)
**_Click to view team screen_**

The roster section is is a little unique in the sense that you're able to click and view a team members own section.  Here you're able to read their bio, their stats, and look at their recent matches, personal or team matches.  You would be able to click on any of those recent matches and watch a VOD of that match.
[![Individual Roster Screen](/img/overwatch_app/individualRoster1x.jpg "Individual Roster Screen")](/img/overwatch_app/indRosterLong1x.jpg)
**_Click to view individual roster screen_**

## Forums Section

The forums section is where users would be able to view the latest patch notes, maintenance times, general Overwatch discussion, as well as hero forums to talk all about strategies and whatnot.  I also wanted to add a "Latest Blizzard Post" carousel that users could swipe through and then click on to view particular forum posts.
[![Forums Screen](/img/overwatch_app/forums1x.jpg "Forums Screen")](/img/overwatch_app/forums1x.jpg)
**_Click to view forums screen_**

When a user clicks on one of the forum buttons, such as the _News And Updates_ button, they're shown all of Blizzards latest posts dealing with upcoming patch notes, or maintenance times.  Users would not be able to post or comment in this section, only read what Blizzard employees have posted.
[![News And Updates Screen](/img/overwatch_app/newsAndUpdates1x.jpg "News And Updates Screen")](/img/overwatch_app/newsAndUpdatesLong1x.jpg)
**_Click to view news and updates screen_**

## Heroes Section

The heroes section is where users would be able to see all the playable heroes in Overwatch.  By clicking on a heroes portrait, the user is taken to that heroes section.
[![Heroes Screen](/img/overwatch_app/heroes1x.jpg "Heroes Screen")](/img/overwatch_app/heroes1x.jpg)
**_Click to view heroes screen_**

Each hero screen would show off their abilities, backstories, and three sections that a user could click to view the best players for that particular hero, a link to that heroes forums section, and a strategy link that leads to the latest blog posts that talk about strategies for effectively using that hero in battle.
[![Individual Hero Screens](/img/overwatch_app/indvHeroes1x.jpg "Individual Hero Screens")](/img/overwatch_app/heroeslong1x.jpg)
**_Click to view individual hero screens_**

## Live Section

The live section is where users would go to watch tournament streams or to watch individuals streaming Overwatch.  Harnessing the power of Twitch, users could favorite, chat, or just watch people play Overwatch at either a competitive level, or watch their favorite Twitch streamers play Overwatch.
[![Live Screen](/img/overwatch_app/live1x.jpg "Live Screen")](/img/overwatch_app/liveHomeLong@1x.jpg)
**_Click to view live screen_**

While a normal Overwatch stream would just have the video streaming at the top and a chat box below it, I wanted the tournament streams to not have a chat window at all, but instead have a live map and scoreboard for people who wanted a more engaging E-Sports experience.  I used to watch a lot of Counter-Strike matches, and one of the things that I loved was having a live map showing me where each team member was located.  This type of information would make matches really intense, especially when two opposing team members were extremely close to one another.  So that's what I wanted for my Overwatch app, a live map showing where the team members from each side where located, and this map constantly update when someone was killed.  I also wanted a kill log below the map so that user could scroll through if they missed who killed whom.  

Users could also click the **_Score_** button, and that would show off the scores for every game that has been played between the two teams thus far.  You could click each game to see the final scores, and who was the MVP for that game on each team.  
[![Tournament Screen](/img/overwatch_app/tournament1x.jpg "Tournament Screen")](/img/overwatch_app/tournamentStream1x.jpg)
**_Click to view tournament screen_**

There are a million improvements that I could make on this app mockup, but working on this by myself was a lot of work on its own.  However, I really enjoyed the experience of trying to solve for a problem that I could easily see myself in when it comes to wanting an app for just Overwatch.  The next thing that I'm going to try and do is make a prototype of this in [Invision](http://www.invisionapp.com/).
