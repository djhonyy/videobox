Original Description that you cand find in http://videobox-lb.sourceforge.net/

Youtube, Metacafe, Google Video, iFilm and custom flashnew
----------------------------------------------------------------------------------------
Introduction

Videobox is a 6kb script, which shows your videos in the page with an overlay. It was inspired from Lightbox.v2 and uses some of the Slimbox's code. It's written for the wonderful mootools library. And used swfobject to embed flash.

----------------------------------------------------------------------------------------
Usage

Firstly, you should include 3 javascript files to your page. You can change the path, if you upload it to somewhere else. You can paste the code below in your head tag.

<script type="text/javascript" src="js/mootools.js"></script>
<script type="text/javascript" src="js/swfobject.js"></script>

<script type="text/javascript" src="js/videobox.js"></script>

And you must include the css file(for the styles).

<link rel="stylesheet" href="css/videobox.css" type="text/css" media="screen" />

And, here is the thing:

<a href="http://www.youtube.com/watch?v=uhi5x7V3WXE" rel="vidbox" title="caption">our video</a>

Add the rel="vidbox" to your video page's link to show video links in Videobox, and add title="my caption" to add caption to a box.


You can also start your videos with javascript.

Videobox.open("your video page url","your caption","vidbox widht height");

----------------------------------------------------------------------------------------
Notes

Videobox is licensed under MIT License. If you like it you can

If a videobox link doesn't have any connection with the video sites, it will be shown as custom flash movie.

Internet Explorer waits for a little time to show the video. At least my IE6 does.

I had to attach the video URLs to page URL, if you overcome that thing please tell me.

If you want to show FLV files you should use Jeroen Wjering's Flash FLV Player with custom flash feature.

My name is Faruk Can 'farkob' Bilir and I'm a highschool student in Turkey. You can contact me at farkob [at] google's mail [dot] com.

If you find a bug or want to suggest a feature, please tell me.



----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
Tradução livre




