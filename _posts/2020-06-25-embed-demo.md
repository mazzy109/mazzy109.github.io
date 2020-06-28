---
layout: post
title: "Showing off how to embed stuff"
date: 2020-06-27
---

Basically from what I can tell, you just have to have the include ready to go in your includes folder, and then paste your link with the correct imbed id. So like this I think:

{% include youtubePlayer.html id="Q2aaCDNjWEg" %}

Lets test that.

...

Okay, So I had to change the include plugin, but now you just need the youtube ID in the id=X part of that include. 

...

And then the last think I did was wrap the youtube include in a div tag. You can look at the sytax but basically you just name the class in the div tag that wraps the whole youtube plugin, which exists in the includes folder. Then I copy pasted some stuff for CSS that made the video resizable based on browser. Looks better now!

...

Here comes a soundcloud test

<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/770639065&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/user-270585867" title="auxdependent" target="_blank" style="color: #cccccc; text-decoration: none;">auxdependent</a> · <a href="https://soundcloud.com/user-270585867/supernaked" title="Supernaked" target="_blank" style="color: #cccccc; text-decoration: none;">Supernaked</a></div>

wow that was a lot