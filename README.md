Twitter's Bootstrap 3 without responsive features
================================================

Bootstrap 3 will be mobile first. No more separate responsive CSS file. Nice, but what if you don't need / want the resposive features for some reason? So i try to compile Compile Twitter's Bootstrap 3 without resposive features.
[Read more](http://bassjobsen.weblogs.fm/compile-twitters-bootstrap-3-without-responsive-features/)

Download the none responsive css here.

Use ".col-" as class prefix for all your grid rows now.

In most cases set a fixed width for your containers, like:
     
     <style>.container {width:970px;}</style>

Before start using this first read: http://getbootstrap.com/getting-started/#disable-responsive this solution don't reset the @grid-float-breakpoint and don't reduce filesize.
