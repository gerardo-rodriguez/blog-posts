## A look into the past, circa ~2010

 - By this point in my career, I'd been playing with JavaScript for ~3 years. 
 - Experiences with AS3/C++ really forced me to learn about OOP and also introduced me to design patterns, such as the MVC software architecture pattern.
 - Jumping into using the Zend PHP Framework was a real thought-opener which gave me one example of how to interpret the MVC pattern.
 - I started wondering about applying software architecture patterns, such as MVC, onto the client-side.

Eventually, the opportunity came along to team up with 2 very talented developers/designers. We had a larger-scale project that was going to have a good amount of JavaScript written. We wanted to be more organized, more structured. We took the jump of trying to write our own MVC interpretation for an AJAX driven website.

We learned:

 - Trying to abstract the JavaScript was a great way to really think about how to better architect the app.
 - Trying to apply the MVC pattern was tricky in the world of JavaScript.

Some questions and/or challenges we ran into:

 - What is a model?
 - What is a view? The HTML page, right?
 - Do you have a bunch of individual JavaScript files representing your different classes/controllers?
 - How many is too many JavaScript files?
 - Does this mean we have a back-end MVC setup completely separate from the front-end MVC setup?
 - Updating the content of the HTML page via the JS view controller was still clunky.

We ended up trying to group together similar controllers into single files. We also ended up having one large "view" controller JavaScript file that handled all of the JSON data content and updated it on the page.

Overall, what we ended up coming up with worked, but it definitely wasn't perfect. It did allow us to abstract our code out into controllers and attempt to interpret what the "model" and "view" would represent and how this integrated with the HTML actual view.

## Fast-forward to the summer of 2012

I couldn't help but think that the last attempt at adding an MVC layer onto the client-side was a solid step forward. By no means was it perfect, but I felt good about moving into this direction.

A new project came along during this time that would again present the opportunity to re-visit the idea of MVC on the client-side. Initially, I came in with the mindset that I could take my previous attempt and push it further. This ended up being true, but this time around, how I approached it was much different.

## Don't be hard-headed, no need to re-invent the wheel aka there are smarter folks out there

I really wanted to take what I had done and push it further. I just knew that I'd be able to learn more in doing so. I started down this path, and in doing more research, started finding that there were some JavaScript client-side MVC frameworks/libraries that might be inspirations. After digging deeper, I found myself asking, why not actually use an MVC framework that is already existent? After taking a step back and reminding myself that I only had a certain amount of time to work with, I opted to give a hard look at what already existed.

## Hello Backbone.js

After surveying the landscape during these current times, I finally landed on Backbone.js. It seemed that it was pretty easy to start with, there were plenty of folks using it, which meant I could find plenty of help/answers if I got stuck.

Backbone.js on its own was great! It provided the concept of a model, controller, and also played nicely with another wonderful library that'd I'd used already, Handlebars.js. I loved having some sort of, for lack of better term, "backbone" to my application. That being the case, it still felt as though there was a lot that architecturally needed to be figured out.

Doing some more research, I found another library called Marionette.js. There were a few Backbone.js app examples that used Marionette.js to help simplify the creation of larger-scale applications. After going through some examples, I felt the perfect combination had been found in Handlebars.js + Backbone.js + Marionette.js.

## Handlebars.js + Backbone.js + Marionette.js worked wonders

I couldn't have asked for a better opportunity than the one that had presented itself for me to full-on architect an app allowing existing libraries/frameworks to handle what they do well. I loved this experience. I felt as though I'd found the solution to any mid to large scale JavaScript applications. Indeed, in this moment, it was the right call to make. It allowed me to learn so much and I was very thankful for the opportunity. I ended up using Backbone.js for a few smaller projects thereafter. I couldn't believe I'd attempted to architect JavaScript apps in the past without something like Backbone.js. I did not regret letting go of what I had started to take advantage of the works of smarter folks than myself.

## Summer 2013, the landscape changes again

If there's one thing constant in our industry, it is change. Once again, a project came through that would give me the opportunity to consider using a client-side MVC framework. Since I'd had experience using Handlebars.js + Backbone.js + Marionette.js, I felt the decision upon what frameworks/libraries to use was a given.

At the same time, though, I couldn't help but be curious about some other frameworks that had joined in on the fun. Such names as AngularJS and Ember.js started flirting with my curiousity. At one point, this page titled [Top JavaScript MVC Frameworks](http://www.infoq.com/research/top-javascript-mvc-frameworks) landed in front of me. This helped me whittle down some of the options out there so I could at least focus on a few, if I indeed wanted to pursue this.

## Learn something new again, yes, that's where the fun is

After doing more research, mostly around AngularJS and Ember.js, I decided that I'd at least strongly consider using something other than Handlebars.js + Backbone.js + Marionette.js. I was slightly hesitant, only because I'd have to figure out something new...which, ironically, also made it super interesting and fun for me, having to figure out something new.

Since I'd only have enough time to try and learn one new framework, I tried to be as efficient as possible. Further research led me to believe that AngularJS lent itself more toward smaller to mid-scale apps while Ember.js lent itself to larger scale apps. The project that was forthcoming was a medium sized project. I opted to give my full attention to AngularJS based on this.

## Bye bye Handlebars.js + Backbone.js + Marionette.js, hello AngularJS!

I went through a few tutorials in AngularJS, and I quickly began to fall in love with it. The immediate "wow" factor was definitely apparent. I didn't realize how much work I had to do in Backbone.js to do some of the wonderful data-binding awesomeness that AngularJS came built with. I found myself writing a whole lot less boiler-plate code to do some of the stuff that I'd done in Backbone.js. Best of all, AngularJS was what Handlebars.js + Backbone.js + Marionette.js in one single framework! This was great! That meant there wasn't those odd moments when you weren't quite sure how separate libraries were supposed to mesh together. There was no meshing with AngularJS. It was already one whole unit, ready to provide whatever you were looking for. Backbone.js & friends, I thank you for what you taught me and what you provided me...but it was time to move on. There was no longer doubt that I'd push forward with AngularJS as my framework of choice.

## Final thoughts

I've taken you on quite the ride, if you actually were able to read all of it. I wrote quite a lot. I've officially completed my first AngularJS app, and I still love it and I will definitely continue forward with AngularJS as my number 1 option. I will be honest in that I haven't had a true chance to play with Ember.js. I hope I can find time to do so. I'd hate to not be able to give it a fair chance. Who knows, maybe Ember.js takes over? Maybe it takes over in specific situations? Maybe AngularJS still holds strong and maintains itself as the top JavaScript MVC option? I hope I can allow this to play out.

In my journey, I've realized a few things:

- Don't get stuck on one technology/library/framework, feed the urge to explore.
- It makes sense that present-day frameworks have taken what was there previously and made it better.
- You're going to hit moments where you get stuck and can't figure things out. Step away from the computer, breathe, come back in a few.
- We live at such a wonderful time where there is always new stuff to learn.
- It's good to have more than one option.

I hope you enjoyed my journey. I didn't go into detail, but as you can see, I'd have to write a whole book to do so. I'll try to keep future blog posts shorter. If you're anything like me, unless it's really good, I won't read longer posts. Thanks for reading!