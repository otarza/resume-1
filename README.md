Irakli Saparishvili (Safareli)
=============

Front-End Software Engineer
-----------------------

- Email: <i.safareli@gmail.com>
- safareli @ [Github](http://github.com/safareli) @ [Twitter](http://twitter.com/safareli) @ [LinkedIn](http://linkedin.com/in/safareli) @ [Gibbon](http://gibbon.co/safareli) @ [SpeakerDeck](http://speakerdeck.com/safareli) @ [YouTube](https://www.youtube.com/user/iSafareli/videos)

## Summary


I am technology agnostic software engineer specialised in front-end development. I started coding when I was 15 and during my career I have gained a lot experience as a front-end web developer. However, I also possess substantial experience developing applications for Android, iOS, and Drupal. Digging into Functional, Dataflow and Reactive Programming, React.js, Living Style Guides and CSS architecture to find ways of delivering maintainable, scalable and modular UI. I am looking for opportunities to use my experience and knowledge to improve the wayes of build UIs and improve front-end workflow.

In my role as the co-founder of uniHack, I have organized the biggest college hackathons in the Caucasian region. In addition to this, I'm driving local developer communities and organizing meetups which allows me to bring together a group of people who share the love of creating.

I am passionate about building high quality applications and user interfaces with modern web technologies. In my free time I enjoy contributing to open source projects, experimenting with physics simulations and audio visualizations, reading, listening to music and biking in cities or countryside.


## Experience

*As a freelance developer I have worked on some small mobile apps and internal web applications for different organizations/companies.*


### Freelancer Front-end Engineer @ [WeAreDe](http://weare.de.com/)

####**StyleDiplomacy** - online fashion Store

This project required analysis of 13 PSDs (some of these contained more than 1 page in it). Since automation is bases for productive work I wrote a [script](https://github.com/safareli/psd-extractor) with **[psd.js](https://github.com/meltingice/psd.js)**, used it to parse all of those files and got [data](https://github.com/safareli/psd-extractor/blob/master/examples/extracted.json) I needed to proceed. I standardized received data, throwing away about **66%** of colors and **50%** of font-sizes (slight variation of colors for instance, indistinguishable for human eye, are just a waste of development time). Layout was not simple, I needed really advanced, fully responsive grid system, so I based it on **flexbox**. I also used **React.js** with **JSX** to get react components (like public interface of css components written with [CSS Bliss](https://github.com/gilbox/css-bliss) style guide) and templates (which were using those components) and generated static html pages based on this system. While working I noticed that after building initial frame, I didn’t even need to write any custom css - in the end client got highly responsive and modular pages:
> [Subscribe](https://sandbox.weare.de.com/stylediplomacy/build/),
[Category](https://sandbox.weare.de.com/stylediplomacy/build/category/),
[Checkout](https://sandbox.weare.de.com/stylediplomacy/build/checkout/),
[Contact](https://sandbox.weare.de.com/stylediplomacy/build/contact/),
[Designer](https://sandbox.weare.de.com/stylediplomacy/build/designer/),
[Designers](https://sandbox.weare.de.com/stylediplomacy/build/designers/),
[Destination](https://sandbox.weare.de.com/stylediplomacy/build/destination/),
[Home](https://sandbox.weare.de.com/stylediplomacy/build/home/),
[Lookbook](https://sandbox.weare.de.com/stylediplomacy/build/lookbook/),
[Post](https://sandbox.weare.de.com/stylediplomacy/build/post/),
[Product](https://sandbox.weare.de.com/stylediplomacy/build/product/),
[Search](https://sandbox.weare.de.com/stylediplomacy/build/search/),
[Terms](https://sandbox.weare.de.com/stylediplomacy/build/terms/),
[Error](https://sandbox.weare.de.com/stylediplomacy/build/404/),
[Styleguide](https://sandbox.weare.de.com/stylediplomacy/build/styleguide/).
in Right Navigation: Menu, Card, Wishlist, Search, Login/Register


####**Rooms Gazette** - blog of [Rooms Hotel](http://roomshotels.com/)

Collected all colors, font sizes, and spacings, put thous into **sass** dictionaries and generated [Responsive Utility](https://github.com/safareli/responsive-utils) classes. combined with some other components I had a stong foundaition for building pages I needed to deliver. after some time i deedn't even needed to touch css and I just combine thous components and utility classes and still build fully responsive pages:
> [Homepage](https://sandbox.weare.de.com/roomsgazette/build/), [Guests](https://sandbox.weare.de.com/roomsgazette/build/guests.html), [Text](https://sandbox.weare.de.com/roomsgazette/build/text.html), [events](https://sandbox.weare.de.com/roomsgazette/build/events.html)


### Software Engineer @ [AzRy](http://azry.com/)
*May 2014 – February 2015* (10 months) Tbilisi, Republic of Georgia

My first task was to rewrite the [*LEPL - Legislative Herald of Georgia*](https://matsne.gov.ge) website from the old version in Joomla to **Drupal** 7. Upon successful completion, I began work on a native mobile application. In this role, I created **HTTP API** and worked on sections of the **iOS** app using **Objective-C**. Following this, I worked as a front-end developer in [TBC Bank's](http://tbcbank.ge) project [P2P](https://p2p.ge) - pear to pear money transfer. I used **Jade** for rapid Prototyping, **MVCSS** with **stylus** for writing maintainable and scalable **CSS** (also combined ways of generating responsive grids with utility classes and generated realy helpful **responsive utility classes**) and **Gulp.js** for development workflow automation.

### Software Engineer @ [ITDC](http://itdc.ge/)
*November 2012 – August 2013* (10 months) Tbilisi, Republic of Georgia

My main focus was working on MyVideoTV application for [*Android devices*](https://play.google.com/store/apps/details?id=ge.myvideo.hlsstremreader) and custom [*TV Boxes*](http://www.myvideo.ge/tvbox) running Android. The majority of code was written in **Java** using the **Android SDK**. I also worked as a front-end developer for responsive web sites. I used **Guard** for automating development workflow, **Sass** and **Compass** for writing **CSS**, **Bootstrap** and **jQuery** Libraries.


## Community Involvement

### Co-founder & Co-Organizer @ [uniHack](http://unihack.io)
*December 2013 – Present* Tbilisi, Republic of Georgia

I organized the first international college hackathon in the country of Georgia with around 500 students from 5 countries. Besides organizational work I developed the main web sites for our **hackathons**. I developed simple particles' **physics 2D simulation** as a **Canvas** background of [uniHack.io](http://unihack.io). I have used **gl-matrix** for high performance vector math,  **browserify** and **CoffeeScript** for **JavaScript**, **Stylus** for **CSS** and **Jade** for **HTML**. Because of our need to go international I used  **Gulp.js** for building *bilingual* **static sites**. Also I used **THREE.js** for 3D background of hackTbilisi ([2014](http://2014f.hacktbilisi.com/) and [2015](http://2015f.hacktbilisi.com/)).

*Sources of these sites are available on our [GitHub page](http://github.com/uniHackge).*


## Education

Computer Science, B.S.  
Fall 2013 to Present  
[Georgian Technical University](http://gtu.edu.ge/Eng/), Tbilisi, Georgia



-----------------------

*Notes*:

- The most resent version of this resume is available at [github.com/safareli/resume](https://github.com/safareli/resume)
- I'm using [markdowntopdf.com](http://www.markdowntopdf.com/) to generate pdf from markdown
