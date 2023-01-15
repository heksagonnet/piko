---
author: Jean Burgo
title: Github
date: 2019-03-08
description: My Github Exploration
tags: ["markdown","git", "Hugo", "html", "themes"]
categories: ["themes", "syntax"]
math: false
ShowBreadCrumbs: false
draft: false
---

A while back I was wondering what was [Github]() and how it was used. Although I had downloaded some resources from it, I never really understood what it was used for. 

![](/uploads/github.png)
## The start of my learning journey
I was finally intrequed enough to begin my learning journey with Github. 

After watching many Youtube videos on what Github was, I realized that I needed a project to use Github to get me started. 

I decided to build a simple website (this website right here), but I didn't know where to start. 

The last time I built a website was in 2005. I used Adobe Dreamweaver to create a canvas and publish it through an FTP connection. I am no expert, but clearly that is not the best bethod to build a website. 

I had zero knowledge of markdown and my html skills can't go beyond a "Hello World" page. 

## Tools used
I turned to [Hugo](https://gohugo.io/) as it promissed to be the simplest way to build a website. Hugo uses templates like the one I am using on this website [(Piko) created by heksagon](https://www.heksagon.net/template/piko/). After many failed attempts using other templates (I'm sure I was doing it wrong) decided to stick with Piko. It was a bit difficult to understand at first, but there is no doubt this is one of the best Hugo templates out there. 

I am still wrestling with some issues. Sometimes I spend way too long trying to get something to work. After hours of watching Youtube videos or reading online I have to move on to use a different strategy. Unfortunately, there is not a lot of documentation I could use to overcome these issues. 

To publish my website I went with [Netlify](https://www.netlify.com/) because of a good suggestion from a Youtube video. The first template I use had massive issues. I learned that adding the public directory, and declaring the version of Hugo I used fix those critical errors. After long hours, the website did not look the same as it did on my localhost. I am not sure why that was, but after three days I gave up using the clarity theme. 

I still don't know how to get the social media buttons or the contact form to work. There is a lot more content I want to add to the stait website but I will built it little by little. I am very happy with the progress I made. 

# Steps
After all of these issues were streighten out I was able to practice how to use Github. 
- I created a Github account [jeanburgos](https://github.com/jeanburgos) where I was able to find and fork the Piko theme. For what I understand, forking creates a copy of the original content and places it on your account. This makes sense because I want to make changes to my website, not the original template. 

- I got mixed up between [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) and [Visual Studio Code](https://code.visualstudio.com/). I still couldn't tell you what is the different application for both, but I just knew that it looked different that many of the videos I watch trying to get Github and the developing environment. I used Visual Studio Code to link a master branch and link the repositories. Once this was completed I was able to creat push and pull request between Github and my computer runnig Visual Studio Code. Other area that took me some time to understand was that it is necessary to not only save, but commit what you saved so that it can be sent to Github. 

- After Github was set up, I was able to link it with Netlify. The chain reaction looked like this.
1. Changes made in my computer 
2. Save changes > commit saved changes (must type commit message)
3. Commit is saved and updated in Github
4. Github content in sent and sync with Netlify to publish on the website automatically. 


<!--more-->
