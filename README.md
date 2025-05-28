# Lab8-Starter

 ## Graceful Degradation and Service Workers

[Lab8](https://ebluong005.github.io/Lab8_Starter/)

A Service Worker is a bit of JavaScript your browser runs in the background, separate from any webpage. It helps power things like background syncing, push notifications, and—maybe most importantly—offline access by caching files. Think of it as a smart middleman between your browser and the internet: when you try to load something, the service worker can decide whether to serve it from the network or from its local cache. This makes it a key part of building Progressive Web Apps (PWAs) that feel fast and keep working even when you're offline.

Graceful degradation is a design strategy that makes sure your site still works if the browser doesn’t support advanced features like service workers. The idea is to build the basics first, so users always get a functional experience. Then, if the browser can handle more, you add the extra bells and whistles. For example, even if someone’s browser can’t go offline, they should still be able to visit and use your site the usual way.

Service Workers and Graceful Degradation let you build web apps that are powerful and reliable—no matter what device or browser someone’s using.
