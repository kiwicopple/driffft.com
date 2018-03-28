---
title: "Mixed Reality with Google StreetView"
date: 2018-01-16T14:32:18+08:00
draft: false
weight: 0 # 0 = normal, 1 = featured
featuredimage: 'tracking-street-view.jpg'
blurb: "Google StreetView provides an accessible 'overlay' for the real world. Using cheap consumer devices we created an augmented reality where real people are digitally transposed into Google StreetView."
---


### Introduction

We started experimenting with Mixed Reality in 2013. Since this was before the arrival of Google Glass, Microsoft Hololens, and Magic Leap, we used available consumer devices to create an augmented glasses. These glasses provided an augmented experience using Google StreetView. These early experiments provided the fundamental insights for exaQuark, a Mixed Reality platform which can scale to millions of users.


<video width="100%" autoplay="" loop="">
  <source src="/images/raw/mixed-reality-user-tracked.mp4" type="video/mp4">
</video>
<figcaption>Elodie is tracked in the real world and an avatar mirrors her movements in HybridEarth</figcaption>


#### Our augmented glasses

At the time of our earliest experiments, augmented glasses weren't easily accessible. We built a custom set using available consumer devices:

```
- an Epson Moverio glasses. This is a wifi enabled device that runs Android
- a Samsung Galaxy S3 mini smartphone
- a clamp, strong tape, etc. to interlock the two android devices.
```

![hybridearth Glasses](/images/1000/hybridearth-glasses.jpg)
<figcaption>Our 2013 augmented glasses</figcaption>


The Epson Moverio connects to the internet via the mobile phone. The app for our “hybrid glass” has 2 parts: one running on the glasses, another one on the smartphone. The smartphone performs most of the work, tracking the user's location and the direction they are facing.


#### Creating an augmented reality

Google StreetView offers an amazingly complex "digital replica" of the world, which performs a lot of the heavy lifting for Mixed Reality. For our experiments we built HybridEarth, which uses StreetView and a custom-built digital representation of our office. HybridEarth contains digital avatars of "remote" users who can roam around the world.


<video width="100%" autoplay="" loop="">
  <source src="/images/raw/hybridearth-avatar.mp4" type="video/mp4">
</video>
<figcaption>Remote users can explore the world as digital avatars</figcaption>

It also contains "local" users (wearing AR glasses). Local users are mapped to the digital world, as shown on the screen in the first video:

<video width="100%" autoplay="" loop="">
  <source src="/images/raw/mixed-reality-user-tracked.mp4" type="video/mp4">
</video>
<figcaption>Local users are represented in HybridEarth as digital avatars</figcaption>


From the AR glasses, "real users" can see the remote avatars mapped into their physical location. Here is an example of what they see:

<video width="100%" autoplay="" loop="">
  <source src="/images/raw/hybridearth-ar-view.mp4" type="video/mp4">
</video>
<figcaption>Remote avatars can be seen through the AR glasses</figcaption>


#### Next steps

This year we are hoping to see AR devices become more mainstream. If there is interest in HybridEarth we will open it up to for users to explore and develop their own mixed reality environments, using StreetView as a common map to explore between the environments.
