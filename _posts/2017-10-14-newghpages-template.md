---
title: "install gh-pages template"
excerpt: "How to install template in github online without messing with jekyll or ruby and gem command line"
categories:
  - Tuto
tags:
  - Github
---

## Objective:
>How did you manage to add this super minimal template on your github? I just followed the "getting started" and nothing else append except a lot of "Error 404". In two minut, I'll burn everything down!

Mmmmm, yes, Indeed. I spend some time to understand myself because we don't actually need to play with gem and rebuild something.  
Since we don't use any server, everything is take cared by github online.

## SO, let's build ourself a website with github

{% raw %}<img src="https://user-images.githubusercontent.com/12049360/32783449-14fa6384-c94c-11e7-96bc-2ed08f71e164.png
" alt="">{% endraw %}

To help during my setup I have filled this issue with my mistakes, my loot and comments.  
[It could help... I don't know.](https://github.com/nicolasdb/nicolasdb.github.io/issues/10)

I'll assume you already have a github account and I'll skip some change I made on \_config.yml  
Let's start then...  

1. clone on your computer the repo of the future website. If you tried already, you'll have something with your name and .github.io with stuff into, that's the one.  
2. No need to clone the template repo, just download the .zip  
For example, [use mine for now,](https://github.com/nicolasdb/nicolasdb.github.io/archive/master.zip)  I have made all the changes we need from the original repo.
3. Back to your xxx.github.io folder, delete everything BUT the .git folder   
![image](https://user-images.githubusercontent.com/12049360/32784466-34f65b72-c94f-11e7-80f7-aca55ab5a470.png)  
It's hidden so if you don't see it, good, leave it hidden. It contain all the data for git, the commits and shit.
4. Extract the .zip somewhere and copy/paste everything BUT the .git folder into your xxx.github.io.   
**Trust me, You don't want this puppy messing with your own .git**
5. And now, it's time to commit all the changes online.  
   - you can do it with github desktop or any GUY you want if you prefer
   - you can try with these lines. It's a good opportunity to try command line. It's easy.

Just follow this, one by one.  
*IF you're on PC, open "git Shell",  
ELSE any terminal.*
   ```
   cd valonlisbeth.github.io
   git fetch     // c'est pour vérifier s'il y a eu des changements en ligne
   git pull       // c'est pour downloader ces changements
   git add .       // c'est pour ajouter les modifs faites en local (dans le dossier .git)
   git commit -m "reset template web"      
   // c'est pour créer le commit et signaler ces changements en ligne avec -m pour le message
   git push     // c'est pour uploader ces modifications
   ```
you should see something like that appening:  

![image](https://user-images.githubusercontent.com/12049360/32782949-6412477c-c94a-11e7-88a7-fad69c46857a.png)

Pay attention on colors and what's mention.  
In my case just now, I had made some change on files localy and added a picture online. So I had to first fetch and pull the picture then add my change in some post (.md), commit these changes and push it back online.  
when everything is nice, you get [master =] in blue.  

Cool, do you feel the hacker in yourself?  
Practice these, work online, fetch and pull, work localy, add and commit, observe how it change, it will become easy.   
![image](https://user-images.githubusercontent.com/12049360/32783034-a8486304-c94a-11e7-8fe7-4d97c80aa961.png)

  6\. Last step. Go to "Settings"  

![image](https://user-images.githubusercontent.com/12049360/32785731-85ed06ae-c952-11e7-931e-57343b5108ba.png)

It should look like that.  
I think it's automatic for xxx.github.io repo because github will associate repo name and files in it. I don't know, I don't remember now. Anyway you cannot choose which branch to use for website or anything with the xxxx.github.io address, it's allways the "Master" and it's kind easier that way but that's another story.  

![image](https://user-images.githubusercontent.com/12049360/32785828-bd310912-c952-11e7-8d8a-430a28d1d3de.png)

# @ this point, you should have my website on your address.github.io - YEAH

And as always, you can help me and [contribute on this one here](https://github.com/nicolasdb/nicolasdb.github.io/blob/master/_posts/2017-10-14-newghpages-template.md)  

![image](https://user-images.githubusercontent.com/12049360/32787427-c97b07b4-c956-11e7-8c53-b82c62ed1309.png)
