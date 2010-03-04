SleekGallery
==========
A [jQuery] [1] port of [JonDesign's SmoothGallery] [2]

###What is it?
Using jQuery 1.3.2 or newer, this javascript gallery and slideshow system allows you to have simple and smooth (cross-fading...) image galleries, slideshows, showcases and other cool stuff on your website... 

###So, what is so cool about it ? 
Unlike other systems out there, JonDesign's SmoothGallery was designed from the ground up to be standard compliant: You can feed it from any document, using custom css selectors.

SleekGallery continues in this spirit and tries to be flexible, configurable and yet as lightweight as possible. Currently the base slideshow script is 37kb uncompressed. 

This can be reduced to less than 7kb using javascript minification and gzip compression on your webserver.

###Why consider it instead of a Flash-based solution ?
* Let's imagine you want to add a showcase of your last products, or even a showcase of one product on your homepage. Would you want to restrict it only to the users who have Flash enabled ?
* Another important point is the fact that using this script, you will have fully standard compliant web pages (which is important for accessibility, for example).
* Using a flash based solution, search engines won't see your content nor links. Not really the expected result, right ?
* Oh, and do you really want to rely on a big company's proprietary licensed app for your website ?

###On what browsers does it run ? 
Since it's based on the jQuery library and the dynamically generated code is fully (X)HTML compliant it should support all all modern and capable browsers.

Only browsers on the current YUI Graded Browser Support ["A-Grade"] [3] chart will officially be supported regarding visual features.

###What's currently missing compared to SmoothGallery 2.1beta1
* HistoryManager so that the browsers back and forward buttons control the gallery
* The "enhanced" set of transitions has not been ported yet
* Gallery Sets have not been ported yet

  [1]: http://jquery.com/ "jQuery"
  [2]: http://smoothgallery.jondesign.net/ "JonDesign's SmoothGallery"
  [3]: http://developer.yahoo.com/yui/articles/gbs/#gbschart "A-Grade"
