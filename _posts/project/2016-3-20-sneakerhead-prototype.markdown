---
layout: post
title:  "Sneakerhead App Prototype"
date:   2016-3-20 06:45:19 -0800
categories: project
tags: snippet
featured_image: "/img/sneakerhead/principle.jpg"
post_images: false
---
## SNKRHEAD Prototype Using Principle

I really enjoy making UI's in sketch a lot, but what I really love is prototyping UI ideas.  Everything from figuring out the actual application flow, and what a user would see when using my app, to the finer details like what buttons should do when clicked, or subtle animations that should play when an action is performed.  The software that I've been prototyping with as of late has been [Principle](http://principleformac.com/).  It's the only prototyping software as of late that has really clicked in my brain.  Sadly there's only a handful of tutorials for it, so for the most part, I've learned Principle through trial and error.

I started my prototype with a simple fade in of the title and logo used for the app, as well as text instructing the user to tap to begin using the app.  The app would then fade into the **_What's New_** section of the application.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead1.mp4" type="video/mp4">
  <source src="/video/snkrhead1.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

I wanted to make a **_What's New_** section that showcased what new sneakers were available for purchase.  I wanted to use large pictures of the shoes, but couldn't figure out a good way of showcasing the whole shoe on the screen.  So I went with just showing off the tip of the shoe to entice users to click the **_learn more_** button to check out that particular shoes section.  I thought of doing some kind of parallax effect that happens when you swipe to the left to view the next shoe.  However, in the end, I chose to just do a simple controller indicating what slide you're on.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead2.mp4" type="video/mp4">
  <source src="/video/snkrhead2.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

When a user clicks on a **_skip_** button that's viewable on one of the **_What's New_** slides, it'll take them to the **_Shoes_** section.  There, a user can scroll through the different shoes available for purchase, and when a user swipes a particular shoe, they can view the second color available, which they can then click to view that particular shoes page.  When looking back on this video, I realize that I give no indication that a user can swipe to the left to see another shoe color, so I should have put some kind of indicator telling the user that there's two pictures for each shoe listed.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead3.mp4" type="video/mp4">
  <source src="/video/snkrhead3.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

When a user clicks on the **_learn more_** button that's viewable on one of the **_What's New_** slides, it'll take them to that particular shoe's page.  Here a user can read a description of the shoe, slide through more photos of the shoe, read the benefits of that sneaker, switch between the two color options, and finally purchase the sneaker.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead4.mp4" type="video/mp4">
  <source src="/video/snkrhead4.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

Here's a second video showing that a user can click on a particular color of the shoe from the **_Shoes_** section, and it will take that user to that particular shoe color, and not what the default color would be if they clicked the **_learn more_** button from the **_What's New_** slide.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead6.mp4" type="video/mp4">
  <source src="/video/snkrhead6.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>

The final video shows off what happens when a user clicks the **_purchase_** button.  A sidebar slides in from the left where they can choose their shoe size, quantity and the add to cart button.  When the **_add to cart_** button is clicked, the **_Shopping Cart_** screen slides in from the bottom listing all the items that a user added to their purchasing list.  
The **_place order_** button was something that I struggled with for a while, because I wanted a way that users didn't have to make an account with my sneaker app, but instead use an account that they probably already have, and a service that they trust to use for purchasing items.  So I went with Amazon's purchasing method of a one click purchase that is quick and easy to use.  Now Amazon uses a slide to purchase action, where I went with a hold down to purchase button.  Either method would work just fine, the whole point was to make purchasing shoes using the app simple and direct using a service that's already trusted by millions.  
Finally I added a purchasing process screen for fun to indicate to the user that their transaction is processing.
<div class="snkrhead_video">
<video width="375" height="667" controls>
  <source src="/video/snkrhead5.mp4" type="video/mp4">
  <source src="/video/snkrhead5.webm" type="video/webm">
Your browser does not support the video tag.
</video>
</div>
