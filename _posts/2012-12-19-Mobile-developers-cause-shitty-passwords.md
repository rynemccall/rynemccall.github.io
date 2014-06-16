---
layout: post
title: "Mobile developers cause crappy passwords"
date: 2012-12-19 18:00
categories: technology
---

I’m a software engineer, so my tolerence for password pain is a lot higher than most of my friends. (Don’t even get me started on my wife’s passwords.) But, I recently realized that many of my passwords to important sites (like Google, Facebook, Twitter, etc) are way too simple to be considered secure and are often the same (even though I use a password vault to store my passwords). Why is this happening?

I think I’ve got it figured out.

Here is the login screen for Facebook right after I installed them on my new Nexus 4:

![facebook]({{ site.url }}/assets/facebook-mobile-login-screenshot.png)

And here's Twitter:

![Twitter]({{ site.url }}/assets/Twitter-mobile-login-screenshot.png)

Notice anything in common?

Who in their right mind wants to type a password like “I,~^6/_p4;d4G&82f1P5y<+5M” on a touch keyboard? Even grumpy software engineers are going to opt for a password like “somethingSimple1” when confronted with a password blank and a touch keyboard.

To Facebook’s credit, you can change your password without reauthenticating your devices; but, I think that is too much to ask of a user to authorize a mobile device (especially since many folks own multiple devices these days). Other applications do not even throw us this bone.

Unfortunately, things are even worse over in the iOS world (at least as of iOS 5.1.1 that my iPad 1 is running). In addition to the problems with app log in, every time I go to buy or upgrade anything, iOS asks me for my Apple ID and password. On an iPad keyboard this ends up being something easy to type (exactly like the password to my apps above). Wow, not good.

While we all laugh at the stupid passwords that “dumb users” use every year, I think it’s time we admit that we are causing this problem for some of our users.

My proposal for mobile apps where initial account creation happens on a website is a device authentication process that looks like:

![wireframe of authentication solution]({{ site.url }}/assets/authenticate-your-device-wireframe.png)

I haven’t thought much about going in the other direction (initial account creation on device); if you have, throw some ideas my way.

Oh, and one more thing. While we’re building this, why not throw in a “manage authenticated devices” page while we’re at it. That would be awesome.

So, with 2013 right around the corner, let’s make a resolution to stop causing our users to use crappy passwords!