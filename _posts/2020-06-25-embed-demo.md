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
