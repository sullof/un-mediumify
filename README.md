![Un-mediumify](un-mediumify_96.png)

# Un-mediumify
Medium is just a blog platform. A blog post is a web page with text and
images, sometimes embedded videos. It doesn't and shouldn't need javascript.

Whenever I visit sites that are using medium, my browser uses far too much CPU
for what should be a static page.

I also find abhorrent that Medium thought it a good idea to modify the current
URL in the browser bar with a tracking number after the fragment identifier
(hash mark).  
For a while, this anti-feature broke a must-have browser functionality: when
I reloaded the page, the browser didn't put me at the same position
in the page as I last left it, but instead at the top.

Therefore, there is a need for a stop-the-fan-from-spinning and
stop-the-idiocy browser extension that makes reading on Medium sites a bearable experience.
I don't trust Medium on its own to provide a decent experience on Firefox.

This WebExtension turns javascript off on medium-platform sites while still
repairing image links so that it can be read as any other blog (because,
for whatever nonsense reason, images aren't loaded and don't appear if you
don't enable javascript on Medium. Fuck you, Medium, seriously).

# Usage
On medium sites that aren't under the medium.com domain, click on the
un-mediumify button in the URL bar to repair the image links.

On medium.com posts, the image links should be automatically repaired without
a need for user action.

# License
Released under the GPLv3.
