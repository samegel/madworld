# Optimizing Web Output
Daniel Ferguson
* 47% of users expect a page to load in 2 seconds
* 40% of users will abandon a site that doesn't load in 3 seconds

Things you can control w/Flare:
1. Reduce number of requests - browsers only load 5-6 elements at a time. This is called the "waterfall".
2. Increase speed of server-to-client transfer. Get rid of dead weight.
3. Provide code that renders quickly. Specifically create CSS that loads quickly.


# Sprites
Browsers render multiple classes from right to left

div.homePDFSection
ID selectors render faster than anything else bc/they have to be unique

# Getting rid of dead weight
There is a lot of dead weight data in images
Use a png compressor - giftofspeed.com for png compression
Combine image sprites w/image compression to save on dead weight

# Minification
Grunt - run as post build event in target
https://www.smartoutput.com/articles

# More CSS performance features
@import rule - includes all of one stylesheet in another
To load multiple stylesheets, instead of using @import,
1. Allow multiple stylesheets in target
2. Link Stylesheets in masterpage

# Future steps
"Render blocking" CSS and JS loads up front. Put this javascript at the bottom, grunt may be able to do this. Ferguson
is investigating which JS can be deferred.