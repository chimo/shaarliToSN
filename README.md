# Note

I'm done with this. If someone wants to maintain it send me a note and I'll transfer the repo. Or just fork it, or whatever.

# Intro

Adds a simple "Share to StatusNet" link to your [shaarli](http://sebsauvage.net/wiki/doku.php?id=php:shaarli) 0.0.37beta installation.  
It opens a new tab/window with a pre-populated "bookmark" type of notice.

![Screenshot](http://chromic.org/images/shaarli.png)

# Install

1. Backup your original **/tpl/linklist.html** in case things go wrong.
1. Overwrite **/tpl/linklist.html** with **linklist.html** provided in this project.
1. **(Optional)** If you're using your own instance of StatusNet, replace "identi.ca" with your domain on line 75.

A unified diff (linklist.diff) is available if you want to see exactly what changed from the original.

# Flattr this

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=chimo&url=https://github.com/chimo/shaarliToSN&title=shaarliToSN&language=&tags=github&category=software) 
