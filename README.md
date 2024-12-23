# Site Tweaks

A collection of scripts and CSS so I can avoid heavier tooling.

Chromes extension security model is a bit problematic. An extension doing anything
interesting needs to "Read and modify your data" on all sites. Toss in things like
[Chrome extensions being maliciously hijacked](https://thehackernews.com/2017/08/chrome-extension-hacking.html),
and minimizing the number installed seems prudent.

As it turns out, it only takes a tiny bit of scaffolding to wrap up scripts that
I would otherwise use something like
[tampermonkey](http://tampermonkey.net/) anyway, so
there's minimal inconvenience.

Manage extensions in the Chrome web store [Developer Dashboard](https://chrome.google.com/webstore/developer/dashboard)

### Resources
* 101 Tutorial
    - https://robots.thoughtbot.com/how-to-make-a-chrome-extension
* Chrome developer docs
    - https://developer.chrome.com/extensions/overview
    - https://developer.chrome.com/extensions/content_scripts
* Web store dev dashboard
    - https://chrome.google.com/webstore/developer/dashboard
