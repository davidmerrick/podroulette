I listen to a ton of podcasts, and often it's difficult to decide which one to listen to.
Sometimes machines are better to delegate these decisions to 🤖.

Enter PodRoulette.

This repo contains an RSS feed XML with a list of podcasts I listen to. A GitHub Action deploys it to an S3 bucket. 
I have an iOS [shortcut](https://apps.apple.com/us/app/shortcuts/id915249334) that pulls down this feed, picks a random item from it, and opens it in Spotify.

The shortcut is configured like this:

![Screenshot of shortcut](img/podroulette.jpg)

Enjoy all the free time you have now from having your podcasts chosen for you 🌴.
