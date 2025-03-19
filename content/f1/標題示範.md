---
title: Why the switch?
date: 2025-03-02T13:47:01.456Z
description: On why I switched website systems.
---
# What Happened?

If this isn't your first time on my website, you might notice that not only is the domain different, there is also a drastic change of style. That is because I have switched over from Wordpress. 

# Why?

> tl;dr I am too lazy to migrate the old one.

Assuming you know a slight bit about website building (if you don't, don't mind the rest because it will only get more and more technical as we discuss), you must know Wordpress. It's the most widely used website CMS (content management system) around the world. In fact, more than half of the websites in the world are built using Wordpress. The no-code, user-friendly interface and logic makes it easy for beginners. That's why most of my previous websites are Wordpress-based, including my original blog. 

Not wanting to pay for hosting, I figured out that GitHub Pages is my best option since traffic won't be high and Git makes it easier to keep track of edits. But the biggest setback of using GitHub Pages is that it can only host static websites. The definition of a static website is that it's built purely with HTML and CSS (sometimes including JS), but to be descriptive, it indicates that the website doesn't have any interactive functions and is stationary. Because the backend of Wordpress is not static, it needs to be converted to static with another program, and that's what I did for my last blog.

Even though the editing was flawless and the only additional step is to convert it to static, another issue occurred when I switched to a new PC: simply cloning or pulling from Git is not enough, and re-installing Wordpress and all the plugins I was using is a big hassle.

A few days ago, I finally decided to continue blogging. But this time, I have decided to start over and switch to Hugo. Not only is it faster in rendering, I can also use the CMS remotely on a browser without using Git. All I have to do is do a one-time OAuth app setup, and I can access the admin panel anywhere with my GitHub account.

Another reason not to use Wordpress is that Hugo renders based on markdown files. My daily noting driver is Joplin, and it also uses markdown. This means I can blog whenever I want, even on a plane, and upload it directly once I have internet access.

# Conclusion

That's all my main reasons for switching, excluding a few minor ones, like customization, that I didn't mention. But that's all for today, and I'll slowly be migrating some of the posts on the previous website to this one. See y'all next time!
